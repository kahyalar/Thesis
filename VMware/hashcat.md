```shell
kali$ hashcat -b                                                        
hashcat (v6.1.1) starting in benchmark mode...

============================================================
* Device #1: pthread-Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz, 
1417/1481 MB (512 MB allocatable), 4MCU

Benchmark relevant options:
===========================
* --optimized-kernel-enable

Hashmode: 0 - MD5
Speed.#1.........:   272.6 MH/s (14.80ms) 
@ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 100 - SHA1
Speed.#1.........:   145.4 MH/s (27.81ms) 
@ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1400 - SHA2-256
Speed.#1.........: 80907.6 kH/s (51.23ms) 
@ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1700 - SHA2-512
Speed.#1.........: 23160.5 kH/s (44.69ms) 
@ Accel:256 Loops:1024 Thr:1 Vec:4

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES
Speed.#1.........:  2142.0 kH/s (59.96ms) 
@ Accel:32 Loops:1024 Thr:1 Vec:8

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5)
Speed.#1.........:    22442 H/s (90.17ms) 
@ Accel:1024 Loops:500 Thr:1 Vec:8

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) 
Speed.#1.........:     1579 H/s (76.65ms) 
@ Accel:32 Loops:32 Thr:1 Vec:8

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) 

zsh: killed     hashcat -b
```

