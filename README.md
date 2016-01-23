# User-env

Just some simple ansible tasks to set up my shell environment across my hosts. Not anticipating that this will be useful to anyone else.

## gotchas

Emacs config -- you may need to set up the virtualenv manually in .emacs.d (jedi install-server doesn't work on linux apparently?)

```
mkdir .emacs.d/.python-environments
cd !$
virtualenv default
# open emacs, then run M-x jedi:install-server, M-x jedi:setup
```
