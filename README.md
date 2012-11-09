Glue mod
========

Author: Joe Topjian, joe@topjian.net
Mod by: KeepZero, i@keepzero.net

Glue is a simple PHP class that maps URLs to classes. The concepts are similar to web.py for Python.

Information on how to use Glue can be found at http://gluephp.com.

DIFF with origin glue.php
=========================
- Remove URL rewrite require, now not require URL rewirte.
- Splite the REQUEST_URI with a '?' char, not require special regex in urls


License
=======
Glue is licensed under a BSD license. See LICENSE file for further details.

Pull Requests
=============
Since creating and publishing GluePHP, I have received a lot of patches and pull requests. Each
modification is vastly different than the other.

GluePHP is a __very__ simple PHP script and there are an almost infinite amount of modifications
and alternative styles that can be applied to it. Because of this, I do not accept patches or
pull requests. All patches that I have received have had very good ideas, so I do not think it
would be fair to accept some patches and not others (since most are incompatible with each other).

GluePHP is BSD licensed. By all means, fork the code, hack it up as much as you want, and 
republish it. :)
