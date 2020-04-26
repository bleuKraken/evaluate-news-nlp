# Aylien Sentiment Analyzer

This project is about using Webpack along with other front end developer tools to create a webpage that uses Aylien API to process and display data.

The goal of this project is to get practice with:
- Setting up Webpack
- Sass styles
- Webpack Loaders and Plugins
- Creating layouts and page design
- Service workers
- Using APIs and creating requests to external urls

## Getting started


`cd` into the project root folder and run
- `npm install`

## Setting up the API

First, you will need to go [here](https://developer.aylien.com/signup). Signing up will get you an API key. Don't worry, at the time of this course, the API is free to use up to 1000 requests per day or 333 intensive requests. It is free to check how many requests you have remaining for the day.


Second, create a file named ".env" in the root directory of the project. File with your API keys like this:
```
API_ID=**************************
API_KEY=**************************
```
## Starting the Server
Inside of the root directory of the project, right click and open a terminal window. 
Type in `npm run start` to run the API server

## Starting client in Production
Inside of the root directory of the project, open ANOTHER terminal window and 
Type in `npm run build-prod` to run client

## Starting client in Development
Then in `npm run build-dev` to run client

## Testing with Jest
Type in `npm run test` to test with Jest

## Paste in a link! 
Everything should be good to go, now just paste in a link and click on "Analyze Link"
