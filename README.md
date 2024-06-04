# Pytest 

Pytest is a useful tool to run test scripts with python

## How to define test files and test cases?

Pytest standard logic is to look for any file that starts with "test" and those are considered as test files. The same conversion also works to define test cases, meaning that any defined function starting with the "test" statement will be considered as one test case.

## Methods
- assert - validation method that checks if the statement is true and throw an exception in case it is not, causing the test to fail

## Running tests
- pytest - run all test cases
- pytest test_shopping_cart.py - run all test cases from the file
- pytest test_shopping_cart.py::test_can_get_total_price - run only one specific function from the file

### Flags
-s - force states to print out

## Fixtures
Fixtures can be used in order to provide context to test cases. It replaces repetitive function calls by defining a generic function that is passed as argument inside the test cases

## Mocks
Mocks are used to mimic fake behaviors by mocking one specific condition or set of data 

## Documentation
- [Pytest](https://docs.pytest.org/en/8.2.x/)
- [Unit test mock](https://docs.python.org/3/library/unittest.mock.html)