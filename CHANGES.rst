Changelog
=========


1.2 (unreleased)
----------------

- Add a utils view so that tokens can be added more easily from a script [dmarks]
- Apply the tokenrole interface to ATCTMixin so it applies to folders too [dmarks]
- fix to prevent request being accessed unless its there. helps with p.a.async [djay]


1.1.1 (2019-01-06)
------------------

- Fixed missing urllib import with Python3 compatible import and add six as dependency
  [MrTango]


1.1 (2018-10-17)
----------------

- Quote url path when setting cookie
- Fix email tests and travis tests
  [instification]


1.0 (2018-04-16)
----------------

- Use email of current user, instead of system email
  [tomgross]


1.0rc3 (2017-11-08)
-------------------

- Fix error when sending token url via email
  [tomgross]


1.0rc2 (2017-09-06)
-------------------

- Make ATContentTypes optional
  [tomgross]


1.0rc1 (2017-08-02)
-------------------

- Fix getting request
  [tomgross]


1.0b2 (2017-05-05)
------------------

- Fix packaging issue
  [tomgross]


1.0b1 (2017-05-05)
------------------

- Plone 5 compatibility
  [tomgross]

- Add adapter for construction token URL
  [tomgross]
