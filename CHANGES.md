### dev

[full changelog](http://github.com/yolk/valvat/compare/v0.3.4...master)

### 0.3.4 / 2011-08-01

[full changelog](http://github.com/yolk/valvat/compare/v0.3,3...v0.3.4)

* Normalize all input on initialization (by [SpoBo](https://github.com/SpoBo))

### 0.3.3 / 2011-06-02

[full changelog](http://github.com/yolk/valvat/compare/v0.3,2...v0.3.3)

* Add Valvat::Utils.iso_country_to_vat_country (by [Deb Bassett](https://github.com/urbanwide))

### 0.3.2 / 2011-01-14

[full changelog](http://github.com/yolk/valvat/compare/v0.3,1...v0.3.2)

* Fixed localization strings (en/de)
* Moved locales folder to lib/valvat/locales

### 0.3.1 / 2011-01-12

[full changelog](http://github.com/yolk/valvat/compare/v0.3,0...v0.3.1)

* ActiveModel validation: Failed validations with _match_country_ now use error message with country from given attribute
* ActiveModel validation: Failed validations with _match_country_ skip lookup and syntax checks

### 0.3.0 / 2011-01-12

[full changelog](http://github.com/yolk/valvat/compare/v0.2.3...v0.3.0)

* ActiveModel validation: added _match_country_ option to validate if iso country code of vat number matches another attribute.

### 0.2.3 / 2011-01-10

[full changelog](http://github.com/yolk/valvat/compare/v0.2.2...v0.2.3)

* Valvat::Utils.normalize now removes spaces and special chars anywhere

### 0.2.2 / 2011-01-10

[full changelog](http://github.com/yolk/valvat/compare/v0.2.1...v0.2.2)

* Using vies directly via soap/savon again; isvat.appspot.com is not _really_ reliable.
* Added support for Valvat#exist? as an alias of Valvat#exists?

### 0.2.1 / 2011-01-07

[full changelog](http://github.com/yolk/valvat/compare/v0.2.0...v0.2.1)

* Fixed blocker in valvat/lookup

### 0.2.0 / 2011-01-07

[full changelog](http://github.com/yolk/valvat/compare/v0.1.1...v0.2.0)

* Rewrote Valvat module to a vat number class for convenience + internal use of Valvat instances
* I18n: Default error messages in german

### 0.1.1 / 2011-01-07

[full changelog](http://github.com/yolk/valvat/compare/v0.1.0...v0.1.1)

* Fixed issue with country web service down and added spec
* Stubbed web service specs with fakeweb
* Added documentation for ActiveModel support

### 0.1.0 / 2011-01-07

[full changelog](http://github.com/yolk/valvat/compare/v0.0.3...v0.1.0)

* ActiveModel validation: added optional lookup support
* ActiveModel validation: I18n support with country specific messages
* ActiveModel validation: I18n locales in english and german
* Fixed bug with wrong iso country code on greek vat number (EL != GR)
* Valvat::Util.split only returns countries from europe

### 0.0.3 / 2011-01-06

[full changelog](http://github.com/yolk/valvat/compare/v0.0.2...v0.0.3)

* Basic support for ActiveModel validation

### 0.0.2 / 2011-01-06

[full changelog](http://github.com/yolk/valvat/compare/v0.0.1...v0.0.2)

* Use REST-wrapper for accessing VIES web service; this removes dependency on savon and some lines of code. See http://isvat.appspot.com/