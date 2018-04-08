Examination Core
===============================


http://coolexam.org/

Copyright (c) 2009-2018 Bitcoin Core Developers

Copyright (c) 2011-2018 Litecoin Core Developers

Copyright (c) 2014-2018 Dash Core Developers

Copyright (c) 2018 Examination Developers


What is Examination?
----------------

Examination is an experimental new digital currency that enables anonymous, instant
payments to anyone, anywhere in the world. Examination uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network. Examination Core is the name of open
source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Examination Core software, see http://coolexam.org/


License
-------

Examination Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Examination
development team members simply pulls it.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see [doc/coding.md](doc/coding.md)) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/examinationcoin) are created
regularly to indicate new official, stable release versions of Examination.


**compiling for debugging**

Run configure with the --enable-debug option, then make. Or run configure with
CXXFLAGS="-g -ggdb -O0" or whatever debug flags you need.

**debug.log**

If the code is behaving strangely, take a look in the debug.log file in the data directory;
error and debugging messages are written there.

The -debug=... command-line option controls debugging; running with just -debug will turn
on all categories (and give you a very large debug.log file).

The Qt code routes qDebug() output to debug.log under category "qt": run with -debug=qt
to see it.

