# **VDS**

sudo apt update

**Chrome Remote Desktop**:

- wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb

- sudo apt install ./chrome-remote-desktop_current_amd64.deb


**XFCE Desktop Environment**:

- sudo DEBIAN_FRONTEND=noninteractive \
     apt install --assume-yes xfce4 desktop-base dbus-x11 xscreensaver


- sudo bash -c 'echo "exec /etc/X11/Xsession /usr/bin/xfce4-session" > /etc/chrome-remote-desktop-session'
 
 
- sudo systemctl disable lightdm.service


**Chrome Remote Code**:

- https://remotedesktop.google.com/headless


**Firefox**:

- sudo apt install firefox

**Google Chrome**:

- wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

- sudo apt install ./google-chrome-stable_current_amd64.deb
