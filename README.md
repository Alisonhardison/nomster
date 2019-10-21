# Nomster
A Yelp clone that integrates with the Google Maps API and includes features like user comments, star ratings, image uploading, and user authentication. 

This app is viewable here https://nomster-alison-hardison.herokuapp.com

## Software requirements
 - Rails 5.0.0 or higher

 - Ruby 2.3.1 or higher

 - PostgreSQL 9.6.8 or higher
 
 ## Navigate to the Rails application
  $ cd /nomster
  
 ## Set configuration files
  $ rails new nomster --database=postgresq
  
 ## Create the database
  $ rake db:create
  
 ## Starting the local server
  $ rails server -b 0.0.0.0 -p 3000
  
 ## Production Deployment
  $ heroku create nomster-alison-hardison
  
  $ git push heroku master
  
 ## Support
  Bug reports and feature requests can be filed with the rest for the Ruby on Rails project here:
  https://github.com/Alisonhardison/nomster/issues
  


