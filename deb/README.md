# DEB packages for apt package managers

This repository provides *deb* packages to install PenRed. Each one has been
compiled with the following capabilities,

1. PenRed-* : Compiled only with multi-threading capabilities
2. PenRed-dicom-* : Compiled with multi-threading and DICOM capabilities

You can download the entire repository or use the following instruction to download a single *deb*,

```console
curl https://raw.githubusercontent.com/PenRed/packages/master/deb/PenRed-XXXX.x86_64.deb --output PenRed.deb
```
where XXXX depends on the desired file to download. Then, install it using

```
sudo apt install ./PenRed.deb
```

Finally, check the installation using 

```
penred -v
```
to print the installed PenRed version.
