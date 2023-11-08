---
type: document
title: Initiate Git repository
description: ""
date: 2023-11-01T18:29:43+01:00
draft: false
owner: ""
classification: internal
dateRevision: 2023-11-01T18:29:43+01:00
dateEffective: 2023-11-01T18:29:43+01:00
controls: []
domains: []
weight: 1
---

Initializing a new git repository is as simple as

1. open a terminal,
1. create a new directory or go to an existing directory,
1. run `git init`

{{<note>}}
It doesn't matter if the directory is empty of not.  Existing files in the directory will be considered as untracked files after the repository is initialized.
{{</note>}}

## Linux and MacOS

Assuming we are going to initialize a new repository in a new directory `~/projects/myrepo`.  We run

```bash
$ mkdir ~/projects/myrepo
$ cd ~/projects/myrepo
$ git init
```

After it, a hidden directory `.git` is created

```bash
$ ls -a ~/home/projects/myrepo
.git
```

## Windows

Use __Git CMD__ as the terminal.  Assuming we are going to initialize a new repository in a new folder `%USERPROFILE%\Documents\myrepo`.  We do

```PowerShell
C:\> mkdir %USERPROFILE%\Documents\myrepo
C:\> cd %USERPROFILE%\Documents\myrepo
C:\> git init
```

A hidden directory `.git` is created

```PowerShell
C:\> dir /a:h
 Volume in drive C has no label.
 Volume Serial Number is 1AC2-CFF3

 Directory of C:\Users\Hong\Documents\myrepo

02/11/2023  06:15    <DIR>          .git
               0 File(s)              0 bytes
               1 Dir(s)  13.321.207.808 bytes free
```