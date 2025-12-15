# Automated-deployment-of-a-simple-home-server-on-ubuntu-using-snaps
Nowadays, user privacy is extremely important. Big-tech services such as Google Drive, online office programs, and others are frequently used to harvest personal data, which can then be used in many different ways. This small project aims to simplify the deployment of a basic home server and make it accessible for non-technical users.

Installation:
1. Install Ubuntu on your computer(any other distribution with the "snapd" package installed would work as well)
2. Download the scripts folder from this repository
3. Unpack the folder in any directory(if you are using the main version of Ubuntu with GNOME desktop and Nautilus file manager, just double click the scripts.zip file)
4. Right click on the master_script.sh and choose the option "make executable"(the name may be different in  different file managers)
5. Right click the master_script.sh file again and choose the option to run it. You will se a terminal window asking for your sudo password. Just enter the password that you use to log into the system and press enter.
6. Wait until a browser window with the Nextcloud registration page appears. Enter a name and a password for the admin account and complete the registration. Update the page a few times until it shows that the configuration is complete.
7. Return to the terminal window and press enter to continue the installation process
8. Wait until the browser window appears once more with the Jellyfin account creation page and the Nextcloud login page.
9. Press any key in the terminal window to close it. You can now delete the scripts folder.
10. To know the IP adress of the device that you are going to use as a server, run the ip a command in the terminal.
11. To connect to the server from other devices you can use browsers or respective applications(all are available on Flatub, Snap store(the Application Center on Ubuntu), Google Play and Appstore for mobile devices). 
