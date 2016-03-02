# xml_split

A python script for breaking large XML files into smaller
ones. Adapted from https://gist.github.com/benallard/8042835 by Benoit
Allard. The only change so far has been to use the codecs module to
open the output files to write using the `utf-8` character encoding
rather than `ascii`.
