# Realtime chat

## Description
That's a realtime chat where you can send message to another user. To test, you can create two users and message yourself.

## How to install?

### Backend
```npm install express cors axios```
express - http framework for running node servers
cors - can call this server from anywhere else on the internet
axios - can make API calls to chatengine.io

npm install --save-dev nodemon
nodemon is just optional, but it it helps to run node.js server in development mode

### Frontend
npm create vite@latest
this command helps to set react project(choose React + JavaScript during setting the project)

npm install
it helps to install all of the dependencies because it doesn't do that by default(there is no need to do it if you copied and pasted the project)

## API keys
I hide my API keys, so you can get them in https://chatengine.io/. You need Project ID and Private key for project. You should sign up in chatengine and find keys in "Project Settings" tab.

Backend Private Key. backend folder -> index.js -> line 15
Instead of process.env.API_KEY, you should paste your Private key.

Frotend Project ID. frotnent folder -> src -> ChatPage.jsx -> line 5
Instead of process.env.API_KEY, you should paste your Porject ID.

## Run
cd frontent
you need to run the project in froentend folder

npm run dev
Here we go! Enjor:D
