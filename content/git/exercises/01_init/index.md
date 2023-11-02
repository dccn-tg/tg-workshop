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

1. go to a directory, and
1. run `git init`

Assuming we are going to initialize a new repository in an existing directory `~/projects/myrepo`.  We run

```bash
$ cd ~/projects/myrepo
$ git init
```

After it, a hidden directory `.git` is created

```bash
$ ls -a ~/home/projects/myrepo
.git
```

{{<note>}}
It doesn't matter if the directory is empty of not.  Existing files in the directory will not be considered as untracked files after the repository is initialized.
{{</note>}}

## section 1

### subsection 1

### subsection 2

## section 2