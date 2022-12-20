![Avalanche](assets/avalanche.png)
# <b> <i> Project Avalanche</i>

Getting Started:
==============

Create the directories
----------------------

As a first step, you'll have to create and enter a folder with the appropriate name.
To do that, run these commands:

```bash
   mkdir avalanche
   cd avalanche
```
   
To initialize your local repository, use a command like this:

```bash
     repo init -u https://github.com/AvalancheOS/manifest -b 13
```

Then to sync up:
================

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
Compilation of Cherish OS:
====================

From root directory of Project, perform following commands in terminal


```bash
. build/envsetup.sh
 lunch device-codename-userdebug
 mka bacon -j$(nproc --all)
```
 -----------------------------------------------------------------------------
