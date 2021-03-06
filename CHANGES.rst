Changes
=======

4.1.1 (unreleased)
------------------

- TBD


4.1.0 (2014-12-29)
------------------

.. note::

   Support for PyPy3 is pending release of a fix for:
   https://bitbucket.org/pypy/pypy/issue/1946

- Add support for Python 3.4.

- Add support for testing on Travis.


4.0.2 (2013-11-12)
------------------

- Add missing ``six`` dependency


4.0.1 (2013-02-22)
------------------

- Fix a previously untested Python 3.3 compatibility problem.


4.0.0 (2013-02-14)
------------------

- Remove hard dependency on ``zope.tal``, which was already conditionalized
  but required via ``setup.py``.

- Add support for Python 3.3 and PyPy.

- Replace deprecated ``zope.interface.implements`` usage with equivalent
  ``zope.interface.implementer`` decorator.

- Drop support for Python 2.4 and 2.5.

- Fix documentation link in README.txt


3.5.2 (2012-05-23)
------------------

- Subexpressions of a 'string:' expression can be only path expressions.
  https://bugs.launchpad.net/zope.tales/+bug/1002242


3.5.1 (2010-04-30)
------------------

- Remove use of ``zope.testing.doctestunit`` in favor of stdlib's 'doctest.


3.5.0 (2010-01-01)
------------------

- Port the lazy expression from ``Products.PageTemplates``.


3.4.0 (2007-10-03)
------------------

- Update package setup.

- Initial release outside the Zope 3 trunk.


3.2.0 (2006-01-05)
------------------

- Corresponds to the verison of the zope.tales package shipped as part of
  the Zope 3.2.0 release.

- Documentation / test fixes.


3.0.0 (2004-11-07)
------------------

- Corresponds to the verison of the zope.tales package shipped as part of
  the Zope X3.0.0 release.
