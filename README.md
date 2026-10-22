# youtube_scraper

## How to run! 

Download [python](https://www.python.org/downloads/)

Clone this code into your own workspace.  

Edit code:  
1. Enter the correct YouTube playlist link
2. Log into YouTube in whatever browser you are using. Default is safari. If different, replace correct browser in code. 
    1. May have to go into settings to give VScode /terminal full disk access permissions (text me if this is the case) 

In terminal:  
Navigate to folder where this code is saved.

```  
python3 -m venv venv
source venv/bin/activate
pip install yt-dlp
python3 youtube_scrape.py
```


Saves to folder named transcripts in the same file path as wherever you saved this code. 

**NOTE**: every video needs to already have a transcript. If it doesn’t you need to run machine learning / voice recognition

Code that does this:  
        -  https://github.com/Dicklesworthstone/bulk_transcribe_youtube_videos_from_playlist  
        -  https://gist.github.com/udaylunawat/6c3cf79abbcffd0029905cc253c28869  

