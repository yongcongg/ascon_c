# ascon_c

Ascon C implementation with libsodium which generates a random string that is safe to use for cryptography

gcc main.c permutations.c printstate.c -o ascon -lsodium
