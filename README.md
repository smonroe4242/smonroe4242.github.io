# Steven Monroe

## Contact

Phone Number:	(941) 726-1302

School Email:	smonroe@student.42.us.org

Personal Email:	scmonroe96@gmail.com

## Education

### Locations

- **42 School Silicon Valley**
	- March 2018 - Current; 

### Languages

- C99
- C++98

## Personal Skills

- Strong communicator: meticulous listening and careful planning while dynamically allocating team fworkload

- Well-developed process for communicating about software development and design in clear and explicit ways from peer to peer learning system

- Home-grown self-motivated learner, worker, and maker, coming from an entirely self-driven education

- Experienced with and enthusiastic about stress-testing software for edge cases and finding weak points in program architecture

- Sharp, focused, and unrelentingly solution-oriented


# Showcase Project Rough Draft
## Corewar
- This project is an implementation of an assembler and virtual machine in the style of Corewar(Jones, Dewdney, 1984)
- This project was written to C99 standard within Ecole 42's Norminette code style constraints
	- 80 character line limit
	- 25 lines per function
	- 5 functions per file
	- Emphasis on readability and modularity in code
	- No `for`, `do while`, or `switch case`
	- Several other code style restrictions
- Only the following 11 standard library functions were allowed, the rest had to be implemented in pure C99
	- open, read, write, lseek, close
	- malloc, realloc, free
	- perror, strerror, exit
- This is a group project, with three official members

### The Assembler:
- Rules for a language containing 16 operations, each capable of taking 0 - 3 arguments
- Label system capable of forward and backward declarations
- Two pass system:
	- Instructions are digested in to machine code as encountered
	- Label addresses are calculated as encountered and stored seperately
	- Label references are filled with 0 in machine code buffer
	- Blanks are filled with address offsets in second pass with known table of labels
- Upon syntax error, message is printed containing the bad syntax and line number in file
- If error occurs, all memory is cleared and freed and no file is created or written to

### The Virtual Machine:
- Simulated parallel execution of 1 to 4 assembly programs, referred to as 'champions'
- Shared memory space where champions are loaded and run
- 16 32-bit registers and a carry flag
- Access to 16 operations specified by the language which act on shared memory and local registers
	- Original Redcode mimicked CISC instruction set
	- Language specification for the project is modified to be more of a hassle to code in
- Multiple program counters or PC's, initially one for each champion
- Capability to accomodate an arbitrary amount, with PC's being added and removed frequently
- Order in which PC's are created is significant and so needs to remain intact

# Projects

## C99

* [Corewar](https://github.com/smonroe4242/Corewar)

	- Virtual Machine capable of running 1 - 4 assembly programs
	- Built assembler capable of producing executable files from source code
	- 3 person group project, built in style of 1984 Corewar game
	- Currently in debugging phase

* [ft_ssl_md5](https://github.com/smonroe4242/ft_ssl_md5)

	- OpenSSL implementation in C
	- MD5 and SHA256 hashing algorithms currently implemented
	- Modular codebase with a focus on extensibility and reusability of functions

* [Piscine Starfleet](https://github.com/smonroe4242/Piscine_Starfleet)

	- Two week advanced intensive curriculum on algorithm implementation and application
	- Complex data structure implementation and use
	- Sorting algorithm comparisons and optimization
	- Recursive, statistical, dynamic programming exercises
	- Understanding of big O time and space complexities
	- 16 total whiteboard interview session alternating interviewer/interviewee

* [Libft](https://github.com/smonroe4242/libft)

	- C99 standard library implementation
	- First project completed at school to gain in depth understanding of C language
	- Currently expanded to 82 functions to date and growing

## C++98

* [ft_retro](https://github.com/smonroe4242/ft_retro)

	- Ncurses arcade shooter for terminal
	- 12 hour project

* [ft_gkrellm](https://github.com/smonroe4242/ft_gkrellm)

	- System Monitor built over a weekend
	- Ncurses TUI and SFML GUI modes
	- Dynamic interface serving system call information
	- 38 hour project
