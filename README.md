# URL-Shortener

A simple url shortening command-line based application written in python using bit.ly, j.mp, tiny.cc and more


## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [Supported Services](#supported-services)


## Install

### Method 1 - Using pip

```bash
pip install URL-Shortener
```

### Method 2 - Build from source

```bash
$ git clone  https://github.com/lakshminarayana-k/URL-Shortener.git
$ cd URL-Shortener
$ python setup.py install
```

## Usage

##### Shorten URL using bit.ly

```bash
$ shortn <url>
```

##### Shorten URL using j.mp

```bash
$ shortn -j <url>
```

##### See help for more information.

```bash
$ shortn --help
```

      Usage: shortn [-h] [-j] [-t] [-i] [-v] [-c] [-V] url
       
      Shorten URL using the following services: bit.ly, j.mp, t.cn, is.gd, v.gd,
      tiny.cc.
       
      positional arguments:
        url            Enter the URL to shorten here
       
      optional arguments:
        -h, --help     show this help message and exit
        -j, --jmp      use j.mp to shorten url
        -t, --tcn      use t.cn to shorten url
        -i, --isgd     use is.gd to shorten url
        -v, --vgd      use v.gd to shorten url
        -c, --tinycc   use tiny.cc to shorten url
        -V, --version  show program's version number and exit
        
## Supported Services

* bit.ly
* j.mp
* t.cn
* is.gd
* v.gd
* tiny.cc
 
