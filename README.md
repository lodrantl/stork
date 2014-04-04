Java Native Executable Library
==============================

### Contributors

 - [Mfizz, Inc.](http://mfizz.com)
 - Joe Lauer (Twitter: [@jjlauer](http://twitter.com/jjlauer))

### Overview

Utility for generating native launchers for Java-based applications across Windows,
Linux, and Mac OSX. Unlike other "service wrappers", this utility can create
simple console application

While other Java service wrappers attempt to handle re-spawning via a secondary
controller process, what about relatively simple console apps / daemons or
an interest in using better tools for handling re-spawning like monit.

### Canonical layout of application folder

    <app_home>
     - bin
     - lib
     - conf
     - share
     - data

#### Windows

http://jslwin.sourceforge.net/

https://github.com/kohsuke/winsw


### License

Copyright (C) 2014 Joe Lauer / Mfizz, Inc.

This work is licensed under the Apache License, Version 2.0. See LICENSE for details.