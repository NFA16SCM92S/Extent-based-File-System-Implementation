Our version of xv6 was build and run on a vagrant box running ubuntu 14.04.5 LTS (GNU/Linux 3.13.0-132-generic x86_64). Included with the source code is the vagrant file that you can use to generate the same vagrant box the software was developed, run, and tested on if needed (see https://www.vagrantup.com/ for details on vagrant use); however, it should compile on any version of linux where qemu is installed using the command 

make clean ; make ; make qemu-nox

Included with our xv6 source code is the file we used to test our implementation and understanding: fsTest.c. It can be run from the shell prompt in xv6 with the command fsTest. See Deliverable 2—Test Data and the manual description of the lseek() system call for descriptions of the tests. 

Our base code was a direct fork from https://github.com/mit-pdos/xv6-public to https://bitbucket.org/jduggerIIT/xv6-pa4. The master branch of the bitbucket repository is the original code from mit-pdos. All changes to the original code were done under the PA4 branch.