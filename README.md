# Termux Bootstrap

You can Download one from my Termux Bootstraps for an Special Termux experience
I create a new Folder System

# Install

step 1
```bash
cd /data/data/com.termux/files/
mkdir usr-n
cd usr-n
curl -OL $url
tar -xvf *.tar.xz
```
The url variable set you if you are copy one from my bootstrap file link from the Release and run following command

```bash
url="paste link here"
```

Step 2
For Step 2 boot in Failsafe
```bash
cd /data/data/com.termux/files/
rm -rf usr
mv usr-n/usr .
rm -rf usr-n
```

I will work on an Boostrap Installer script

This Bootstrap support actually only ARM i will work fore more

## Warning
If you not Run the Step2 in Failsafe then crash your Termux

### LICENSE 
This Programm is under the MIT License
