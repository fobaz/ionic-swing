<a name="0.1.0"></a>
## [0.1.0](https://github.com/peterpeterparker/ionic-swing/compare/v0.0.10...v0.1.0) (2017-11-09)
* **project:** Migration of the project structure to use Angular CLI
* **project:** Introduction of ng-packagr to build the module
* **lib:** Update angular 5.0.0 and rjxs 5.5.2

<a name="0.0.7"></a>
## [0.0.7](https://github.com/peterpeterparker/ionic-swing/compare/v0.0.6...v0.0.10) (2017-06-18)
* **lib:** Update angular, rjxs and zone.js

<a name="0.0.6"></a>
## [0.0.6](https://github.com/peterpeterparker/ionic-swing/compare/v0.0.5...v0.0.6) (2017-05-11)
* **lib:** Update to zonejs
* fix publish on npm

<a name="0.0.5"></a>
## [0.0.5](https://github.com/peterpeterparker/ionic-swing/compare/v0.0.4...v0.0.5) (2017-05-11)
* **lib:** Update to angular 4.1.0

<a name="0.0.4"></a>
## [0.0.4](https://github.com/peterpeterparker/ionic-swing/compare/v0.0.3...v0.0.4) (2017-04-26)

### Features

* **lib:** Lodash replaced by underscore.js ([#1]https://github.com/peterpeterparker/ionic-swing/issues/1)
* **lib:** Angular, rxjs and zone updated to reflect Ionic 3.1.0 dependencies ([#3]https://github.com/peterpeterparker/ionic-swing/issues/3)

### Comments

The main reason behind the replacement of lodash by underscore is the size of the library. In an Ionic app the size of the bundle is a major factor regarding the boot time, therefore, smaller the libs are, faster the app boot will be.
