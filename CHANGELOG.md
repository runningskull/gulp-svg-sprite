## 1.2.4 Maintenance release (unreleased)
* Made vinyl a regular dependency in [preparation for npm@3](http://blog.npmjs.org/post/110924823920/npm-weekly-5) ([#25](https://github.com/jkphl/gulp-svg-sprite/issues/25))
* Updated dependencies

## 1.2.3 Bugfix release (2015-06-08)
* Compatible with [svg-sprite 1.2.3](https://github.com/jkphl/svg-sprite/tree/v1.2.3)
* Fixed string conversion regression ([svg-sprite #89](https://github.com/jkphl/svg-sprite/issues/89))

## 1.2.2 Maintenance release (2015-06-05)
* Compatible with [svg-sprite 1.2.2](https://github.com/jkphl/svg-sprite/tree/v1.2.2)
* Introduced "icon" box sizing strategy ([svg-sprite #57](https://github.com/jkphl/svg-sprite/pull/57), [grunt-svg-sprite #35](https://github.com/jkphl/grunt-svg-sprite/issues/35#issuecomment-74232726))
* Fixed regression bug introduced by [#23](https://github.com/jkphl/gulp-svg-sprite/pull/23) ([#24](https://github.com/jkphl/gulp-svg-sprite/issues/24))

## 1.2.1 Feature release (2015-06-04)
* Compatible with [svg-sprite 1.2.1](https://github.com/jkphl/svg-sprite/tree/v1.2.1)
* Updated dependencies & development dependencies ([svg-sprite #67](https://github.com/jkphl/svg-sprite/pull/67), [svg-sprite #82](https://github.com/jkphl/svg-sprite/issues/82))
* Relocated the shape transformations list config option
* Added custom root attributes support ([svg-sprite #87](https://github.com/jkphl/svg-sprite/issues/87))
* Introduced a global post-processing transformation option ([svg-sprite #64](https://github.com/jkphl/svg-sprite/issues/64), [svg-sprite #87](https://github.com/jkphl/svg-sprite/issues/87))

## 1.1.2 Bugfix release (2015-04-22)
* Compatible with [svg-sprite 1.1.2](https://github.com/jkphl/svg-sprite/tree/v1.1.2)
* Fixed symbol example template regression bug ([svg-sprite #70](https://github.com/jkphl/svg-sprite/issues/70#issuecomment-95307588))
* Added mixin option to CLI arguments
* Fixed boolean CLI argument notation ([svg-sprite #76](https://github.com/jkphl/svg-sprite/issues/76))
* Added whitespace replacement for shape IDs ([svg-sprite #77](https://github.com/jkphl/svg-sprite/issues/77))

## 1.1.1 Bugfix release (2015-04-19)
* Compatible with [svg-sprite 1.1.1](https://github.com/jkphl/svg-sprite/tree/v1.1.1)
* Updated dependencies & development dependencies
* Added viewBox attribute to SVG stacks ([svg-sprite #73](https://github.com/jkphl/svg-sprite/issues/73))
* Fixed example document path resolution bug ([svg-sprite #70](https://github.com/jkphl/svg-sprite/issues/70))
* Allow negative viewBox values ([svg-sprite #72](https://github.com/jkphl/svg-sprite/pull/72))
* Fixed symbol example document ([svg-sprite #71](https://github.com/jkphl/svg-sprite/pull/71))
* Improved error log for invalid SVG files ([svg-sprite #69](https://github.com/jkphl/svg-sprite/issues/69))

## 1.1.0 Maintenance release (2015-04-04)
* Compatible with [svg-sprite 1.1.0](https://github.com/jkphl/svg-sprite/tree/v1.1.0)
* Added mixin option ([svg-sprite #66](https://github.com/jkphl/svg-sprite/issues/66); ATTENTION: May break custom templates!)
* Updated development dependencies

## 1.0.20 maintenance release (2015-03-28)
* Compatible with [svg-sprite 1.0.20](https://github.com/jkphl/svg-sprite/tree/v1.0.20)
* Fixed several CLI bugs in svg-sprite ([svg-sprite #65](https://github.com/jkphl/svg-sprite/issues/65))
* Updated dependencies

## 1.0.19 Maintenance release (2015-03-08)
* Compatible with [svg-sprite 1.0.19](https://github.com/jkphl/svg-sprite/tree/v1.0.19)
* Changed alias for shape.dest CLI option
* Updated dependencies
* Fixed ID bug with view sprites
* Fixed sprite CSS path calculation

## 1.0.18 Bugfix release (2015-02-20)
* Compatible with [svg-sprite 1.0.18](https://github.com/jkphl/svg-sprite/tree/v1.0.18)
* Removed excessive console output

## 1.0.17 Maintenance release (2015-02-20)
* Compatible with [svg-sprite 1.0.17](https://github.com/jkphl/svg-sprite/tree/v1.0.17)
* Optimized stylesheet templates
* Introduced boolean hasCommon template variable
* Updated dependencies
* Fixed incomplete dimension CSS selector suffix ([grunt-svg-sprite #31](https://github.com/jkphl/grunt-svg-sprite/issues/31))

## 1.0.16 Maintenance release (2015-02-11)
* Compatible with [svg-sprite 1.0.16](https://github.com/jkphl/svg-sprite/tree/v1.0.16)
* Fixed missing file extensions with CSS resources ([svg-sprite #54](https://github.com/jkphl/svg-sprite/issues/54))
* Fixed broken sprite URL in css/view example HTML documents ([svg-sprite #53](https://github.com/jkphl/svg-sprite/issues/53))
* Fixed wrong base path for intermediate SVG shapes
* Removed the automatic dot prefix for CSS selectors ([svg-sprite #55](https://github.com/jkphl/svg-sprite/issues/55))

## v1.0.14 Maintenance release (2015-02-08)
* Compatible with [svg-sprite 1.0.14](https://github.com/jkphl/svg-sprite/tree/v1.0.14)
* Restructured documentation
* Fixed error with falsy rendering configurations ([svg-sprite #52](https://github.com/jkphl/svg-sprite/issues/52))

## v1.0.13 Maintenance (2015-01-28)
* Compatible with [svg-sprite 1.0.13](https://github.com/jkphl/svg-sprite/tree/v1.0.13)
* Fixed windows path separator bug ([#6](https://github.com/jkphl/gulp-svg-sprite/issues/6))
* Made dimension attributes (width & height) optional ([svg-sprite #45](https://github.com/jkphl/svg-sprite/issues/45))
* Added cache busting option for non-CSS sprites ([svg-sprite #48](https://github.com/jkphl/svg-sprite/issues/48))

## v1.0.12 Maintenance (2015-01-27)
* Compatible with [svg-sprite 1.0.12](https://github.com/jkphl/svg-sprite/tree/v1.0.12)
* Added dimension CSS output for non-CSS sprites ([#45](https://github.com/jkphl/svg-sprite/issues/45))
* Bumped lodash dependency version ([svg-sprite #44](https://github.com/jkphl/svg-sprite/issues/44))

## v1.0.11 Bugfix release
* Compatible with [svg-sprite 1.0.11](https://github.com/jkphl/svg-sprite/tree/v1.0.11)
* Fixed coordinate distortion in CSS sprites ([svg-sprite #41](https://github.com/jkphl/svg-sprite/issues/41))

## v1.0.10 Feature release
* Compatible with [svg-sprite 1.0.10](https://github.com/jkphl/svg-sprite/tree/v1.0.10)
* Added support for custom mode keys

## v1.0.9 Maintenance release
* Compatible with [svg-sprite 1.0.9](https://github.com/jkphl/svg-sprite/tree/v1.0.9)
* Updated dependencies
* Introduced `svg` getter in templating shape variables
* Fixed logging error in SVGO optimization
* Fixed missing XML namespaces in SVG stack 
* Fixed cache busting errors with example HTML document 

## v1.0.8 Bugfix release
* Compatible with [svg-sprite 1.0.8](https://github.com/jkphl/svg-sprite/tree/v1.0.8)
* Fixed broken rendering template path resolution ([#29](https://github.com/jkphl/grunt-svg-sprite/issues/29))

## v1.0.7 Feature & bugfix release
* Compatible with [svg-sprite 1.0.7](https://github.com/jkphl/svg-sprite/tree/v1.0.7)
* Improved error handling
* Improved XML & DOCTYPE declaration handling and fixed ([grunt-svg-sprite #28](https://github.com/jkphl/grunt-svg-sprite/issues/28))

## v1.0.6 Feature release
* Compatible with [svg-sprite 1.0.6](https://github.com/jkphl/svg-sprite/tree/v1.0.6)
* Made shape ID namespacing configurable ([grunt-svg-sprite #27](https://github.com/jkphl/grunt-svg-sprite/issues/27))
* Added extended alignment options ([svg-sprite #33](https://github.com/jkphl/svg-sprite/issues/33))

## v1.0.5 Bufix release
* Compatible with [svg-sprite 1.0.5](https://github.com/jkphl/svg-sprite/tree/v1.0.5)
* Fixed regression bug with SVG stacks

## v1.0.4 Bugfix release
* Compatible with [svg-sprite 1.0.4](https://github.com/jkphl/svg-sprite/tree/v1.0.4)
* Fixed XML & doctype declaration bug with inline sprites ([#2](https://github.com/jkphl/gulp-svg-sprite/issues/2))

## v1.0.2
* Initial release, compatible with [svg-sprite 1.0.2](https://github.com/jkphl/svg-sprite/tree/v1.0.2)