# Discord Reputation Bot

Welcome to the **Utrax Reputation Bot**! This bot enhances server engagement by allowing users to gain or lose reputation points based on community interactions.

## Features

- **User Reputation System**: Users can earn **Green Points** (🟢) or **Red Points** (🔴) based on their interactions within the server.
  - **Green Points**: Positive interactions like helpful messages or answers.
  - **Red Points**: For negative interactions, although the bot does not initiate this, it counts against the reputation.

- **Integration with Rick Bot**:
  - **Solana Contract Address Monitoring**: The bot now integrates with Rick Bot to monitor and react to Solana contract addresses shared for new coin calls.
  - **Reputation Votes for Coin Callers**: Users can vote on the accuracy or success of coin calls made by others, influencing their reputation score.

- **Leaderboard**: Keeps track of the top 10 users based on their reputation score. 
  - **Score Calculation**: Users earn points based on the difference between their green and red points.
  - **Reputation Percentage**: Shows the percentage of green points out of total points, indicating a user's overall reputation health.

- **Slash Commands**:
  - `/leaderboard`: Displays the top 10 users in the server based on their reputation.
  - `/checkuser`: Allows checking the reputation points of a specified user.
  - `/ping`: A simple command to check if the bot is active.
  - `/deletefromleaderboard`: For admins to remove a user from the leaderboard (requires administrative permissions).

- **Reaction-Based Voting**: Users can vote for messages by reacting with specific emojis (🟢 for positive feedback, 🔴 for negative).

- **Privacy and Data Management**:
  - **Data Storage**: User reputation data is stored in a SQLite database (`points.db`).
  - **Privacy Policy**: [Link to Privacy Policy](https://github.com/UtraxHQ/UtraxRepBot/blob/main/PRIVACY_POLICY.md)
  - **Terms of Service**: [Link to Terms of Service](https://github.com/UtraxHQ/UtraxRepBot/blob/main/TERMS_OF_SERVICE.md)
  
- **Logging**: Detailed logging is implemented for debugging and monitoring bot activity:
  - Console logging
  - Error logs
  - API call logs

- **Cooldown System**: Prevents spam voting by imposing a cooldown period after each vote.

- **Automatic Leaderboard Updates**: The leaderboard is periodically updated to reflect changes in user reputation.

## Usage

1. **Invite the Bot**: Use the bot's invite link to add it to your Discord server.

2. **Interact**: Users can interact by sending messages or reacting to others' messages with the designated emojis.

3. **Check Reputation**:
   - Use `/checkuser @username` to see a user's reputation stats.

4. **View Leaderboard**:
   - Issue the `/leaderboard` command to see who's leading in your server.

## Commands

- `/leaderboard` - Displays the server's top 10 reputation holders.
- `/checkuser <@user>` - Checks the reputation of the specified user.
- `/ping` - Checks if the bot is online.
- `/deletefromleaderboard <userId>` - Remove a user from the leaderboard (admins only).

## Setup

To get this bot contact Nourek
Discord: @Nourek
X: https://x.com/Nourekx 
TG: [@Noureketh](https://t.me/noureketh)


Feel free to reach out with any questions, suggestions, or if you'd like to contribute!

---
