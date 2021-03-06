## 1.3.1 (2019-11-29)

* Align the polyfill features with the [new Working Draft of CSS Spatial Navigation Level 1](https://www.w3.org/TR/2019/WD-css-nav-1-20191126/)
* Fix a bug for spatial-navigation-action: auto by [commit](https://github.com/WICG/spatial-navigation/commit/bceff39b5ca059303193c0ec85c066aa9254d252)
* Modify the spatial-navigation-function implementation by [commit](https://github.com/WICG/spatial-navigation/commit/408ff1607abd8c07085a8de1bbe8bd448e188b58)
* Drop `inside` attribute of `spatialNavigationSearch` API [(#211)](https://github.com/WICG/spatial-navigation/pull/211)
* Add and modify the sample demos

## 1.3.0 (2019-10-31)

* Add chrome extension [(#197)](https://github.com/WICG/spatial-navigation/pull/197)
* Add spatial-navigation-function CSS Property by [commit](https://github.com/WICG/spatial-navigation/commit/14654aa651a6ee06106ab0823046b3a4e59d6156)
* Make `spatialNavigationSearch` API takes inside option by [commit](https://github.com/WICG/spatial-navigation/commit/a5603e51f2417f37e38e1fcab37706486fa46ae3) depending the [spec](https://github.com/w3c/csswg-drafts/issues/3743)
* Modify the condition of scroll container [(#200)](https://github.com/WICG/spatial-navigation/pull/200)
* Fix the focus movement properly inside iframe element
* Add the behavior of moving focus to inside overlapped elements by [commit](https://github.com/WICG/spatial-navigation/commit/9131a38349e6c9109b02e33500f0fa63bf6a4233)
* Add resetting the search origin [(#205)](https://github.com/WICG/spatial-navigation/pull/205)

## 1.2.0 (2019-04-18)

* Add UX test cases for verifying the distance function [(#154)](https://github.com/WICG/spatial-navigation/pull/154)
* Improve the distance function depending on [the spec update](https://github.com/w3c/csswg-drafts/pull/3755) [(#165)](https://github.com/WICG/spatial-navigation/pull/165)
* Fix the bug for preventing navigation events
* Remove `navbeforescroll` event
* Add `spatial-navigation-action` CSS Property and its demo [(#171)](https://github.com/WICG/spatial-navigation/pull/171)
* Add internal test cases for overall polyfill behavior
* Add the feature about navigating from the spatial navigation starting point [(#169)](https://github.com/WICG/spatial-navigation/pull/169)
* Optimize `navigate()` [(#172)](https://github.com/WICG/spatial-navigation/pull/172)
* Fix the bug of handling non-focusable elements [(#174)](https://github.com/WICG/spatial-navigation/pull/174)

## 1.1.0 (2019-01-04)

* Change the polyfill file name from spatnav-heuristic.js to spatial-navigation-polyfill.js
* Fix the bug of isFocusable() (added more conditions for focusable elements) [(#147)](https://github.com/WICG/spatial-navigation/pull/147)
* Fix the bug of getSpatialNavigationContainer [(jihyerish#5)](https://github.com/jihyerish/spatial-navigation/pull/5)
* Add enableExperimentalAPIs function
* Add the drowing board for the demo center [(#148)](https://github.com/WICG/spatial-navigation/pull/148)
* Improve the overall performance [(#150)](https://github.com/WICG/spatial-navigation/pull/150)
* Add the polyfill annotation with JSDoc format

## 1.0.0 (2018-09-07)

* Initial version
