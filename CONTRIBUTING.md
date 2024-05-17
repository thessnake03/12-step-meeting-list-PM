# How to contribute

stealing from  https://github.com/rails/rails/blob/main/CONTRIBUTING.md
and https://github.com/opengovernment/opengovernment/blob/master/CONTRIBUTING.md

How to get in touch
github
website

to join the team email tim @

## Submitting changes

### Did you find a bug?
Do not open up a GitHub issue if the bug is a security vulnerability, and instead to refer to our security policy. [link]

- Ensure the bug was not already reported by searching on GitHub under Issues. [link]

- If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

### Did you write a patch that fixes a bug?
- Open a new GitHub pull request with the patch.

- Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

## Coding conventions
copy from our README
These help improve code readability and maintainability:
- Use extensions like DevSense and Prettier to format code on save
- Use the Query Monitor WordPress plugin locally to detect and fix any PHP warnings
- All constants, global functions, and global variables should have a name starting with tsml_
- Functions ought to be useful in multiple places (except functions that are available to end users such as tsml_custom_types)
- Use anonymous functions when possible (we are PHP 5.6+)
- Use bracket syntax for arrays (we are PHP 5.6+)

Also some best practices:
- Don't leave code commented out (if it's needed later we can find it in the git history)
- Don't put database updates or other expensive operations inside a repeat loop
- No unused variables
- Filter inputs


