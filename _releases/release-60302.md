---
layout: releases
version: 6.03/02
release_date: 2015-01-27
state:

toc: true
toc_sticky: true
sidebar:
  nav: "download"
---


## Source distributions

| Platform       | Files | Size |
|-----------|-------|-----|
| source | [root_v6.03.02.source.tar.gz](https://root.cern.ch/download/root_v6.03.02.source.tar.gz) |  95M |


## Binary distributions

| Platform       | Files | Size |
|-----------|-------|-----|
| Scientific Linux Cern 6_amd64 gcc4.8 | [root_v6.03.02.Linux-slc6_amd64-gcc4.8.tar.gz](https://root.cern.ch/download/root_v6.03.02.Linux-slc6_amd64-gcc4.8.tar.gz) | 147M |
| OsX 10.9 i386 | [root_v6.03.02.macosx64-10.9-i386.tar.gz](https://root.cern.ch/download/root_v6.03.02.macosx64-10.9-i386.tar.gz) | 132M |
| OsX 10.10 i386 | [root_v6.03.02.macosx64-10.10-i386.tar.gz](https://root.cern.ch/download/root_v6.03.02.macosx64-10.10-i386.tar.gz) | 132M |



## Installations in AFS and CVMFS
Standalone installations with minimal external dependencies are available at:
~~~
/afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02/x86_64-slc6-gcc48-dbg
/afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02/x86_64-slc6-gcc48-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02/x86_64-mac109-clang60-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02/x86_64-mac1010-clang60-opt
~~~

## AFS
Versions for many different platforms and compilers are available at:
/afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02

To use ROOT directly from AFS:
~~~
. /afs/cern.ch/sw/lcg/external/gcc/4.8/x86_64-slc6-gcc48-opt/setup.sh
. /afs/cern.ch/sw/lcg/app/releases/ROOT/6.03.02/x86_64-slc6-gcc48-opt/root/bin/thisroot.sh
~~~

## Direct Git repository access
The entire ROOT source can be obtained from our public Git repository:

~~~
git clone http://root.cern.ch/git/root.git
~~~
The release specific tag can be obtained using:
~~~
cd root
git tag -l
git checkout -b v6-03-02 v6-03-02
~~~