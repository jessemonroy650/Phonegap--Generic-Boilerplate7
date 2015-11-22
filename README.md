## Phonegap--Generic-Boilerplate7 ##
Date: 2015-11-22<br>
Last Update: 2015-11-22

A generic boilerplate for constructing PhonegapApps with fastclick.js, zepto.js, cli-5.2.0, crosswalk, all core plugins, and full whitelist implementation

*Additions based on updates posted on the [Official Phonegap Blog](http://phonegap.com/blog/2015/06/16/phonegap-updated-on-build/)*<br />
*SEE BOTTOM* for additional official issues as of 2015-06-19

**Additions vs Boilerplate2**

* cli-5.1.1 - unification of versions for different platforms via CLI - See: http://phonegap.com/blog/2015/06/16/phonegap-updated-on-build/
* crosswalk - an alternative to the Google's chrome-based webview - See: https://crosswalk-project.org/documentation/about.html

**Retentions from Boilplate2**

* fastclick.js - removes the 300ms click delay in Android - See: https://github.com/ftlabs/fastclick
* zepto.js - a jquery-like helper library - See: http://zeptojs.com/

*More details about this boilerplate in*

https://github.com/jessemonroy650/Phonegap--Generic-Boilerplate

### ISSUES as of 2015-06-19 ###

* 2015-06-18 - *[Notes for upgrading to cli-5.1.1 on PGB](http://community.phonegap.com/nitobi/topics/notes-for-upgrading-to-cli-5-1-1-on-pgb)* (one to issues fixed @ 2015-06-19T17:42:56)
* 2015-06-19 - There can only be one *phonegap-version* attribute per file; this appears to be a bug.
