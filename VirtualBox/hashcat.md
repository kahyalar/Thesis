```shell
kali$ date +%s.%N && hashcat -b && date +%s.%N
1627508298.470862084
hashcat (v6.1.1) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

OpenCL API (OpenCL 1.2 pocl 1.6, None+Asserts, LLVM 9.0.1, RELOC, SLEEF, DISTRO, POCL_DEBUG) - Platform #1 [The pocl project]
=============================================================================================================================
* Device #1: pthread-Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz, 1423/1487 MB (512 MB allocatable), 2MCU

Benchmark relevant options:
===========================
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........:   176.2 MH/s (11.45ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 100 - SHA1

Speed.#1.........:   117.9 MH/s (17.30ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1400 - SHA2-256

Speed.#1.........: 51189.6 kH/s (39.94ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1700 - SHA2-512

Speed.#1.........: 16034.8 kH/s (65.18ms) @ Accel:512 Loops:1024 Thr:1 Vec:4

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#1.........:     3875 H/s (100.39ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1000 - NTLM

Speed.#1.........:   275.9 MH/s (7.33ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 3000 - LM

Speed.#1.........: 48260.1 kH/s (42.33ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#1.........:   196.5 MH/s (10.53ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5600 - NetNTLMv2

Speed.#1.........: 13993.5 kH/s (74.74ms) @ Accel:1024 Loops:512 Thr:1 Vec:8

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#1.........:  1875.4 kH/s (66.88ms) @ Accel:64 Loops:1024 Thr:1 Vec:8

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#1.........:      953 H/s (72.27ms) @ Accel:1024 Loops:500 Thr:1 Vec:8

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#1.........:      337 H/s (62.19ms) @ Accel:32 Loops:32 Thr:1 Vec:8

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#1.........:     1087 H/s (93.69ms) @ Accel:256 Loops:1024 Thr:1 Vec:4

Hashmode: 7500 - Kerberos 5, etype 23, AS-REQ Pre-Auth

Speed.#1.........:  1060.3 kH/s (61.65ms) @ Accel:4 Loops:128 Thr:64 Vec:8

Hashmode: 13100 - Kerberos 5, etype 23, TGS-REP

Speed.#1.........:  1052.4 kH/s (62.07ms) @ Accel:1 Loops:512 Thr:64 Vec:8

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#1.........:      932 H/s (91.01ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 12899)

zsh: killed     hashcat -b
```

