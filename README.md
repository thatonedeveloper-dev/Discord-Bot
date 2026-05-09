# Discord-Bot
Basically I tired to compress an entirely work in progress script because I was bored. (Have fun.)

also the code is viewable via the code viewer in the website or application.

# IMPORTANT DETAILS FOR SETUP

- Using hard coded tokens are bad practice! This isn't production ready, and may contain security issues, the rest of setup details are in projects branch/directory.

- The uncompressed version in the projects branch is not production ready IT IS A WORK IN PROGRESS it doesn't have data lost protection.
  
- This code is skeleton-only. The data.json, context.json, and filter.json files must be populated with your own intents, patterns, responses, and filter words for the chatbot and moderation to function. The default files contain starter data for demonstration and will NOT produce meaningful conversation without training or customization.

- The TF-IDF model requires a dataset of patterns to match against. Without a populated data.json, the /chat command will respond "I don't understand yet" to everything. Build your own intents or train it via the console !reply command.

# project information 
All project details are inside the documents branch. (The newest Doc-5.8 contains database information and more details about the chatbot, the rest can be explained by AI. On top on where it says 'main' press or click on it.)

All project files are inside the projects folder. (On top on where it says 'main' press or click on it.)

# Important project details

Currently both versions (5.6 & 5.8) will probably work if you modify the directory in the config at the top of the file, and you can just modify the code if you want to change the database type.

# Questions

- databases
  They auto create upon start of the application if the databases aren't found.
- stability
  Currently .Json isn't known to be stability during sudden crash's if its in the middle of a write, I will soon update it so it creates a temporary file to lower data lost. (I have heard .Json just deletes itself if its in the middle of a write or it just removes everything.)
- documentation
  Everything has been greatly explain by Gemini 3 in the documents folder.
- updates
  This codebase was heck to make.. And I will continue anyways because I have nothing to do.
  
If you have questions other here are some answer.

Q: Does this run? A: Yes I've tested it on a android environment but I haven't ran it in wispbyte or oracle cloud yet.
Q: Is this an actual discord bot? A: Yes of course you can get instructions on how to setup discord bots online.(youtube, google, discord)

# other stuff

important notice:
I didn't test any of the special triggers PLEASE TELL ME SERIOUSLY PLEASE

I'm not responsible for data lost if you use this code in deployment, you've been warned that json databases are unstable.
