# privacy-policy
A repository containing the official Privacy Policy for my Discord bot, including information about data collection, usage, storage, and user privacy.
Privacy Policy for Super Bacon
Effective date: November 5, 2026
Bot operator: Super Bacon
Contact: Discord - @chancer.9

Information the bot processes
When you use the bot, it processes information made available through Discord, including Discord user IDs, usernames, server and channel IDs, and command or button interactions. Discord also processes information under its own privacy policy.

Depending on the features enabled in a server, the bot may process:

Messages: The bot reads server messages to award XP, count progress toward daily quests, and handle AFK notices. It does not save ordinary message text as XP data.

Edited and deleted message logs: If a server administrator enables message logging, the bot sends available before-and-after text, attachment names and links, and message, author, and channel identifiers to the configured Discord channel. The bot does not save these logs in its local data files, but the messages posted in Discord may remain there until deleted.


XP and activity data: XP totals, XP cooldown timestamps, daily reward status, and daily quest progress, associated with a user and server.


Poll data: Poll questions, choices, creator and server identifiers, poll message identifiers, and votes associated with voter IDs.


Moderation data: Warnings, moderation actions, reasons, timestamps, and moderator and target user IDs. The bot may also post moderation details in a server’s configured moderation-log channel.

Server settings: Configured channel and role IDs, XP settings, and welcome-message templates.


Rank-card backgrounds: If you upload a background, the bot downloads and stores a processed PNG copy for your server-specific rank card. Use /background reset to remove it

Temporary AFK status: Your AFK message is held in memory and is cleared when you send a message or the bot restarts.

Rank cards use a member’s Discord avatar, username, level, and XP. The generated card is sent to Discord in response to /rank.



How information is used

The bot uses this information to provide its features: XP and leaderboards, daily rewards and quests, polls, AFK notices, rank cards, welcome messages, and administrator-requested moderation and logging. Message and moderation logs are available to people who can access the Discord channels where they are posted.



Storage and sharing

The bot’s persistent data is stored in local files on the machine hosting it. The bot’s code does not include an analytics or advertising feature. Discord is used to receive commands and display bot responses; the hosting provider runs the bot and stores its files. [Name your hosting provider, if applicable.]

The bot does not automatically delete persistent data when a member leaves a server or when a logging feature is disabled. Disabling a feature stops future activity for that feature; it does not remove previously stored files or messages already posted in Discord.



Retention and deletion

The bot has no automatic retention schedule. XP, server settings, polls and votes, moderation history, and uploaded backgrounds may remain until they are removed by the bot operator or server administrators, or the hosting data is deleted.

Some bot commands remove or change only part of a member’s data: /resetxp resets XP, /clearwarnings clears warnings, and /background reset removes a custom background. These commands do not erase every related record; for example, moderation-history entries or poll votes are not removed by those commands.

To request deletion or ask a question about bot-held data, contact [your contact details]. Server administrators can also contact the operator about data for their server. Messages already posted in Discord log channels may need to be deleted separately by someone with the appropriate Discord permissions.



Your choices

You can choose not to use the bot’s commands or features. Server administrators can disable edited/deleted message logging and other configurable features. Ask your server’s administrators how the bot is configured and who can view its log channels.


Changes and contact
This policy may be updated when the bot or its data practices change. For questions or requests, contact [your contact details].

Important: A Discord bot token was exposed in the selected .env text. Revoke and regenerate it in the Discord Developer Portal immediately, then update the bot’s secret configuration. Don’t reuse or repost the exposed token.

