# @redux-saga/types

## 1.1.1
### Patch Changes

- 2b48382: A generic type has been added to the `Task` interface and that should be preferred over using a generic parameter in `Task#result` and `Task#toPromise`.
- 2b48382: Inlined Redux `Action` type to fix compatibility with strict package managers.
