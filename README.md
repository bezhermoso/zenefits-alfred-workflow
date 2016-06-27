# Zenefits Alfred Workflow

> Tested in Alfred 3

This workflow provides the following keywords:

```
Zenefits ...
         Clock in
         Clock out
         Start meal
         End meal
```

## Prerequisites

Install Node.js via [Homebrew](https://brew.sh).

```
$ brew install node
```

Install `zenefits-cli`:

```
$ npm install -g zenefits-cli
```

That's it!

### Important note to `nvm` users:

This workflow expects the `zenefits` executable to be installed in the `system` version of Node.js. Internally, the command is `/usr/local/bin/node /user/local/bin/zenefits [args]`. Installing the `zenefits-cli` package in the `system` version ensures that this works in an
non-login shell which Alfred uses.
