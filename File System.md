# File System

Everything is a file or a directory.
Every device on computer is represented by a file or a directory.
You can mount hard drives or even network shares in a empty directory.


```
root /
├── bin             Essential command binaries. Available in single-user mode.
│
├── boot            Boot loader files.
│                   Contains everything OS needs to boot.
│
├── dev             Device files. All devices live in here.
│
├── etc             System-wide configuration files.
│
├── home
│
├── lib             Libraries essential for the binaries.
├── lib64
│
├── lost+found
│
├── media           Other mounted drives. let OS manage.
│
├── mnt             Other manually mounted drives.
│
├── opt             Add-on application software packages.
│
├── proc
│
├── root
│
├── run
│
├── sbin            Essential *system* binaries. Available in single-user mode.
│
├── srv
│
├── sys
│
├── tmp
│
├── usr
│
└── var
```
