Game archives support for Midnight Commander
============================================

This repository contains a small collection of simple scripts
which allow viewing contents and extracting files from archives
used in various games.

Currently supported files are:
- .wad
- .grp
- .viv

Installation
============

1. Put executable scripts to `~/.local/share/mc/extfs.d`
2. Paste the contents of [this file] into `.config/mc/mc.ext.ini`
   (if it doesn't exist yet, copy `/etc/mc/mc.ext.ini`);
   in case you're still using Midnight Commander 3 and
   `mc.ext` file, use [that file] instead

[this file]: mc.ext.ini
[that file]: mc.ext
