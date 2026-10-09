# Reflection: libatoms_quip

QUIP is a large Fortran package for atomistic simulation with a Python interface called quippy. It has 11,907 commits from 125 authors going back to 2009, but only 1 gap of at least three months. Its pattern is steady work that has slowly declined over time.

The longest gap was 6 months, from October 2024 to March 2025. The commits before it are normal work and do not explain it. The issue tracker does, though. Users kept filing issues the whole time the maintainers were quiet. Issue #669 has 30 comments, #673 has 23, and most of #675 through #682 are still open. Several were about installs breaking, like #674 "pip installation with python3.12" and #687 "CI tests broken." This means users had not left. The maintainers were busy while the packaging fell out of date.

The recovery came from fixing that build. Albert Bartok-Partay renamed the Fortran sources from F95 to F90, and James Kermode then moved the project to meson and added NumPy 2.x support. The same core maintainers led it, with a few new contributors like green-br. The project is Active, and its recent themes are bug fixes and feature development.
