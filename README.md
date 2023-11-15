# IServ package for fusion 360

This repository contains the basic implementation of an IServ-Opsi Fusion-360 package.
Please note that you must copy the latest version of the `Fusion 360 Admin Install.exe` into the data folder.
And if you wish to see the Fusion-360 logo while the installation takes place, plase compy the logo as a file named logo.png into the root of this repo.

To install this package:
1. Log in as root
2. Run ```apt update```
3. Run ```apt install git```
4. Run ```cd /srv/deploy/install/```
5. Run ```git clone https://github.com/Jan-OleGiebel/iserv-package-fusion-360.git```
6. Run ```cd opsi-fusion-360```
7. Copy the  latest version of the `Fusion 360 Admin Install.exe` into data/
8. Copy the logo as a file named logo.png into the root of this repo. Please note the opsi image requirements!
9. Run ```chkdeploy```

Use this package at your own risk! <br/>
© 2023 Jan-Ole Giebel