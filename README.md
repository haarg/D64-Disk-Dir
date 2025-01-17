D64-Disk-Dir
============

[![CPAN version](https://badge.fury.io/pl/D64-Disk-Dir.png)](https://metacpan.org/pod/D64::Disk::Dir)

`D64::Disk::Dir` is a Perl module providing an abstraction layer above `D64::Disk::Image` module (Perl interface to Per Olofsson's "[diskimage.c](https://paradroid.automac.se/diskimage/)", an ANSI C library for manipulating Commodore disk images written in C), enabling users to handle D64 disk image directories in a higher-level object-oriented way.

PREREQUISITES
-------------

* `Array::Iterator` >= 0.06
* `D64::Disk::Image` >= 0.03

VERSION
-------

Version 0.05 (2023-05-14)

INSTALLATION
------------

To install this module type the following:

    perl Makefile.PL
    make
    make test
    make install

DOCUMENTATION
-------------

A comprehensive module documentation is available on [CPAN](https://metacpan.org/pod/D64::Disk::Dir).

COPYRIGHT AND LICENCE
---------------------

This module is licensed under a slightly modified BSD license, the same terms as Per Olofsson's "diskimage.c" library and D64::Disk::Image Perl package it is based on, license contents are repeated below.

Copyright (c) 2003-2006, Per Olofsson
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
