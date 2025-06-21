# Libft – Your Own C Standard Library

Welcome to my implementation of `Libft`, a foundational project at 42 that re-creates many functions from the C standard library. This project was a great opportunity to improve my understanding of memory management, string manipulation, and function implementation in C.

## 🚀 Project Overview

The goal of this project was to code a custom standard library in C, including:
- Standard functions like `memcpy`, `strlen`, `strdup`, etc.
- String, memory, and character operations
- Custom utility functions to extend functionality

> **Note:** This version does **not** include the bonus part (linked list operations).

This library can be reused in future C projects at 42 or anywhere a custom lightweight utility library is needed.

---

## 🧠 What I Learned

- Deep understanding of memory allocation and pointer arithmetic in C  
- Efficient handling of strings, arrays, and memory blocks  
- Structuring reusable C code  
- Writing a complete Makefile and header file  
- Defensive programming and error handling  

---

## 📁 Project Structure

```
libft/
├── ft_*.c            # All custom standard C functions
├── libft.h           # Function declarations
├── Makefile          # Project build rules
```

---

## 🛠️ Functions Implemented

### ✅ Libc Functions (Part 1)

- **ft_isalpha**: Checks if a character is an alphabetic letter (A-Z or a-z).
- **ft_isdigit**: Checks if a character is a digit (0-9).
- **ft_isalnum**: Checks if a character is alphanumeric (letter or digit).
- **ft_isascii**: Checks if a character is an ASCII character (0–127).
- **ft_isprint**: Checks if a character is printable, including space.
- **ft_strlen**: Returns the length of a string (excluding the null terminator).
- **ft_memset**: Fills a block of memory with a specified byte.
- **ft_bzero**: Sets a block of memory to zero bytes.
- **ft_memcpy**: Copies a block of memory from source to destination.
- **ft_memmove**: Copies memory safely, handling overlapping regions.
- **ft_strlcpy**: Copies a string to a buffer of a given size, ensuring null-termination.
- **ft_strlcat**: Appends a string to another, with buffer size checks.
- **ft_toupper**: Converts a lowercase letter to uppercase.
- **ft_tolower**: Converts an uppercase letter to lowercase.
- **ft_strchr**: Returns a pointer to the first occurrence of a character in a string.
- **ft_strrchr**: Returns a pointer to the last occurrence of a character in a string.
- **ft_strncmp**: Compares two strings up to a given number of characters.
- **ft_memchr**: Scans memory for a specific byte.
- **ft_memcmp**: Compares two blocks of memory.
- **ft_strnstr**: Locates a substring in a string, searching up to a given length.
- **ft_atoi**: Converts a string to an integer.
- **ft_calloc**: Allocates and zeros memory for an array.
- **ft_strdup**: Duplicates a string by allocating new memory.

### ✅ Additional Functions (Part 2)

- **ft_substr**: Extracts a substring from a string, given start index and length.
- **ft_strjoin**: Concatenates two strings into a newly allocated string.
- **ft_strtrim**: Trims characters from the start and end of a string.
- **ft_split**: Splits a string into an array of strings using a delimiter.
- **ft_itoa**: Converts an integer to its string representation.
- **ft_strmapi**: Applies a function to each character of a string to create a new string.
- **ft_striteri**: Applies a function to each character of a string, modifying it in place.
- **ft_putchar_fd**: Writes a character to a given file descriptor.
- **ft_putstr_fd**: Writes a string to a given file descriptor.
- **ft_putendl_fd**: Writes a string followed by a newline to a file descriptor.
- **ft_putnbr_fd**: Writes an integer to a given file descriptor.

---

## 🧪 How to Use

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/libft.git
cd libft
```

### 2. Build the library:
```bash
make
```
This will compile all `.c` files and create `libft.a`.

### 3. Use in your C project:
In your source code:
```c
#include "libft.h"
```

To compile:
```bash
gcc -Wall -Wextra -Werror your_code.c -L. -lft
```

---

## 🧪 Test Your Implementation

You can test your libft implementation using [Francinette](https://github.com/alelievr/francinette), a popular automated testing tool designed for 42 libft projects.

To use Francinette:

1. Clone the repo:
   ```bash
   git clone https://github.com/alelievr/francinette.git
   ```
2. Follow the instructions in its README to set up and run tests.

---

## 📌 Why This Project Matters

As a web developer with a background in architecture and software, building `libft` strengthened my low-level programming skills, improved my code organization habits, and taught me to build robust, efficient solutions — skills I apply in JavaScript, React, Node.js, and full-stack development today.

---

## 🧾 License

This project is part of the 42 School curriculum. You’re welcome to use and learn from it, but do not copy it directly for your own submission.

---

## 👤 Author

**Hossein Khoshnevis**  
🧠 Software Developer | 📍 Based in the Netherlands  
[LinkedIn](https://www.linkedin.com/in/hossein-khoshnevis)  
[Portfolio](https://hosseinkhoshnevis.vercel.app/)  
[GitHub](https://github.com/hosseinkhoshnevis94)
