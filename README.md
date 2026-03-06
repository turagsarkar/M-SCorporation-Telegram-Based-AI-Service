# M-SCorporation-Telegram-Based-AI-Service



# Telegram Bot
For access the service visit-  t.me/MSCorporationbot 
# Dataset
For access the data sheet click the link-  
https://docs.google.com/spreadsheets/d/1ICjpI43MMGgnDUMyD8pkdWLLKGiMTWEmLVEwlVv5Bw0/edit?gid=1910807323#gid=1910807323 

# Workflow - 

![img alt](https://github.com/turagsarkar/M-SCorporation-Telegram-Based-AI-Service/blob/1a07760558b82a83e70799420acd5b0b07452c37/Workflow.PNG)

![img alt](https://github.com/turagsarkar/M-SCorporation-Telegram-Based-AI-Service/blob/1a07760558b82a83e70799420acd5b0b07452c37/Error.PNG)

Output in pdf format check the file name output.

# System Setup-
Telegram Bot Configuration

Step 1: Open Telegram and search for BotFather - @BotFather
Step 2: Run the command /newbot
Step 3: Provide a bot name and username and update pic and bio.
Step 4: Copy the generated bot token

The token will be used in the n8n Telegram Trigger node.

# AI agent 

Step 1: Add LLM and configure with API key. In this model OpenAI and Goroq are used.
Step 2: Add Storage for keep update with user key.
Step 3: Add Tool like Sheet and mail account.
 

# Connecting Google Sheets to n8n

Step 1: Add a Google Sheets node
Step 2: Authenticate using a Google account
Step 3: Select the spreadsheet
Step 4: Choose the sheet name
Step 5: Use the “Read” operation for product retrieval
Step 6: Use the “Append” operation for storing bookings

# Email Configuration

Step 1: The Gmail node is used for sending confirmation emails.
Step 2: Authenticate using a Google account. 

#Error Handling 

Step 1: Use callback method for LLM in AI agent
Step 2: Use error handling trigger.
Step 3: Coonect with Sheet for update any kind of error.
Step 4: Add this file into previous file by settings.

# User and Bot interaction:
Check the output.pdf file.







