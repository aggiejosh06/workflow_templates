# Starting a New Rails Project

1. Create an RVM gemset
  1. ```$rvm use ruby-2.3.0@project_name --create```
2. Install project gems
  1. Install rails
    * ```$gem install rails --no-ri --no-rdoc```
  2. Install other project gems including ```bootstrap-sass``` and ```rails_layout```
    *  Add ```gem 'bootstrap-sass'``` and ```gem 'rails_layout'``` to Gemfile
  3. Install gems
    * ```$bin/bundle install```
3. Create new rails project
  1. ```$rails new project_name```
  2. ```$cd project_name```
4. Initialize simple rails layout and bootstrap
  1. Run ```$rails generate layout:install simple --force```
  2.  Initiate bootstrap gem by adding the ```@import "bootstrap-sprockets";``` and ```@import "bootstrap";``` to the bottom of ```application.css.scss```
  3.  Make sure ```//= require jquery``` and ```//= require bootstrap-sprockets``` are included at the bottom of ```application.js```.
5. Initialize git repository
  1. ```$git init```
6. Initialize heroku remote repository
  1. ```heroku create project_name```
7. Start working on git development branch
  1. ```git checkout -b branch_name```
