---
title: Minecraft Manager
subtitle: My take on a bot to manage a Minecraft Server
---

# [Minecraft Manager](https://github.com/Yuri010/Minecraft-Manager)
Minecraft Manager is a Discord.py bot written by me :)\
It gives people in a Discord channel the possibility to not only turn on a self-hosted Minecraft server, but also do various other stuffs with it!

I even added a feature so you can now "link" your Minecraft and Discord together! So now the bot can check if you have Admin on the server and give you control over the console, without leaving the bot-commands channel :P\
Another neat feature is that you can now create, manage and download world snapshots through the bot! This way you don't have to ask for a world download or stuff like that but you can just download it straight from within Discord.

## Why?
I got the idea of making this bot just out of nowhere really. Me and my friends have had multiple Minecraft Servers together, but on some free hosting provider with connection problems, a limited render distance and so on and so forth.
Now, just hosting a simple Minecraft server yourself isn't that hard. But hosting it as a not very tech-savvy person who is used to simple dashboards of hosting providers online? Yeah...

One of the biggest features of this bot is that **you do not need to set up port forwarding for your server!!**

What it does is that it starts the server locally, then a script checks if the server is up and running, the script starts [Ngrok](https://ngrok.com/) so you don't need to port forward anything and then sends the public IP in the Discord chat!

## Alright, so what can it do?
Well, basically everything you need for a simple Minecraft server!
You can-
- Turn it on (Obviously)
- Shut it down
- Access the Minecraft Console based on if you have Operator in the Minecraft server itself
- Check the status (Is it running? What is the IP? How high can I expect the latency to be?)
- Create and manage world snapshots of the server

And some miscellaneous commands (bot ping, display an info message and shut down the bot)

## Demo!
Coming Soon:tm:
