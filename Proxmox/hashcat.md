```shell
kali$ date +%s.%N && hashcat -b && date +%s.%N
1627610106.815084117
hashcat (v6.1.1) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

OpenCL API (OpenCL 1.2 pocl 1.6, None+Asserts, LLVM 9.0.1, RELOC, SLEEF, DISTRO, POCL_DEBUG) - Platform #1 [The pocl project]
=============================================================================================================================
* Device #1: pthread-Common KVM processor, 667/731 MB (256 MB allocatable), 4MCU

Benchmark relevant options:
===========================
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........:   135.1 MH/s (14.93ms) @ Accel:1024 Loops:512 Thr:1 Vec:4

Hashmode: 100 - SHA1

Speed.#1.........:   101.9 MH/s (39.90ms) @ Accel:1024 Loops:1024 Thr:1 Vec:4

Hashmode: 1400 - SHA2-256

Speed.#1.........: 37607.0 kH/s (53.03ms) @ Accel:512 Loops:1024 Thr:1 Vec:4

Hashmode: 1700 - SHA2-512

Speed.#1.........: 10176.0 kH/s (82.01ms) @ Accel:1024 Loops:256 Thr:1 Vec:2

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#1.........:     2518 H/s (63.83ms) @ Accel:256 Loops:1024 Thr:1 Vec:4

Hashmode: 1000 - NTLM

Speed.#1.........:   139.0 MH/s (3.42ms) @ Accel:1024 Loops:128 Thr:1 Vec:4

Hashmode: 3000 - LM

zsh: killed     hashcat -b
```

