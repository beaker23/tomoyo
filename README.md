# tomoyo
This repository hosts various configuration files to ease the creation of domain policy using TOMOYO's learning mode.

The purpose of this project was originally to create a patternize.conf file that greatly eased creation of domain policy using the learning mode in TOMOYO and is capable of working across different platforms. Within this context its aim is to create whole-system MAC domain policy through the learning mode. While this is the original scope it is still incomplete and may be altered or used as desired to create domain policy for specific applications on your system or for whole system MAC.

This was seen as being needed since file systems differ across different platforms and the learning function in TOMOYO can be much simpler to use once a patternize.conf file is created that can create an administrator's desired domain policy. This allows the policy to be more portable across systems, since hardware addresses, installed applications and file systems are likely to differ from system to system. This can cause domain policy to be difficult to port from one system to another if these differences exist.

As a result, the patternize.conf file is an attempt to ease the creation of domain policy, provide a high level of granularity and at the same time allow policy to be portable. The portability can be achieved through altering the patternize.conf and using TOMOYO's learning mode to create the desired domain policy.

Depending upon the desires of a system administrator altering this file and using it in the creation of domain policy can make the security more or less granular.

An exception policy configuration file is not provided and would need to be created by a system administrator.

This does not make creating domain policy automatic using the learning mode. It is only intended to ease and speed up the process while providing granular security. System administration is still needed by a competent admin.

The configuration file is still a work in progress and is incomplete.
