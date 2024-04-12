# Certificates Automation

A simple python script for adjusting and validating certificates prototypes and flavors of devices.

## The script works as CLI with the following arguments:

* `-h` -> Show help message
* `--proto` Choose the wanted prototype out of the constant options. Required.
* `--flavor` Choose the wanted flavor out of the constant options.
* `--adjust-mac` Adjust the mac file name to the hard-coded standard.
* `--validate-suffix` Validate the mac file name suffix is valid.
* `--output-dir` The path to the output directory. If no output directory is given, a default one will be created.
* `--source-dir` The path to the source directory. Required.

__FILE__: [certificates_automation.py](./certificates_automation.py)


# Double Free Exploit

A simple C program which showcases the internals (and exploitation option) of memory allocations in some systems.

## The functions inside the program:

* `example1()` -> Shows the tcache bin linked list that is used for more efficient future allocations.
* `example2()` -> Shows the ability to modify the tcache bin linked list and gain control over future allocations.

__FILE__: [double_free_exploit.c](./double_free_exploit.c)


# C Learning / C++ Learning

Just some code snippets I wrote when I was starting to learn C and C++.

## The functions inside the program:


__DIRS__: [C Learning](./C%20Learning) | [C++ Learning](./C++%20Learning)


# Pythonic System Package

Some old concept I had to implement a bundle of pypi packages, which will give the ability to control
both windows and linux system locally and remotely via shell commands.
The basic idea is stated in the [idea.txt](./Pythonic%20System%20Package/idea.txt) file.
The code is overly complicated and modular. Would definitely refactor it if I ever touch it again.

__DIR__: [Pythonic System Package](./Pythonic%20System%20Package)
