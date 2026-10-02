# How Does It Work
All you have to do, to extend your trial period, is change number in TrialKey element in application.xml. This file is located in /Library/Application Support/Adobe/Adobe Photoshop/AMT. You can navigate there with this command:

```
cd /Library/Application\ Support/Adobe/Adobe\ Photoshop\ */AMT
```
Then you have to open the file and edit it. You can use just TextEdit app.

```
open -a TextEdit application.xml
```
Now find the TrialSerialNumber Data key:

```
<Data key="TrialSerialNumber">911997074887979240115317</Data>
```
And increment this number by one:

```
<Data key="TrialSerialNumber">911997074887979240115318</Data>
```
And that’s it. Now when you relaunch Photoshop you will be prompted to login and you should see fresh 7 days of trial.

# Download
[Or download trial reset here](https://filipmolcik.com/free-photoshop-on-mac-os-x-photoshop-trial-reset/)
