# LIST

```text
intitle:"NetCamSC*" | intitle:"NetCamXL*" inurl:index.html

"Pop-up" + "Live Image" inurl:index.html

intitle:"WEBCAM 7 " -inurl:/admin.html

intext:"Powered by www.yawcam.com"

intitle:"Live View / - AXIS" | inurl:/mjpg/video.mjpg?timestamp

inurl:/live.htm intext:"M-JPEG"|"System Log"|"Camera-1"|"View Control"

inurl:/proc/self/cwd

"/etc/shadow root:$" ext:cfg OR ext:log OR ext:txt OR ext:sql -git

ssh_host_dsa_key.pub + ssh_host_key + ssh_config = "index of / "

intitle:"index of" /.ssh/id_rsa OR id_rsa.pub

intitle:"index of" ./bash_history

"index of" "/home/000~ROOT~000/etc"

intitle:Index.of etc shadow

"index of" "sshd_config"

filetype:pub inurl:ssh -git

intitle:"Apache::Status" (inurl:server-status | inurl:status.html | inurl:apache.html)
```
