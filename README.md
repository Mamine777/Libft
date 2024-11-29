# Libft Project

## Introduction

The **Libft** project marks the beginning of creating your very own C library! It is designed to provide a collection of reusable functions that are invaluable in future projects.
This library includes implementations of standard C library functions, additional utility functions, and bonus functions for linked list manipulation.
Working on this project was an enriching experience, allowing me to build a solid foundation in C programming and system-level function implementation.

## Project Description

The goal of the project is to recreate essential standard C library functions, extend their functionality, and build new helper functions.
These functions are implemented following strict coding norms and with a focus on error handling and memory management.
The final output is a static library (`libft.a`) that can be linked and reused across multiple projects.

### Key Features

1. **Reimplementation of Libc Functions**: 
   - Functions like `strlen`, `strchr`, `memcpy`, and more were recreated with the prefix `ft_`.
   - Memory management functions such as `ft_calloc` and `ft_strdup` were implemented.

2. **Additional Utility Functions**:
   - Functions for string manipulation: `ft_substr`, `ft_strjoin`, `ft_split`.
   - Numeric conversions: `ft_itoa`.
   - Advanced string processing with functions like `ft_strmapi`.

3. **Bonus Functions for Linked Lists**:
   - List creation: `ft_lstnew`.
   - Manipulation: `ft_lstadd_front`, `ft_lstadd_back`, and `ft_lstclear`.
   - Iteration and transformation: `ft_lstiter` and `ft_lstmap`.

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd libft
