## Talon is an awesome project that will allow you to use voice dication, Tobii eye tracker, and even write code on Mac, Linux, or PC. This is a tipsheet to get started with the beta (paid) version. These instructions do not apply to the free version, and are written from a mac user's perspective.   

First, sign up for the beta ($15 USD) at https://www.patreon.com/join/lunixbochs (create a patreon account if you don't already have one)  

Next, join the Slack workspace talonvoice.slack.com. Then, send a direct message to @aegis to let him know you've signed up for the beta program. He'll add you to the beta channel.  

Check the pinned messages for the latest download for your OS (mac, linux, windows). For mac, download the dmg file, then double click to run it, you'll be prompted to copy it into your Applications folder. From there, you can run the program, after which you'll have a new directory called .talon (hidden) in your user's home directory. 

You will need a copy of the https://github.com/knausj85/knausj_talon repo. Git clone (or just download and unzip) into your user directory. So now you'll have users/username/.talon/user folder and the knausj_talon within it (there will be subfolders like apps, code, lang, misc, etc).  

Next, again in the pinned files of the beta channel, find the instructions and URL to download Wav2letter and extract it into .talon if done correctly, the folder structure should have these additional files:  

~/.talon/w2l/en_US  
~/.talon/user/w2l.py  

Next, checkout this list of getting started commands: https://github.com/emmakat/knausj_talon/blob/devbranch/emmakat/list%20of%20commands.md  

If you'd like a notification to show you what Talon is hearing you say, add this notify.py somewhere in your user directory (anywhere in there is fine) https://github.com/emmakat/knausj_talon/blob/devbranch/emmakat/notify.py

Get a good microphone (if you have only bluetooth, you're going to have a bad time). Join the hardware channel to see what others have recommended.

