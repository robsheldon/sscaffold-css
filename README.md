<p align="center">
    <a href="https://sscaffold-css.com/">
        <img width="100%" src="https://sscaffold-css.com/sscaffold_logo.png" alt="logo">
    </a>
</p>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## Introduction

sscaffold combines css rules from [normalize.css](https://github.com/necolas/normalize.css/), [skeleton.css](https://github.com/dhg/Skeleton), and [milligram](https://github.com/milligram/milligram) into a single, reorganized, easy-to-use css file, with bugfixes and a few other updates and additions. It emphasizes sensible defaults and semantic HTML.


## Size vs. skeleton and milligram

sscaffold is a little bit heftier than skeleton or milligram:

| Library                         | Minified Size <sup>(1)</sup> |
| -------                         | ---------------------------: |
| Skeleton 2.0.4 <sup>(2)</sup>   | 7.7K                         |
| Milligram 1.3.0 <sup>(3)</sup>  | 11K                          |
| sscaffold 0.1.0 <sup>(4)</sup>  | 14K                          |

* <sup>(1) Each css file was run through [cssminifier](https://cssminifier.com/) for an apples-to-apples comparison.</sup>
* <sup>(2) The Skeleton 2.0.4 package includes Normalize 3.0.2. The current version of Normalize is 8.0.1. Normalize 3.0.2 was added to the Skeleton 2.0.4 file before minifying it.</sup>
* <sup>(3) Milligram 1.3.0 requires Normalize 5.0.0. The current version of Normalize is 8.0.1. Normalize 5.0.0 was added to the Milligram 1.3.0 file before minifying it.</sup>
* <sup>(4) sscaffold 0.1.0 has no external dependencies. Normalize 8.0.1 has already been integrated into sscaffold.css.</sup>

For 3K over Milligram and 7K over Skeleton you save an https request and get the features of both plus a few extras.

## Using sscaffold

The current version is 0.1.0.

#### jsdelivr:

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/sscaffold-css@0.1.0/sscaffold.min.css" integrity="sha256-NxJ/Enl6+QKA3ysgZq44/qc6cWmUXbAB/hl+QFBuMck=" crossorigin="anonymous">
```

#### npm:

```
npm install sscaffold-css
```

If you want it added to another repository, dependency management system, or cdn, open an issue requesting it and I'll get on it.


## Documentation

The [sscaffold-css.com](https://sscaffold-css.com/) home page is a demo and brief overview of the current release.

Complete documentation is available at [doc.sscaffold-css.com](https://doc.sscaffold-css.com/).


## License

Like everything else it evolved from, sscaffold is being released under the [MIT license](https://opensource.org/licenses/MIT). See [LICENSE](https://github.com/robsheldon/sscaffold-css/blob/master/LICENSE).


## Acknowledgements

sscaffold exists thanks to:

* [normalize](https://github.com/necolas/normalize.css/)
* [skeleton](https://github.com/dhg/Skeleton)
* [milligram](https://github.com/milligram/milligram)
* assorted articles on MDN and css-tricks
* ...and https://github.com/othneildrew/Best-README-Template/


[contributors-shield]: https://img.shields.io/github/contributors/robsheldon/sscaffold-css.svg?style=flat-square
[contributors-url]: https://github.com/robsheldon/sscaffold-css/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/robsheldon/sscaffold-css.svg?style=flat-square
[forks-url]: https://github.com/robsheldon/sscaffold-css/network/members
[stars-shield]: https://img.shields.io/github/stars/robsheldon/sscaffold-css.svg?style=flat-square
[stars-url]: https://github.com/robsheldon/sscaffold-css/stargazers
[issues-shield]: https://img.shields.io/github/issues/robsheldon/sscaffold-css.svg?style=flat-square
[issues-url]: https://github.com/robsheldon/sscaffold-css/issues
[license-shield]: https://img.shields.io/github/license/robsheldon/sscaffold-css.svg?style=flat-square
[license-url]: https://github.com/robsheldon/sscaffold-css/blob/master/LICENSE
