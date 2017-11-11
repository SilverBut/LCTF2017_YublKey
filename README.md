# LCTF 2017: YublKey

Some open-source keyboard, such as GH60, is interestring. However, they can also be hackable if users are trying to flash from something they know completely nothing about it.

This "YublKey" **(not YubiKey!)** will try to modify *tmk_keyboard*, a famous open-source keyboard firmware project. I have added a keylogger into the internal RAM of it, and once accepted appropiate input, it will output all internal RAM contents out.

The target is GH60 (using ATMega32u4, which has a config file in IDA) with only 2Kbytes of SRAM so we need to use it wisely.

See `ctf_output/`(in chinese) for more info.

This contest might be the last time for me, to write a challenge for CTF games. Thanks for XDSEC, and thanks for all my friends.

Happy hacking!

* * *

## Legal Statement

IDA, ATMEL, AVR and all other trademarks cited herein are the property of their respective owners.

Copyright of this repo is belonging to the original author of those code.

Unless otherwise stated, you are requested to follow GPLv3 to use code in this repo.

The following related parts are NOT allowed to use this code, unless a statement is signed and published by the author:

* Humensec (http://www.humensec.com)
* Network Behaviour Research Center (NBRC) in Xidian University (http://nbrc.xidian.edu.cn)
* School of Cyber Engineering of Xidian University (http://ce.xidian.edu.cn)
* Leaders, researchers, students and any other people or entity sharing common benefits with entities above

According to the relevant laws, including the *Cybersecurity Law of the People's Republic of China*, the author and other related entities will resort to legal measures if you are not complying this license.
