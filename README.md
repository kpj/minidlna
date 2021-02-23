# minidlna

(Yet another) fork of https://sourceforge.net/projects/minidlna/.


## Features

* Support subtitles with language code in filename.
* CLI flag to keep process in foreground while still logging timestamps.
* Many more things will be added here.


## Compilation

```bash
$ ./autogen.sh
$ mkdir _build && cd _build
$ ../configure --prefix=$PWD/../_install
$ make
$ make install
```

## Developer notes

The original [repository](https://sourceforge.net/projects/minidlna/) is added as an upstream remote.
New features can be merged in like this:

```bash
# git remote add upstream git://git.code.sf.net/p/minidlna/git
$ git fetch upstream

$ git branch -a
$ git merge remotes/upstream/master
```

## Old README

The old readme can be found in `README`.
