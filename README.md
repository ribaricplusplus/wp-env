# wp-env

**This project is no longer relevant or maintained**

This is a fork of the [original](https://github.com/WordPress/gutenberg/tree/trunk/packages/env) `wp-env`. This fork is created to merge PRs faster. Due to the volume of work in the Gutenberg repository sometimes it takes months to merge a PR, and that's annoying to wait for.

The biggest difference between current Gutenberg `wp-env` and this fork is that the fork lets you add `phpConfig` entry into `.wp-env.json`. For more information see [#28703](https://github.com/WordPress/gutenberg/issues/28703)

Do not submit PRs directly to this repository. If you want a PR that's awaiting review in Gutenberg merged, open an issue here mentioning the PR.

# Usage

Install from `npm` into your project:

`npm i -D @ribarich/wp-env`

Then use it by running `npx wp-env start`, etc. See the original package for all available commands.

# Merged PRs

PRs that this repo integrates which original `wp-env` doesn't:

- https://github.com/WordPress/gutenberg/pull/30377
- https://github.com/WordPress/gutenberg/pull/30053
