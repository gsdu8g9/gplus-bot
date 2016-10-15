# DEPRECATED

# Google Plus status update bot

* Contributors: [lukapusic](https://github.com/lukapusic)
* Author: Luka Pusic <luka@pusic.si>
* Blog post: http://360percents.com/posts/first-google-google-plus-status-update-bot-in-php/

## Description
Google Plus status update bot can log into Google account and update Google+ status. All this is done without Google API,
OAuth, tokens or any other annoying products. The script tries to mimic a real, human login. While I try to maintain the script and keep it working, it happens from time to time that Google changes their source code, rendering the script unusable, therefore the code is somewhat unreliable and should be used with this in mind.

## System requirements
* PHP with Curl extension

## Instructions
1. Open gplus.php and edit email and password
2. run it ```php gplus.php```

## Changelog

#### Nov 11, 2011
* added debug parameter, pageid parameter, pc_uagent parameter
* page updating still not implemented

#### Nov 16, 2011
* changed the way baseurl is determined, google removed base href

#### Dec 15, 2011
* post visibility is not public by default

#### Mar 2, 2012
* fixed "&" encoding (thx Pauly)

## Known issues
* fails if you didn't confirm mobile location terms and conditions
* fails if you have mobile verification enabled (aka 2 step authentication), no way to fix this

## TODO
* add an option to change post visility
* add posting to pages
* make username and password input as argument

## License
[CC-BY-NC](https://creativecommons.org/licenses/by-nc/2.0/), [Luka Pusic](http://pusic.si)
