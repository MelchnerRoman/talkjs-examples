# How to create a poll in TalkJS

This is an example project for the tutorial on [how to create a poll with TalkJS](https://talkjs.com/resources/how-to-create-a-poll-in-talkjs/).

This project uses [HTML Panels](https://talkjs.com/docs/Features/Customizations/HTML_Panels/) to allow you to display a HTML document in your chats, just above the message field. We’ll use a panel to display the results of a poll, where users voted using custom action buttons. The question in this poll is sent as a [System Message](https://talkjs.com/docs/Reference/Concepts/System_Messages/). This System Message is created through a call to a backend server through TalkJS’s [REST API](https://talkjs.com/docs/Reference/REST_API/Getting_Started/Introduction/).

> [!TIP]
> [Download this example project as a zip file](https://github.com/talkjs/talkjs-examples/releases/latest/download/howtos.how-to-create-a-poll.zip)

## Prerequisites

To run this tutorial, you will need:

- A [TalkJS account](https://talkjs.com/dashboard/login)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

## How to run the tutorial

1. Clone or [download this project]((https://github.com/talkjs/talkjs-examples/releases/latest/download/howtos.how-to-create-a-poll.zip)).
2. Replace `<APP_ID>` and `<SECRET_KEY>` in `index.html` and `server.js` with the values found in your [TalkJS dashboard](https://talkjs.com/dashboard/login).
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the server.
5. Navigate to localhost:3000 in your broswer.
6. Vote using the poll button and click End Poll to view the results.
