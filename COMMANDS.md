# Commands Documentation

## General Commands

- `!hello`
  - **Description**: Greets the user.
  - **Usage**: `!hello`

- `!ping`
  - **Description**: Checks the bot’s latency.
  - **Usage**: `!ping`

- `!userinfo @user`
  - **Description**: Displays information about the mentioned user.
  - **Usage**: `!userinfo @user`

- `!serverinfo`
  - **Description**: Displays information about the server.
  - **Usage**: `!serverinfo`

## Moderation Commands (Admin Only)

- `!mute @user`
  - **Description**: Mutes the mentioned user.
  - **Usage**: `!mute @user`

- `!ban @user`
  - **Description**: Bans the mentioned user.
  - **Usage**: `!ban @user`

- `!kick @user`
  - **Description**: Kicks the mentioned user from the server.
  - **Usage**: `!kick @user`

- `!clear [number]`
  - **Description**: Deletes the specified number of messages from the channel.
  - **Usage**: `!clear 10`

## Fun Commands

- `!meme`
  - **Description**: Sends a random meme.
  - **Usage**: `!meme`

- `!quote`
  - **Description**: Sends a random inspirational quote.
  - **Usage**: `!quote`

- `!8ball [question]`
  - **Description**: Answers your yes/no question with a random response.
  - **Usage**: `!8ball Will I pass my exams?`

- `!joke`
  - **Description**: Tells a random joke.
  - **Usage**: `!joke`

## Music Commands

- `!play [song name or URL]`
  - **Description**: Plays a song from YouTube.
  - **Usage**: `!play Never Gonna Give You Up`

- `!skip`
  - **Description**: Skips the currently playing song.
  - **Usage**: `!skip`

- `!stop`
  - **Description**: Stops the music and clears the queue.
  - **Usage**: `!stop`

## Coding Commands

- `!leetcode [username]`
  - **Description**: Fetches the LeetCode profile of the specified user.
  - **Usage**: `!leetcode your_username`

- `!codeforces [username]`
  - **Description**: Fetches the Codeforces profile of the specified user.
  - **Usage**: `!codeforces your_username`

- `!github [username]`
  - **Description**: Fetches the GitHub profile of the specified user.
  - **Usage**: `!github your_username`

## Utility Commands

- `!remindme [time] [message]`
  - **Description**: Sets a reminder for the specified time.
  - **Usage**: `!remindme 10m Take a break`

- `!poll [question] [option1] [option2] ...`
  - **Description**: Creates a poll with the given options.
  - **Usage**: `!poll What's your favorite language? Python JavaScript C++`

- `!weather [location]`
  - **Description**: Provides the current weather for the specified location.
  - **Usage**: `!weather Tokyo`

## Event Commands (Admin Only)

- `!events`
  - **Description**: Lists upcoming events.
  - **Usage**: `!events`

- `!addevent [date] [description]`
  - **Description**: Adds a new event to the calendar.
  - **Usage**: `!addevent 2024-09-15 Hackathon`

## Resource Commands

- `!resource [topic]`
  - **Description**: Provides a link to a resource on the specified topic.
  - **Usage**: `!resource python`

- `!docs [language]`
  - **Description**: Provides a link to the official documentation for the specified programming language.
  - **Usage**: `!docs javascript`

## Interactive Commands

- `!button`
  - **Description**: Sends a message with a button.
  - **Usage**: `!button`

- `!vote [topic]`
  - **Description**: Starts a vote on the specified topic.
  - **Usage**: `!vote Should we add a new channel?`

## Game Commands

- `!trivia`
  - **Description**: Starts a trivia game.
  - **Usage**: `!trivia`

- `!rps [choice]`
  - **Description**: Play Rock, Paper, Scissors with the bot.
  - **Usage**: `!rps rock`

## Custom Commands (Admin Only)

- `!addcommand [trigger] [response]`
  - **Description**: Adds a custom command to the bot.
  - **Usage**: `!addcommand !hello Hello, world!`

- `!removecommand [trigger]`
  - **Description**: Removes a custom command from the bot.
  - **Usage**: `!removecommand !hello`
