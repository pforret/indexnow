![bash_unit CI](https://github.com/pforret/indexnow/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/indexnow/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/indexnow)
![GH stars](https://img.shields.io/github/stars/pforret/indexnow)
![GH tag](https://img.shields.io/github/v/tag/pforret/indexnow)
![GH License](https://img.shields.io/github/license/pforret/indexnow)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# indexnow

submit URLs to search engine with IndexNow protocol

## 🔥 Usage

```
Program : indexnow  by peter@forret.com
Version : v0.0.1 (Apr 22 16:07:13 2023)
Purpose : submit URLs to search engine with IndexNow protocol
Usage   : indexnow [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/script]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/script]
    <action>         : [choice] action to perform  [options: action1,action2,check,env,update]
                                  
### TIPS & EXAMPLES
* use indexnow action1 to ...
  indexnow action1
* use indexnow action2 to ...
  indexnow action2
* use indexnow check to check if this script is ready to execute and what values the options/flags are
  indexnow check
* use indexnow env to generate an example .env file
  indexnow env > .env
* use indexnow update to update to the latest version
  indexnow update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

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
