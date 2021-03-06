# Version 0.4.0.3

* Bump upper bound on `exceptions` dependency.


# Version 0.4.0.2

* Workaround `sendLazy` build issues in Windows 8 (see #13).

* Bump upper bound on `network` dependency.


# Version 0.4.0.1

* Add `sendLazy` and `sendMany` to `Network.Simple.TCP`.


# Version 0.4

* Bump lower and upper bounds `exceptions` dependency. Replacing some
  uses of `MonadCatch` with `MonadMask.

* Bump upper bound on `network` dependency.

* Bump upper bound on `transformers` dependency.


# Version 0.3.1

* Bumped upper-bounds on `exceptions` dependency.


# Version 0.3.0

* Re-export `Network.Socket.close` at `Network.Simple.TCP`, except
  called `closeSock`.

* Re-export `Socket`, `SockAddr`, `HostName` and `ServiceName` from
  `Network.Socket` at `Network.Simple.TCP`.

* Generalize the `IO` monad by using `MonadIO` and `MonadCatch` (from
  the `exceptions` library).


# Version 0.2.1.0

* Export `send` and `recv` from `Network.Simple.TCP`.

* Re-export `Network.Socket.withSocketsDo` from `Network.Simple.TCP`.


# Version 0.2.0.1

* FIX: `acceptFork` now properly closes the connection socket, even in
  case of asynchronous exceptions.


# Version 0.2.0.0

* `Network.Simple.TCP.serveFork` was renamed to `serve`, and the previous
  function named `serve` was removed.


# Version 0.1.0.1

* Fixed typos, including the maintainer email.


# Version 0.1.0.0

* First release.
