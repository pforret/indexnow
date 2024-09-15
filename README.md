![bash_unit CI](https://github.com/pforret/indexnow/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/indexnow/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/indexnow)
![GH stars](https://img.shields.io/github/stars/pforret/indexnow)
![GH tag](https://img.shields.io/github/v/tag/pforret/indexnow)
![GH License](https://img.shields.io/github/license/pforret/indexnow)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# pforret/indexnow

![](assets/indexnow.jpg)

submit URLs to search engine with [IndexNow protocol](https://www.bing.com/indexnow/getstarted)

## 🔥 Usage

```
Program : indexnow  by peter@forret.com
Version : v1.0.0 (Sep 15 19:06:37 2024)
Purpose : submit URLs to search engine with IndexNow protocol
Usage   : indexnow [-h] [-Q] [-V] [-f] [-A <API>] [-K <KEY>] [-L <LOG_DIR>] [-T <TMP_DIR>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -Q|--QUIET       : [flag] no output [default: off]
    -V|--VERBOSE     : [flag] also show debug messages [default: off]
    -f|--FORCE       : [flag] do not ask for confirmation (always yes) [default: off]
    -A|--API <?>     : [option] API endpoint  [default: https://api.indexnow.org/IndexNow]
    -K|--KEY <?>     : [option] API key for IndexNow - get one on https://www.bing.com/indexnow/getstarted
    -L|--LOG_DIR <?> : [option] folder for log files   [default: /Users/pforret/log/indexnow]
    -T|--TMP_DIR <?> : [option] folder for temp files  [default: .tmp]
    <action>         : [choice] action to perform  [options: sitemap,url,key,check,env,update]
    <input>          : [parameter] input url (1 page or sitemap) (optional)
                                  
### TIPS & EXAMPLES
* use indexnow sitemap <url> to submit all URLs in a sitemap to Bing/Google
  indexnow sitemap https://example.com/sitemap.xml
* use indexnow url <url> to submit 1 URL to Bing/Google
  indexnow url https://example.com/news/page100/
* use indexnow key <url> to check the key file
  indexnow -K AZ102512655155PMDGHERY4225865 key https://example.com
* use indexnow check to check if this script is ready to execute and what values the options/flags are
  indexnow check
* use indexnow env to generate an example .env file
  indexnow env > .env
* use indexnow update to update to the latest version
  indexnow update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar```

## ⚡️ Examples

```bash
> indexnow -h 
# get extended usage info
> indexnow env > .env
# create a .env file with default values
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/indexnow

or with `git`

	$ git clone https://github.com/pforret/indexnow.git
	$ cd indexnow

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2024 Peter Forret

