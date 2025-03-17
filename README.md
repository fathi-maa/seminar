# RUBY ON RAILS

	Create a new Rails application and explore its directory structure.    
Modify the config/routes.rb file to add a route for the home#index action .
	Create a basic HomeController and a corresponding view.

Steps to implement the excercise:

* step1 :
	rails new myapp

*step2:  config/routes.rb
	Rails.application.routes.draw do
  		root "home#index"  # Sets the homepage route
	end

* step 3: Creating HomeContoller
	rails generate controller Home

* step 4: app/controllers/home_controller.rb
	class HomeController < ApplicationController
  		def index
  		end
	end

* step 5: creating a file 'index.html.erb' inside app/views/home/ 
	touch app/views/home/index.html.erb

* step 6:
	writing the html code here for the index page

* step 7:running the rails application
	rails server


  
