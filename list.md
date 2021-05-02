# LIST

```sh

# Netcams
intitle:"NetCamSC*" | intitle:"NetCamXL*" inurl:index.html

# Netcams
"Pop-up" + "Live Image" inurl:index.html

# Netcams
intitle:"WEBCAM 7 " -inurl:/admin.html

# Netcams
intext:"Powered by www.yawcam.com"

# Netcams
intitle:"Live View / - AXIS" | inurl:/mjpg/video.mjpg?timestamp

# Netcams
inurl:/live.htm intext:"M-JPEG"|"System Log"|"Camera-1"|"View Control"

# Access to the filesystem
inurl:/proc/self/cwd

# Log files that may contain the shadow file
"/etc/shadow root:$" ext:cfg OR ext:log OR ext:txt OR ext:sql -git

# SSH Keys
ssh_host_dsa_key.pub + ssh_host_key + ssh_config = "index of / "

# SSH Keys
intitle:"index of" /.ssh/id_rsa OR id_rsa.pub

# Bash History Files
intitle:"index of" ./bash_history

# Filesystem Access
"index of" "/home/000~ROOT~000/etc"

# Shadow files
intitle:Index.of etc shadow

# SSH server configs
"index of" "sshd_config"

# SSH keys
filetype:pub inurl:ssh -git

# FTP servers
intitle:"index of" inurl:ftp

# Netcams
inurl:top.htm inurl:currenttime

# Servers that have not been set up yet
intitle:"Apache2 Debian Default Page: It works"

```
