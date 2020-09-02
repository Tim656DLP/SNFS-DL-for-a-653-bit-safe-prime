# SNFS-DL-for-a-653-bit-safe-prime

We employ the special number field sieve to solve a discrete logarithm problem in a prime field Fp where p is a safe prime of bitsize 653.
The polynomial pair are computed by LLL lattice reduction and the individual logarithm are also done manually with some techniques and choosing parameters carefully. The sieving procedure and linear algebra are finished by cado-nfs.
The sketch briefly explains the whole procedure （with some small error in the format).

Our ongoing work is better lattice construction to find the potential trapdoor more quickly. 
