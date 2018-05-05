# LICENSE

BipCot NoGov Software License (www.bipcot.org), version 1.12 / No warranty of usability of BipCoin software.

This original computer code and resulting program was made by Beastlick Internet Policy Commission Outreach Team, 2016. All rights to make fun of you reserved. https://bipcoin.org

(Adapted from CryptoNote code, covered by permissive MIT license. https://cryptonote.org )

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions and adaptations of source code or program must retain the entirety of this license, including retaining attribution of the license holder of the software.

Redistributions in binary form must reproduce the entirety of this license.

Neither the name of the license holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission. Furthermore, no attempt will be made to impersonate the person or entity whose software is being used or modified.

Governments, and agents and subcontractors of same, are not permitted to use this software or derivations of this software.

If governments, agents and subcontractors of same use this software, or derivations of this software, all agencies and persons directly and knowingly involved may be shamed in public, by name, on the Internet, on radio, and in any media now extant or invented in the future, throughout the known universe and elsewhere, in perpetuity. Governments, agents and subcontractors of same that use this software, or derivations of this software, agree to endure this shaming, without comment or action.

Any person or entity that violates any part of this agreement will also be shamed as above, and agrees to endure this shaming, without comment or action.

The BipCot NoGov Software License adopts the first 3 clauses of the 3-Clause BSD license (Berkeley Software Distribution license) and adopts the BSD "as is" text at the end. The 3-Clause BSD license is in the Public Domain. However, there is no partnership or endorsement created or implied between the creators or users of The BipCot NoGov Software License and the creators or users of the BSD license, or vise versa.

This version allows for "LIBERTARIAN INDULGENCES." i.e. low level government workers like mailmen and peaceful future Internet freedom hero contractors can use the thing that is licensed. But cops, goons, politicians, alphabet soup agency workers, etc, and anyone who carries a gun or orders the use of guns for the gub'mnint is still forbidden. (LICENSE HOLDER SHOULD REMOVE THIS PART, SECTION 8, TO REMOVE THIS OPTION.)

THIS SOFTWARE IS PROVIDED BY THE LICENSE HOLDER AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE LICENSE HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


## Building Bitcedi

### On *nix:

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55 or later.

You may download them from:

- http://gcc.gnu.org/
- http://www.cmake.org/
- http://www.boost.org/

Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

#### Advanced options:

Parallel build: run `make -j<number of threads>` instead of `make`.

Debug build: run `make build-debug`.

Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.

Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows:
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55 or later. You may download them from:

- http://www.microsoft.com/
- http://www.cmake.org/
- http://www.boost.org/

To build, change to a directory where this file is located, and run this commands:
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.

Good luck!
