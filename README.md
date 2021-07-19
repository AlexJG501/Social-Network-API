# Social-Network-API

## Description
A REST API for a social media app. Built with Express, Mongoose, and MongoDB.

## User Story
- AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

## Models
- User
- Thought
- Reaction (used as a subdocument in Thought)

## Endpoints
**User**
- Get all users:        `GET /api/users`
- Create/Make a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:id`
- Update a user:        `PUT /api/users/:id`
- Delete/remove a user:        `DELETE /api/users/:id`
- Add a friend:         `PUT /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Reaction**
- Add reaction:       `PUT /api/thoughts/:id/reactions`
- Delete reaction:    `DELETE /api/thoughts/:id/reactions`

**Thought**
- Get all of the thoughts:     `GET /api/thoughts`
- Create thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:id`
- Update a thought:     `PUT /api/thoughts/:id`
- Delete a thought:     `DELETE /api/thoughts/:id`

## Packages
- express
- moment
- mongoose

## Screen Recording
