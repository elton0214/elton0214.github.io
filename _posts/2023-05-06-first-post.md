---
title: Create your blog via Jekyll - Chirpy theme
date: 2023-05-04
categories: [startup]
tags: [firstblog]
---

# Brief
* "Chirpy" is one of Jekyll theme. "Jekyll" is a simple blog-oriented website generator or "static site generators".<br>
* using Markdown language to write blogs.<br>
* your web will look like this (or you can switch to light-mode):<br>
![](https://camo.githubusercontent.com/5a66291b5a52ebd0c59e1fff1525a4afedf1270407d0b1a9d52fc756566833e3/68747470733a2f2f6368697270792d696d672e6e65746c6966792e6170702f636f6d6d6f6e732f646576696365732d6d6f636b75702e706e67)
![](/assets/images/my-jekyll-website.jpg)

# Tutorial
### 1. Create a new repo via chirpy-starter
access [chirpy-starter](https://github.com/cotes2020/chirpy-starter/generate)
and name the new repo USERNAME.github.io, where USERNAME represents your GitHub username.

### 2. Clone the repo to your computer
`$git clone <repo_you_just_created>`

### 3. Install Ruby and Jekyll
[Install Ruby and Jekyll on windows](https://rubyinstaller.org/downloads/) <br>
[Install Ruby and Jekyll on other systems](https://jekyllrb.com/docs/installation/) <br>
(since Jekyll is developed in Ruby)

### 4. Install project dependency
open terminal in the project > run `$bundle`

---
### 5. Load the website
run `$bundle exec jekyll s` and access `localhost:4000` to see your web<br>
(the command runs Jekyll within the context of a Ruby environment that is defined by your site's Gemfile and Gemfile.lock files.)

### 6. Customize global settings
customize your settings in `_config.yml` <br>
you can ref my [_config.yml](https://github.com/elton0214/elton0214.github.io/blob/main/_config.yml). (just modify the basic info is enough e.g.timezone~avatar)

### 7. Restart the website
run `$bundle exec jekyll s` and refresh `localhost:4000`

### 8. Create your first post
go to folder `_posts` and create a file `yyyy-mm-dd-postname.md`(this is your post)<br>
and put this on the top of the post:
```
---
title: Create your blog via Jekyll - Chirpy theme 
date: 2023-05-04
categories: [startup]
tags: [firstblog]
---
```
after update your post, refresh local:4000 to see the updates.<br>
ps. ref using vscode as editor so that you can see the markdown file in live, like this:
![](/assets/images/ref-to-use-vscode.jpg)

---
### 9. Host it on github / Push the commits(changes)
open terminal in the project > run `git add . && git commit -m '<your_comments>' && git push`<br>
you can check the status on Github > Actions<br>
(this works by github CICD: Github Actions)<br>
(deploy detail is on: \\.github\workflows\pages-deploy.yml)<br>

### 10. Access your website
Github > Settings > Pages > Visit site

---
### 11. Update/Add new posts
repeat step 8~10
<br><br>

# Ref
[Chirpy official doc](https://chirpy.cotes.page/posts/getting-started/) <br>
[Chirpy Starter](https://github.com/cotes2020/chirpy-starter) <br>
[youtube tutorial](https://www.youtube.com/watch?v=F8iOU1ci19Q) <br>