# script-flatten-and-compress
flattens, strips, and compresses bash scripts

flattens
  follows all ./source includes and writes them into a single script
strips
  remove all comment and blank lines
compresses
  compresses with gzip and wraps it so it can still be ran

why flatten a script
sometimes going through the hassle of finding and installing libraries just to try your script on a new system is painful.  Flattening copies all the libraries into your script, so it just works.

why strip a script
just want it a bit smaller.  It hard to think when this would be useful with the current data transfer speeds and storage sizes, but it may come in handy for certain applications.

why compress a script
again this boils down to size.  Another usage of compressing stuff into your script is packaging.
i.e. download a single script that contains and can deploy all the files of a package.
