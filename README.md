# Steven Monroe

## Contact

Phone Number:	(941) 726-1302

School Email:	smonroe@student.42.us.org

Personal Email:	scmonroe96@gmail.com

## Education

- **42 School Silicon Valley** (Ecole 42)
	- March 2018 - Current
- State College of Florida
	- August 2010 - December 2017
- New College of Florida
	- August 2015 - May 2017
- HarvardX Online CS50 course
	- Spring 2012

## Languages

- C99
- C++98

# Showcase Project
## [Corewar](https://github.com/smonroe4242/Corewar)
- This **group project** is an implementation of an assembler and virtual machine in the style of Corewar(Jones, Dewdney, 1984)

- This project was written in **standard C99** within Norm, Ecole 42's **programming standard**
	- 80 character line limit
	- 25 lines per function
	- 5 functions per file
	- Emphasis on **readability** and **modularity** in code
	- No `for`, `do while`, or `switch case`
	- Several other code style restrictions
- Only the following 11 standard library functions were allowed, the rest had to be implemented in pure C99
	- open, read, write, lseek, close
	- malloc, realloc, free
	- perror, strerror, exit

### The Assembler:
- Rules for a language containing 16 operations, each capable of taking 0 - 3 arguments
- Label system capable of **forward and backward declarations**
- Two pass system:
	- Instructions are digested into machine code as encountered
	- Label addresses are calculated and stored seperately
	- Label references are filled with 0's in the outfile buffer
	- Blanks are filled with address offsets in second pass using table of labels
- Upon syntax error, message is printed containing the failing syntax and line number in file
- If error occurs, **all memory is cleared and freed** and no file is created or written to

### The Virtual Machine:
- Simulated **parallel execution** of 1 to 4 assembly programs, referred to as 'champions'
- Shared memory space where champions are loaded and run
- 16 32-bit registers and a carry flag
- Access to 16 operations specified by the language which act on shared memory and local registers
	- Original Redcode mimicked **CISC instruction set**
	- Language specification for the project is modified to be more of a **hassle** to code in
- Multiple program counters or PC's, initially one for each champion
- Capability to accomodate an **arbitrary amount**, with PC's being added and removed frequently
- Order in which PC's are created is significant and so needs to remain intact

# Projects

## C99

* [Piscine Starfleet](https://github.com/smonroe4242/Piscine_Starfleet)

	- Two week advanced intensive curriculum on intelligent **algorithm implementation and application**
	- Complex **data structure** implementation and use
	- Sorting algorithm comparisons and **optimization**
	- Recursive, statistical, dynamic programming exercises
	- In-depth understanding of **Big O notation** and time and space complexities
	- 16 whiteboard interview sessions completed while alternating roles
	
* [ft_ssl_md5](https://github.com/smonroe4242/ft_ssl_md5)

	- OpenSSL implementation in C
	- MD5 and SHA256 hashing algorithms currently implemented
	- **Modular codebase** with a focus on **extensibility** and **reusability** of functions

* [Libft](https://github.com/smonroe4242/libft)

	- C99 standard library implementation
	- First project completed at Ecole 42 to gain a **ground-up understanding** of C language
	- Currently expanded to 82 functions to date and growing
	
## C++98

* [ft_retro](https://github.com/smonroe4242/ft_retro)

	- Single player arcade shooter for terminal
	- Object oriented with an ncurses based engine
	- **12 hour** project

* [ft_gkrellm](https://github.com/smonroe4242/ft_gkrellm)

	- System Monitor built over a weekend
	- Ncurses TUI and SFML GUI modes
	- **Dynamic user interface** serving system call information
	- 38 hour project

# Personal Skills

- Self-motivated learner worker and maker with a project based self-driven educational background
- Clear and conscise communicator concerning software development and design thanks to a peer to peer education system
- Often sought out by peers for help finding, explaining, and fixing bugs in software
- The most common question I recieve is `Hey Steven, can you come try and break this?` and the answer is always yes
- Passionate about stress-testing software and exercising deep corner cases
- Skilled, practiced, and excited with the dubugging process

