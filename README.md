# openssl-lib

latest openssl libary

# compile enviroment

## openssl-1.0.2m
0. win10 pro x64
1. openssl-1.0.2m (2017-Nov-02 14:51:59)
2. perl 5.24.2
3. nasm  2.12.0.2
4. visual studio 2017 community

## openssl-1.1.1b

### env
0. win10 pro x64
1. openssl-1.1.1b (2019-Feb-26 14:34:59 )
2. ActivePerl 5.26.3 Build 2603 (64-bit)
3. nasm  2.14rc16
4. visual studio 2019 community

### build script
```cmd
cd C:\openssl-1.1.1b
C:\openssl-1.1.1b>perl Configure VC-WIN64A no-asm --prefix=d:\openssl_lib
C:\openssl-1.1.1b>nmake
C:\openssl-1.1.1b>nmake test
C:\openssl-1.1.1b>nmake install
```