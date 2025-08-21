# globetm-noload-2025-full-tutorial-
Follow this tutorial for gtmnoload ovpn+dnstt 2025

requirement: 
Kelangan ng internet/data sa pagrun ng script (after successful installation ng script pwede na irun ung   step 4 kahit walang load ang sim)
termux app from this github link.

for android 7, 8, 9, 10, 11, 12, 13, 14, 15.
https://github.com/termux/termux-app/releases/tag/v0.118.3

for android 5, 6.
https://github.com/termux/termux-app/releases/download/v0.119.0-beta.1/termux-app_v0.119.0-beta.1+apt-android-5-github-debug_universal.apk

1. Install Termux app

2. Run this script
```
termux-setup-storage
```

4. Run this script
bash <(curl -ks https://raw.githubusercontent.com/arjienx/client-dnstt-app/main/install)

5. Run this script 
for gtm noload server 1 run this script:

dnstt-client -udp 124.6.181.160:53 -pubkey 33416e51778ed97e3380fbf56eb4f8bae8e46716816762bfd06dea342afd1a3a ovpn1.izphvpn.com 127.0.0.1:8888

for gtm noload server 2 run this script:

dnstt-client -udp 124.6.181.160:53 -pubkey 33416e51778ed97e3380fbf56eb4f8bae8e46716816762bfd06dea342afd1a3a ovpn2.izphvpn.com 127.0.0.1:8888

Ps: need disable power saving mode sa termux app. 
or allow to run in background.
