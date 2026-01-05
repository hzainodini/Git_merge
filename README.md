# Semantic Commit Messages:

Semantic commit messages are a structured way of writing commit messages that 
clearly describe what kind of change was made and why, using a consistent format. 
They typically follow the pattern type(scope): short description, where the type 
(such as feat, fix, docs, refactor, or test) communicates the intent of the change
at a glance. This approach improves readability of the project history, makes code
reviews easier, helps automate changelogs and releases, and allows team members to
quickly understand the impact of each commit without digging into the code. 
There are some examples:

feat: (new feature for the user, not a new feature for build script)

fix: (bug fix for the user, not a fix to a build script)

docs: (changes to the documentation)

style: (formatting, missing semi colons, etc; no production code change)

refactor: (refactoring production code, eg. renaming a variable)

test: (adding missing tests, refactoring tests; no production code change)

chore: (updating grunt tasks etc; no production code change)