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

## Old README

The old readme can be found in `README`.
