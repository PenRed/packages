# RPM packages for yum and dnf package managers

This repository provides rpm packages to install PenRed using yum or dnf. Each one has been
compiled with the following capabilities,

1. PenRed-* : Compiled only with multi-threading capabilities
2. PenRed-dicom-* : Compiled with multi-threading and DICOM capabilities

You can download the entire repository or use the following instruction to download a single rpm,

```console
curl https://raw.githubusercontent.com/PenRed/packages/master/rpm/PenRed-XXXX.x86_64.rpm --output PenRed.rpm
```
where XXXX depends on the desired file to download. Then, install it using

```
sudo dnf install PenRed.rpm
```

Finally, check the installation using 

```
penred -v
```
to print the installed PenRed version.
