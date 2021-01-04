# Google-Meet-Bot
Using JavaScript and NodeJS (Puppeteer module), this script automates signing in to Google in extra stealth, navigates to Google Meet wih disabled notifications, turns off camera and microphone before joining the meeting, greets everyone in chat and turns on captions on behalf of the user. 

## How to use
- NodeJS can be downloaded from [here](https://nodejs.org/en/). It automatically installs npm (node package manager) with it. 
- Check NodeJS and npm versions using <code>node -v</code> and <code>npm -v</code>.
- Download a copy of the project using [ZIP](https://github.com/Ritika-Das/Google-Meet-Bot/archive/main.zip) and extract it, or HTTPS clone the repository using Git ([download here](https://git-scm.com/downloads)) using command <code>git clone https://github.com/Ritika-Das/Google-Meet-Bot.git</code>.
- Switch to your project directory (Meet-Bot) in Terminal and initialise it with npm using <code>npm init</code> and hitting Enter to agree with the particulars for package.json.
- Install Puppeteer using <code>npm i puppeteer</code>, which automatically downloads Chromium with it.
- Use <code>npm i</code> to install all the required dependencies listed in package.json to be used in our project.
- Use command <code>node app.js</code> in Terminal to see the bot in action in Chromium!

## Troubleshooting if Chromium denies sign-in
- Sign in with the Google account which you want to use with the bot to attend meetings.
- Open https://myaccount.google.com/.
- Go to [Security](https://myaccount.google.com/security) tab.
- Scroll down to [Less Secure App Access](https://myaccount.google.com/lesssecureapps) and turn on access by switching the <code>Allow less secure apps: OFF</code> to ON.

## Notable Mentions
Huge thanks to [@ShivamJoker](https://github.com/ShivamJoker)'s YouTube [tutorial](https://youtu.be/fCG8u6aIkOo) for the motivation, and unlimited assistance for this project at times when I got stuck with silly obstacles.
