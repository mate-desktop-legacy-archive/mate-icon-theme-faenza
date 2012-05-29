dnl Process this file with autoconf to produce a configure script.
AC_PREREQ(2.53)

AC_INIT([mate-icon-theme-faenza], [1.3.0], [http://www.mate-desktop.org])
AC_CONFIG_SRCDIR([matefaenza/index.theme])

AM_INIT_AUTOMAKE([1.9 tar-ustar foreign])

# Workaround to make aclocal get the right flags
AC_SUBST(ACLOCAL_AMFLAGS, "\${ACLOCAL_FLAGS}")

# Define the toplevel path here
AC_SUBST(THEMEDIR, "\${datadir}/icons/matefaenza")

AC_CONFIG_FILES([
Makefile
matefaenza/Makefile
])

AC_OUTPUT
