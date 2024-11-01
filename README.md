# BedrockStream-AI-Agent-Twitch
🎞️Elevate your Twitch stream with AI-powered interactions and seamless channel management. Harness the power of Amazon's Bedrock Agent to engage your audience like never before, while effortlessly controlling your stream with intuitive commands."

This code does the following:

1. It uses the `twitchio` library to create a Twitch bot.
2. The main functionality of querying the Bedrock Agent is preserved with the `!ask` command.
3. Additional Twitch-specific commands have been added:
   - `!uptime`: To show how long the stream has been live.
   - `!followage`: To show how long a user has been following the channel.
   - `!shoutout`: To give a shoutout to another streamer.
   - `!game`: To change or display the current game.
   - `!title`: To change or display the current stream title.

4. The `send_long_message` function has been adjusted for Twitch's 500 character limit per message.

To use this bot:

1. Fill in the `TWITCH_TOKEN` and `TWITCH_CLIENT_ID` with your Twitch OAuth token and Client ID.
2. Add the channel names you want the bot to join in `TWITCH_INITIAL_CHANNELS`.
3. Fill in the `AGENT_ID` and `AGENT_ALIAS_ID` for your Bedrock Agent.
4. Implement the logic for the additional commands (uptime, followage, game, title) as these require interaction with Twitch's API.

Remember to handle your Twitch credentials securely and not share them publicly. Also, make sure you comply with Twitch's terms of service and API usage guidelines when implementing and using this bot.
![crewai_diag](https://github.com/user-attachments/assets/70b8a20f-e676-445f-8a00-2c61a116d3e9)

![diagram](https://github.com/user-attachments/assets/838570e2-e0ef-4cb8-8fc8-ccc58ce2bf9f)
