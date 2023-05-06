---
title: Using Jekyll to Create your blog
date: 2023-05-04
categories: [startup]
tags: [firstblog]
---

# Tutorial
### 1. Create a new repository from chirpy-starter
https://github.com/cotes2020/chirpy-starter/generate
and name the new repository USERNAME.github.io, where USERNAME represents your GitHub username.
### 2. clone the repo
git clone <repo_you_just_created> 
### 3. install Ruby
https://rubyinstaller.org/downloads/
### 4. install project dependency
open terminal in the project > $bundle
### 5. load the website
$jekyll serve
or $bundle exec jekyll s
localhost:4000
### 6. Customize global settings
go to _config.yml and change the settings
### 7. restart the website
$bundle exec jekyll s
### 8. create your first post
go to folder _posts and create a file xxx.md