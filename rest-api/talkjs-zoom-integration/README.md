# How to create Zoom meetings directly from your TalkJS chat

This is an example project to go with our tutorial on [How to create Zoom meetings directly from your TalkJS chat](https://talkjs.com/resources/how-to-create-zoom-meetings-in-talkjs/).

The project uses TalkJS's [custom headers](https://talkjs.com/docs/Features/Customizations/Creating_Custom_Headers/) to add a new header with a button to start Zoom meetings from the chat. The button is hooked to a backend server that calls the Zoom API to create a meeting and also sends a message to the chat with the details of the meeting.

> [!TIP]
> [Download this example project as a zip file](https://github.com/talkjs/talkjs-examples/releases/latest/download/rest-api.talkjs-zoom-integration.zip)

## Prerequisites

To run this tutorial, you will need:

- A [TalkJS account](https://talkjs.com/dashboard/login)
- A [Zoom account](https://zoom.us/signup)
- [Node.js](https://nodejs.org/en)

## How to run the tutorial

1. Clone or [download this project](https://github.com/talkjs/talkjs-examples/releases/latest/download/rest-api.talkjs-zoom-integration.zip).
2. Replace `<YOUR_APP_ID>` in `server/server.js` with the value found in the **Settings** tab of your [TalkJS dashboard](https://talkjs.com/dashboard/login).
3. Follow the instructions in the [tutorial](https://talkjs.com/resources/how-to-create-zoom-meetings-in-talkjs/) to set up your Zoom app and add the credentials to a `.env` file.
4. Follow the instructions in the tutorial to update your TalkJS theme.
5. Go to the `server` folder and run `npm install` to install dependencies.
6. Run `npm start` to start the NodeJS server.
7. Open `index.html` from a browser, or through an extension like Live Server from your favorite IDE or text editor.
