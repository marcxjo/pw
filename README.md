# pw - A Password Store Manager for the GNU Password Store

`pw` is a simple wrapper script for `pass` that enables the user to
conveniently specify a password store as a positional argument.

This is handy to enable separation of passwords into dedicated use
cases, such as

* separate stores for personal and work passwords
* shared password repositories
* dedicated storage for private key or client-specific passwords (i.e.,
  passwords which you may specifically _not_ want to sync elsewhere)

This script ships with bash completion that enables `pw` to run with a
similar workflow to `pass`. Note that it is currently _not_ implemented
as a `pass` extension (see https://www.passwordstore.org/#extensions),
but this may change in the future.

`pw` is released under the MIT license.

