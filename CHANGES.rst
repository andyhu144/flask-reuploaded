Changelog
=========

1.4.0 (2023.10.03)
------------------
- fix deprecation warning for pytest
- drop support for Python 3.6 / 3.7
- add support for Python 3.12
- upgrade dependencies for building docs

1.3.0 (2022.12.20)
------------------
- improve documentation
- drop support for Python 3.6
- add support for Python 3.11
- update dependencies for building documentation


1.2.0 (2021.11.07)
------------------
- add contexts to coverage report
- pin documentation dependencies to prevent future breakage
- fix typing errors (mypy) with recently released Flask 2.0.1
- add support for Python 3.10


1.1.0 (2021.05.09)
------------------
- make type checkers aware that this library is using type annotations


1.0.0 (2021.04.07)
------------------
- raise test coverage to 100%
- use official `Pallets` theme for the documentation
- remove deprecated `patch_request_class` helper function; use `MAX_CONTENT_LENGTH` instead.
- `autoserve` now has been deactivated by default and needs explicit activation
  via the setting `UPLOADS_AUTOSERVE=True`


0.5.0
-----
- improve documentation of example app
- document surprising `autoserve` feature
- issue a warning when using `autoserve` without explicit configuration


0.4.0
-----
- add type annotations
- drop support for Python 2 and Python 3.5
- deprecate `patch_request_class`
- use a `src` directory for source code
- add tox env for check-python-versions
- add flake8-bugbear
- add short contribution guide
- add `getting started`
- delete broken example and add minimal example to README
- add support for Python 3.9
- use gh actions instead of Travis CI


0.3.2
-----
- documentation update

  * update docs/index.rst
  * use blue ReadTheDocs theme
  * update sphinx configuration
  * add documentation link to `setup.py`, so it shows on PyPi
  * add note about documentation in the README file
  * delete old theme files
- configure `isort` to force single line imports


0.3.1
-----
- add badges to README
- add migration guide from `Flask-Uploads` to `Flask-Reuploaded`
- add packaging guide
- update installation instruction in README


0.3
---

The following changes were introduced in the early `Flask-Reuploaded`
release series.

- rename package from `Flask-Uploads` to `Flask-Reuploaded`
- update `setup.py`
- start using pre-commit.com
- update README
- setup CI (Travis)
- fix broken tests
- make use of `pytest` instead of the no longer maintained `nose`
- add a changelog and start tracking changes
