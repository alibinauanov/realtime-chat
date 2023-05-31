# Realtime chat

## Description
That's a realtime chat where you can send message to another user. To test, you can create two users and message yourself.

## How to install?

### Backend
```npm install express cors axios```<br />
express - http framework for running node servers<br />
cors - can call this server from anywhere else on the internet<br />
axios - can make API calls to chatengine.io<br />

```npm install --save-dev nodemon``` - nodemon is just optional, but it it helps to run node.js server in development mode

### Frontend
```npm create vite@latest``` - this command helps to set react project(choose React + JavaScript during setting the project)<br />

```npm install``` - it helps to install all of the dependencies because it doesn't do that by default(there is no need to do it if you copied and pasted the project)<br />

## API keys
I hide my API keys, so you can get them in https://chatengine.io/. You need Project ID and Private key for project. You should sign up in chatengine and find keys in "Project Settings" tab.<br /><br />

Backend Private Key. backend folder -> index.js -> line 15<br />
Instead of process.env.API_KEY, you should paste your Private key.<br /><br />

Frotend Project ID. frotnent folder -> src -> ChatPage.jsx -> line 5<br />
Instead of process.env.API_KEY, you should paste your Porject ID.<br />

## Run
```cd frontent``` - you need to run the project in froentend folder<br />

```npm run dev``` - Here we go! Enjoy:D<br />
