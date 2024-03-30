---
sidebar_position: 2
---

# GitHub User or Org Scan

The GitHub user or organization scan allows you to scan a GitHub user or organization for secrets. We will use the `--github-owner` option to specify the user or organization to scan.

To avoid rate limiting and to scan private repositories, you will need to provide a GitHub personal access token with `repo` access. You can create a token by following the instructions [here](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token).

Use the `-t` or `--token` option to provide the token.

Below we are going to scan the `bogu` GitHub organization for secrets.

```bash
$ bogu --github-owner bogu-io --token ghp_dHLrWLcEXAMPLErZwmIllFMz9RrEXAMPLErV
Bogu v0.0.14

Starting GitHub User scan...

...
```

By default bogu will output information about the file it is scanning and the secrets it finds. You can turn this output off by using the `-s` or `--silent` option.

```bash
$ bogu --github-owner bogu-io --token ghp_dHLrWLcEXAMPLErZwmIllFMz9RrEXAMPLErV -s
Bogu v0.0.14

Starting GitHub User scan...

$
```
