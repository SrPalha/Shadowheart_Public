# English README - Raffle Bot

This bot implements a Discord bot for conducting interactive raffles. The bot allows users to participate in a raffle by clicking a button and will randomly select a winner when the raffle's time expires.

## Description
This Discord bot allows you to create raffles for your community with a defined prize. Users can enter the raffle by clicking a button, and the bot will randomly select a winner when the raffle's time is up.

## Key Features

1. **Raffle Creation**: Administrators can initiate raffles by specifying the prize, raffle time in minutes, a prize image URL, and the game price (optional).

2. **Participation in Raffle**: Users can participate in the raffle by clicking the "Enter Raffle" button while the raffle is active.

3. **Automatic Raffle**: When the raffle time expires, the bot will randomly choose a winner from the participants and announce it in the channel.

4. **Remaining Time Updates**: The bot regularly updates the remaining time in the raffle, displaying it in the message title.

## How to Use

1. When the bot is online, an administrator can start a raffle using the `!start` command followed by four arguments:
   - Prize: A description of the prize.
   - Time in Minutes: The raffle's duration in minutes.
   - Image URL: The URL of an image representing the prize.
   - Game Price (optional): The game price associated with the prize.

   For example: `!start Xbox Series X 60 https://example.com/xbox.jpg 499`

2. A raffle message will be created with an "Enter Raffle" button. Users can participate by clicking this button while the raffle is active.

3. The bot will regularly update the remaining time in the raffle. When the time runs out, it will randomly choose a winner from the participants and announce it in the channel.

## Customization
You can customize the code by adjusting the commands, messages, and bot appearance to meet the needs of your community.

## Important Note
This bot uses the Discord.py library and requires proper configuration, including your bot's token, to work on your Discord server. Be sure to replace `'TOKEN'` with your bot's token on the last line of the code.

---

If you have any specific questions about how to run or customize the bot, feel free to ask!
