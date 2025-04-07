# TMVA-SOFIE

How to build:

```
git clone git@github.com:guitargeek/tmva-sofie.git
cd tmva-sofie
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX=../install
make install -j8
```

To make it not collide with TMVA-SOFIE in ROOT, some things still need to be done:

  * put headers in differnt directory
  * rename libraries
  * use a different namespace
