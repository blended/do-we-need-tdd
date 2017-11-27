[![Coverage Status](https://coveralls.io/repos/github/blended/talks-do-we-need-tdd/badge.svg?branch=master)](https://coveralls.io/github/blended/talks-do-we-need-tdd?branch=master)
[![npm version](https://badge.fury.io/js/beginners-tdd-workshop-by-blended.svg)](https://badge.fury.io/js/beginners-tdd-workshop-by-blended)

[![JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

# If the code deserves to be written, it deserves to have tests.

[![Greenkeeper badge](https://badges.greenkeeper.io/heneise/talks-do-we-need-tdd.svg)](https://greenkeeper.io/)

## Introduction
### Why?
> Before you implement,
> write the test.

The evidence says:
- TDD can reduce bug density.
- TDD can encourage more modular designs (enhancing software agility/team velocity).
- TDD can reduce code complexity.

### 5 Questions Every Unit Test Must Answer

1. What are you testing?
1. What should it do?
1. What is the actual output?
1. What is the expected output?
1. How can the test be reproduced?


    import test from 'tape';

    // For each unit test you write,
    // answer these questions:
    test('What component aspect are you testing?', assert => {
      const actual = 'What is the actual output?';
      const expected = 'What is the expected output?';

      assert.equal(actual, expected,
        'What should the feature do?');

      assert.end();
    });


For some philosophy, see docs/TheWayOfTestivus.pdf

## Sources

- [5 Questions Every Unit Test Must Answer](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d#.j7hmhyo85)
- [What's the difference between unit, functional, acceptance, and integration tests?](http://stackoverflow.com/questions/4904096/whats-the-difference-between-unit-functional-acceptance-and-integration-test/4904533#4904533)
- https://github.com/hoodiehq/hoodie/blob/master/package.json
- https://github.com/semantic-release/semantic-release/blob/caribou/package.json
