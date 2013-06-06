## Installation

Place `pre-commit` in `~/.git_template/hooks/pre-commit`

Add `~/.git_template` as your `templatedir` by running:

``` sh
git config --global init.templatedir '~/.git_template'
```

You will need to run `git init` in any existing repositories for the hook to begin working.
You will also need to re-run `git init` if any changes are made to the `pre-commit` script.

**Note:** Requires `git >= 1.7.1`.

## Thanks

The original script was created by Jamie Lawrence,
go check out his [blog post] on it.

[blog post]: http://jamie.ideasasylum.com/2013/02/preventing-the-stupid-mistakes-like-committing-focustrue/
