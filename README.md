# Discord bot Setup

- open Discord Developer Portal
- create a new application
- reset the applications token (This is important as this is used to control the bot, DO NOT LEAK!)
- open any editor or IDE and replace the 'place_your_token_here' if your using the compressed version replace the 'tk' if your using uncompressed replace 'Bot_token' make sure to replace only the text 'place_your_token_here'.
- open discord and go to your settings
- enable developer settings in the accessibilities tab
- click on the three dots and copy your profile ID
- head back to the code editor, IDE, text editor and replace the profile ID for the compressed version you will see a bunch of numbers you'll replace that with your copied number, for the uncompressed version you'll see it below the 'bot_token'.
- lastly change the directory, you will see a android directory that will not work if you saved it in a different environment or a different folder, change the directory to match the same directory as where the file is downloaded. (use a dedicated file manager on mobile or for windows just copy the directory.)
- press save and start the bot!

# info

this Branch/directory contains compressed and uncompressed versions.

make sure to download all libraries needed, all libraries are seen at the top of the code.

# warning

As mentioned before this isn't production ready code, hardcoding tokens are a terrible practice you should use a .env (will disappear on mobile) if your on windows, if your using a third party service use the uncompressed version, I'll give a guide and a compatible version with wispbyte.
