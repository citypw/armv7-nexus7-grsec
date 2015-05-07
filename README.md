# armv7-nexus7-grsec

PaX/Grsecurity patch for Nexus7, which the original version is 3.4
kernel based with a bunch of backport features and fixes. In some
particular cases, TrustZone is useless if the Android kernel were
compromised. I don't think we need another rootkit-friendly solution
like SELinux always does. Get rid of one entire class of vulns in
kernel would be an inevitable ways to make your device secure.


# Credit for PaX/Grsecurity

PaX/Grsecurity is the most respected 0ld sch00l community and they
have been creating the best defense-in-depth kernel hardening solution
for 14 years. What PaX/Grsecurity brings to us, is amazing and
incridble work. Unfortunately, there are a lot of reasons that
PaX/Grsecurity don't get the credit what they deserves. Let me make
this short: To love those who are hatred by BIG BROTHER. That's the 
fuc*ing point.


# What makes us ticks

The age of IoT( Internet of things) is coming soon...There will be
huge numbers of devices running with diverse communication
protocols. For the simply classify, I'll only treat these devices as
two types: One with TCP/IP stack, or not. The one with TCP/IP stack
might have high probablity run with GNU/Linux. The one without TCP/IP
stack may be just a simple MCU stuff. The heterougenous network need
to be protected in various ways. These devices may be running on our
cars, refrigrator, or everywhere around us, which could be a risk to
our money-shitty property and even lives. That's one of most important
reasons we need to "H A R D E N E N I N G   E V E R Y T H I N G" by free
software.
