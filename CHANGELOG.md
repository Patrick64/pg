# 1.2.0

2015-01-02

- Deprecated the {exp:pg} tag which will be removed in a future verion (use {exp:pg:pair} instead).
- Added the ability to get a one dimensional array value from the param tag: {exp:pg:param key="key" array_key="values"}.
- Added general effeciency optimizations.

# 1.1.2

2014-10-11

- Added missing scope to functions to eliminate warning in PHP 5.6.x.

# 1.1.1

2014-06-12

- Updated the param tag to use XSS cleaning on GET/POST values.

# 1.1.0

2014-05-29

- Added single tag for fetching individual GET/POST values.

# 1.0.0

2014-05-12

- Initial commit.