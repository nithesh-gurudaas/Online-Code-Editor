## Getting Started

1. Clone this repository 
2. `cd` into it and use the command `npm install` to download dependencies.
3. Run `node server.js` to start the Express server.
4. On another terminal, `cd` into the client folder, run `npm install` followed by `npm start` to start the development server. Open http://localhost:3000 in your browser.
5. Use Ctrl+C to stop the execution of both the programs

## Pre-requisites

- [Node.js](https://nodejs.org/en) and npm

## Built With

- [React](https://reactjs.org)
- [Pusher Channels](https://pusher.com/channels)

##Basic explanation:
* A webpage that functions as a webpage editor similar to [codepen.io](https://codepen.io/), with each editor as a tab rather than all three appearing at the same time. [Code mirror API](https://codemirror.net/) was used for implementing the editor area, and the changes are reflected in the preview pane. The preview pane uses the port 5000, whereas the editing is done on the webpage that uses port 3000, and information is dynamically updated from both. Port 5000 acts as a server, while 3000 would act as the client.
