# SPlus_MD5


This module allows for basic MD5 calculations in S+. This is useful to maintain compatibility with 2-series processors.

Please note, this module will only calculate the MD5 for a string less than 40 characters long. Array based math in S+ makes it 
complicated to do more than that.

MD5 generator based on the code found on this page: http://pajhome.org.uk/crypt/md5/index.html