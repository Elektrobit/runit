# runit

Maintained repository of `runit`, a cross-platform Unix init scheme with service supervision;
a replacement for sysvinit and other init schemes.

It runs on GNU/Linux, *BSD, Mac OS X, and Solaris, and can easily be adapted to other
Unix operating systems. runit implements a simple three-stage concept.

- Stage 1 performs the system's one-time initialization tasks.
- Stage 2 starts the system's uptime services (via the runsvdir program).
- Stage 3 handles the tasks necessary to shutdown and halt or reboot.

More information is on the original website: http://smarden.org/runit/

NOTE: This repository was forked from a maintained version by Void Linux and incorporates
patches that fix issues found by users as well as certain compiler warnings.

The source history was obtained from <http://smarden.org/git/runit.git/>, but
the release tarballs have been pruned from this version.
