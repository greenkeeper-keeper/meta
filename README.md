# greenkeeper-keeper

greenkeeper-keeper is a service to automatically merge passing [greenkeeper](https://greenkeeper.io) PRs

## Motivation

[Greenkeeper](https://greenkeeper.io) is a fantastic service that makes it easy for me to keep dependencies up to date. However, it can get a bit noisy and create quite a few PRs. Hence, [the birth of greenkeeper-keeper](https://medium.com/@kurtiskemple/keeping-up-with-greenkeeper-io-a8d6c1703e4a).

To help you keep up with all of that activity, greenkeeper-keeper can automatically accept PRs from greenkeeper as long as all of your commit status checks pass.

## Designed to help, not take over

greenkeeper-keeper is limited to handling only PRs from greenkeeper. It will not attempt to accept PRs from other sources.

It will only accept PRs that have passing [commit status checks](https://help.github.com/articles/about-required-status-checks/). If any checks fail, greenkeeper-keeper will comment on the PR to inform you that it could not accept the PR and will let you take care of resolving the problem.
