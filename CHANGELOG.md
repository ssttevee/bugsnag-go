# Changelog

## 1.2.2 (2017-08-25)

### Bug Fixes

* Point osext dependency at upstream, update with fixes

## 1.2.1 (2017-07-31)

### Bug Fixes

* Improve goroutine panic reporting by sending reports synchronously in the
  case that a goroutine is about to be cleaned up
  [#52](https://github.com/bugsnag/bugsnag-go/pull/52)

## 1.2.0 (2017-07-03)

### Enhancements

* Support custom stack frame implementations
  [alexanderwilling](https://github.com/alexanderwilling)
  [#43](https://github.com/bugsnag/bugsnag-go/issues/43)

* Support app.type in error reports
  [Jascha Ephraim](https://github.com/jaschaephraim)
  [#51](https://github.com/bugsnag/bugsnag-go/pull/51)

### Bug Fixes

* Mend nil pointer panic in metadata
  [Johan Sageryd](https://github.com/jsageryd)
  [#46](https://github.com/bugsnag/bugsnag-go/pull/46)

## 1.1.1 (2016-12-16)

### Bug Fixes

* Replace empty error class property in reports with "error"

## 1.1.0 (2016-11-07)

### Enhancements

* Add middleware for Gin
  [Mike Bull](https://github.com/bullmo)
  [#40](https://github.com/bugsnag/bugsnag-go/pull/40)

* Add middleware for Negroni
  [am-manideep](https://github.com/am-manideep)
  [#28](https://github.com/bugsnag/bugsnag-go/pull/28)

* Support stripping subpackage names
  [Facundo Ferrer](https://github.com/fjferrer)
  [#25](https://github.com/bugsnag/bugsnag-go/pull/25)

* Support using `ErrorWithCallers` to create a stacktrace for errors
  [Conrad Irwin](https://github.com/ConradIrwin)
  [#35](https://github.com/bugsnag/bugsnag-go/pull/35)

## 1.0.5 (2015-08-18)

### Bug Fixes

* Avoid swallowing errors which occur upon delivery

## 1.0.4 (2015-05-28)

### Bug Fixes

* Fix appengine integration broken by 1.0.3

## 1.0.3 (2015-02-12)

### Bug Fixes

* Allow any Logger with a Printf method.

## 1.0.2 (2014-09-18)

### Bug Fixes

* Use bugsnag copies of dependencies to avoid potential link rot

## 1.0.1

### Bug Fixes

* gofmt/golint/govet docs improvements.

## 1.0.0 (2014-07-17)

### Enhancements

Initial release
