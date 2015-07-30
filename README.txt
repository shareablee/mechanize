# Mechanize

Repo forked from existing Mechanize python package to fix a bug explained here:
https://github.com/jjlee/mechanize/pull/58

## Deployment
From the base of shareablee/web directory run  the following:
```
fab -R group_django -- /srv/env/bin/pip install -U git+ssh://git@github.com/shareablee/mechanize.git
```

## Usage

To use this repository instead of the mechanize repo installed automatically with `pip install` follow these steps:
 - From the root directory of the web repo, run `pip uninstall mechanize`
 - From the root of this directory, run `python setup.py develop`