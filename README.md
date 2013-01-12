Install under ubuntu:
=====================

Install python: 

    `sudo apt-get install python`

Get GAE for linux : 

    wget http://googleappengine.googlecode.com/files/google_appengine_1.7.2.zip
    cd /home/zhanglong/tool
    unzip -q google-appengine_1.7.2.zip

Get goagent:
    
    cd google-appengine
    git clone git@github.com:Aaronlong31/goagent.git
    
Upload your config(please modify GAE id in goagent/server/app.yaml):
    
    sudo python appcfg.py update goagent/server/python
Input your email and password.

Modify appid in goagent/local/proxy.ini.

Create desktop quickstart:

    sudo mv goagent/local/goagent.desktop /usr/share/applications/
    # update the path in goagent.desktop
    sudo chmod 777 /usr/share/applications/goagent.desktop

Install under windows
=====================
...

Enjoy it!


    
    

