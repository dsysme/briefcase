# Contributing code to ODK Briefcase

This is a living document. If you see something that could be improved, edit this document and submit a pull request following the instructions below!

## Submitting a pull request
To contribute code to ODK Briefcase, you will need to open a [pull request](https://help.github.com/articles/about-pull-requests/) which will be reviewed by the community and then merged into the core project.

1. [Set up your development environment](https://github.com/opendatakit/briefcase#setting-up-your-development-environment). 

1. To make sure you have the latest version of the code, set up this repository as [a remote for your fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/) and then [sync your fork](https://help.github.com/articles/syncing-a-fork/).

1. Create a branch for the code you will be writing:

        git checkout -b NAME_OF_YOUR_BRANCH

1. If there is an [issue](https://github.com/opendatakit/briefcase/issues) corresponding to what you will work on, **comment on it** to say you are addressing it. 

1. Once you've made incremental progress towards you goal, commit your changes with a meaningful commit message. Use [keywords for closing issues](https://help.github.com/articles/closing-issues-via-commit-messages/) to refer to issues and have them automatically close when your changes are merged.

        git commit -m "Do a thing. Fix #1."

1. Push changes to your fork to make them publicly available:

        git push

1. When your changes are ready to be added to the core ODK Briefcase project, [open a pull request](https://help.github.com/articles/creating-a-pull-request/). Make sure to set the base fork to `opendatakit/briefcase`. Describe your changes in the comment, refer to any relevant issues using [keywords for closing issues](https://help.github.com/articles/closing-issues-via-commit-messages/) and tag any person you think might need to know about the changes.

## Style guidelines
For now, match the style of the code in the file you are editing.

## Code from external sources
ODK Briefcase is released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0). Please make sure that any code you include is an OSI-approved [permissive license](https://opensource.org/faq#permissive). **Please note that if no license is specified for a piece of code or if it has an incompatible license such as GPL, using it puts the project at legal risk**.

Sites with compatible licenses (including [StackOverflow](http://stackoverflow.com/)) will sometimes provide exactly the code snippet needed to solve a problem. You are encouraged to use such snippets in ODK Briefcase as long as you attribute them by including a direct link to the source. In addition to complying with the content license, this provides useful context for anyone reading the code. 