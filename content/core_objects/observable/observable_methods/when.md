# when

`Rx.Observable.when(...args)`
<a href="#rxobservablewhenargs">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/when.js "View in source") 

A series of plans (specified as an Array of as a series of arguments) created by use of the Then operator on patterns.

![when](https://github.com/Netflix/RxJava/wiki/images/rx-operators/and_then_when.png)

### Arguments
1. `args` *(arguments|Array)*: A series of plans (specified as an Array of as a series of arguments) created by use of the then operator on patterns.

#### Returns
*(`Observable`)*: Observable sequence with the results form matching several patterns. 

#### Example

[](http://jsbin.com/vobuh/1/embed?js,console)

### Location

File:
- [/src/core/observable/when.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/when.js)

Dist:
- [rx.joinpatterns.js](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.joinpatterns.js)

Prerequisites:
- [`rx`](https://www.npmjs.org/package/rx).joinpatterns.js
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`rx`](https://www.npmjs.org/package/rx)JS-JoinPatterns

Unit Tests:
- [/tests/observable/when.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/when.js)