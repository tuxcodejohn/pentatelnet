AC_INIT([pentatelnet],[0.1])
AC_CONFIG_SRCDIR([src/telnetd.c])
AC_CONFIG_HEADERS([src/config.h])
AC_GNU_SOURCE

AC_DEFINE(DOMAIN_NAME,["c3d2.de"],  domain that serves this stuff )


dnl put this to gengetopt stuff.....
AC_DEFINE(MY_LISTEN_PORT,[11123],Port we listen for requests)


AM_INIT_AUTOMAKE([ color-tests \
		  silent-rules \
		  parallel-tests])

AC_PROG_CC
AM_PROG_CC_C_O
PKG_CHECK_MODULES([LIBEVENTSTUFF], [libevent > 2.0.0])

dnl AC_CHECK_PROGS(gengetopt, gengetopt, [false])
dnl GENGETOPT=$gengetopt
dnl AC_SUBST(GENGETOPT)
dnl AC_ARG_VAR(var-name, help-string)

dnl AC_ARG_ENABLE(debug_pc,
dnl 	      [  --enable-debug_pc    Thou shall use this to debug without an icnovalike platform],
dnl 	      AC_DEFINE([DEBUG_NOT_ICNOVA]), )

AC_OUTPUT([
Makefile
src/Makefile
])

