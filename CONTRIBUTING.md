# How to contribute

Do you want to help develop tsml? We welcome new members! Please find out more at [code4recovery.org](https://code4recovery.org). We meet regularly to discuss new features and other upcoming projects.

## Submitting changes

To submit a change, please send a [GitHub Pull Request to tsml](https://github.com/code4recovery/12-step-meeting-list/pull/new/master) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)).  Please follow our coding conventions (below).

## Reporting security bugs

To report a security issue, please use the [Security Tab](https://github.com/code4recovery/12-step-meeting-list/security), located under the repository name. If you cannot see the "Security" tab, select the ... dropdown menu, and then click Security. Please include as much information as possible, including steps to help our team recreate the issue.

## Coding conventions

These help improve code readability and maintainability:

- Use extensions like [DevSense](https://www.devsense.com) and [Prettier](https://prettier.io/) to format code on save
- Use the [Query Monitor WordPress plugin](https://wordpress.org/plugins/query-monitor/) locally to detect and fix any PHP warnings
- All constants, global functions, and global variables should have a name starting with `tsml_`
- Functions ought to be useful in multiple places (except functions that are available to end users such as `tsml_custom_types`)
- Use anonymous functions when possible (we are PHP 5.6+)
- Use bracket syntax for arrays (we are PHP 5.6+)
- We are PSR-12 compliant

Also some best practices:

- Don't leave code commented out (if it's needed later we can find it in the git history)
- Don't put database updates or other expensive operations inside a repeat loop
- No unused variables
- Filter inputs


