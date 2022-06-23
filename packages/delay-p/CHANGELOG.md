# @redux-saga/delay-p

## 1.1.3
### Patch Changes

- 2b48382: Fixed an issue with arguments that exceed the maximum value for the internally-used `setTimeout`. Previously it could overflow based on the input that was too big and thus a timeout could resolve immediately.
