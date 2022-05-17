# Libft

## 🗣️ About this project

> This project is about coding a C library.<br/>
> It will contain a lot of general purpose functions your programs will rely upon.<br/>
> This is Version 15 of this project<br/>

For detailed information, refer to the [**subject of this project**](https://github.com/vascopearson/Libft/blob/master/libft_subject.pdf).

## 🛠️ Usage

### Requirements

The library is written in C language and thus needs the **`gcc` compiler** and some standard **C libraries** to run.

### Instructions

**1. Compiling the library**

To compile the library, run:

```shell
$ cd path/to/libft && make all
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```C
#include "libft.h"
```

and, when compiling your code, add the required flags:

```shell
-lft -L path/to/libft.a -I path/to/libft.h
```
