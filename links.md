# Red Team Links
https://paper.bobylive.com/Security/The_Red_Team_Guide_by_Peerlyst_community.pdf

## Windows POCs
https://github.com/MzHmO/Exploit-Street

## Sharp Tools
https://github.com/Flangvik/SharpCollection/tree/master/NetFramework_4.7_x64
- SeatBelt
- SharpUp
- SharpChromium
- SharpKatz

## BOF Kernel Exploit Example 
https://github.com/apkc/CVE-2024-26229-BOF/tree/main

## NetNTLM Hash Leaks 
https://www.securify.nl/en/blog/living-off-the-land-stealing-netntlm-hashes/

## Startup folder path 
C:\Users\user\AppData\Roaming\Microsoft\Windows\StartM~1\Programs\Startup\

## WMI
https://github.com/XiaoliChan/wmiexec-Pro

## 64-bit AMSI Patch 
<code>
        xor eax, eax ; clear eax<br>
        shl eax, 16 ; shift eax left by 16 bits<br>
        or ax, 0x57 ; Set the lower 16 bits value to 0x57<br>
        ret
</code>
- A custom patch for `AmsiScanBuffer` that sets the return value to `S_OK` (0x00000057), effectively bypassing AMSI by faking a clean scan result.

## Windows Shellcoding 
https://nytrosecurity.com/

https://github.com/ahmedkhlief/Ninja/blob/master/core/agents/cmd_shellcodex64.ninja


# VR Links

## cross-compilers 
https://toolchains.bootlin.com/


## Ghidra 

## Reversing C Structures 
https://www.youtube.com/watch?v=ntTV8V7KVco

## Reversing C++ Objects 

https://www.youtube.com/watch?v=ir2B1trR0fE

## Linux Exploitation

### Calling Conventions

https://dp12.github.io/posts/calling-conventions-for-pwn-and-profit/

### Syscall Tables 

https://syscalls.w3challs.com/

### Linux Exploit Training

https://pwn.college/software-exploitation/

## Linux Heap Exploitation 

https://heap-exploitation.dhavalkapil.com/introduction

https://ctf-wiki.org/pwn/linux/user-mode/heap/ptmalloc2/introduction/

https://hackliza.gal/en/posts/r2heap/

https://www.hoppersroppers.org/roadmap/training/heap.html


## Kernel Exploitation

https://github.com/xairy/linux-kernel-exploitation

https://lkmidas.github.io/posts/20210123-linux-kernel-pwn-part-1/

https://lkmidas.github.io/posts/20210223-linux-kernel-pwn-modprobe/


# Windows Exploitation 

## Windows Heap 

https://www.youtube.com/watch?v=hetZx78SQ_A

https://www.blackhat.com/docs/us-16/materials/us-16-Yason-Windows-10-Segment-Heap-Internals-wp.pdf

https://www.slideshare.net/slideshow/windows-10-nt-heap-exploitation-english-version/154467191#7


## KASLR Bypass

https://hackyboiz.github.io/2025/04/13/l0ch/bypassing-kernel-mitigation-part0/en/

## Windows Kernel exploitation 

https://vuln.dev/windows-kernel-exploitation-vm-setup/

https://vuln.dev/tags/kernel-exploit/

## Windows PatchGuard 

https://web.archive.org/web/20230429180618/http://zerocondition.com/posts/demystifying-patchguard/


## Windows x64 Stack-Based Overflow 

https://nytrosecurity.com/2018/01/24/stack-based-buffer-overflows-on-x64-windows/

https://github.com/hvictor/targetserv-x64/tree/main

## Windows VR
https://v-v.space/
