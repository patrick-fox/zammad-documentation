Continuous integration
**********************

All pushes to our main repo @ https://github.com/zammad/zammad will trigger build tests. 
We use internal build tests on internal and external continuous integration platforms.

Internal
========

* Done in our private Continuous integration platform

External
========

Travis-CI
---------

* You can find the build test results @ https://travis-ci.org/zammad/zammad
* If you fork the Zammad repo you're able to also use travis-ci.org to get your builds tested
* Just change the file ".travis.yml" to fit your needs
* Currently build test status is: 
.. image:: https://travis-ci.org/zammad/zammad.svg?branch=develop
  :target: https://travis-ci.org/zammad/zammad

