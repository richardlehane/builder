# PRONOM Builder

Uses the roy tool to harvest PRONOM and then builds skeleton suites ([regular](https://github.com/exponential-decay/skeleton-test-suite-generator) and [container](https://github.com/exponential-decay/skeleton-container-test-suite-generator)). Uses [travis](https://travis-ci.org) to automate creation of [releases](https://github.com/richardlehane/builder/releases).

## Rolling a new release

Make sure follow tags configured with `git config --global push.followTags true`. Then:

- update DROID and container signature files in this repository
- commit change
- tag e.g. `git tag -a v91 -m "PRONOM v91 release"`
- then push to master.

