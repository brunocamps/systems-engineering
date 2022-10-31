# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

- Configure bootstrap:
1. Follow instructions below
https://blog.corsego.com/rails-6-install-bootstrap-with-webpacker-full
2. Run yarn add @popperjs/core

* Configure Devise for authentication:

- Added gem 'devise' to gemfile

- Execute on Terminal: rails generate devise:install 

- Follow instructions on terminal

- rails generate devise user

It has now generated a new migration defining the User (migration needed), also defined Devise signatures on models/user.rb

- Add before_action :authenticate_user! to application_controller.rb

- Generate views with gem Devise:
rails generate devise:views

- Devise confirmable: not implemented yet.

