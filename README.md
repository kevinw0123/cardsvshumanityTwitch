OFFICIAL WEBSITE:

/////////////////////////////////////////////////////////////////////
http://www-scf.usc.edu/~wangkj/cardsagainsthumanity/cardschatbot.html
/////////////////////////////////////////////////////////////////////




# Twitch Chatbot Hackathon
We are using the Twitch chatbot template to create a cards against humanity chatbot

## Important links
* Getting started documentation for the Twitch platform: https://dev.twitch.tv/docs 
* Overview of the Twitch chat structure: https://dev.twitch.tv/docs/irc 
* Twitch authentication guide (necessary for connecting to chat): https://dev.twitch.tv/docs/authentication
* The Twitch Developers forums are a great place to find existing questions and answers: https://discuss.dev.twitch.tv 

### Structure
`simple-chatbot.html`
Provides the user interface for the leaderboard and calls into the `chatClient` to connect to Twitch chat.

`simple-chatbot.js`
Provides all of the inner workings for the chat bot including connecting, sending user credentials, and joining the correct channel. The leaderboard rendering code is also inside of this file.

`leaderboard.css`
Makes the leaderboard look...better than an unformatted table. Kappa.# cardsvshumanityTwitch
