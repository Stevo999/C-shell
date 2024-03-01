**README**

**Group Members:**

- Student ID 1: [Insert Student ID]
- Student ID 2: [Insert Student ID]
- Student ID 3: [Insert Student ID]

**Shell Implementation**

**Features Implemented:**
The following are the features implemented in this project
1. **Executing Simple Commands:** Implemented the execution of simple shell commands such as `ls`, `cat`, and `rm`.
2. **I/O Redirection:** Implemented I/O redirection for input (`<`) and output (`>`). Now the shell can handle commands like `ls > file.txt` and `cat < file.txt`.
3. **Pipes:** Implemented command pipelines using pipes (`|`). Now the shell can handle commands like `ls | sort | uniq | wc`.

**Testing Process:**

- Created a test script (`t.sh`) containing various shell commands, including simple commands, I/O redirection, and pipes.
- Compiled the shell code (`sh.c`) using `gcc sh.c`.
- Executed the shell with the test script using `./a.out < t.sh`.
- Verified that the shell correctly executed each command in the test script and produced the expected output.

run the following commands to execute the code
 (i) Run 'gcc sh.c' command to compile the c code 
 (ii)Run './sh' command to execute the shell
 (ii) Type the command eg ls etc
 (iii) You can also Run './a.out<t.sh>' command to execute the shell with the test scripts

    The code will execute the shell with the test scripts which are:

1. cat < y | sort | uniq | wc > y1
2. cat y1
3. rm y1
4. ls | sort | uniq | wc
5. rm y
6. ls > y

 Note

 The commands are run on linux Operating system, the program can only be run efficiently in Linux
 t.sh is a test script used only to run the shell with the test commands.