# SNFS-DL-for-a-653-bit-safe-prime

We employ the special number field sieve to solve a discrete logarithm problem in a prime field Fp where p is a safe prime of bitsize 653.
The polynomial pair are computed by LLL lattice reduction and the individual logarithm are also done manually with some techniques and choosing parameters carefully. The sieving procedure and linear algebra are finished by cado-nfs.
We briefly explains the whole procedure in sketch.pdf（with some small errors in the format).


p = 226671109844264104545393215633510050592980509260033239076755401127690125575291115426645018258595424343996894536095668 03813691163927790935258104921196863722947966948283866110442812635122066048 059643 which is a 653-bit safe prime.    
The target is T = 203005070592540824555274795196851486531088117681823646726975883864642834367706539412047765329386234457958048544087932317359161170570537560839181720216078851349835845125090086476057167076337758  
Let g = 5 be a generator of this prime field Fp we get the discrete logarithm of T in base g:  
logt = 11711391724874890704542871336515356421985211880470075302494452452863779671043113505398296072898919423902046138529998148774470486378831446553377214645219460630171198839853758696803310506604260502374  


Computation effort:  
about 318 hours calendar time computation or equivalently 1.74 core years on a HP- workstation with 48 cores of 2.2GHz Intel Xeon E5-2946v4 processor.









Our ongoing work is better lattice construction to find the potential trapdoor more quickly. The sketch.pdf file will be uploaded later.
