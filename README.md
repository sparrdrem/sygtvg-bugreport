# sygtvg-bugreport

Bug report program. Used to send bugreports to issues.

### Building Linux Debian Package

Prerequisites:
```
apt-get install dpkg-dev
```

Extract the linux-binary folder from the zip archive. cd into linux binary and enter root. Once in root, run
```
dpkg-buildpackage -us -uc
```
and the package will build. When the package is installed, head to Menu > Games > Sam&Yoe Group Bug Reports
