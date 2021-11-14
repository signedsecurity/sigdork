# sigdork

[![release](https://img.shields.io/github/release/signedsecurity/sigdork?style=flat&color=0040ff)](https://github.com/signedsecurity/sigdork/releases) ![maintenance](https://img.shields.io/badge/maintained%3F-yes-0040ff.svg) [![open issues](https://img.shields.io/github/issues-raw/signedsecurity/sigdork.svg?style=flat&color=0040ff)](https://github.com/signedsecurity/sigdork/issues?q=is:issue+is:open) [![closed issues](https://img.shields.io/github/issues-closed-raw/signedsecurity/sigdork.svg?style=flat&color=0040ff)](https://github.com/signedsecurity/sigdork/issues?q=is:issue+is:closed) [![license](https://img.shields.io/badge/license-MIT-gray.svg?colorB=0040FF)](https://github.com/signedsecurity/sigdork/blob/master/LICENSE) [![twitter](https://img.shields.io/badge/twitter-@signedsecurity-0040ff.svg)](https://twitter.com/signedsecurity)

## Resources

* [Features](#features)
* [Usage](#usage)
* [Installation](#installation)
    * [From Binary](#from-binary)
    * [From source](#from-source)
    * [From github](#from-github)
* [Contribution](#contribution)

## Usage

To display help message for sigurlx use the `-h` flag::

```
$ sigdork -h

     _           _            _    
 ___(_) __ _  __| | ___  _ __| | __
/ __| |/ _` |/ _` |/ _ \| '__| |/ /
\__ \ | (_| | (_| | (_) | |  |   < 
|___/_|\__, |\__,_|\___/|_|  |_|\_\ v1.2.0
       |___/

USAGE:
  sigdork [OPTIONS]

OPTIONS:
  -e, --engine          search engine (default: google)
  -p, --pages           number of pages (default: 1)
  -q, --query           search query (use `-q -` to read from stdin)
```

## Installation

#### From Binary

You can download the pre-built binary for your platform from this repository's [releases](https://github.com/signedsecurity/sigdork/releases/) page, extract, then move it to your `$PATH`and you're ready to go.

#### From Source

sigdork requires **go1.14+** to install successfully. Run the following command to get the repo

```bash
$ GO111MODULE=on go get -u -v github.com/signedsecurity/sigdork/cmd/sigdork
```

#### From Github

```bash
$ git clone https://github.com/signedsecurity/sigdork.git; cd sigdork/cmd/sigdork/; go build; mv sigdork /usr/local/bin/; sigdork -h
```
## Contribution

[Issues](https://github.com/signedsecurity/sigdork/issues) and [Pull Requests](https://github.com/signedsecurity/sigdork/pulls) are welcome.