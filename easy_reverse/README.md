## Easy Reverse

### To Access
URL: https://crackmes.one/crackme/5b8a37a433c5d45fc286ad83
password: crackmes.one

### Solution
1. Search for "main" function under "Functions"
2. Replace undefined "main function" wiht standard C function `int main (int argc, char * * argv)`
3. In the decmplier section of the main fucntion, it is observed that at line 9 checks if the first command line argument `agrv[1]` is of length 10.
4. In line 10, the argument shoudl also contain the character `@` at the 5th position. 

Ex: `./rev50_linux64-bit 1234@67890`
