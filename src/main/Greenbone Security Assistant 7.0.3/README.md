For detailed code changes, please visit
https://github.com/greenbone/gsa/commits/gsa-7.0
or get the entire source code repository and view log history:
$ git clone https://github.com/greenbone/gsa.git
$ cd gsa && git checkout gsa-7.0 && git log

This is the third maintenance release of the Greenbone Security
Assistant (GSA) 7.0 module for the Open Vulnerability Assessment System
release 9 (OpenVAS-9). It is the web client that makes the full feature
set of OpenVAS Manager available in a web browser.

Many thanks to everyone who has contributed to this release:
Timo Pollmeier, Matthew Mundell, Hani Behabiles, Bjoern Ricks, Michael
Wiegand.

### Main changes compared to 7.0.2:

- An issue which caused saving a scan config to fail under certain circumstances has been addressed.
- An issue which caused the users language setting to be reset under certain circumstances has been addressed.
- A log message is now written for every successful login.
- A number of minor interface issues have been addressed.
- The limit on the target host input field has been removed.
- Support for responding to a request for 'robots.txt' has been added.
- An issue which caused performance problems when deleting overrides has been addressed.
- An issue which caused the refresh function to interrupt the access to any gsa menu has been addressed.
- An option to resume uncompleted scheduled tasks has been added.
- SMB alerts have been added.
- Cancelling the loading of a page, dialog, dashboard etc. in GSA can now also cancel the corresponding request to manger, improving performance.
- An issue which caused an internal error getting performance info of an unconnected slave has been addressed.
- German translations have been updated.
- Arabic translations have been updated.
- French translations have been updated.
- Chinese translations have been updated.
- An issue which caused problems where pages reverted to a built in filter has been addressed.
- The group selection for users now only shows groups which the current user has permission to add users to.
- The HTTP header "Host" now has to be validated against a list of IP addresses and hostnames, which includes localhost and local interface addresses by default.
- The new TippingPoint alert method has been added.
- Status details to certain error dialogs have been added.
- New error message for invalid Host header has been added.
- Date pickers in the schedule dialogs now allow setting dates in the past.
- Documentation and help have been updated.
- An issue with file upload form elements has been fixed.
- The performance of the result details has been improved by requesting manager to skip counting the results.