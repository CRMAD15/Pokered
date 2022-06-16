# POKERED SOCIAL NETWORK OF POKEMONS

#### Table of Contents
1. [Introduction](#introduction)
2. [Intructions](#intructions)
3. [End Points](#end-points)


## Introduction
Second project developed by Gabriela Benalcázar and Cristian Calderón as part of the bootcamp at Ironhack, where we had to work on the server side and use at least one API.

## Intructions
1. On the main page you can search for a pokemon, no registration is required.

2. You can register if you want to have a profile. With the registration you can sign up for events that are in the events section, by attending you will get the Pokémon that are given in that event.

3. When you get a certain amount of pokemon the ADMIN can change your ROLE to TRAINER you can access your own Gym and have the ability to create events. 

## End Points

| METHOD   |      URL      |  DESCRIPTION|
|----------|:-------------:|------:      |
| GET      |  /register    | Retrieve register form |
| POST     |  /register    | Create a new User      |
| GET      |  /login       | Retrieve  login form   |
| POST     |  /login       | Login user             |
| POST     |  /logout      | Logout user            |
| GET      |  /pokemon     | Details all pokemons     |
| GET      |  /pokemon/:id | One pokemon   |
| GET      |  /profile     | User profile     |
| GET      |  /profile/edit| Retrieve edit form  |
| POST     |  /profile/edit| Edit profile User  |
| GET      |  /profile/events| Retrieve User´s events |
| GET      |  /profile/gym   | Retrieve User´s gym  |
| POST     |  /profile/delete| Delete profile User  |
| GET      |  /events           | Retrieve event list |
| GET      |  /events/details   | Retrieve event details |
| GET      |  /events/create    | Retrieve event form | =>///// only for leaders 
| POST     |  /events/create    | Create event  |
| GET      |  /events/edit      | Retrieve event form | =>///// only for leaders 
| POST     |  /events/edit      | Edit event  |
| POST     |  /events/delete    | Delete event  |




