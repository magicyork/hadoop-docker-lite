- Create base image with [Alpine Linux distro](http://www.alpinelinux.org/) 
- Install essential linux packages
- Install Open JDK 7. All hadoop images should extend this one.
- Prepare image with directories like /opt


Building the image
----
- ``docker build -t pkeropen3/alpine-base .``

Version
---
- Alpine linux:  latest
- Java: Open JDK 7 

