# Libft

![Score](https://img.shields.io/badge/Score-100%2F100-lightgrey) ![C](https://img.shields.io/badge/C-94.3%25-lightgrey) ![Makefile](https://img.shields.io/badge/Makefile-5.7%25-lightgrey)

> *Your first custom C library*

---

## About 📌

**Libft** is the first project of the **42 Common Core** and the only project in **Rank 00**.

The goal is to build a reusable static C library, `libft.a`, by recreating essential functions from the C standard library and implementing additional utility functions from scratch.

It establishes the foundations used throughout later 42 projects, introducing **memory management, pointers, strings, dynamic allocation, file descriptors, modular programming, and Makefiles**.

---

## Functions 🔧

### Part 1 – Libc Reimplementations

#### Character checks

* `ft_isalpha`
* `ft_isdigit`
* `ft_isalnum`
* `ft_isascii`
* `ft_isprint`

#### String functions

* `ft_strlen`
* `ft_strchr`
* `ft_strrchr`
* `ft_strncmp`
* `ft_strlcpy`
* `ft_strlcat`
* `ft_strnstr`
* `ft_strdup`

#### Memory functions

* `ft_memset`
* `ft_bzero`
* `ft_memcpy`
* `ft_memmove`
* `ft_memchr`
* `ft_memcmp`
* `ft_calloc`

#### Conversions

* `ft_toupper`
* `ft_tolower`
* `ft_atoi`

---

### Part 2 – Additional Utilities

#### String manipulation

* `ft_substr`
* `ft_strjoin`
* `ft_strtrim`
* `ft_split`

#### Conversion

* `ft_itoa`

#### String iteration

* `ft_strmapi`
* `ft_striteri`

#### File descriptor output

* `ft_putchar_fd`
* `ft_putstr_fd`
* `ft_putendl_fd`
* `ft_putnbr_fd`

---

## Compilation ⚙️

From the `libft` directory:

```bash id="6t1p2z"
make
```

This generates the static library:

```text id="kbqy9o"
libft.a
```

Other available commands:

```bash id="k3g7wu"
make clean
make fclean
make re
```

The project is compiled with:

```text id="c8l11i"
-Wall -Wextra -Werror
```

---

## Usage 💻

Include the library header:

```c id="9f06l5"
#include "libft.h"
```

Compile your program with the library:

```bash id="0l2e7b"
cc main.c libft.a -o program
```

---

## What I Learned 🧠

* Manual memory management in C
* Pointer and array manipulation
* Dynamic memory allocation
* String and memory operations
* Writing reusable and modular functions
* Building static libraries
* Organizing projects with Makefiles
* Working with file descriptors



# Libft

![Score](https://img.shields.io/badge/Score-100%2F100-lightgrey) ![C](https://img.shields.io/badge/C-94.3%25-lightgrey) ![Makefile](https://img.shields.io/badge/Makefile-5.7%25-lightgrey) 


> *Your first custom C library*

---

## About 📌

Create a static C library (`libft.a`) reimplementing common libc functions and adding utility routines. Strengthen memory management, string handling, and modular design.

---

## Functions 🔧

### Part 1 – Libc reimplementations

* Character tests: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
* String manipulators: `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strlcpy`, `ft_strlcat`, `ft_strnstr`, `ft_strdup`
* Memory handlers: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
* Conversions: `ft_toupper`, `ft_tolower`, `ft_atoi`

### Part 2 – Additional utilities

* Substrings & joins: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
* Number & string I/O: `ft_itoa`, `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`
* String mappers: `ft_strmapi`, `ft_striteri`

---

