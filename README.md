gtest-1.6.0 system i version
=====

If, or while this changes won't be included in mainstream source tree, you can obtain 
Google Tests porting for os/400 | IBM System i there.

Building
=====
It can be fully compiled via CRTCPPMOD.
Yours gtest-1.6.0 bundle must be putted on system i as a set of stream files.
Just run
```bash
CRTCPPMOD SRCSTMF('<gtest-path>/src/gtest-all.cc') INCDIR('<gtest-path>/include''<gtest-path>')
```
