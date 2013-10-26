gtest-1.6.0 system i version
=====
It's a port of Google Testing framework to IBM System i aka (os/400) aka (AS/400) aka (i5/OS).
If, or while this changes won't be included in mainstream source tree, you can obtain 
Google Tests porting for os/400 | IBM System i there.

Building
=====
It can be fully compiled via CRTCPPMOD.
Your gtest-1.6.0 bundle must be putted on system i as a set of stream files.<br>
Just run for compile module:
```bash
CRTCPPMOD SRCSTMF('<gtest-path>/src/gtest-all.cc') INCDIR('<gtest-path>/include''<gtest-path>')
```

Then this module can be linked to any ILE programm via CRTPGM.
