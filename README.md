cpuminer-opt is a fork of cpuminer-multi by TPruvot with optimizations
imported from other miners developped by lucas Jones, djm34, Wolf0, pooler,
Jeff garzik, ig0tik3d, elmad, palmd, and Optiminer, with additional
optimizations by Jay D Dee.

All of the code is believed to be open and free. If anyone has a
claim to any of it post your case in the cpuminer-opt Bitcoin Talk forum
or by email.

https://bitcointalk.org/index.php?topic=1326803.0

mailto://jayddee246@gmail.com


Supported Algorithms
--------------------
                          m7m          Magi (XMG)
How to build
------------

1. You need a raspberry pi board (Only tested on pi 3)

2. The following command should install everything you need on Debian based
distributions such as Ubuntu or PI64 :

sudo apt-get install build-essential libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev automake zlib1g-dev libncurses5-dev curl

build-essential  (for Ubuntu, Development Tools package group on Fedora)
automake
libjansson-dev
libgmp-dev
libcurl4-openssl-dev
libssl-dev
pthreads
zlib


3. Run ./build.sh to build on Linux

4. Start mining.

./cpuminer -a m7m -o url -u username -p password

Errata
------

Benchmark testing does not work for x11evo.

Bugs
----

Users are encouraged to post their bug reports on the Bitcoin Talk
forum at:

https://bitcointalk.org/index.php?topic=1326803.0

All problem reports must be accompanied by a proper definition.
This should include how the problem occurred, the command line and
output from the miner showing the startup and any errors.

Donations
---------

I do not do this for money but I have a donation address if users
are so inclined.

bitcoin:12tdvfF7KmAsihBXQXynT6E6th2c2pByTT?label=donations (Original Dev)
bitcoin:3LoZbmNMNBFF7mudQ8L1HhpE6thLskCXq6  (Me)

Happy mining!

