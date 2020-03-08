# CHANGELOG

[sscaffold-css](https://sscaffold-css.com/) does its best to follow [semantic versioning](https://semver.org/):

* MAJOR releases may break layouts using previous versions and should be thoroughly tested;
* MINOR releases make an effort to not break layouts using previous versions but may contain bugfixes that could change some aspects of the layout;
* PATCH releases include only small, simple bug fixes and should be compatible with all previous versions of the same MAJOR release.

PATCH releases will be backported to previous MAJOR releases when applicable and I'm in the mood for it.

## RELEASES

### 0.1.1
March 8, 2020

* Fix missing `and` from `@media` queries (https://github.com/robsheldon/sscaffold-css/issues/10)
* Fix `svg+xml` values mangled by a naughty CSS minifier; trying a different minifier (https://github.com/robsheldon/sscaffold-css/issues/9)


### 0.1.0
January 15, 2020

* Initial release following limited pre-release testing.