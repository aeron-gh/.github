# Contributing

Thanks for helping. This guide covers my personal repositories. If a repository has its own
`CONTRIBUTING.md`, follow that one: it comes first.

By taking part, you agree to follow the
[Code of Conduct](https://github.com/aeron-gh/.github/blob/main/CODE_OF_CONDUCT.md).
Found a security problem? Don't open an issue. Follow the
[security policy](https://github.com/aeron-gh/.github/blob/main/SECURITY.md) instead.

## Before you start

- Small fix, like a typo or a broken link? Open a pull request.
- Anything bigger? Open an issue first, so we can agree on the approach.
- Keep one change per pull request. Small pull requests get reviewed faster.
- Never commit passwords, private keys or access tokens.

## Pull request titles

Use [Conventional Commits](https://www.conventionalcommits.org): `type: summary`. The summary is
lowercase and imperative, and the whole title is at most 72 characters.

```text
fix: handle an empty list
docs: fix the broken setup link
```

I squash-merge pull requests, so the title becomes the commit on the default branch.
