# Birdwatching

Birdwatching is a full stack JavaScript application with an Express server and MongoDB database.

Contextually speaking, it was a homework exercise assigned as part of a software development course. Much of what you see here was provided as start code, which you can see exactly as it was (including most of the content of this very README) inside `startpoint`. The rest was just making it work like it was supposed to, which mostly involved writing CREATE and DESTROY routes in `server/helpers/create_router.js` and adding the Express JSON parser to `server/server.js`. The rest is minor and immaterial.

You may be confused by the instructions below if you haven't installed various other dependencies, notably [Node.js](https://nodejs.org/en/). Furthermore, I experienced a certain amount of jank when using the latest version (18.4) for a similar implementation and had to explicitly roll it back to the latest LTS version instead (16.15.1) to get everything working properly, so I wouldn't be surprised if that were the case for this one too. Specifically, I ran the following:
```
npm i n -g
sudo n stable
```

## Getting Started

These instructions should get you a copy of the project up and running on your local machine for development purposes.

### Server

Install server dependencies:

```
cd server
npm install
```

Seed the database:

```
npm run seeds
```

Run express:

```
npm run server:dev
```

### Client

```
cd ../client
npm install
npm start
```
