# Researchers Uncover Threat of ‘Unusual’ Virtual Machine Crypto Mining ...

###### 2019-06-24 04:06

Cybersecurity firm ESET has detected what it describes as an unusual and persistent cryocurrency miner distributed for macOS and Windows since August 2018.

According to ESET, the new malware, dubbed “LoudMiner,” uses virtualization software — VirtualBox on Windows and QEMU on macOS — to mine crypto on a Tiny Core Linux virtual machine, thus having the potential to infect computers across multiple operating systems.

The miner itself reportedly uses XMRig — an open-source software used for mining privacy-focused altcoin monero (XMR) — and a mining pool, thereby purportedly thwarting researchers’ attempts to retrace transactions.

The research revealed that for both macOS and windows, the miner operates within pirated applications, which are bundled together with virtualization software, a Linux image and additional files.

ESET notes that the miner targets applications whose purposes are related to audio production, which usually run on computers with robust processing power and where high CPU consumption — in this case caused by stealth crypto mining — might not strike users as suspicious.

ESET has identified three strains of the miner targeted at macOS systems, and just one for Windows thus far.

Network connections to unusual domain names — due to scripts inside the virtual machine that contacting the C&C server to update the miner’s configuration — are another giveaway, the researchers add.

[Original source](https://cointelegraph.com/news/researchers-uncover-threat-of-unusual-virtual-machine-crypto-mining)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")