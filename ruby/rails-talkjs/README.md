# Rails and TalkJS example

This is an example project for TalkJS's tutorial on [how to build a Rails chat app with TalkJS](https://talkjs.com/resources/how-to-add-chat-to-a-rails-app-with-talkjs/). This example demonstrates how to integrate TalkJS with a Ruby application that uses the Rails framework.

> [!TIP]
> [Download this example project as a zip file](https://github.com/talkjs/talkjs-examples/releases/latest/download/ruby.rails-talkjs.zip)

## Prerequisites

To run this tutorial, you will need:

- A [TalkJS account](https://talkjs.com/dashboard/login)
- [Ruby](https://www.ruby-lang.org/en/downloads/)

## How to run the tutorial

1. Clone or [download this project](https://github.com/talkjs/talkjs-examples/releases/latest/download/ruby.rails-talkjs.zip).
2. Replace `<APP_ID>` in `rails-talkjs/app/javascript/conversation.js` with the value found in the **Settings** tab of your [TalkJS dashboard](https://talkjs.com/dashboard/login).
3. Install Rails:

   ```bash
   gem install rails
   ```

4. Install other project dependencies:

   ```bash
   bundle install
   ```

5. Run `rails db:migrate` to create the database table for users.
6. Run `rails db:seed` to seed the database with test data (this will first delete any test data that's already in the database).
7. Run `rails server` to start the server.
8. Go to `http://127.0.0.1:3000/chat` to try the example out.
