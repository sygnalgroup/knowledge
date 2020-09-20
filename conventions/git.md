# Git Conventions

* Branch `develop` is where ongoing development is made.
* Branch `master` is always, as expected, the production ready code.
* Create feature branches off of `develop` using the naming convention `descriptive-branch-name`. Do not use prefixes like: `feature/`, `hotfix/`, `bug-`.
* We should never merge against these branches if the CI is not green.
* Merge PRs using the Github UI.
* Commit messages should follow [Tim Pope's recommendation for good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

# PR Conventions

* Your PR description should always containg the `What?` and `Why?`.
* The PR owner is responsible for merging the PR and closing the branch after merged.
* Your PR should be approved by at least two developers of the company.
* All PR's must be tested by at least 1 developer and the code should be reviewed by at least 1 developer. If both developers make both things,
it's the perfect scenario.
* After you code review, don't forget to comment in the PR the steps that you did.
  * `Just coding review`
  * `Just tests`
  * `Testing & Code Review` (The best scenario)

### How to test PR?

1. Download the code base.
2. Check out the feature branch.
3. Make the whole process to make the code run. (If doubts, ask the developer that opened the PR.)
4. Test the whole feature to ensure that it is working as expected.
  * If it's working as expected, comment in the PR, `Feature tested. It's working fine. Great Job!`
  * If it isn't working as expected, comment in the PR, `Feature tested. It it isn't working as expected. (Describe the problem here)!`
