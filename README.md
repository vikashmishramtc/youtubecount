# Youtube Backend

## Description

This project serves as the backend for a YouTube-like platform, providing APIs for managing channels like adding, deleting, updating, subscribers, and subscriptions of a channel.

## Live
- It is deployed on Vercel [Live Link](https://youtube-backend-anurag.vercel.app/).

## Table of Contents

1. [Technologies Used](#technologies-used)
2. [Installation ](#installation)
3. [Features](#features)
4. [Routes](#routes)
5. [Folder Structure](#folder-structure)
6. [Acknowledgement](#acknowledgments)
7. [Project History](#project-history)
8. [Contributors](#contributors)
9. [License](#license)

## Technologies Used
- Node.js 
- Express.js
- EJS 
- Mongoose 
- MongoDB
- HTML 
- CSS 
- Tailwind CSS 
- JavaScript 

## Installation

1. Clone the repository.
2. Navigate to the folder and run `npm install` to install backend dependencies.
3. Run `node index.js` to start the backend server.

## Features
- Lots of youtube backend api 
- A simple user interface for visualization 
- Free to use any api 

## Routes

| SN | Route | Method | Details |
|----|-------|--------|---------|
| 1  | [/yt/all](https://youtube-backend-anurag.vercel.app/yt/all) | GET | Get all channels |
| 2  | [/yt/names](https://youtube-backend-anurag.vercel.app/yt/names) | GET | Get all channel names |
| 3  | [/yt/:channelId/subscribers](https://youtube-backend-anurag.vercel.app/yt/:channelId/subscribers) | GET | Get all subscribers of a channel |
| 4  | [/yt/:channelId/subscriptions](https://youtube-backend-anurag.vercel.app/yt/:channelId/subscriptions) | GET | Get all subscriptions of a channel |
| 5  | /yt/:channelId/subscribe | POST | Subscribe to a channel |
| 6  | /yt/addChannel | POST | Add a new channel |
| 7  | /channelId/delete | DELETE | Delete a channel |
| 8  | /channelId/update | PUT | Update a channel |

## Folder Structure

<pre>
|-- src
    |-- assets 
    |-- controllers 
    |-- data
    |-- models 
    |-- routes 
    |-- views
    |-- connectionDB.js 
|-- index.js
|-- package.json
|-- package-lock.json
</pre>

## Acknowledgments

- [EJS](https://ejs.co/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- Google


## Contributors
- You are welcome to contribute here!

## License

You are free to:

- Use — the software for any purpose
- Share — Copy and redistribute the material in any medium or format
- Adapt — Remix, transform, and build upon the material

Under the following terms:

- Attribution — You must give appropriate credit.
- NonCommercial — You may not use material for commercial purposes.

## Thank You
