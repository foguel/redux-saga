# @redux-saga/core

## 1.1.4
### Patch Changes

- 2b48382: Require `CpsCallback` in all functions passed to the `cps` effect creator. This fixes a regression caused by TS 4.0 changing the behavior around spreading `never` into tuple types
- 2b48382: A generic type has been added to the `Task` interface and that should be preferred over using a generic parameter in `Task#result` and `Task#toPromise`.
- 2b48382: Added warnings when using `take(channelOrPattern)` incorrectly with more than one parameter. It helps to surface problem with `take(ACTION_A, ACTION_B)` being used instead of `take([ACTION_A, ACTION_B])`.

- Updated dependencies [2b48382]
- Updated dependencies [2b48382]
- Updated dependencies [2b48382]
  - @redux-saga/types@1.1.1
  - @redux-saga/delay-p@1.1.3
