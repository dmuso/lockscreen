# Lockscreen

Immediately lock your Mac with no questions asked!

To build:

    $ clang -F /System/Library/PrivateFrameworks -framework login -o lockscreen lockscreen.c

Originally found at: https://stackoverflow.com/questions/1976520/lock-screen-by-api-in-mac-os-x
