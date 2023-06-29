# 💬 Chat with Youtube!  

#### A tool for you to go beyond just watching your Youtube videos.  

This tool uses [BardAPI](https://github.com/dsdanielpark/Bard-API/) to summarize any Youtube video you may give it. Apart from that, you can treat it as a normal conversation with a chatbot (Bard in this case), since that is what it essentially is.   

This tool is intended to be used as a research tool, where you take the topics discussed in a video, and then start a whole thread or a rabbit hole based on it, as demonstrated below:  

[https://github.com/iCaran/YT-Gist/assets/91419527/0032aa87-7069-4849-acea-599ad4f2da3d](https://github.com/iCaran/Chat-With-Youtube/assets/91419527/091bc4a7-80f5-4931-a310-3507843e8c84) 

## 🔔 IMPORTANT UPDATE   

### UPDATE - Bard API issues    

Google has been messing with their internal apis, and [breaking the bardapi](https://github.com/dsdanielpark/Bard-API/issues/80).  
Thanks to the constant effort of [dsdanielpark](https://github.com/dsdanielpark) the api is fixed and maintained consistently.

If you're a new installer and have never run `setup.bat` or `./setup.sh` before this, do so and after wards in a cmd/terminal run the following command, and do this everytime the script breaks  
`pip install bardapi` or `pip install --upgrade bardapi`    

Old users are recommended to the same to keep this script functioning. 

## 🚀 Quickstart  

1. Make sure you have [Python 3.8](https://www.python.org/downloads/release/python-3810/) installed. This tool works reliably only with Python 3.8     

2. Grab a Google Bard API access token (read how [here](https://github.com/dsdanielpark/Bard-API#readme), or see below), paste it inside `token.txt`.      

3. Download the latest release:   
   - 💻 Windows: [YTchat.zip](https://github.com/iCaran/Chat-With-Youtube/releases/download/v1.0.0/YTchat.zip)    
   - 🐧 Linux: [YTchat.tar.xz](https://github.com/iCaran/Chat-With-Youtube/releases/download/v1.0.0/YTchat.tar.xz)   

4. Extract and run the setup script:   
   - Windows: Double-click `setup.bat`   
   - Linux: `chmod +x setup.sh` and `./setup.sh`    
      - then, `chmod +x chat.sh`
   
5. Talk to Bard or Summarize a video:    
   - Windows: Double click `chat.bat` and when prompted, enter a URL or type a prompt   
   - Linux: `./chat.sh` and when prompted, enter a URL or type a prompt   

6. Sit back and enjoy your conversations!   

## 🔑 Getting a Bard Token     

1. Visit https://bard.google.com/  
2. Press F12 to open the dev console     
3. Go to *Session* -> *Application* -> *Cookies*         
4. Copy the value of the `__Secure-1PSID` cookie   
5. Paste that value into the file named `token.txt`   

> **Warning:** Do not share your Bard token with anyone!
---
### There is a [v2](https://github.com/iCaran/Chat-With-Youtube/tree/gensim) available, which is for specific use cases, this version is for general purposes.
