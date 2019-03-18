# FavArtists
This app at its core is simple. It will be an archive of vinyl records for sale and categorized by artist. We won't be implementing a ton of foreign logic but rather just getting the foundations of an API-based application in order. We'll touch on authentication (not using Devise 😉) and basic CRUD.

There will be two apps.

A Ruby on Rails backend - This will handle our data, sessions, and authentication.
A Vue.js frontend - This will be the view layer but also the one responsible for sending and receiving data to our rails-based backend. The front-end will run on a different instance using the Vue-CLI to help us set up an app.

# USED IN THIS BUILD
Rails 5.2.2
Ruby 2.5
Gem bcrypt 3.1.7
Gem rack-cors
Gem redis 4.1.0
Gem jwt-sessions

# Run the app locally
Install Ruby
Download and extract the code from the FavArtists
cd into the app directory
Run gem install bundler to install bundler
Run bundler install to install app dependencies
Run rails server
Access the running app in a browser at http://localhost:3000
