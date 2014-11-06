jentin-test-5.3.2
=================

installs PHP 5.3.2 on Ubuntu 10.04 and runs PHPUnit 3.6 for Jentin.


Links
---

Jentin: https://github.com/sigma-z/Jentin

Docker Repository: https://registry.hub.docker.com/u/stevennikolic/jentin-test

Output
---

PHP 5.3.2-1ubuntu4.28 with Suhosin-Patch (cli) (built: Oct 29 2014 11:54:47)

Copyright (c) 1997-2009 The PHP Group

Zend Engine v2.3.0, Copyright (c) 1998-2010 Zend Technologies


PHPUnit 3.6.12 by Sebastian Bergmann.

...............................................................  63 / 101 ( 62%)

.....................................F

Time: 0 seconds, Memory: 9.00Mb

There was 1 failure:

1) Test\Jentin\Mvc\View\RendererTest::testGetNotExistingVarTriggersError

Failed asserting that exception of type "\PHPUnit_Framework_Error_Notice" is thrown.

/var/www/Jentin/vendor/pear-pear.phpunit.de/PHPUnit/bin/phpunit:46

FAILURES!

Tests: 101, Assertions: 181, Failures: 1.
