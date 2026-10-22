# Installation

**You need to have local admin access** to be able to install WSL. Without this, DevStart itself might be installed, but it will be unable to install WSL.

Download the .exe file from [releases](https://github.com/techyon-io-horsing-around/devstart/releases). Download will be stopped and warned against, as file is not approved by Microsoft (yet). Do the following to get it despite the warning:

<img width="463" height="344" alt="download" src="https://github.com/user-attachments/assets/c63f0bee-d814-417e-a5ec-fe2b97d75365" />

Run the file. It's a 4 step procedure before vm with tools are installed. After this you must setup Git, Github and your IDE. The 4 step process must be done in DevStart UI. Rest is recomended to do inside the vm with task command (follow the instructions in DevStart, and banner info in the Linux terminal). The tasks can alternatively be run inside DevStart UI (expand "Git and projects" and "Editors", but it's faster to do this steps from linux terminal with task command).

**You might be instructed to reboot your computer after the first step** (installing WSL). In case: Restart when instructed and start the DevStart program again and follow instructions.


## Maintanance

Expand "Maintenance" in bottom of DevStart to 
* refresh Zscalar sertificate in Linux vm (if you get strange ssl/tls errors, it might be because cert i vm are outdated. Zscalar cert is copied from your windows host to Linux vm during installation, but after some time, you might need to refresh it in the vm).
* Update the Linux welcome message (might be updated in further updates of devstart)
* Export backup of DevStart VM
* Delete Devstart VM

## Update DevStart
DevStart checks after updates on start, and each hour. **It's safe an strongly recommended to update as soon as possible.** You might also manually trigger check by clicking on the button right of the version information in to of the app. You will see tip on restart app to update about this place if update exists. Just click on it, and devstart will download, update and restart it self. Your running linux VM will continue in the background and not be affected by the update. **Please keep DevStart updated. It will not destroy you linux VM or any of your work on it.**

### Update your vm with new tasks etc.
New versions of DevStart might have new tasks steps or other improvements which can be nice to have in your development environment. To update your VM with the last updates from last version of DevStart:
* Open DevStart
* Below **"Tasks and maintenance"**, run **"Install welcome message"**

  
