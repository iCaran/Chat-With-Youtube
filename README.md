# 💬 Chat with Youtube! (v2) 

#### A (more precise but less practical) tool for you to go beyond just watching your Youtube videos.  

Similar to  as [Youtube Summarizer v2](https://github.com/iCaran/YT-Gist/tree/v2-gensim_based)

# v2
- [v1](https://github.com/iCaran/Chat-With-Youtube/tree/master) uses TF-IDF based NLP summary, which is less accurate in extracting the meaning of the text, but provides shorter summaries
- v2 uses Gensim based NLP summary, which is much more accurate in extracting the meaning of the text, but provides much larger summaries
- Overall, due to the max token size limit of any AI Chatbot (especially in free plans), larger NLP summaries as prompts will exceed the limit and will fail
### Use this version when the video size is short and more accuracy is required

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
   - 💻 Windows: [YTchat.zip] (coming soon)    
   - 🐧 Linux: [YTchat.tar.xz] (coming soon)   

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
