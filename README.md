SSLStrip+
=========
Forked
----
This is a new version of [Moxie´s SSLstrip] (http://www.thoughtcrime.org/software/sslstrip/) with the new feature to avoid HTTP Strict Transport Security (HSTS) protection mechanism.  
  
This version changes HTTPS to HTTP as the original one plus the hostname at html code to avoid HSTS. Check my slides at BlackHat ASIA 2014 [OFFENSIVE: EXPLOITING DNS SERVERS CHANGES] (http://www.slideshare.net/Fatuo__/offensive-exploiting-dns-servers-changes-blackhat-asia-2014) for more information.  
  
For this to work you also need a DNS server that reverse the changes made by the proxy, you can find it at https://github.com/LeonardoNve/dns2proxy.


Demo video at: http://www.youtube.com/watch?v=uGBjxfizy48


BUT
===

Cause the new gag law which criminalized the publication of 'offensive' security tools/techniques I have to delete this repository. You can find good forks on MITMf framework (https://github.com/byt3bl33d3r/MITMf) or MANA rogue AP (https://github.com/sensepost/mana).