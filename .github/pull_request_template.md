# Pull Request template

Please, go through these steps before you submit a PR.

1. Make sure that your PR is not a duplicate.
2. If not, then make sure that:

    a. You have done your changes in a separate branch.
       Branches MUST have descriptive names that start with the type of change.
       Branch names must end with the task id.
       Good examples are:
      - `fix-facebook-login-33055952`
      - `feat-facebook-login-33055952`
      - `docs-create-user-33055952`
      - `chore-rename-docker-env-33055952`

    b. You have a descriptive and atomic commit message with a short title (first line).

    c. You have only one commit (if not, squash them into one commit).

    d. `npm run lint` doesn't throw any error. If it does, fix them first and amend your commit (`git commit --amend`).

    d. `npm test` doesn't throw any error. If it does, fix them first and amend your commit (`git commit --amend`).

3. **PLEASE REMOVE THE ABOVE TEMPLATE AND THIS LINE BEFORE SUBMITTING**
<!--- Provide a general summary of your changes in the Title above -->

## What does this PR do
<!--- Describe your changes in detail -->

### Motivation and Context
<!--- Why is this change required? What problem does it solve? -->
<!--- If it fixes an open issue, please link to the issue here. -->

### How Has This Been Tested
<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, tests ran to see how -->
<!--- your change affects other areas of the code, etc. -->

### Github Project Task Url

[33055952](https://github.com/Gamio-technology/iserver-starter/projects/1#card-33055952)

#### Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Documentation (Documentation only changes)
- [ ] Style (Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc))
- [ ] Refactor (A code change that neither fixes a bug nor adds a feature)
- [ ] Performance (A code change that improves performance)
- [ ] Test (Adding missing tests or correcting existing tests)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Build (Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm, yarn, docker))
- [ ] CI/CD (Changes to our CI configuration files and scripts (example scopes: Travis, CircleCI, BrowserStack, SauceLabs))
- [ ] Chore (Other changes that don't modify src or test files)
- [ ] Revert (Reverts a previous commit)

### Checklist
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask! -->
- [ ] My code follows the code style of this project.
- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.
