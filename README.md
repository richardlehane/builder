# PRONOM Builder

Uses the roy tool to harvest [PRONOM](http://nationalarchives.gov.uk/PRONOM/Default.aspx) and then builds Ross Spencer's skeleton suites ([regular](https://github.com/exponential-decay/skeleton-test-suite-generator) and [container](https://github.com/exponential-decay/skeleton-container-test-suite-generator)). Uses Github Actions to automate creation of [releases](https://github.com/richardlehane/builder/releases).

## Rolling a new release

Make sure follow tags is configured with `git config --global push.followTags true`. Then:

- replace DROID and container signature files in this repository with latest
- commit change
- tag e.g. `git tag -a v91 -m "PRONOM v91"`
- then push to master.