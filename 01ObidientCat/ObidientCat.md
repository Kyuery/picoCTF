# Obedient Cat
* **Category:** General Skills
* **Author:** SYREAL

## Description

This file has a flag in plain sight (aka "in-the-clear")

## Solution:

The challenge gives us a link to download which downloads a file named "flag" for us. After seeing that it is of a file-type unrecognized by Windows, we can take the hint from the challenge name and try to use the Unix "cat" command on it with:

```bash
cat flag
```

## Flag:

```bash
picoCTF{s4n1ty_v3r1f13d_2aa22101}
```
