# Contributing to Teki Linux
Love Teki Linux and want to help? Thanks so much, there's something to do for everybody!

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue or assessing patches and features.

## Using the issue tracker

The [issue tracker](https://github.com/tekilinux/TekiLinux-amd64/issues) is
the preferred channel for [bug reports](#bugs), [features requests](#features)
and [submitting pull requests](#pull-requests).

**Important Reminders: (For Maintainers)**
- After creating an issue don't forget to Add Github Power-ups on our
[Trello Board](https://trello.com/b/xqUrR6Ys/tekilinux-tekilinux-amd64).
- To add a GitHub Power-up, click your issue on Issues List and from there look for the GitHub Power-up.

<a name="bugs"></a>
## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful - thank you!

Guidelines for bug reports:

1. **Use the GitHub issue search** &mdash; check if the issue has already been reported.

2. **Check if the issue has been fixed** &mdash; try to reproduce it using the latest `master` or development branch in the repository.

3. **Isolate the problem** &mdash; ideally create a [reduced test case](https://css-tricks.com/reduced-test-cases/) and a live example (source provided is for web application but also applicable for this project).

A good bug report shouldn't leave others needing to chase you up for more information. Please try to be as detailed as possible in your report. What is your environment? What steps will reproduce the issue? What tools are you using when
experiencing the problem? What would you expect to be the outcome? All these details will help people to fix any potential bugs.

Example:

> Short and descriptive example bug report title
>
> A summary of the issue and the OS environment or tools in which it occurs. If
> suitable, include the steps required to reproduce the bug.
>
> 1. This is the first step
> 2. This is the second step
> 3. Further steps, etc.
>
> `<url>` - a link to the reduced test case (could be a gist or any code sample)
>
> Any other information you want to share that is relevant to the issue being
> reported. This might include the lines of code that you have identified as
> causing the bug, and potential solutions (and your opinions on their
> merits).


<a name="features"></a>
## Feature requests

Feature requests are welcome. But take a moment to find out whether your idea fits with the scope and aims of the project. It's up to *you* to make a strong case to convince the project's developers of the merits of this feature. Please provide as much detail and context as possible.


<a name="pull-requests"></a>
## Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

**Please ask first** before embarking on any significant pull request (e.g.
implementing features, refactoring code, porting to a different language),
otherwise you risk spending a lot of time working on something that the
project's developers might not want to merge into the project.

Please adhere to the coding conventions used throughout a project (indentation,
accurate comments, etc.) and any other requirements (such as test coverage).

Adhering to the following process is the best way to get your work
included in the project:

### RULES TO KEEP IN MIND:
- Naming convention for local branch should be the issue number
- Pull request title should follow this format: **Issue_#: Title**
- Commits for pull request should follow this format: **Issue_#: Commit Message**

Git Flow concept could be visualised here after forking the repository: 
[*Forking Workflow*](https://guides.github.com/introduction/flow/)

Advantage and description of this Git Flow can be read here:
[*Comparing Workflows: Forking Workflow*](https://www.atlassian.com/git/tutorials/comparing-workflows#forking-workflow)

Git Flow on creating a pull request (Step by Step):
1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your fork, and configure the remotes:
   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/TekiLinux-amd64.git
   # Navigate to the newly cloned directory
   cd TekiLinux-amd64
   # Assign the original repo to a remote branch
   git remote add upstream https://github.com/tekilinux/TekiLinux-amd64.git
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

3. Create a new branch (off the `master` branch) to contain your feature, change, or fix:
   ```bash
   git checkout -b <Issue_Number>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) or your code is unlikely be merged into the main project. Use Git's [interactive rebase](https://help.github.com/articles/about-git-rebase/) feature to tidy up your commits before making them public.

5. Push your local branch up to your fork:

   ```bash
   git push origin <Issue_Number>
   ```

6. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description. The template for pull request is already set for you to fill up.

**IMPORTANT**: By submitting a patch, you agree to allow the project
owners to license your work under the terms of the [MIT License](https://github.com/tekilinux/TekiLinux-amd64/blob/master/LICENSE).