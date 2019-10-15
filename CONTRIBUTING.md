# Contributing

When contributing to this repository, please first discuss the change you wish
to make via issue, email, or any other method with the owners of this repository
before making a change.

If you are new to contributing then please start with "Issues" available on the
website.

Please note we have a code of conduct, please follow it in all your interactions
with the project.

## Commits

Please follow all the best practices for creating commits.

Read these articles:

- [Writing good git commits]

- [Git commit best practices]

[Writing good git commits]: (https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
[Git commit best practices]: (https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices)

## Branches

This project uses [Gitlab Flow] for development.

There is only one permanent branch. Its the `master`.
This branch is where the development takes place.

In most cases we have a series of `release` branches. The naming convention of
this branch goes like this:

  `release-v1.2.3`

These branches are read-only. Once created no additional commits are pushed into
it. For that create new release branch.

For all development use `master` branch, but developers are free to create and
maintain additional `feature` branch.

The naming convention of `feature` branch goes like this:

  `feature-new_awesome_feature_v1.2.3`

But these branches are to be merged back into the `master`.

On some cases additional `staging` and `production` could be used.

There will be only one `staging` and only one `production` branch.

No Hotfixes. If any emergency patch fixes push to master and create new release
branch.

Hotfixes causes lot of trouble. Not worth it.

[Read more][Gitlab Flow] about this.

## Tagging

All tags start with `v`.
Examples: `v3.2.1`.

The versioning scheme we use is [SemVer](http://semver.org/).

## Merge/Pull Request Process

1. Ensure that no build files are uploaded and if possible update the
gitignore file.
2. Update the README.md with details of changes to the interface, this includes
new environment variables, exposed ports, useful file locations and container
parameters.
3. Increase the version numbers in any examples files and the README.md to the
new version that this. Merge/Pull Request would represent.
4. You may accept the Merge/Pull Request in once you have the sign-off of two other
developers, or if you do not have permission to do that, you may request the
second reviewer to merge it for you.
5. All Merge/Pull Request needs to be labeled appropriately. Check the [Labelling method].
6. All Merge/Pull Request must also be attached to a milestones.

## Creating a new Issue

Please use issues as much as possible. Issues are the best way to communicate
about the project. Don't email the project maintainers unless necessary.

Please use the template. Every issue must have correct labels, milestone
information.

For Bug reports one issue per bug. If multiple bugs are related then use related
feature on the website or add the url to the related bug in the Description.

### Labelling method
All issues are categorised into three:

1. **Priority**
    1. ~"Priority: Critical"
    2. ~"Priority: High"
    3. ~"Priority: Medium"
    4. ~"Priority: Low"

2. **Type**
    1. ~"Type: Bug"
    2. ~"Type: Maintenance"
    3. ~"Type: Enhancement"
    4. ~"Type: Discussion"

3. **Status**
    1. ~"Status: To Do"
    2. ~"Status: In Progress"
    3. ~"Status: In Review"

[Labelling method]: (#labelling-method)

[Gitlab Flow]: (https://docs.gitlab.com/ee/workflow/gitlab_flow.html)
