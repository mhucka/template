# Guidelines for contributing to this project

Any constructive contributions &ndash; bug reports, pull requests (code or documentation), suggestions for improvements, and more &ndash; are welcome.

## Conduct

Everyone is asked to read and respect the [code of conduct](CODE_OF_CONDUCT.md) before participating in this project.

## Coordinating work

A quick way to find out what is currently in the near-term plans for this project is to look at the [GitHub issue tracker](https://github.com/mhucka/template/issues), but the possibilities are not limited to what you see there &ndash; if you have ideas for new features and enhancements, please feel free to write them up as a new issue or contact the developers directly!

## Submitting contributions

Please feel free to contact the primary author (Mike Hucka) directly, or even better, jump right in and use the standard GitHub approach of forking the repo and creating a pull request.  When committing code changes and submitting pull requests, please write a clear log message for your commits.

### Git commit messages

As of 2024, I try to prefix commit messages using a subset of [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), as follows:

- `fix`: a commit of the type fix patches a bug in your codebase (this correlates with PATCH in Semantic Versioning).
- `feat`: a commit of the type feat introduces a new feature to the codebase (this correlates with MINOR in Semantic Versioning).
- `refactor`: A code change that neither fixes a bug nor adds a feature. If it's only for comment changes, use `docs` instead. If it involves the test suite, use `test` instead.
- `style`: Changes that only affect stylistic choices.
- `docs`: Documentation work of any kind, including comments-only changes in code (but not if the only purpose is to change something involving style – use `style` for those). Also includes refactoring docs. Also includes website work.
- `build`: Work on the build system, continuous integration, etc. Includes Makefiles, scripts, refactoring build code.
- `test`: Test case work of any kind. Includes refactoring test cases.
- `revert`: Change that undoes a previous change.
- `chore`: Anything that's not one of the above.

Use an exclamation for breaking changes: `feat!: change handling of errors`.

I don't use scoping modifiers (like putting module names in parentheses).
