## [4.1.1](https://github.com/cheminfo-js/convert-to-jcamp/compare/v4.1.0...v4.1.1) (2020-06-24)


### Bug Fixes

* varName to name and extra space ([318ff9b](https://github.com/cheminfo-js/convert-to-jcamp/commit/318ff9b0e143922db7d076f0bb56ec58acb26de2))



# [4.1.0](https://github.com/cheminfo-js/convert-to-jcamp/compare/v4.0.1...v4.1.0) (2020-06-24)


### Features

* deal with label property in variable ([21eea52](https://github.com/cheminfo-js/convert-to-jcamp/commit/21eea52537234dbc9b5c6401b303a19aaab7a9f9))



## [4.0.1](https://github.com/cheminfo-js/convert-to-jcamp/compare/v4.0.0...v4.0.1) (2020-06-24)


### Bug Fixes

* properties of variables are lowercase ([efa700d](https://github.com/cheminfo-js/convert-to-jcamp/commit/efa700d16dd8e64a59c09d6522014d9377e593e4))



# [4.0.0](https://github.com/cheminfo-js/convert-to-jcamp/compare/v3.1.1...v4.0.0) (2020-06-24)


### Bug Fixes

* allow lowercase or uppercase variables ([b602e51](https://github.com/cheminfo-js/convert-to-jcamp/commit/b602e51a3ceb967f0c6db8e9af89d7b19e13ad6c))


### Features

* add fromVariables ([b20e667](https://github.com/cheminfo-js/convert-to-jcamp/commit/b20e6678d1cde72c4c07cbcb42b9e651f827d62f))



## [3.1.1](https://github.com/cheminfo-js/convert-to-jcamp/compare/v3.1.0...v3.1.1) (2020-06-21)


### Bug Fixes

* hard coded var names in ntuple ([d246301](https://github.com/cheminfo-js/convert-to-jcamp/commit/d24630137c13fbc3b42aea07ab5004ed92430390))



# [3.1.0](https://github.com/cheminfo-js/convert-to-jcamp/compare/v3.0.0...v3.1.0) (2020-06-11)


### Bug Fixes

* update name xUnits and yUnits ([fe61275](https://github.com/cheminfo-js/convert-to-jcamp/commit/fe612753da6690137af0ea8a7da6591f72537170))


### BREAKING CHANGES

* The parameters name where changed in order to reflect correct
xUnits and yUnits LDR
* xUnit -> xUnits
* yUnit -> yUnits



# [3.0.0](https://github.com/cheminfo-js/convert-to-jcamp/compare/v2.0.1...v3.0.0) (2020-06-11)


### Features

* meta options for meta information ([df7996f](https://github.com/cheminfo-js/convert-to-jcamp/commit/df7996fa9323e9b837fb7c0c2c4d1367855d27fd))
* rename type to dataType ([54949fb](https://github.com/cheminfo-js/convert-to-jcamp/commit/54949fbc028c37b02ad770bcf91bc278272efad8))


### BREAKING CHANGES

* The options contains now 2 fields
* info: contains general information like title, dataType
* meta: contains meta information that will end up as '$' labeled records
* In order to respect the name in the final jcamp the
parameter `type` has been renamed to `dataType`



<a name="1.0.0"></a>
# [1.0.0](https://github.com/cheminfo-js/convert-to-jcamp/compare/v0.2.0...v1.0.0) (2018-02-12)


### Features

* parse from an arrray of points or a xy object ([ec138d2](https://github.com/cheminfo-js/convert-to-jcamp/commit/ec138d2))



<a name="0.1.1"></a>
## [0.1.1](https://github.com/cheminfo-js/convert-to-jcamp/compare/v0.1.0...v0.1.1) (2017-07-31)



<a name="0.1.0"></a>
# 0.1.0 (2017-07-31)


### Features

* initial implementation ([#1](https://github.com/cheminfo-js/convert-to-jcamp/issues/1)) ([c4ac188](https://github.com/cheminfo-js/convert-to-jcamp/commit/c4ac188))



