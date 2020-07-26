## Test-driven development

Test-driven development (TDD) is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, then the code is improved so that the tests pass.

<p align="center">
  <img src="https://github.com/teles1g/tdd/blob/master/jest.png?raw=true" alt="Tdd"/>
</p>

#### Types of tests

1. Unitary
   - They test a minimal or pure function that does not perform side effects like access to the database or external integrations.

2. Integration
   - The main bacl-end tests, test full functionality like access to routes until the controller returns.

3. E2E
   - Interface tests that simulate user access.

#### Start Server Back-End

```
-> ~/cd back-end

-> ~/yarn

-> ~/yarn test
```

Documentation: https://jestjs.io/
