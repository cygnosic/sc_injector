# sc_injector
The code simply injects the shellcode into a given process id as input.
Shellcode used in the code:msfvenom -p windows/exec CMD=calc.exe -b "\x00\xFF" -f c 
