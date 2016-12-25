# Sample Chatbot  
This repo contains a simple chatbot built using Node (Typescript) and leverages the [Microsoft Bot Framework](https://dev.botframework.com) and [LUIS](https://luis.ai).  

The contents of this repo are more or less what you get when you create a new Chatbot using the [swell generator](https://github.com/swellaby/generator-swell).  


## Usage  
1. Clone this repo
2. Install dependencies - `npm install`  
3. Transpile typescript - `npm run build`
4. Run `node src/console.js` to start the bot for interaction over the console, run `node src/server.js` to interact with the bot via the api/[bot channel emulator](https://download.botframework.com/bf-v3/tools/emulator/publish.htm)  

To run unit tests - `npm run test`  
To clean transpiled code - `npm run clean`