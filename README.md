# Project Euler

The files in this directory contain encrypted versions of my solutions to
[Project Euler](https://projecteuler.net) problems (at least for the ones I haven't misplaced). To
prevent copying of solutions, each solution is encrypted with blowfish, using the solution to the
problem as the encryption key. Specifically, the files were encoded using the following command:

    openssl enc -bf-cbc -in problem095.py -out problem095.py.enc

One way to decode these files is to the the following command:

    openssl enc -d -bf-cbc -in problem095.py.enc -out problem095.py

Please don't spread these solutions online without them being encrypted, to encourage people to
solve these problem themselves first.
