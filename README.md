# Warning! This is the main development branch.

Do not use this branch for production environments. This branch (master) is for development purposes. Users looking for the current release branch, checkout [stable](https://github.com/aurarad/Auroracoin/tree/stable).


# AuroraCoin AUR

http://auroracoin.is

Follow [@OfficialAUR](https://twitter.com/OfficialAUR)

Copyright (c) 2014-2018 Auroracoin Developers


## What is AuroraCoin?

Auroracoin is a cryptocurrency for Iceland. It was initially based on Litecoin and 50% premined, later it incorporated the multi-algorithm PoW
approach of DigiByte. The premined coins were distributed to the entire population of Iceland, commencing on midnight 25th of March 2014.


## Community

Forums: http://auroraspjall.is/

Irc: #aur on freenode

http://www.reddit.com/r/auroracoin

http://www.reddit.com/r/AURmarket

https://bitcointalk.org/index.php?topic=1044432.0

## License

Auroracoin is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

## Development Process

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/aurarad/auroracoin/tags) are created
regularly to indicate new official, stable release versions of Auroracoin.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

## Testing

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.


## Developers

Developers are encouraged to create tools for Auroracoin to support the adoption of Auroracoin. Such software, e.g. for
payments, will help Icelanders start using the currency in their daily lives.

Interested in helping out? Please email auroracoin@auroracoin.is, and let us know how you can help.


## OSX
export OPENSSL_ROOT_DIR=/usr/local/Cellar/openssl/1.0.2t/
export OPENSSL_INCLUDE_DIR=/usr/local/Cellar/openssl/1.0.2t/include
