A simple iptable scripted android firewall flashable, mainly for blocking certain apps from sending any outputs hence potato that app's network capability. This was made before I realise that lineageos or Android Nougat in general can ground apps and disconnect them from the internet but it was still a fun learning experience poking with android init files as well as discovering playing around with modern android recovery's addon.d feature.

If you're only interested in the script, check /system/etc/firewall.sh on this repository

Features(/system/etc/firewall.sh):

Block apps from accessing the internet by providing a list of package name in /data/appNetBlacklist_last

Force DNS server by redirecting all udp port 53 traffic to ip address stored in /data/nameserver
