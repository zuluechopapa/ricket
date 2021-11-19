# ricket
pseudo random password generator in perl


this depends on the availability of the system utility 'md5sum' to help
randomize and convert seeding letters into numbers.

example -
zep@hydra:~/ricket$ perl ricket test 14
passwd: U1-Ovo6(1im#*4

the strong password is intended to be replicated from the 'seed' string (in this case 'test') consistently.
allowing you to have a sort of 'meta secret' to generate your password.
e.g. you could use a seed string of you@your.email4sales.amazon.site and some arbitrary, large number (32, 40, 64?)
and have very strong (for some sites, possibly trying to use characters that aren't available) passwords.
