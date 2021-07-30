```shell
root$ hashcat -b
hashcat (v6.1.1) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

OpenCL API (OpenCL 1.2 pocl 1.6, None+Asserts, LLVM 9.0.1, RELOC, SLEEF, DISTRO, POCL_DEBUG) - Platform #1 [The pocl project]
=============================================================================================================================
* Device #1: pthread-Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz, 13775/13839 MB (4096 MB allocatable), 8MCU

Benchmark relevant options:
===========================
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........:   501.9 MH/s (16.66ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 100 - SHA1

Speed.#1.........:   208.3 MH/s (38.92ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1400 - SHA2-256

Speed.#1.........: 99242.8 kH/s (82.56ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1700 - SHA2-512

Speed.#1.........: 30414.8 kH/s (68.64ms) @ Accel:512 Loops:512 Thr:1 Vec:4

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#1.........:     7212 H/s (42.94ms) @ Accel:256 Loops:1024 Thr:1 Vec:8

Hashmode: 1000 - NTLM

Speed.#1.........:   774.6 MH/s (10.65ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 3000 - LM

Speed.#1.........: 87653.6 kH/s (93.66ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#1.........:   551.3 MH/s (14.99ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5600 - NetNTLMv2

Speed.#1.........: 37729.4 kH/s (55.26ms) @ Accel:512 Loops:512 Thr:1 Vec:8

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#1.........:  3481.4 kH/s (71.86ms) @ Accel:32 Loops:1024 Thr:1 Vec:8

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#1.........:    27918 H/s (51.33ms) @ Accel:512 Loops:500 Thr:1 Vec:8

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#1.........:     1654 H/s (84.65ms) @ Accel:64 Loops:16 Thr:1 Vec:8

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#1.........:     2139 H/s (95.20ms) @ Accel:128 Loops:1024 Thr:1 Vec:4

Hashmode: 7500 - Kerberos 5, etype 23, AS-REQ Pre-Auth

Speed.#1.........:  3000.2 kH/s (87.02ms) @ Accel:32 Loops:16 Thr:64 Vec:8

Hashmode: 13100 - Kerberos 5, etype 23, TGS-REP

Speed.#1.........:  2997.8 kH/s (87.11ms) @ Accel:16 Loops:32 Thr:64 Vec:8

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#1.........:     1778 H/s (95.56ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 12899)

Speed.#1.........:     1114 H/s (70.44ms) @ Accel:128 Loops:1024 Thr:1 Vec:4

Hashmode: 7100 - macOS v10.8+ (PBKDF2-SHA512) (Iterations: 1023)

Speed.#1.........:    13974 H/s (72.29ms) @ Accel:128 Loops:1023 Thr:1 Vec:4

Hashmode: 11600 - 7-Zip (Iterations: 16384)

Speed.#1.........:     2332 H/s (54.43ms) @ Accel:64 Loops:4096 Thr:1 Vec:8

Hashmode: 12500 - RAR3-hp (Iterations: 262144)

Speed.#1.........:      335 H/s (47.56ms) @ Accel:32 Loops:16384 Thr:1 Vec:8

Hashmode: 13000 - RAR5 (Iterations: 32799)

Speed.#1.........:     1156 H/s (53.52ms) @ Accel:256 Loops:1024 Thr:1 Vec:8

Hashmode: 6211 - TrueCrypt RIPEMD160 + XTS 512 bit (Iterations: 1999)

Speed.#1.........:     8151 H/s (61.82ms) @ Accel:512 Loops:256 Thr:1 Vec:8

Hashmode: 13400 - KeePass 1 (AES/Twofish) and KeePass 2 (AES) (Iterations: 24569)

Speed.#1.........:      870 H/s (48.90ms) @ Accel:128 Loops:1024 Thr:1 Vec:8

Hashmode: 6800 - LastPass + LastPass sniffed (Iterations: 499)

Speed.#1.........:    80627 H/s (96.52ms) @ Accel:1024 Loops:499 Thr:1 Vec:8

Hashmode: 11300 - Bitcoin/Litecoin wallet.dat (Iterations: 200459)

Speed.#1.........:      143 H/s (72.94ms) @ Accel:256 Loops:1024 Thr:1 Vec:4

Started: Wed Jul 28 11:45:59 2021
Stopped: Wed Jul 28 11:58:01 2021
```

