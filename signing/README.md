# 420 Signer

420 Signer is an extremely fast and versatile signing utility for the macOS (and CentOS soon) operating system.

  - Based on [zSign] by [@zhlynn]
  - Used by the Ignition Team [@TryIgnition]
  - 100% Open Source

### Requirements
* OpenSSL 1.0.2t
* macOS
* P12
* Mobileprovision
* Password
* Some terminal knowledge

### Features
* Sign app
* Bulk resign app

### To-Do

### Installation
```
cd path/to/420Signer/folder/
chmod 777 420
chmod 777 420Signer
```

### Example
```
# Sign a single app

./420Signer -f SA -a ~/Downloads/dolphin.ipa -m ~/Downloads/420/mb.mobileprovision -c ~/Downloads/420/p12.p12 -p 123

# Sign a folder full of apps

./420Signer -f R -b ~/Desktop/IPAs -m ~/Downloads/420/mobileprovision.mobileprovision -c ~/Downloads/420/p12.p12 -p password
```

License
----
GNU General Public License v3.0


**Free Software, Hell Yeah!**
   
[@TryIgnition]: <https://twitter.com/TryIgnition>
[@zhlynn]: <https://github.com/zhlynn>
[zSign]: <https://github.com/zhlynn/zsign>