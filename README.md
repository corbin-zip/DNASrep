# DNASrep
DNAS replacement server

This is a small setup to run your own DNAS service for Playstation 2. The scripts basically replay packets that were captured by the DNAS forever project.

MCrypt has been removed with PHP 7.2. This version of DNASrep takes care of this problem by using OpenSSL instead.

After more investigations I added folde "more" with scripts, examples and notes. It should provide a good base for people who want to emulate more functions aof the original DNAS server infrastructure like banning mechanisms or title control. It also holds the prove that it's theoretically possible to authenticate titles that weren't captured by the DNASrep project back in the days.