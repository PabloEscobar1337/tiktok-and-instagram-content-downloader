# tiktok-and-instagram-content-stealer

this program allows you to save multiple videos or photos to your device from instagram and tiktok without a watermark and you have an option to send all these saved videos to the telegram channel of your choice.

## how to execute

##### step 0

download and install [Python](python.org)

##### step 1

install dependencies
```bash
pip install -r dependencies
```
##### step 2

input instagram and tiktok video/photo links in the **data.txt**

##### step 3

```bash 
cd lib
python launcher.py
```

that's it!

if you want to send all the downloaded videos to the telegram channel of your choice, remove the comment from **sendTelmain()** in the **launcher.py**, add the link to your channel in the 13th line of **sendT.py** and add your api ID and hash in the **auth.txt**.
