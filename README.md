# Linux Shell in C

Simple Linux shell written in C.

## What Does It Do?

* Executes built-in commands:
    * cd
    * help
    * exit
    * pwd
    * history
    * ! (previous command)
    * !n (nth previous command)
* Executes external commands by forking child process.

## Built With

* C
* Linux

## Usage

Compile shell.c from Linux terminal

```c
$ gcc -o shell shell.c
```

Execute the program

```c
$ ./shell
```

You are now in the shell

```c
>> help
>> pwd
>> [...]
>> exit
```

## Author

**Radhesh Goel** [radhesh1](https://github.com/radhesh1)

## Acknowledgments

* Boston University MET Master of Science Computer Science Program
* MET CS 575 Operating Systems
* [https://brennan.io/2015/01/16/write-a-shell-in-c/](https://brennan.io/2015/01/16/write-a-shell-in-c/)