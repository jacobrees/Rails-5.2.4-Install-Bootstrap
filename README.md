# Rails 5.2.4 Install Bootstrap

# Getting Started

Copy Gemfile into Rails Project

Run `bundle install`

Add this Meta Tag to 'views/layouts/application.html.erb'
 `<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">`

## Make sure that 'app/assets/javascripts/application.js' looks like this (Order Matters)
//= require rails-ujs<br/>
//= require activestorage <br/>
//= require turbolinks <br/>
//= require jquery <br/>
//= requre jquery-ujs <br/>
//= require bootstrap<br/>
//= require_tree .

## Add this to 'app/assets/stylesheets/custom.scss'

@import "bootstrap-sprockets";<br/>
@import "bootstrap";<br/>
