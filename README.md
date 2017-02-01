perl-virtualenv
===============

Virtual Environment for Perl

# Goal
I came from Python world and would like to see the virtual-env virtualenvwrapper functionality brought to the Perl world. I'm guessing I'll be accomplishing this in combination with Perlbrew.

### To Do / Roadmap
-add virtual-env wrapper
-add mkvirtualenv functionality
-port virtualenv shell scripts to work with Perl

Usage
-----

### Activate & deactivate

```bash
$ cd /path/to/project
$ /path/to/perl/bin/virtualenv.pl venv
$ source venv/bin/activate
(venv) $ perl -v
(venv) $ cpanm -v
(venv) $ deactivate
$ perl -v
```

### Use it directly

```bash
$ /path/to/project/venv/bin/perl -v
```
