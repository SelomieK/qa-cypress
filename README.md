# qa-test-fixed

### Cause of failure and adjustment
#### `1.2`     
- Cause
  - Enter is typed before verify the input text
- Adjustment
  - First we type the input item
  - verify the text in the text field is same as item
  - type {enter}

 
#### `1.4.1`   
- Cause
  - text field is not detected after double click
 - Adjustment
   - find text field selector
   - Clear "pay Electric bill "before typing "Pay water bill"
#### `1.4.4` 
- Cause
 - Assign commands to variable and re use in other commands is not recommended.
- Adjustment
  - Instead of checking the existence of assigned command variable button, check the DOM element existence. or use then().
  - fixed using checking the dom element   
  
### Expand the Test Suite

In the following section, labeled `1.5`, there is a set of tests that has not yet been implemented. It is your responsibility to create and implement each of the test cases, including the `beforeEach` block.
#### Before each
- loop in the list of todo for ech item click X delete.
#### `1.5.1` 
- check item count DOM is not in the page.
#### `1.5.2`
- add one item to todo list
- check added item is last item since it starts with empty list.
- check item count DOM contains 1
#### `1.5.3`
 - Assign todo lists to variable
 - use for loop to write items of list todo list DOM
 - Each time an item is added make sure it is the last from the list of todos

## Extra Points

Mochawesome reporter is configured locally and on workflow: refer to the latest workflow in the actions of this repository. Generated HTML report can be found in artefact section. 
