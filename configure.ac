AC_INIT([Haskell base package], [1.0], [libraries@haskell.org], [base])

dnl Calling AC_CHECK_TYPE(T) makes AC_CHECK_SIZEOF(T) abort on failure
dnl instead of considering sizeof(T) as 0.
AC_CHECK_TYPE([struct MD5Context], [], [AC_MSG_ERROR([internal error])], [#include "include/md5.h"])
AC_CHECK_SIZEOF([struct MD5Context], [], [#include "include/md5.h"])
