## Guide

The first two rows of the tests file must describe the deault setup and run commands. It will be automatically applied to tests, unless sepcified later.
If you don't have any default command you can leave it as Default-setup-command: ''.

The test file text is build to have tasks and for each task a test number. The full structure of each task is:

```
# Task 1
## Test 1
- Score: points for that test
- Setup-command: if you a another command rather than the default, put it 'like this'
- Run-command: if you a another command rather than the default, put it 'like this'
- Input: First-line
Second-line
- Expected Output: The output
```
