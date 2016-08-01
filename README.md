Team Toxic 6.0 Beta (AOSP)+RRO
===========

To initialize your local repository using the AOSP-RRO trees, use a command like this:
````bash
repo init -u git://github.com/Team-Toxic/platfrom_manifest.git -b mm
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh falcon
./build.sh titan
```

