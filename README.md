# 35225

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Currently Renovate is opening PRs for indirect golang dependencies:
golang.org/x/net
golang.org/x/crypto

## Expected behavior

Renovate should open only PRs for direct dipendencies

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/35225
