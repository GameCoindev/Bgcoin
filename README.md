# What is Bgcoin?
<img src="https://a.poolcc.cc/favicon3.ico" width="150">
Bgcoin is a decentralized secure cryptocurrency that is easy to mine devoid from 51% attack and it provide easy means of transactions between individuals. It is a Multi-algorithm coin. ButKoin uses a Smartnode collateral and reward system that prevent hyperinflation.<br>
Bgcoin abbreviation is BGC<br>
Bgcion is mainly used in the circulation of games. It is a kind of general game currency. Later, it will be used in a large number of games with high degrees of freedom, and most props in the game can be freely traded. With the increase of the popularity of the game, the value of bgcoin will rise, and the increase of the value of bgcoin will also help promote the game. Therefore, it is a currency complementary to the game.

# Download Address
 [bgc-qt.zip](https://a.poolcc.cc/bgc-qt.zip)<br>
 The source code will be published here after March

# Pool List
The block has 5000 BGC,among them, 1000 BGC will be paid to smart nodes after 5761 height and 250 BGC will always be paid to developers.<br>
1.http://pool.bgcoin.top/

# Supported Algorithms



| Algorithm   | GPU CPU Asic|
| ----------- | ----------- |
| [Ghostrider](https://a.poolcc.cc/xmrig%E6%97%A0%E6%8A%BD%E6%B0%B4.zip)  | CPU         |
| Yespower    | CPU         |
| Lyra2z330   | CPU         |
| Sha256      | Asic        |
| Scrypt      | Asic        |

# Smartnodes Collaterals



| Height   | Collaterals | reward |
| ----------- | ----------- | ----------- |
|    0-5761   |    5,000,000  |      0%    |
| 88720-176720  |    10,000,000  |      20%    |
| 176720-264720  |    15,000,000  |      20%    |
| 264720- ∞  |    20,000,000  |      20%    |

License
-------

But Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is done in separate branches.
[Tags](https://github.com/but/but/tags) are created to indicate new official,
stable release versions of But Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).



Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.
