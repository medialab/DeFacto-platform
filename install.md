# 1. Setup of the wiki

## WAR 

XWiki Standard 13.4.5.

No specific configuration.

## Wikis

The project consists of a main wiki installed with the standard flavor.

## Extensions

Install the following extensions:

* Video macro: org.xwiki.contrib:macro-video version 1.14.1
* HTTP application: org.xwiki.contrib:xwiki-http-lib version 1.0
* Relations application: org.xwiki.contrib:application-relations-ui version 3.0

Uninstall the following extensions:

* XWiki Standard Tour: org.xwiki.platform:xwiki-platform-distribution-flavor-tour
* XWiki Default Templates: org.xwiki.contrib.templates:application-templates-ui

## Apache

* robots.txt: make sure to remove the line disallowing indexing the /download/ URLs: ```Disallow: /xwiki/bin/download/```

# 2. Installation of the custom code

## File system modules 

No specific configuration.

## Main wiki

### New Install

* Delete page "Main.WebHome" without deleting its children.
* Download XAR 
* Update wiki to monolingual, French only (check)
* Import XAR with Admin account, with options "reset history to 1.1", and "import as backup package" activated

### Upgrade

* Download XAR
* Import XAR with Admin account, with options "reset history to 1.1", and "import as backup package" activated
