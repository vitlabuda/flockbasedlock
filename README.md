# FlockBasedLock
**FlockBasedLock** is a Python 3 library which allows even completely unrelated processes or threads to acquire and then release atomic locks bound to a specific file. 
As the name suggests, it uses the ``flock()`` syscall to perform the (un)locking.


## Requirements
The library has been written for **Linux**, but it will probably work on other Unixes as well.
Tested on Debian 10 (Linux 4.19) with Python 3.7.

No dependencies (other than the Python standard library) are required.


## Usage 
All the library's functionality is contained within the ``FlockBasedLock`` class. 
The library's public API is documented using docstrings; see the [flockbasedlock.py](flockbasedlock/flockbasedlock.py) file.

Usage examples can be found in the [tests](tests) directory.


## Licensing
This project is licensed under the 3-clause BSD license. See the [LICENSE](LICENSE) file for details.

Written by [Vít Labuda](https://vitlabuda.cz/).
