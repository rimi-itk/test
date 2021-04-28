# Test

### GitHub Actions

We use [GitHub Actions](https://github.com/features/actions) to check coding
standards whenever a pull request is made.

Before making a pull request you can run the GitHub Actions locally to check for
any problems:

[Install `act`](https://github.com/nektos/act#installation) and run

```sh
act -P ubuntu-latest=shivammathur/node:focal pull_request
```

(cf. <https://github.com/shivammathur/setup-php#local-testing-setup>).
