# qa-test

Please clone this project, carefully follow the provided instructions, and submit your code in a separate git repository that you create.

## Setup and Run

Install the project by running

```sh
npm install
```

Run the Cypress end to end project by running

```sh
npx cypress open --e2e
```

## Problem Statement

### Identify and Resolve Code Issues

When executing the tests in `todo.cy.ts`, you will notice that tests `1.2`, `1.4.1`, and `1.4.4` are currently failing. Your task is to identify the cause of failure in each test and make the necessary adjustments to the code in order to resolve the issues. Your goal is to ensure that the tests pass as expected.
### Cause of failure and adjustment
#### `1.2`     
- Cause
- - Enter is typed before verify the input text
- Adjustment
- -First we type the input item
- -verify the text in the text field is same as item
- -type {enter}

 
#### `1.4.1`   
#### `1.4.4` 

### Expand the Test Suite

In the following section, labeled `1.5`, there is a set of tests that has not yet been implemented. It is your responsibility to create and implement each of the test cases, including the `beforeEach` block.

## Extra Points

Mochawesome reporter is configured locally and on workflow: refer to the latest workflow in the actions of this repository. Generated HTML report can be found in artefact section. 
