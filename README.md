# TDLib builds

Custom builds of TDLib and Telegram Bot API server using manual `workflow_dispatch` trigger.

Current builds:

* TDLib
  * Windows
  * Ubuntu 14
* Telegram Bot API server
  * Ubuntu 14

## Notes

* On Linux you may need `libc++` v1 installed (i.e. `libc++1` on Debian).
* On Linux OpenSSL version numbers must match, but build letters may not match. For example, `1.1.0` is not compatible with `1.1.1`, but `1.1.1c` is compatible with `1.1.1i`. Use `openssl version` command to check your installed version.
