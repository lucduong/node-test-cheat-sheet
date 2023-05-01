# node-test-cheat-sheet

The node test runner cheat sheet

<!-- toc -->

- [Test structure](#test-structure)
- [Matchers](#matchers)
  - [Basic matchers](#basic-matchers)
  - [Truthiness](#truthiness)
  - [Numbers](#numbers)
  - [Strings](#strings)
  - [Arrays](#arrays)
  - [Objects](#objects)
  - [Exceptions](#exceptions)
  - [Snapshots](#snapshots)
  - [Mock functions](#mock-functions)
  - [Misc](#misc)
  - [Promise matchers](#promise-matchers)
- [Async tests](#async-tests)
  - [async/await](#asyncawait)
  - [Promises](#promises)
  - [done() callback](#done-callback)
- [Mocks](#mocks)
  - [Mock functions](#mock-functions-1)
  - [Returning, resolving and rejecting values](#returning-resolving-and-rejecting-values)
  - [Mock modules using a mock file](#mock-modules-using-a-mock-file)
  - [Mock object methods](#mock-object-methods)
  - [Mock getters and setters](#mock-getters-and-setters)
  - [Clearing and restoring mocks](#clearing-and-restoring-mocks)
  - [Accessing the original module when using mocks](#accessing-the-original-module-when-using-mocks)
  - [Timer mocks](#timer-mocks)
- [Skipping tests](#skipping-tests)
- [Testing modules with side effects](#testing-modules-with-side-effects)
- [Usage with Babel and TypeScript](#usage-with-babel-and-typescript)
- [Resources](#resources)
- [You may also like](#you-may-also-like)
- [Contributing](#contributing)
- [Sponsoring](#sponsoring)
- [Author and license](#author-and-license)

<!-- tocstop -->

## Test structure

```js
import { describe, test } from 'node:test';
import assert from 'node:assert';

import { add } from '../math.mjs';

describe('math', () => {
  test('should return 3 when using add function with params 1, 2', () => {
    assert.strictEqual(add(1, 2), 3);
  });
});
```

## Matchers

### Basic matchers

```js

```

### Truthiness

```js
```

### Numbers

```js

```

### Strings

### Arrays

### Objects

### Exceptions

### Snapshots

### Mock functions

### Misc
