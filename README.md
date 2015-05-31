# GCC4.9
**GNU Compiler Collection 4.9**

## Installation Notes
### Order of installation
* GMP 4.3.2
* ISL 0.12.2 (requires GMP 4.3.2)
* MPFR 2.4.2 (requires GMP 4.3.2)
* MPC 0.8.1 (requires GMP 4.3.2 & MPFR 2.4.2)
* CLooG 0.18.1 (requires GMP 4.3.2 & ISL 0.12.2)
* GCC 4.9 (requires all above)

**Reminder: make sure the prerequisite library files are in the **LD_LIBRARY_PATH** environmental variable. 