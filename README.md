

<p align="center">

<h1 align="center"> Go Installer </h1>

<p align="center">
<img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat">
<img src="http://hits.dwyl.io/kerolloz/go-installer.svg">
<img src="https://travis-ci.com/kerolloz/go-installer.svg?branch=master">
</p>

<p align="center">
Automate the installation of Golang with no more <strike>hassle of environment variables setting</strike>. :wink: <br>
Go is a fast and easy programming language so, the installation should be <b>fast and easy</b> :zap:, as well.
</p>

</p>

<p align="center">
<img src="https://pilsniak.com/wp-content/uploads/2017/04/golang.jpg" style="width: 80%; height: 80%;">
</p>

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

<p align="center">
<img src="https://media.giphy.com/media/fAKdnja3pZuc4SHt5g/giphy.gif" style="width: 100%;">
</p>

## Insatll golang on Ubuntu or Mac

Tested by Travis :heavy_check_mark: on:
- Linux :penguin:
- Mac :computer:


## Acknowledgments

- Inspired by [golang-tools-install-script](https://github.com/canha/golang-tools-install-script) by canha :sparkles:

## License

[MIT License](/LICENSE.md)
