# 9front_coding_scripts
Code navigation/formatting scripts made for use in a 9front VM

These are designed to be run under a git repo, since that's what I'm interacting with 99% of the time (for better or worse).

* host - set username/host for running commands on the host. required for some scripts
* a+ - indent
* a- - deindent
* acme_savepos - save current position in a file
* f - find file(s), plumb if only 1 file found
* fixws - fix trailing whitespace, convert tabs to spaces, and remove carriage returns
* gaf - get all (C) functions
* gb - go back to previously saved acme position (used after running acme_savepos)
* gh - go to (C) function prototype (only searches headers)
* git - ssh to host, cd to mapped /mnt/term directory, and run 'git'
* gr - search for "thing" (using git grep)
* gra - search for "thing" (using native 9 tools only)
* gri - search for "thing" (using git grep, case-insensitive)
* gt - go to (C) function definition
* pygt - go to (python) function or class definition
* make - ssh to host, cd to mapped /mnt/term directory, run 'make'
* mounthost - ssh mount the host
* pygaf - get all (python) functions
* pygt - go to (python) function/class definition
* r - ssh to host, cd to mapped /mnt/term directory (if currently in a /mnt/term directory), run command (used in several scripts, can be used by itself)
* rdir - ssh to host, cd to $1, run $2, wait for <enter> (used with my git plumbing rule)
* rw - ssh to host, cd to /mnt/term directory (if currently in a /mnt/term directory), run command, wait for <enter> (used with my manpage plumbing rule)
* vnc - vnc to host
