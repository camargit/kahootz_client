# General Assembly Group Project - Kahoot Clone

## Technology
* ReactJS version: v16.8
* Ruby version: ruby 2.6.2p47 (2019-03-13 revision 67232)
* Rails version: Rails 5.2.3
* Database: PostgreSQL 11
* Messaging: JSON Web Tokens & Action Cable 
* Style: SCSS
* Hosted: Heroku


## What is Kahoot
Multiple player quiz game. Players use a group pin to join a game and answer multiple choice questions from their computer.
Get It Out Here: (https://kahoot.com/)

## Getting Started

### Setup Database
1. Download accompanying backend from https://github.com/jamaspy/kahootz_server
2. `cd` in `kahootz_server`
3. `bundle install` to setup required gems
4. `rails db:create` to create your local database (Postgresql is required)
5. `rails db:migrate` 
6. `rails db:seed` to generate the quizzes in your local database (This could take a while)
7. `rails s` to start the server on `localhost:3000`

### Startinmg the UI 
1. `cd in `kahootz_client`
2. `npm install` to initialise the app
3. `npm start` and `Y` to chose to start the server on a different port `localhost:3001`
4. Your broswer will open up to the Join Game screen as a User. 
5. Navigate to `localhost:3001/login` or `localhost:3001/signup` and signup



