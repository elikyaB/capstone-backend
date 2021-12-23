# Notare 2.0 - Notes App

This is the backend for the Notare 2.0 App, using Masonite through Heroku to form the API for the [Svelte frontend.](https://github.com/elikyaB/capstone-frontend)

## Dependencies

- Python v3.10
- PostgreSQL 14
- Masonite 3.0.13
- Heroku

## Models

#### Note Schema
- title: String
- body: String

## Route Table

| Route | URL | Description |
| ----- | --- | ----------- |
| Index | `/notes` | GET request, returns all notes |
| Create | `/notes` | POST request, uses request body to add product to user cart |
| Update | `/notes/:id` | PUT request, updates specified note |
| Destroy | `/notes/:id` | DELETE request, removes specified note |
| Show | `/notes/:id` | GET request, shows the specified note |