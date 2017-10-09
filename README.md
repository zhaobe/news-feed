# news-feed
A RSS news feed

## newsfeed (ruby specific)
### Setup
- `rails new newsfeed` and cd into newsfeed directory
- `rake db:create`
- add `feedjira` and `twitter-bootstrap-rails` in Gemfile, `bundle install`
- run `rails generate bootstrap:install static` to generate bootstrap files

## newsfeed-bootstrap
### Setup
[reference] (https://github.com/yeoman/generator-angular)
- make sure to have npm installed on local machine then run `npm install -g grunt-cli bower yo generator-karma generator-angular`
- make and cd into a new directory (i.e. newsfeed-bootstrap)
- `yo angular <app-name>`, options selected: no Gulp, no Sass, yes Bootstrap, default Angular modules