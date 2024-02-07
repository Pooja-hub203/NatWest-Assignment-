# NatWest-Assignment-

Employee Dashboard Contract Testing:
This repository contains code for contract testing between the Employee service (provider) and the Dashboard service (consumer) using the Pact framework in Python.

Contract Creation:
The contract for the Employee service is defined to include interactions for getting employee details, creating an employee, and updating an employee. Similarly, the contract for the Dashboard service includes interactions for getting employee details, creating an employee, and updating an employee.

Test Cases:
Several test cases have been implemented to validate the requirements of the contract testing:

1. Consumer Contract Creation Fail without Provider: Validates that consumer contract creation fails if the provider contract does not exist.
2. Consumer Contract Subset of Provider Contract: Ensures that the consumer contract is always a subset of the provider contract.
3. Consumer Contract Updated on Provider Contract Change: Verifies that the consumer contract is updated as soon as the provider contract changes.
4. Consumer Contract Not Breaking After Provider Contract Change: Validates that the consumer contract is not breaking after the provider contract changes.
5. Consumer Contract Creation Fail if Not Subset of Provider: Checks that consumer contract creation fails if the consumer contract is not a subset of the provider contract.
6. Consumer Contract Creation Fail if Not Valid: Ensures that consumer contract creation fails if the consumer contract is not valid.
7. Consumer Contract Creation Success if Valid and Subset: Validates that consumer contract creation succeeds if the consumer contract is a subset of the provider contract and is valid.
   
These test cases ensure robust contract testing between the Employee and Dashboard services, facilitating reliable communication and preventing breaking changes.
