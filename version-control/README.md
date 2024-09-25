Version control
===============

Version control should be respected to a degree. We want to be able to utilize version control to find reasoning behind changes over the years, but we don't want it to add unnecessary friction to our development workflow in our day-to-day work, especially when working with a multi-deliverer environments.

Commandments
------------

-	Use consistent language. If the team writes their commits in a certain language, use that language.
-	Use consistent phrasing. Either use the "Description" model or the "Command" model.
	-	Description is e.g. "fix(top-nav): Fixes the share button visibility on main page"
	-	Command is e.g. "fix(top-nav): Fix the share button visibility on main page"
-	Either always use tags or never use tags
	-	Tagging commits by their "category" is a team effort. If your team can't agree on a convention, don't use one.
	-	Examples for tagging can be found at the [tagging section](#tagging)
-	If you are using a ticketing system, always, when applicable, include the ticket number in the commit message

### Tagging

If your team decides to use a tagging method, a good starting point would be a subset of these tags:

| Commit prefix | Title                    | Description                                                                                                 |
|---------------|--------------------------|-------------------------------------------------------------------------------------------------------------|
| feat          | Features                 | A new feature                                                                                               |
| fix           | Bug Fixes                | A bug Fix                                                                                                   |
| docs          | Documentation            | Documentation only changes                                                                                  |
| style         | Styles Changes           | that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)              |
| refactor      | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                   |
| perf          | Performance Improvements | A code change that improves performance                                                                     |
| test          | Tests                    | Adding missing tests or correcting existing tests                                                           |
| build         | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| ci            | Continuous Integrations  | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| chore         | Chores                   | Other changes that don't modify src or test files                                                           |
| revert        | Reverts                  | Reverts a previous commit                                                                                   |
