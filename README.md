# angular-study-guide
Angular Study Guide

What is the difference between Promises and RxJS?
  a) Promises are always async. They return 1 value. Need to call the then() method.
  b) RxJS may be async. Stream of 0 or more values. We call the subscribe() method.
      obs.subscribe (value => {
        // do something with the value
}
  
