# Test case for home page

## login

see [login page test](./loginTestCase.md)

## Create a test suite

1. Click on "add" button : the test suite creation popin should appear
2. Enter a name for the test suite
3. Enter the git repo address : "git@github.com:riegelTech/vertest-repo-test.git"
4. Validate : should see next step
5. Choose branch : check that all available branches are displayed
6. Validate : should see next step, time counter
7. Add a file selector or many
8. Click on "finish" button : popin should disappear and new test suite should be visible on grid

## Edge cases

1. Test a name duplication in the test suites
2. Choose a non existing git repo
3. Choose a locked SSH key
4. Select a user and validate its name
