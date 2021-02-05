# OverRide

If you thought Rainfall was easy, here’s a more daunting challenge. 
Override is last ISO that will have you search for faults present in the protected binaries, and re-build these binaries depending on their behavior.

## Levels:

* levelO: Reverse password
* level1: Buffer overflow - ret to personal env /bin/sh shellcode
* level2: Format string exploit - ret to system call
* level3: Bruteforce sequences
* level4: Buffer overflow - ret to personal env reading shellcode
* level5: Format string exploit - ret to personal env /bin/sh shellcode
* level6: Reading binary to match cmp
* level7: Triple followed ret2libc out modified sys('/bin/sh')
* level8: Wrong format - redirecting output file
* level9: Utilisation of 1 non fill byte to call exec /bin/sh function
