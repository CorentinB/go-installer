

<center>

<h1> Go Installer </h1>

<br>

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
[![HitCount](http://hits.dwyl.io/kerolloz/go-installer.svg)](http://hits.dwyl.io/kerolloz/go-installer)
[![Build Status](https://travis-ci.com/kerolloz/go-installer.svg?branch=master)](https://travis-ci.com/kerolloz/go-installer)

<br> <br>

Automate the installation of Golang with no ~~hassle of environment variables setting~~. :wink:  
Go is a fast and easy programming language so, the installation should be **fast and easy** :zap:, as well.

</center>

<br>

<img src="https://pilsniak.com/wp-content/uploads/2017/04/golang.jpg" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;">

## How to use it

You can clone the repository or just use `wget` to download the script

```bash
wget https://raw.githubusercontent.com/kerolloz/go-installer/master/go.sh
bash go.sh
```
Now, You can go grab a cup of coffee :coffee:, set back :relieved: and watch the magic happen! :crystal_ball:

## How it works

The script does the following steps:

- automatically checks the installed operating system (Linux or Mac)
- detects system architecture (armv6, armv8, amd64, i386)
- parses the [golang](https://golang.org/dl) download page for the latest version of Go that is available for your platform and architecture
- downloads the latest version
- creates needed folders for workspace and Go binaries
- extracts the files of the downloaded package
- adds the binaries to PATH environmental variable

<img src="https://media.giphy.com/media/fAKdnja3pZuc4SHt5g/giphy.gif" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;">


## Insatll golang on Ubuntu or Mac

Tested by Travis on:
- Linux :white_check_mark:
- Mac :white_check_mark:


### Acknowledgments

- Inspired by [golang-tools-install-script](https://github.com/canha/golang-tools-install-script) by canha :sparkles:

## License

[MIT License](/LICENSE.md)
