MakersBnB Challenge
==================

Brief Summary of Approach
-------
Maker's Academy group project to create a clone of a popular website which lets you list and book spaces to stay in.



Points for development:
* improve CSS
* implement back buttons

Instructions
-------
* Clone this repository
* cd StrengthBnB
* Run the command 'bundle' in the project directory to ensure you have all the gems
* you will need to create databases in psql on your local repository:
  - psql
  - CREATE DATABASE makersbnb_development
  - CREATE DATABASE makersbnb_test
  - \q to exit
* rackup (usually localhost:9292 on your browser)

User stories
--------
```
As a user
So that I can list a space
I would like to sign up

As a user
So that someone can hire my space
I would like to list a space

As a user
So that I can provide information for the space
I would like to provide a name, description and price for the space.

As a user
So that someone can hire a space
I would like to show the dates my space is available

As a signed-up user
So I can hire a space
I would like to request to hire a space for one night

```


Spec
```
Any signed-up user can list a new space.
Users can list multiple spaces.
Users should be able to name their space, provide a short description of the space, and a price per night.
Users should be able to offer a range of dates where their space is available.
Any signed-up user can request to hire any space for one night, and this should be approved by the user that owns that space.
Nights for which a space has already been booked should not be available for users to book that space.
Until a user has confirmed a booking request, that space can still be booked for that night.
```

Technologies Used:
--------
* RSpec
* Ruby
* DataMapper
* postgresSQL database
* Bcrypt gem (for encrypting user passwords)
* Sinatra web framework
