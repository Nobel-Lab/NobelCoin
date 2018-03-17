Nobelcoin Core integration/staging tree
www.nobelcoin.com

What is Nobelcoin?
Nobelcoin is an experimental digital currency that enables instant payments to anyone, anywhere in the world. Nobelcoin uses peer-to-peer technology to operate with decentralize authority: managing transactions and issuing money are carried out collectively by the network. Nobelcoin Core is the name of open source software which enables the use of this currency.
For more information, as well as an immediately useable, binary version of the Nobelcoin Core software, see http://www.nobelcoin.com/ or read the Original White Papar.
License
The MIT License (MIT)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the”Software”), to deal in the Software without restriction, including without limitation the rights to use, copy modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies of substantial portions of the Software.
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Development Process
The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are created regularly to indicate new official, stable release versions of Nobelcoin Core.
The contribution workflow is described inCONTRIBUTING.md.
The developer mailing list should be used to discuss complicated or controversial changes before working on a patch set.
Testing
Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.
Automated Testing
Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check. Further details on running and extending unit tests can be found in /src/test/README.md.
There are also regression and integration tests, written in Python, that are run automatically on the build server. These tests can be run (if the test dependencies are installed) with: test/functional/test_runner.py
The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.
Manual Quality Assurance (QA) Testing
Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.
Translations
Changes to translations as well as new translations can be submitted to Nobelcoin Core's Transifex page.
Translations are periodically pulled from Transifex and merged into the git repository. See the translation processfor details on how this works.
Important: We do not accept translation changes as GitHub pull requests because the next pull from Transifex would automatically overwrite them again.
Translators should also subscribe to the mailing list.

