# Getting started with NervaOS
![AvalancheOS](https://github.com/AvalancheOS/manifest/blob/master/banner.png?raw=true)


## Initialize Local Repository
-------------
```bash
  repo init -u https://github.com/AvalancheOS/manifest -b <select_branch>
```


## Syncing Repository
-------------
```bash
   repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```


## Lunch Command
-------------
```bash
  . build/envsetup.sh
  lunch ava_<devicecodename>-userdebug
  mka bacon -j$(nproc --all)
```