# Trainual One Page App

This is a single page application that will handle Create, Update and Delete actions. 

It was built based on unique tools from Rails world:

- Turbolinks
- StimulusJs
- StimulusReflex
- CableReady

* Database: PostgreSQL
* Cache: Redis (on dev)

## How to start up
On Development environment run the following commands 

- rails dev: cache
- rails db: create
- rails db: migrate
- rails db: seed


## Features
- No heavy javascript libraries used to minify bundle size
- assets managed by webpacker
- most of the time pure html is transferred over the wire with almost no painfully slow page refreshes
- coloumns sorting
- search field with filter functionality
- form in modal
- validations for name, email, phone
- seed data to create 1000 users
- results paginated (25 per page)
- constraints both in code and on database level


