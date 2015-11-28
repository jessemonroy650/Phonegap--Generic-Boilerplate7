## Phonegap--Generic-Boilerplate7 ##
Date: 2015-11-22<br>
Last Update: 2015-11-27

A generic boilerplate for constructing PhonegapApps with fastclick.js, zepto.js, cli-5.2.0, crosswalk, all core plugins, and full whitelist implementation.

**NOTE: Networking has not been tested fully.**

*Additions based on updates posted to*

- [config.xml gets an update](http://phonegap.com/blog/2015/11/17/config_xml_update/) - 2015/11/17
- [config.xml gets an update - part 2](http://phonegap.com/blog/2015/11/19/config_xml_changes_part_two/) - 2015/11/19

**Features**

* cli-5.2.0 - unification of versions for different platforms via CLI - See: http://phonegap.com/blog/2015/06/16/phonegap-updated-on-build/
* crosswalk - an alternative to the Google's chrome-based webview - See: https://crosswalk-project.org/documentation/about.html
* fastclick.js - removes the 300ms click delay in Android - See: https://github.com/ftlabs/fastclick
* zepto.js - a jquery-like helper library - See: http://zeptojs.com/

*More details about this boilerplate in*

https://github.com/jessemonroy650/Phonegap--Generic-Boilerplate


### Test Parameters ###

- Phonegap Compiler Version: cli-5.2.0
- Test Device: LG Leon LTE
- Android Version: 5.1.1
- Test Device: Apple iPodtouch
- iOS Version: 8.4.1

### ISSUES as of 2015-11-23 ###

- `CSP` appears not to be working
- [Exit] fires, but does not clear properly, and splash screen does not load on reload.


- QUESTION - What are the `name` Blackberry? http://phonegap.com suggests there are others, but https://build.phonegap.com/ only suggests iOS,Android,Windows
- QUESTION - blog does not address, `gap:qualifier` and `gap:density`?
- QUESTION - what are valid children of `<platform (...)>` - `<icon>,<splash>,<preference>,<plugin>,'whitelist'`?
