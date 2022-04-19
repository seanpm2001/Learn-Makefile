
***

![/Makefile.png](/Makefile.png)

### Learning Makefile

I am not too experienced with Makefile (GNU Make) at the moment. This document will go over my knowledge of the Makefile (GNU Make) language so far.

This document used version 4.3 of the GNU Make programming language.

#### Comments in Makefile

Comments in Makefile are similar to most scripting languages (such as Shell) they look like this:

```makefile
# This is a single line comment in Makefile
# Makefile doesn't support multi-line comments as far as I know.
```

This example works with every version of Makefile, except for some versions of OpenMakefile.

_/!\ This example has not been tested yet, and may not work_

#### Break keyword in Makefile

Makefile does NOT support the `break` keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in Makefile

A hello world program in Makefile can be written in Shell format, or C++ format.

##### Shell

```makefile
# Hello World (Shell/Makefile)
echo "Hello World"
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

##### C++

```makefile
# Hello World (C++/Makefile)
std::cout >> "Hello World"
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### File deletion in Makefile

I have no way to test makefile, so I believe this is how you delete files, based on semantics (NOT syntax highlighting)

WARNING: These files have not been tested, and may have destructive capabilities. Unless you really know what you are doing, please run these in a burner virtual machine ONLY.

##### Single file deletion

Deleting a single file:

```makefile
# Delete a single file
cd /new%20folder/
rm -f Sample.txt
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

##### Multiple file deletion deletion

Delete all files in a directory/folder/inode:

```makefile
# Delete all files in an inode
cd /new%20folder/
rm -f /new%20folder/*
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

##### Single inode deletion

Deleting a single inode/directory:

```makefile
# Delete a single inode
rm -rf /new%20folder/
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

##### Multiple inode deletion deletion

Delete all inodes within a directory/folder/inode:

```makefile
# Delete all inodes within a directory
cd /bigFolder/
rm -f /*
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

##### Delete your entire system

For obvious reasons, don't do this outside of a virtual machine

```makefile
# Delete everything
sudo rm -rf /* -no-preserve-root-
```

I feel like this might be Shell only, and not makefile supported.

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### Make a directory

Create a directory using Makefile

```makefile
# Make a single directory in Makefile
mkdir /New Folder/
```

This example works with every version of Makefile (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Makefile knowledge comes from reading documentationn on Wikipedia. I know very little about the language at the moment.

#### Other knowledge of Makefile

1. Makefile is a system build language

2. Makefile uses various file extensions, including `*.mk` `*.mak` and `*.mak` but is commonly stored in a file without an extension, titled `makefile` or `MAKEFILE`

3. Makefile is now commonly known as GNU make, as the original UNIX implementation was replaced by it

4. The make software tool dates back to 1976, April

5. Makefile is a language recognized by GitHub

6. Makefile is an open source language

7. Makefile also uses the `*.am` file extension for use in GNU AutoMake, which is translated from the file `makefile.am` to `makefile.in`

8. No other knowledge of Makefile at the moment.

***

**File version:** `1 (2022, Monday, April 18th at 7:40 pm PST)`

***
