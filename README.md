Dalecoin Cpu miner for windows os 64bit
=======================================

Simply download the code to your desktop.
edit minedalecoin.bat file with the correct details on dalecoin config file (minerd --url=http://127.0.0.1:11115 --userpass=dalecoinrpc:anypassword)
once set, save and double click to start mining


Dalecoin Cpu miner for Ubuntu 18.04 os 64bit
============================================

you may compile the binaries from the source code here or use the already compiled version  and run this code in your terminal

Use the following commands to compile and install minerd.

wget https://github.com/pooler/cpuminer/releases/download/v2.5.0/pooler-cpuminer-2.5.0.tar.gz
tar -xzvf pooler-cpuminer-2.5.0.tar.gz
cd cpuminer-2.5.0/
./configure CFLAGS="-O3"
make

then run

./minerd --url=http://127.0.0.1:11115 --userpass=dalecoinrpc:anypassword
