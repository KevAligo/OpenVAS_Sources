This is the third maintenance release of the openvas-scanner 5.1 module
for the Open Vulnerability Assessment System 9 (OpenVAS-9).

Many thanks to everyone who has contributed to this release:
Hani Benhabiles, Juan Jose Nicola, Timo Pollmeier, Jan-Oliver Wagner
and Michael Wiegand.

### Main changes compared to 5.1.2:

- An issue which caused the scanner host process to get stuck searching for plugins has been addressed.
- Dependency for openvas-libraries has been raised from 9.0.2 to 9.0.3.
- Checking routines for tcp and udp required ports have been improved.
- Handling of requests from manager during the plugin load up has been improved.
- Support to specify a regex-based mandatory key has been added.
- New scanner option "time_between_request" has been added.
- NVT metadata cleanup has been improved.