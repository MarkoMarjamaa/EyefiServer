# EyefiServer
Yet Another EyefiServer ( for Python 3.11)

Copied from https://github.com/dgrant/eyefiserver2

Create directory /root/eyefiserver and venv for it
Place conf to /etc and py to /root/eyefiserver. 
Run eyefiserver.sh restart to restart server etc...

Eyefi uses port 59278. The card searches your network for that port, so there's no fixed ip or hostname. 

In my case the mac_address and upload_key were in sqlite3 file 
C:\Users\XXXX\AppData\Local\Eye-Fi\cloud\server.db
Drop it to sqlite3 and run
select * from devices;
There's your mac_address and upload_key. 

It's not supposed to be pretty. 
