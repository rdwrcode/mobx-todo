# Todo with Mobx and React 

## Test with jest

* setup for testing
```
npm i -D enzyme jest babel-jest
```

* when there is no test written

```
npm run test

> mobx-todo@0.1.0 test ~/dev/js/study/mobx-todo
> jest

No tests found
  5 files checked.
  testPathDirs: ~/dev/js/study/mobx-todo - 5 matches
  testRegex: (/__tests__/.*|\.(test|spec))\.js$ - 0 matches
  testPathIgnorePatterns: /node_modules/ - 5 matches
```

* Add tests in Jest
Jest will run anything in the __tests__ directory by default
```
npm run test

> mobx-todo@0.1.0 test ~/dev/js/study/mobx-todo
> jest

 PASS  __tests__/TodoStore.test.js (7.944s)
  TodoStore
    ✓ creates new todos (9ms)

Test Summary
 › Ran all tests.
 › 1 test passed (1 total in 1 test suite, run time 18.698s)
```

## Reference:
[semaphore tutorial](https://semaphoreci.com/community/tutorials/how-to-test-react-and-mobx-with-jest)

