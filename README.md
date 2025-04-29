# Webcam-Monitoring-Bot
Automatically detects and kicks users who activate their webcam for more than 2 seconds (configurable) in a Discord voice channel.
Key Features
Webcam Detection

Monitors voice channels in a specific server (configurable via SERVER_ID).

Detects when a user starts or stops their webcam.

Time-Based Enforcement

Tracks how long a user keeps their webcam on.

Kicks the user if they exceed the time limit (default: 2 seconds).

Automatic Kick with Reason

Kicks the violator with the message:

"You do not have permission to use the webcam"

Logs actions in the console for moderation review.

Server-Specific Operation

Only monitors the specified Discord server (no accidental kicks in other servers).

Configurable Settings

BOT_TOKEN – Your bot’s authentication token.

SERVER_ID – The Discord server ID where enforcement happens.

WEB_CAM_TIME_LIMIT – Adjustable time threshold (in seconds).

Error Handling

Prevents crashes if:

The bot lacks kick permissions.

The user leaves before being kicked.

Other unexpected issues occur.

Use Cases
✔ Strict No-Webcam Servers – Enforces rules against webcam usage.
✔ Privacy-Focused Communities – Prevents accidental/malicious video sharing.
✔ Moderation Automation – Reduces manual work for admins.

Requirements
Bot Permissions:

View Channels

Connect to Voice Channels

Kick Members

Python Libraries: discord.py (pip install discord.py)
