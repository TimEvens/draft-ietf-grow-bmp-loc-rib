Support for Local RIB in BGP Monitoring Protocol (BMP)
======================================================

> ### draft-ietf-grow-bmp-local-rib

- - -

Generating text from xml
------------------------

> One time only

* Install the latest [xml2rfc](https://xml2rfc.tools.ietf.org/)
* On Mac, you can install it using ```brew install xml2rfc```

> You'll do this each time you want to generate a text version

```
tievens@$ xml2rfc draft-ietf-grow-bmp-loc-rib.xml --text
Parsing file draft-ietf-grow-bmp-loc-rib.xml
Created file draft-ietf-grow-bmp-loc-rib.txt
```

Diff/Changes
------------

Normally use github to see the diffs but you can use command line ```git diff```, standard ```diff```, ```colordiff``` or something better such as Jetbrains [IntelliJ](https://www.jetbrains.com/idea/) which will provide one of the best side by side diffs.  

Example using colordiff.  

* Install colordiff: ```brew install colordiff```
* Run: ```colordiff -bBu draft-evens-grow-bmp-loc-rib-00.txt draft-ietf-grow-bmp-loc-rib.txt```

##### Example:

```diff
--- draft-evens-grow-bmp-loc-rib-00.txt	2017-05-23 09:30:56.000000000 -0700
+++ draft-ietf-grow-bmp-loc-rib.txt	2017-06-07 10:27:41.000000000 -0700
@@ -4,14 +4,15 @@

 Global Routing Operations                                       T. Evens
 Internet-Draft                                              S. Bayraktar
-Intended Status: Standards Track                             M. Bhardwaj
-Expires: September 11, 2017                                Cisco Systems
-March 10, 2017                                                P. Lucente
+Updates: 7854 (if approved)                                  M. Bhardwaj
+Intended status: Standards Track                           Cisco Systems
+Expires: December 9, 2017                                     P. Lucente
                                                       NTT Communications
+                                                            June 7, 2017

-         Support for Local RIB in BGP Monitoring Protocol (BMP)
-                   draft-evens-grow-bmp-local-rib-00

+         Support for Local RIB in BGP Monitoring Protocol (BMP)
+                     draft-ietf-grow-bmp-loc-rib-00

 Abstract

@@ -24,46 +25,39 @@
    Decision Process. These are the routes over all peers, locally
    originated, and after best-path selection.
```



