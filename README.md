# Stream

A toy functional reactive stream library for JavaScript (Similar to RxJS, XStream, MostJS, ...)

## Factories:

- Stream.of()
- Stream.fromArray()
- Stream.fromPromise()
- Stream.fromEvent()
- Stream.interval()

## Composing Operators:

- Stream.map()
- Stream.mapTo()
- Stream.filter()
- Stream.takeUntil()

## Articles

The following articles go through writing this toy library from scratch:

1. [Understanding the observable type by reimplementing a naive version of it](http://nick.balestra.ch/2016/Understanding-the-observable-type/)
2. [Understanding observables by creating them out of arrays, events and promises](http://nick.balestra.ch/2016/creating-observables/)
3. [Understanding observables by implementing few composition operators](http://nick.balestra.ch/2016/composing-observables/)
