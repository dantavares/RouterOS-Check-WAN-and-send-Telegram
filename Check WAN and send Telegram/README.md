# RouterOS - Check WAN and send Telegram
This script for RouterOS checks whether the internet connection is online or offline, and sends a message via Telegram bot.

Instructions:

1. Create a bot through @botfather
2. Create a group, and register your bot as an administrator
3. In RouterOS, create a scheduler, and paste the script
4. Edit the script, insert at least your BOT Token and ChatID (Telegram Room)
5. Put a comment with the exact name of the interface, in their respective routes,
   if you want the script to deactivate and activate the route if it is offline or online