This code allows you to send a message or message to all selected users in Telegram!
  
If you add several messages - it sends a different one each time

Put `msgs.txt` and `usernames.txt` in the directory with the file.

**Example usernames.txt:** 
@User1
@User2
@User3
etc.

markdown
Copy

**Sample msgs.txt of different messages each time :** 
Hi, my name is Pasha...
Hi, How are you...
Hi, What are you doing...
etc.

markdown
Copy

**Sample msgs.txt of one message each time :** 
Hi, my name is Pasha...

Copy

In the code in the variable 
BASE = "Specify directory with file"
Api_id and Api_Hash = Data of your account from which messages will be sent.

markdown
Copy

After start you will have a file `done.txt`, there will be a list of those to whom you have already sent messages and in the file and in the file `usernames.txt` those to whom the bot has already written will be deleted.  

**What do you get?  
- A bot that writes from your Telegram account, different messages to a list of users.  

**How to use it?  
- Advertisements for services.  
- Scam.  
- Group ads  
