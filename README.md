# Renovate discussion #37850

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

1. Add an `.nvmrc` file to the root of your repo, behind latest.
2. See dependency dashboard entries and PRs created for updating Node.
3. Include a comment in the `.nvmrc` file using the hash comment syntax (`# comment`) https://github.com/nvm-sh/nvm/issues/3336.
4. See how Renovate closes the PRs and removes the entries from the dep. dashboard.

## Expected behavior

1. Add an `.nvmrc` file to the root of your repo, behind latest.
2. See dependency dashboard entries and PRs created for updating Node.
3. Include a comment in the `.nvmrc` file using the hash comment syntax (`# comment`) https://github.com/nvm-sh/nvm/issues/3336.
4. Renovate should keep the Node PRs open (and continue to open them for future updates).

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/37850
