maven-pom-mode
==============

An EMACS major mode for editting maven pom files


I am creating this mode to pull together a lot of the ideas on pom editting from around the inter-tubes as well as to integreate with https://github.com/m0smith/malabar-mode via issue https://github.com/m0smith/malabar-mode/issues/92.

## What it is good for

* Integrates with nxml-mode for error highlighting and code completion.  
** `C-M-i` give valid suggestions. 
** `C-c /` will close a tag.
* Search for artifacts in maven central via `maven-pom-search`

## Installation

From the shell:

```
git clone https://github.com/m0smith/maven-pom-mode.git
```

In Emacs:

```
(add-to-list 'load-path "path to maven-pom-mode")
(load "maven-pom-mode")
```

## Acknowledgements

I am indeed standing on the shoulders of giants including:
*  [torstein.k.johansen](http://tkj.freeshell.org/emacs/xml/#my-rnc-files) for nXML integration ideas and files
*  [Dave Paroulek](https://github.com/upgradingdave/maven-mode) for the work on searching for artifacts in maven central (or other nexus repo)
