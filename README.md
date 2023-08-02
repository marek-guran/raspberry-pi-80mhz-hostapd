# Working 80 MHz hostapd for Raspberry Pi 4B
I have tested it with RaspAP and used Ubuntu Server 23.04.

I was trying to make this work for months and I could not find any hostapd.conf, that would do 80 MHz. Anything I found to make it work, was just crashing the hostapd. So I just tried and tried and managed to make it work in the end.

Note: It is 80 MHz, but for some reason it allows only 433 Mbps link speed instead of 866 Mbps. But still better than 200 Mbps on 40 MHz.
