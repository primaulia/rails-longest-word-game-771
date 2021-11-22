No Database AirBnB
Let’s build a simple AirBnB clone with a remote static JSON DB with:

URL = https://raw.githubusercontent.com/lewagon/flats-boilerplate/master/flats.json

[] Create new rails app --> rails new ?? --skip-active-storage --skip-action-mailbox
[] A home page listing flats --> GET '/', to: 'flats#index'
[] A dynamic show page for a specific flat --> GET '/flats/:id', to: 'flats#show'
