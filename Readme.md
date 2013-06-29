CMEP-sources
============

This is the real content for CMEP-site.

Copied from CMEP-Site/sources on Saturday 29th June 2013 at 15:52.
A record of the history before this date exists in the CMEP-Site repository.

Assuming that CMEP-Site lives in parentDir/CMEP-Site, please follow these instructions:

1. `cd parentDir`

1. `git clone git@github.com:CMEPorg/CMEP-sources.git`. You should now have CMEP-site and CMEP-sources alongside each other.

1. `cd CMEP-Site` -- change directory to the site

1. `grunt clearance:0` -- Clearance levels of 0 or above will cause CMEP-Site to use this CMEP-sources
directory. The location of CMEP-sources is in fact configurable in `Gruntfile.coffee` through the variable `yeomanConfig.content`. By default it is set to '../CMEP-sources'.

1. To switch to using the sample sources located at `yeomanConfig.samples` -- by default the sources directory inside CMEP-site, say `grunt clearance:-1`. All negative clearance levels cause the samples site to be used.


1. To check at any time which sources are currently configured, use `grunt clearance`.