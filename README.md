```
                   ,   /^\     ___
                  /^\_/   `...'  /`
               ,__\    ,'     ~ (
            ,___\ ,,    .,       \
             \___ \\\ .'.'   .-.  )
               .'.-\\`.`.  '.-. (
              / (==== ."".  ( o ) \
            ,/u  `~~~'|  /   `-'   )
           "")^u ^u^|~| `""".  ~_ /
             /^u ^u ^\~\     ".  \\
     _      /u^  u ^u  ~\      ". \\
    ( \     )^ ^U ^U ^U\~\      ". \\
   (_ (\   /^U ^ ^U ^U  ~|       ". `\
  (_  _ \  )U ^ U^ ^U ^|~|        ". `\.
 (_  = _(\ \^ U ^U ^ U^ ~|          ".`.;
(_ -(    _\_)U ^ ^ U^ ^|~|            ""
(_    =   ( ^ U^ U^ ^ U ~|
(_ -  ( ~  = ^ U ^U U ^|~/
 (_  =     (_^U^ ^ U^ U /
  (_-   ~_(/ \^ U^ ^U^,"
   (_ =  _/   |^ u^u."
    (_  (/    |u^ u.(
     (__/     )^u^ u/
             /u^ u^(
            |^ u^ u/
            |u^ u^(       ____
            |^u^ u(    .-'    `-,
             \^u ^ \  / ' .---.  \
              \^ u^u\ |  '  `  ;  |
               \u^u^u` . `-'  ;  |
                `-.^ u`._   _.'^'./
                   "-.^.-```_=~._/
                      `"------"'

               ~~~~ PRINTF PROJECT ~~~~
                  Holberton School
```

## 📚 Resources

### Read or Watch
- [Secrets of printf](https://www.cprogramming.com/)
- [Group Projects Concept Page](https://intranet.holbertonschool.com)
- [Flowcharts Concept Page](https://intranet.holbertonschool.com)

### Man Pages
```bash
man printf (3)
```

## 📋 Requirements

### General
- **Allowed Editors**: `vi`, `vim`, `emacs`
- **Compilation**: Ubuntu 20.04 LTS using `gcc` with flags: `-Wall -Werror -Wextra -pedantic -std=gnu89`
- **File Endings**: All files must end with a new line
- **README.md**: Mandatory at the root of the project folder
- **Code Style**: Must follow the `Betty` style guide (checked with `betty-style.pl` and `betty-doc.pl`)
- **Global Variables**: Not allowed
- **Functions per File**: Maximum of 5 functions per file
- **Main Files**: The provided `main.c` files are examples only. Do not push your own `main.c` to the repository
- **Header File**: All function prototypes must be included in `main.h`
- **Include Guards**: All header files must have include guards

### GitHub
- One project repository per group
- Cloning/forking a repository with the same name before the second deadline results in a **0% score**

## 🔧 Authorized Functions and Macros

The following functions and macros are permitted:

| Function/Macro | Man Page |
|---|---|
| `write` | `man 2 write` |
| `malloc` | `man 3 malloc` |
| `free` | `man 3 free` |
| `va_start` | `man 3 va_start` |
| `va_end` | `man 3 va_end` |
| `va_copy` | `man 3 va_copy` |
| `va_arg` | `man 3 va_arg` |

## 🛠️ Compilation

Compile your code using:

```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
```

### Important Notes
- **Do not push C files with `main` functions** to the root directory (use a `test` folder instead)
- Our evaluation files will include your header file with: `#include main.h`
- All test files should be placed in a separate `test` folder

## 📁 Project Structure

```
project-name/
├── README.md
├── main.h
├── file1.c
├── file2.c
├── file3.c
└── test/
    └── main.c (your test files)
```

## ✅ Checklist Before Submission

- [ ] All files end with a new line
- [ ] No global variables used
- [ ] Maximum 5 functions per file
- [ ] All functions documented and prototyped in `main.h`
- [ ] `main.h` has include guards
- [ ] Code follows Betty style guide
- [ ] All source files compile without warnings or errors
- [ ] No `main.c` in root directory
- [ ] README.md is present and complete

---

**Happy Coding! 🚀**