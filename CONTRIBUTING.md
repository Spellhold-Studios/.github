# Contributing Guidelines

This guide serves to set clear expectations for everyone involved with the project so that we can improve it together while also creating a welcoming space for everyone to participate. Following these guidelines will help ensure a positive experience for contributors and maintainers.

### Contents

- [Code of Conduct](#book-code-of-conduct)
- [Asking Questions](#question-asking-questions)
- [Opening Issues](#inbox_tray-opening-issues)
- [Requesting Features](#bulb-requesting-features)
- [Submitting Pull Requests](#repeat-submitting-pull-requests)
- [Writing Commit Messages](#memo-writing-commit-messages)
- [Credits](#pray-credits)

## :book: Code of Conduct

Please review our [Code of Conduct](https://github.com/Spellhold-Studios/.github/blob/main/CODE_OF_CONDUCT.md). It is in effect at all times. We expect it to be honored by everyone who contributes to this project.

## :question: Asking Questions

[GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) are not the appropriate place to ask questions about this project and should be reserved for filing bug or compatibility reports. If you want to ask a question, give a suggestion or comment on this project, please use [GitHub Discussions](https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/participating-in-a-discussion) instead.

## :inbox_tray: Opening Issues

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), check if you are using the latest version of the project. If you are not up-to-date, see if updating fixes your issue first.

A great way to contribute to the project is to send a detailed issue when you encounter a problem. We always appreciate a well-written, thorough bug report.

- **Review the available documentation** before opening a new issue.

- **Do not open a duplicate issue!** Search through existing issues to see if your issue has previously been reported. If your issue exists, comment with any additional information you have. You may simply note "I have this problem too", which helps prioritize the most common problems and requests.

- **Fully complete the provided issue template.** The bug report form requests all the information we need to quickly and efficiently address your issue. Provide as much information as you can. Be clear, concise, and descriptive.

- **Use [GitHub-flavored Markdown](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).** Especially put code blocks and console outputs in backticks (```). This improves readability.

- **Prefer using [reactions](https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/)**, not comments, if you simply want to "+1" an existing issue.

## :bulb: Requesting Features

Suggestions are always welcome! While we will consider all requests, we cannot guarantee your request will be accepted. Your idea may be great, but also out-of-scope for the project. If accepted, we cannot make any commitments regarding the timeline for implementation and release.

- **First consult your ideas** with the project maintainers in [Discussions](https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/participating-in-a-discussion).

- **Do not open a pull request** to add new features without discussing it with the maintainers.

- **Be precise about the proposed outcome** of the feature and how it relates to existing features.

## :repeat: Submitting Pull Requests

Before [forking the repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests) for non-trivial changes, it is usually best to first [open an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue) or comment on an existing issue to present your intended approach for solving the problem. If you would like to suggest a new feature, first [start a discussion](https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/participating-in-a-discussion#creating-a-discussion) to talk it over with the maintainers.

- **Smaller is better.** Submit one pull request per bug fix or feature. A pull request should contain isolated changes pertaining to a single bug fix or feature implementation. Do not refactor or reformat code that is unrelated to your change. It is better to submit many small pull requests rather than a single large one. Enormous pull requests will take enormous amounts of time to review, or may be rejected altogether. 

- **Coordinate bigger changes.** For large and non-trivial changes, open an issue to discuss a strategy with the maintainers. Otherwise, you risk doing a lot of work for nothing!

- **Prioritize understanding over cleverness.** Write code clearly and concisely. Remember that source code usually gets written once and read often. Ensure the code is clear to the reader. The purpose and logic should be obvious to a reasonably skilled developer, otherwise you should add a comment that explains it.

- **Follow existing coding style and conventions.** Keep your code consistent with the style, formatting, and conventions in the rest of the code base. Consistency makes it easier to review and modify in the future. For example, if all private properties are prefixed with an underscore `_`, then new ones you add should be prefixed in the same way. Or if methods are named using camelcase, like `thisIsMyNewMethod`, then do not diverge from that by writing `this_is_my_new_method`.

- **Use the repo's default branch** unless instructed otherwise by the project maintainers. Generally, branch from and [submit your pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork) to the repo's default branch. Usually this is `main`, but it could be `dev`, `develop`, or `master`. The project maintainers may decide to switch the base branch for your proposed changes.

- **Attempt to [resolve any merge conflicts](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github)** that occur. When in doubt, request assistance in the pull request comments.

- **Write properly constructed sentences**, including punctuation. Use spaces, not tabs.

## :memo: Writing Commit Messages

Please follow this guide to [write a great commit message](https://chris.beams.io/posts/git-commit/).

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line (example: "Fix networking issue")
6. Wrap the body at about 72 characters
7. Use the body to explain *why*, not *what and how* (the code shows that!)
8. If applicable, prefix the title with the relevant component name (examples: "[Docs] Fix typo", "[Profile] Fix missing avatar")

Not every commit requires both a subject and a body. Sometimes a single line is fine, especially when the change is so simple that no further context is necessary. For example:

> Fix typo in introduction to user guide

Nothing more need be said; if the readers wonder what the typo was, they can simply take a look at the change itself.

If the changes are more extensive, you may need to add some more details:

```
[TAG] Short summary of changes in 50 chars or less

Add a more detailed explanation here, if necessary. Possibly give 
some background about the issue being fixed, etc. The body of the 
commit message can be several paragraphs. Further paragraphs come 
after blank lines and please do proper word-wrap.

Wrap it to about 72 characters or so. In some contexts, 
the first line is treated as the subject of the commit and the 
rest of the text as the body. The blank line separating the summary 
from the body is critical (unless you omit the body entirely); 
various tools like `log`, `shortlog` and `rebase` can get confused 
if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how or what. The code explains 
how or what. Reviewers and your future self can read the patch, 
but might not understand why a particular solution was implemented.
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

 - Bullet points are okay, too

 - A hyphen or asterisk should be used for the bullet, preceded
   by a single space, with blank lines in between

Note the fixed or relevant GitHub issues at the end:

Resolves: #123
See also: #456, #789
```

## :pray: Credits

Many ideas and statements in this document were based on or adopted from the [contributing guidelines](https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md) written by [@jessesquires](https://github.com/jessesquires).
