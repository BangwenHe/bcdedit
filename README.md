# bcdedit
=======

BCD editor - Windows Boot Configuration Data

## Origin Repo

[bcdedit](https://github.com/trolldbois/bcdedit)

## Installation

1. `sudo apt install python3-hivex`
2. `python3.6 bcdedit.py sample/bcd-1 show all`

APT will install the `libhivexmod` module for python3.6 in `/usr/lib/python3/dist-packages/libhivexmod.cpython-36m-x86_64-linux-gnu.so`, so we can just use python3.6 to run this programme.
