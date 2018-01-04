## Welcome!

We’re so glad you’re thinking about contributing to a Lawrence Livermore
National Laboratory open source project! If you’re unsure about anything, just
ask — or submit your issue or pull request anyway. The worst that can happen is
we’ll politely ask you to change something. We appreciate all friendly
contributions.

If you have any questions or want to read more, check out the [LLNL Open Source
Guidelines GitHub repository](https://github.com/LLNL/open-source-guidelines),
or just [shoot us an email](mailto:github-admin@llnl.gov).

## Table of Contents
[How To Contribute](#how-to-contribute)
  * [Reporting an Issue & Feature Suggestions](#reporting-an-issue--feature-suggestions)
  * [Pull Requests](#pull-requests)
  * [License](#license)
  * [Contributor's Declaration](#contributors-declaration)

## How To Contribute

### Reporting an Issue & Feature Suggestions
You can find a list of all outstanding issues and feature requests on our Github
issue tracker. Before creating a new issue or feature suggestion, ensure that:
* The issue or feature request hasn't been addressed in a newer version.
* That the issue or feature request doesn't already exist in the issue
tracker.

If the issue or feature request already exists, please provide additional
information if possible.

When creating a new issue, please provide at least the following information:
* Software Version
* Steps to reproduce the problem
* Any additional information (i.e. python call stacks, scheduler output
or logs)

### Pull Requests
If you would like us to consider a change or addition to the code base, feel
free to submit a pull request. Your pull request must meet the following
criteria before it can be merged.

* Your pull request must be based on the current `develop` branch and
apply without conflicts.
* Please try to limit pull requests to a single commit which resolves
one issue.
* Make sure your commit messages have a `Signed-off-by` line. See
[Contributor's Declaration](#contributors-declaration) for more information.
* For large pull requests, consider structuring your changes as a stack of
logically independent patches which build on each other.  This makes large
changes easier to review and approve which speeds up the merging process.
* Try to keep pull requests simple. Simple code with comments is much easier
to review and approve.
* Your pull request must pass automated testing.
* All proposed changes must be approved by a project member.

Git can append the `Signed-off-by` line to your commit messages. Simply
provide the `-s` or `--signoff` option when performing a `git commit`.
For more information about writing commit messages, visit [How to Write
a Git Commit Message](https://chris.beams.io/posts/git-commit/).

### License
This code is distributed under the License. Note that the phrase
"above copyright notice" in the license text refers to the current list of
copyrights that appears in the [LICENSE](LICENSE.md) file found
in the master branch.

### Contributor's Declaration
We have adopted the signed-off-by process as described in Section
11 of the Linux kernel document on [Submitting Patches](
https://www.kernel.org/doc/html/latest/process/submitting-patches.html).
Each proposed contribution to this code base must include the
text "Signed-off-by:" followed by the contributor's name and email address.
This is the developer's certification that they have the right to submit the
patch for inclusion into the code base and indicates agreement to the
Developer's Certificate of Origin:

"By making a contribution to this project, I certify that:
1. The contribution was created in whole or in part by me and I have the right
to submit it under the open source license indicated in the file; or
2. The contribution is based upon previous work that, to the best of my
knowledge, is covered under an appropriate open source license and I have the
right under that license to submit that work with modifications, whether
created in whole or in part by me, under the same open source license (unless
I am permitted to submit under a different license), as indicated in the file;
or
3. The contribution was provided directly to me by some other person who
certified (1), (2) or (3) and I have not modified it.
4. I understand and agree that this project and the contribution are public and
that a record of the contribution (including all personal information I submit
with it, including my sign-off) is maintained indefinitely and may be
redistributed consistent with this project or the open source license(s)
involved."

Proposed contributions failing to include a "Signed-off-by:" certification
will not be accepted into the code base. The maintainers reserve the right
to revert any commit made without the required certification.
