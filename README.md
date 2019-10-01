# NGROK

## What is it?
NGROK is a platform that, using the installed utility, allows you to organize remote access to a web server or some other service running a PC. Access is organized through the secure tunnel created at the start of ngrok. The PC, at the same time, may be located behind the Network, and may not have a static IP address.

## Installation:
1. Download executable ngrok file
2. Log in here: https://dashboard.ngrok.com/
Got there your token, after it:
```./ngrok authtoken {your_token}```
3. To open port: ```./ngrok http {port}```, for example ```./ngrok http 5000```

Full description:

https://dashboard.ngrok.com/get-started

