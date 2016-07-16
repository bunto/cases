# Bunto Test Cases

This repository is for Bunto sites used to attempt to reproduce issues
with Bunto. They are named by the related repository and issue number.

## Usage

```bash
~$ git clone git://github.com/bunto/cases.git
~/cases$ cd cases
~/cases/bunto-123$ # pick your case and cd into that
~/cases/bunto-123$ bunto build --trace
```

Always run with the latest version of Bunto unless a `Gemfile` is
included.
