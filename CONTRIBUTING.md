# Contributing to T3 Stack Boilerplate with shadcn UI

First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to this project. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to [INSERT EMAIL HERE].

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

- Use the GitHub issue search — check if the issue has already been reported.
- Check if the issue has been fixed — try to reproduce it using the latest `main` branch in the repository.
- Isolate the problem — ideally create a reduced test case and a live example.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.

- Use the GitHub issue search — check if the enhancement has already been suggested.
- Check if the enhancement has already been implemented — try to reproduce it using the latest `main` branch in the repository.
- Suggest your change in a new issue using the appropriate issue template.

### Your First Code Contribution

Unsure where to begin contributing? You can start by looking through these `good-first-issue` and `help-wanted` issues:

- [Good first issues](https://github.com/YOURNAME/YOURREPO/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
- [Help wanted issues](https://github.com/YOURNAME/YOURREPO/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)

### Pull Requests

- Fill in the required template
- Do not include issue numbers in the PR title
- Follow the TypeScript styleguide
- Include thoughtfully-worded, well-structured tests
- Document new code based on the Documentation Styleguide
- End all files with a newline

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line
- Consider starting the commit message with an applicable emoji:
  🎨 `:art:` when improving the format/structure of the code
  🐎 `:racehorse:` when improving performance
  🚱 `:non-potable_water:` when plugging memory leaks
  📝 `:memo:` when writing docs
  🐛 `:bug:` when fixing a bug
  🔥 `:fire:` when removing code or files
  💚 `:green_heart:` when fixing the CI build
  ✅ `:white_check_mark:` when adding tests
  🔒 `:lock:` when dealing with security
  ⬆️ `:arrow_up:` when upgrading dependencies
  ⬇️ `:arrow_down:` when downgrading dependencies
  👕 `:shirt:` when removing linter warnings

### TypeScript Styleguide

- Use `interface` for defining object shapes unless you need specific features from `type`
- Use `type` for unions, intersections, or when you need to take advantage of mapped types
- Use `const` assertions for literal values that won't change
- Prefer `undefined` over `null`
- Use optional chaining (`?.`) and nullish coalescing (`??`) operators
- Utilize TypeScript's strict mode
- Use `enum` sparingly, prefer union types of string literals
- Leverage TypeScript's inference capabilities when it makes code cleaner

### Documentation Styleguide

- Use [Markdown](https://daringfireball.net/projects/markdown) for documentation.
- Reference methods and classes in markdown with the custom `{}` notation:
  - Reference classes with `{ClassName}`
  - Reference instance methods with `{ClassName.methodName}`
  - Reference class methods with `{ClassName.methodName}`

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests.

- `bug` - Issues that are bugs.
- `enhancement` - Issues that are feature requests.
- `documentation` - Issues for improving or creating new documentation.
- `good first issue` - Issues which are good for newcomers.
- `help wanted` - Issues which need extra attention.
- `question` - Issues which are a question.

Thank you for contributing to our project! 🚀
