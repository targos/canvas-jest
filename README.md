# canvas-jest

```
$ npm t

> canvas-jest@1.0.0 test /home/mzasso/git/targos/canvas-jest
> jest

 FAIL  ./test.js
  ● Test suite failed to run

    TypeError: Cannot redefine property: currentTransform
        at Function.defineProperty (<anonymous>)

      at Object.<anonymous> (node_modules/canvas/lib/context2d.js:107:8)
      at Object.<anonymous> (test.js:1:105)
          at Generator.next (<anonymous>)
          at new Promise (<anonymous>)
          at Generator.next (<anonymous>)
          at <anonymous>
      at process._tickCallback (internal/process/next_tick.js:188:7)

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        0.422s, estimated 1s
Ran all test suites.
npm ERR! Test failed.  See above for more details.
```
