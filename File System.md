# File System

Everything is a file or a directory.
Every device on computer is represented by a file or a directory.
You can mount hard drives or even network shares in a empty directory.


```
root /
│
├── home            User's home
│
├── root            Root user's home.
│
│
├── bin             Essential command binaries. Available in single-user mode.
│
├── sbin            Essential *system* binaries. Available in single-user mode.
│
├── lib             Libraries essential for the binaries.
├── lib64
│
├── opt             Add-on application software packages.
│
├── etc             Editable text config.
│                   System-wide configuration files.
│
├── usr             UNIX system resources.
│   │               User application space. Opposed to the bin directory.
│   │
│   ├── bin         Non-essential command binaries for all users.
│   ├── sbin        Non-essential system binaries.
│   ├── lib         Libraries for the binaries in /usr/bin and /usr/sbin.
│   ├── include     Standard include files.
│   ├── src         Source code.
│   ├── share
│   └── local       Local data, specific to this host.
│       ├── bin
│       ├── sbin
│       ├── lib
│       ├── share
│       └── ...
│
├── var             Varible directory. Contains the files that will
│   │               constantly grow in size as you use the system.
│   ├── cache
│   ├── log
│   └── ...
│
│
├── dev             Device files. All devices live in here.
│
├── media           Other mounted drives. let OS manage.
│
├── mnt             Other manually mounted drives.
│
│
├── boot            Boot loader files.
│                   Contains everything OS needs to boot.
│
├── proc            Include process and kernal informatoin as files.
│                   Automatically generated and instant update.
│
├── run             Temporary filesystem runs in RAM.
│                   Store runtime information.
│
├── sys             Interface to the kernel, also have information and
│                   configuration that kernel provides or information
│                   about devices and drivers.
│
├── srv             Service data.
│
└── tmp             Temporary directory.

```
