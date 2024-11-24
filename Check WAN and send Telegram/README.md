# RouterOS - Check WAN and send Telegram
This script for RouterOS checks whether the internet connection is online or offline, and sends a message via Telegram bot.
It can also optionally disable (if it goes offline) and enable (when it comes back online) the route, if you put a comment in it, with the exact name of the interface.

Instructions:

1. Create a bot through @botfather
2. Create a group, and register your bot as an administrator
3. In RouterOS, create a scheduler, set a time range, and paste the script
4. Edit the script, insert at least your BOT Token and ChatID (Telegram Room)
5. Create global variables for each interface to be checked, at the end of the script, as shown in the example.
6. Put a comment with the exact name of the interface, in their respective routes,
   if you want the script to deactivate and activate the route if it is offline or online
