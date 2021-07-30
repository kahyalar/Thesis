```shell
root$ john --test
Will run 8 OpenMP threads
Benchmarking: descrypt, traditional crypt(3) [DES 256/256 AVX2]... (8xOMP) DONE
Many salts:	16842K c/s real, 2313K c/s virtual
Only one salt:	10911K c/s real, 1511K c/s virtual

Benchmarking: bsdicrypt, BSDI crypt(3) ("_J9..", 725 iterations) [DES 256/256 AVX2]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 725
Many salts:	659009 c/s real, 89462 c/s virtual
Only one salt:	473088 c/s real, 65343 c/s virtual

Benchmarking: md5crypt, crypt(3) $1$ (and variants) [MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Warning: "Many salts" test limited: 213/256
Many salts:	161964 c/s real, 22347 c/s virtual
Only one salt:	112128 c/s real, 15792 c/s virtual

Benchmarking: md5crypt-long, crypt(3) $1$ (and variants) [MD5 32/64]... (8xOMP) DONE
Raw:	17819 c/s real, 2420 c/s virtual

Benchmarking: bcrypt ("$2a$05", 32 iterations) [Blowfish 32/64 X3]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 32
Raw:	3350 c/s real, 459 c/s virtual

Benchmarking: scrypt (16384, 8, 1) [Salsa20/8 128/128 AVX]... (8xOMP) DONE
Speed for cost 1 (N) of 16384, cost 2 (r) of 8, cost 3 (p) of 1
Raw:	138 c/s real, 21.7 c/s virtual

Benchmarking: LM [DES 256/256 AVX2]... (8xOMP) DONE
Raw:	54886K c/s real, 7308K c/s virtual

Benchmarking: AFS, Kerberos AFS [DES 48/64 4K]... DONE
Short:	527104 c/s real, 521885 c/s virtual
Long:	2052K c/s real, 2052K c/s virtual

Benchmarking: tripcode [DES 256/256 AVX2]... (8xOMP) DONE
Raw:	8565K c/s real, 1159K c/s virtual

Benchmarking: AndroidBackup [PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:	3531 c/s real, 555 c/s virtual

Benchmarking: adxcrypt [IBM/Toshiba 4690 - ADXCRYPT 32/64]... (8xOMP) DONE
Raw:	45680K c/s real, 6461K c/s virtual

Benchmarking: agilekeychain, 1Password Agile Keychain [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	43264 c/s real, 5918 c/s virtual

Benchmarking: aix-ssha1, AIX LPA {ssha1} [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:	559720 c/s real, 75856 c/s virtual
Only one salt:	509239 c/s real, 69721 c/s virtual

Benchmarking: aix-ssha256, AIX LPA {ssha256} [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:	205568 c/s real, 28198 c/s virtual
Only one salt:	244224 c/s real, 33273 c/s virtual

Benchmarking: aix-ssha512, AIX LPA {ssha512} [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:	105088 c/s real, 14239 c/s virtual
Only one salt:	65664 c/s real, 9248 c/s virtual

Benchmarking: andOTP [SHA256 32/64]... (8xOMP) DONE
Raw:	546133 c/s real, 75893 c/s virtual

Benchmarking: ansible, Ansible Vault [PBKDF2-SHA256 HMAC-256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:	2661 c/s real, 386 c/s virtual

Benchmarking: argon2 [Blake2 AVX]... (8xOMP) DONE
Speed for cost 1 (t) of 3, cost 2 (m) of 4096, cost 3 (p) of 1, cost 4 (type [0:Argon2d 1:Argon2i]) of 0 and 1
Raw:	426 c/s real, 70.2 c/s virtual

Benchmarking: as400-des, AS/400 DES [DES 32/64]... DONE
Raw:	185455 c/s real, 25615 c/s virtual

Benchmarking: as400-ssha1, AS400-SaltedSHA1 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 256/256 AVX2 8x1]... DONE
Many salts:	15113K c/s real, 15113K c/s virtual
Only one salt:	10933K c/s real, 10933K c/s virtual

Benchmarking: asa-md5, Cisco ASA [md5($p.$s) (Cisco ASA) 256/256 AVX2 8x3]... DONE
Many salts:	28899K c/s real, 28899K c/s virtual
Only one salt:	15711K c/s real, 15711K c/s virtual

Benchmarking: AxCrypt [PBKDF2-SHA512/SHA1 AES 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1337 and 60000
Raw:	577 c/s real, 90.4 c/s virtual

Benchmarking: AzureAD [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Warning: "Many salts" test limited: 161/256
Many salts:	164864 c/s real, 22677 c/s virtual
Only one salt:	106455 c/s real, 14974 c/s virtual

Benchmarking: BestCrypt (SHA-256 + AES XTS mode) [Jetico BestCrypt (.jbc) PKCS12 PBE (Whirlpool / SHA-1 to SHA-512) 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:	312 c/s real, 43.6 c/s virtual

Benchmarking: bfegg, Eggdrop [Blowfish 32/64]... (8xOMP) DONE
Raw:	141940 c/s real, 19883 c/s virtual

Benchmarking: Bitcoin, Bitcoin Core [SHA512 AES 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 177864
Raw:	142 c/s real, 21.9 c/s virtual

Benchmarking: BitLocker, BitLocker [SHA-256 AES 32/64]... (8xOMP) DONE 
Speed for cost 1 (iteration count) of 1048576
Raw:	7.5 c/s real, 1.1 c/s virtual

Benchmarking: bitshares, BitShares Wallet [SHA-512 64/64]... (8xOMP) DONE
Many salts:	2335K c/s real, 318393 c/s virtual
Only one salt:	2502K c/s real, 345722 c/s virtual

Benchmarking: Bitwarden, Bitwarden Password Manager [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:	5965 c/s real, 972 c/s virtual

Benchmarking: BKS [PKCS12 PBE 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	63627 c/s real, 9269 c/s virtual

Benchmarking: Blackberry-ES10 (101x) [SHA-512 256/256 AVX2 4x]... (8xOMP) DONE
Warning: "Many salts" test limited: 127/256
Many salts:	128760 c/s real, 17937 c/s virtual
Only one salt:	83136 c/s real, 11727 c/s virtual

Benchmarking: WoWSRP, Battlenet [SHA1 32/64 GMP-exp]... (8xOMP) DONE
Warning: "Many salts" test limited: 116/256
Many salts:	232909 c/s real, 32278 c/s virtual
Only one salt:	214938 c/s real, 29616 c/s virtual

Benchmarking: Blockchain, My Wallet (v2 x5000) [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	7447 c/s real, 1158 c/s virtual

Benchmarking: chap, iSCSI CHAP authentication / EAP-MD5 [MD5 32/64]... (8xOMP) DONE
Many salts:	12468K c/s real, 1694K c/s virtual
Only one salt:	9011K c/s real, 1231K c/s virtual

Benchmarking: Clipperz, SRP [SHA256 32/64 GMP-exp]... (8xOMP) DONE
Raw:	137846 c/s real, 19911 c/s virtual

Benchmarking: cloudkeychain, 1Password Cloud Keychain [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 40000 and 50000
Raw:	269 c/s real, 40.2 c/s virtual

Benchmarking: dynamic=md5($p) [256/256 AVX2 8x3]... DONE
Raw:	49842K c/s real, 48864K c/s virtual

Benchmarking: cq, ClearQuest [CQWeb]... (8xOMP) DONE
Many salts:	172228K c/s real, 23117K c/s virtual
Only one salt:	20709K c/s real, 2876K c/s virtual

Benchmarking: CRC32 [CRC32 32/64 CRC-32C AVX]... DONE
Speed for cost 1 (version [0:CRC-32 1:CRC-32C]) of 0
Many salts:	147726K c/s real, 147726K c/s virtual
Only one salt:	66666K c/s real, 66666K c/s virtual

Benchmarking: sha1crypt, NetBSD's sha1crypt [PBKDF1-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 64000 and 40000
Raw:	1412 c/s real, 216 c/s virtual

Benchmarking: sha256crypt, crypt(3) $5$ (rounds=5000) [SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:	7585 c/s real, 1233 c/s virtual

Benchmarking: sha512crypt, crypt(3) $6$ (rounds=5000) [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:	4785 c/s real, 742 c/s virtual

Benchmarking: Citrix_NS10, Netscaler 10 [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	43112K c/s real, 5878K c/s virtual
Only one salt:	15053K c/s real, 2108K c/s virtual

Benchmarking: dahua, "MD5 based authentication" Dahua [MD5 32/64]... DONE
Raw:	5442K c/s real, 5442K c/s virtual

Benchmarking: dashlane, Dashlane Password Manager [AES PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	3592 c/s real, 559 c/s virtual

Benchmarking: diskcryptor, DiskCryptor [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	5196 c/s real, 746 c/s virtual

Benchmarking: Django (x10000) [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:	2760 c/s real, 402 c/s virtual

Benchmarking: django-scrypt [Salsa20/8 128/128 AVX]... (8xOMP) DONE
Speed for cost 1 (N) of 14, cost 2 (r) of 8, cost 3 (p) of 1
Raw:	152 c/s real, 22.8 c/s virtual

Benchmarking: dmd5, DIGEST-MD5 C/R [MD5 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 180/256
Many salts:	2919K c/s real, 409600 c/s virtual
Only one salt:	3997K c/s real, 545388 c/s virtual

Benchmarking: dmg, Apple DMG [PBKDF2-SHA1 256/256 AVX2 8x 3DES/AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (version) of 2 and 1
Raw:	18384 c/s real, 2517 c/s virtual

Benchmarking: dominosec, Lotus Notes/Domino 6 More Secure Internet Password [8/64]... (8xOMP) DONE
Many salts:	814384 c/s real, 111604 c/s virtual
Only one salt:	440269 c/s real, 61760 c/s virtual

Benchmarking: dominosec8, Lotus Notes/Domino 8 [8/64]... (8xOMP) DONE
Raw:	1846 c/s real, 261 c/s virtual

Benchmarking: DPAPImk, DPAPI masterkey file v1 and v2 [SHA1/MD4 PBKDF2-(SHA1/SHA512)-DPAPI-variant 3DES/AES256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 24000
Raw:	1359 c/s real, 220 c/s virtual

Benchmarking: dragonfly3-32, DragonFly BSD $3$ w/ bug, 32-bit [SHA256 32/64]... (8xOMP) DONE
Many salts:	8632K c/s real, 1160K c/s virtual
Only one salt:	4268K c/s real, 591582 c/s virtual

Benchmarking: dragonfly3-64, DragonFly BSD $3$ w/ bug, 64-bit [SHA256 32/64]... (8xOMP) DONE
Many salts:	6967K c/s real, 945823 c/s virtual
Only one salt:	3061K c/s real, 431233 c/s virtual

Benchmarking: dragonfly4-32, DragonFly BSD $4$ w/ bugs, 32-bit [SHA512 64/64]... (8xOMP) DONE
Many salts:	4284K c/s real, 587711 c/s virtual
Only one salt:	3874K c/s real, 534457 c/s virtual

Benchmarking: dragonfly4-64, DragonFly BSD $4$ w/ bugs, 64-bit [SHA512 64/64]... (8xOMP) DONE
Many salts:	3295K c/s real, 460304 c/s virtual
Only one salt:	2859K c/s real, 398300 c/s virtual

Benchmarking: Drupal7, $S$ (x16385) [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:	1235 c/s real, 172 c/s virtual

Benchmarking: eCryptfs (65536 iterations) [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	419 c/s real, 60.4 c/s virtual

Benchmarking: eigrp, EIGRP MD5 / HMAC-SHA-256 authentication [MD5/SHA-256 32/64]... (8xOMP) DONE
Speed for cost 1 (algorithm [2:MD5 3:HMAC-SHA-256]) of 2
Many salts:	8339K c/s real, 1143K c/s virtual
Only one salt:	7068K c/s real, 964774 c/s virtual

Benchmarking: electrum, Electrum Wallet [SHA256 AES / PBKDF2-SHA512 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (kdf [1:SHA256 2:PBKDF2-SHA512]) of 1 and 2
Raw:	9693 c/s real, 1402 c/s virtual

Benchmarking: EncFS [PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 181474
Raw:	203 c/s real, 31.8 c/s virtual

Benchmarking: enpass, Enpass Password Manager [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	1571 c/s real, 228 c/s virtual

Benchmarking: EPI, EPiServer SID [SHA1 32/64]... (8xOMP) DONE
Many salts:	12328K c/s real, 1703K c/s virtual
Only one salt:	6553K c/s real, 930961 c/s virtual

Benchmarking: EPiServer [SHA1/SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256]) of 1
Many salts:	29166K c/s real, 3959K c/s virtual
Only one salt:	20021K c/s real, 2753K c/s virtual

Benchmarking: ethereum, Ethereum Wallet [PBKDF2-SHA256/scrypt Keccak 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 262144 and 1024, cost 2 (kdf [0:PBKDF2-SHA256 1:scrypt 2:PBKDF2-SHA256 presale]) of 0
Warning: "Many salts" test limited: 4/256
Many salts:	232 c/s real, 36.3 c/s virtual
Only one salt:	124 c/s real, 18.8 c/s virtual

Benchmarking: fde, Android FDE [PBKDF2-SHA1 256/256 AVX2 8x SHA256/AES]... (8xOMP) DONE
Raw:	17655 c/s real, 2756 c/s virtual

Benchmarking: Fortigate256, FortiOS256 [SHA256 32/64]... (8xOMP) DONE
Many salts:	4867K c/s real, 682854 c/s virtual
Only one salt:	6258K c/s real, 863267 c/s virtual

Benchmarking: Fortigate, FortiOS [SHA1 32/64]... (8xOMP) DONE
Many salts:	9522K c/s real, 1317K c/s virtual
Only one salt:	8208K c/s real, 1132K c/s virtual

Benchmarking: FormSpring [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:	9804K c/s real, 9804K c/s virtual
Only one salt:	7855K c/s real, 7855K c/s virtual

Benchmarking: FVDE, FileVault 2 [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 41000 and 70400
Raw:	434 c/s real, 72.3 c/s virtual

Benchmarking: geli, FreeBSD GELI [PBKDF2-SHA512 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 256 and 512
Raw:	23363 c/s real, 3212 c/s virtual

Benchmarking: gost, GOST R 34.11-94 [64/64]... (8xOMP) DONE
Raw:	1425K c/s real, 195529 c/s virtual

Benchmarking: gpg, OpenPGP / GnuPG Secret Key [32/64]... (8xOMP) DONE
Speed for cost 1 (s2k-count) of 65536, cost 2 (hash algorithm [1:MD5 2:SHA1 3:RIPEMD160 8:SHA256 9:SHA384 10:SHA512 11:SHA224]) of 2, cost 3 (cipher algorithm [1:IDEA 2:3DES 3:CAST5 4:Blowfish 7:AES128 8:AES192 9:AES256 10:Twofish 11:Camellia128 12:Camellia192 13:Camellia256]) of 3
Raw:	22784 c/s real, 3098 c/s virtual

Benchmarking: HAVAL-128-4 [32/64]... DONE
Raw:	3062K c/s real, 3062K c/s virtual

Benchmarking: HAVAL-256-3 [32/64]... DONE
Raw:	4326K c/s real, 4326K c/s virtual

Benchmarking: hdaa, HTTP Digest access authentication [MD5 256/256 AVX2 8x3]... DONE
Many salts:	5502K c/s real, 5502K c/s virtual
Only one salt:	4988K c/s real, 4988K c/s virtual

Benchmarking: hMailServer [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:	9955K c/s real, 9955K c/s virtual
Only one salt:	7842K c/s real, 7842K c/s virtual

Benchmarking: hsrp, "MD5 authentication" HSRP, HSRPv2, VRRP, GLBP [MD5 32/64]... (8xOMP) DONE
Many salts:	9535K c/s real, 1311K c/s virtual
Only one salt:	4112K c/s real, 580125 c/s virtual

Benchmarking: IKE, PSK [HMAC MD5/SHA1 32/64]... (8xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1]) of 1 and 2
Raw:	1019K c/s real, 141850 c/s virtual

Benchmarking: ipb2, Invision Power Board 2.x [MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Many salts:	26542K c/s real, 3616K c/s virtual
Only one salt:	15407K c/s real, 2127K c/s virtual

Benchmarking: itunes-backup, Apple iTunes Backup [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (version) of 9 and 10, cost 2 (iteration count) of 10000
Raw:	3288 c/s real, 501 c/s virtual

Benchmarking: iwork, Apple iWork '09 or newer [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 100000
Raw:	711 c/s real, 116 c/s virtual

Benchmarking: KeePass [SHA256 AES 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 50000 and 6000, cost 2 (version) of 1 and 2, cost 3 (algorithm [0=AES, 1=TwoFish, 2=ChaCha]) of 0
Raw:	538 c/s real, 83.2 c/s virtual

Benchmarking: keychain, Mac OS X Keychain [PBKDF2-SHA1 3DES 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	26842 c/s real, 3932 c/s virtual

Benchmarking: keyring, GNOME Keyring [SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 3221
Raw:	17554 c/s real, 2722 c/s virtual

Benchmarking: keystore, Java KeyStore [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Warning: "Many salts" test limited: 9/256
Many salts:	4213K c/s real, 620051 c/s virtual
Only one salt:	3813K c/s real, 594936 c/s virtual

Benchmarking: known_hosts, HashKnownHosts HMAC-SHA1 [SHA1 32/64]... (8xOMP) DONE
Many salts:	6627K c/s real, 912855 c/s virtual
Only one salt:	5439K c/s real, 745135 c/s virtual

Benchmarking: krb4, Kerberos v4 TGT [DES 32/64]... DONE
Short:	303305 c/s real, 275731 c/s virtual
Long:	778126 c/s real, 778126 c/s virtual

Benchmarking: krb5, Kerberos v5 TGT [3DES 32/64]... DONE
Raw:	73206 c/s real, 73206 c/s virtual

Benchmarking: krb5asrep, Kerberos 5 AS-REP etype 17/18/23 [MD4 HMAC-MD5 RC4 / PBKDF2 HMAC-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	811089 c/s real, 112219 c/s virtual
Only one salt:	839477 c/s real, 114114 c/s virtual

Benchmarking: krb5pa-sha1, Kerberos 5 AS-REQ Pre-Auth etype 17/18 [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	9061 c/s real, 1408 c/s virtual

Benchmarking: krb5tgs, Kerberos 5 TGS etype 23 [MD4 HMAC-MD5 RC4]... (8xOMP) DONE
Many salts:	1632K c/s real, 225449 c/s virtual
Only one salt:	689425 c/s real, 97251 c/s virtual

Benchmarking: krb5-17, Kerberos 5 DB etype 17 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Raw:	19275 c/s real, 3003 c/s virtual

Benchmarking: krb5-18, Kerberos 5 DB etype 18 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Raw:	10113 c/s real, 1490 c/s virtual

Benchmarking: krb5-3, Kerberos 5 DB etype 3 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Warning: "Many salts" test limited: 193/256
Many salts:	3070K c/s real, 429634 c/s virtual
Only one salt:	2506K c/s real, 349129 c/s virtual

Benchmarking: kwallet, KDE KWallet [SHA1 / PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	8289 c/s real, 1297 c/s virtual

Benchmarking: lp, LastPass offline [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 45/256
Many salts:	46080 c/s real, 6347 c/s virtual
Only one salt:	38526 c/s real, 5442 c/s virtual

Benchmarking: lpcli, LastPass CLI [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1234
Warning: "Many salts" test limited: 198/256
Many salts:	12546 c/s real, 1740 c/s virtual
Only one salt:	13184 c/s real, 1843 c/s virtual

Benchmarking: leet [SHA-512(256/256 AVX2 4x) + Whirlpool(OpenSSL/64)]... (8xOMP) DONE
Warning: "Many salts" test limited: 17/256
Many salts:	4164K c/s real, 610472 c/s virtual
Only one salt:	4194K c/s real, 606990 c/s virtual

Benchmarking: lotus5, Lotus Notes/Domino 5 [8/64 X3]... (8xOMP) DONE
Raw:	1800K c/s real, 253290 c/s virtual

Benchmarking: lotus85, Lotus Notes/Domino 8.5 [8/64]... (8xOMP) DONE
Many salts:	350720 c/s real, 48043 c/s virtual
Only one salt:	366080 c/s real, 50354 c/s virtual

Benchmarking: LUKS [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	196 c/s real, 30.1 c/s virtual

Benchmarking: MD2 [MD2 32/64]... (8xOMP) DONE
Raw:	579928 c/s real, 79259 c/s virtual

Benchmarking: mdc2, MDC-2 [MDC-2DES]... (8xOMP) DONE
Raw:	2804K c/s real, 389598 c/s virtual

Benchmarking: MediaWiki [md5($s.md5($p)) 256/256 AVX2 8x3]... DONE
Many salts:	36304K c/s real, 36304K c/s virtual
Only one salt:	12677K c/s real, 12677K c/s virtual

Benchmarking: monero, monero Wallet [Pseudo-AES / ChaCha / Various 32/64]... (8xOMP) DONE
Raw:	14.6 c/s real, 2.2 c/s virtual

Benchmarking: money, Microsoft Money (2002 to Money Plus) [MD5/SHA1 32/64]... (8xOMP) DONE
Many salts:	2441K c/s real, 334413 c/s virtual
Only one salt:	1622K c/s real, 230760 c/s virtual

Benchmarking: MongoDB, system / network [MD5 32/64]... (8xOMP) DONE
Speed for cost 1 (salt type) of 0 and 1
Raw:	9733K c/s real, 1324K c/s virtual

Benchmarking: scram [SCRAM PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	7249 c/s real, 1208 c/s virtual

Benchmarking: Mozilla, Mozilla key3.db [SHA1 3DES 32/64]... (8xOMP) DONE
Many salts:	1112K c/s real, 150890 c/s virtual
Only one salt:	868352 c/s real, 118465 c/s virtual

Benchmarking: mscash, MS Cache Hash (DCC) [MD4 32/64]... (8xOMP) DONE
Many salts:	41265K c/s real, 5657K c/s virtual
Only one salt:	8605K c/s real, 1194K c/s virtual

Benchmarking: mscash2, MS Cache Hash 2 (DCC2) [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	5829 c/s real, 826 c/s virtual

Benchmarking: MSCHAPv2, C/R [MD4 DES (ESS MD5) 256/256 AVX2 8x3]... DONE
Many salts:	11233M c/s real, 11233M c/s virtual
Only one salt:	64733K c/s real, 64733K c/s virtual

Benchmarking: mschapv2-naive, MSCHAPv2 C/R [MD4 DES 256/256 AVX2 naive]... (8xOMP) DONE
Many salts:	345833K c/s real, 46234K c/s virtual
Only one salt:	5980K c/s real, 838147 c/s virtual

Benchmarking: krb5pa-md5, Kerberos 5 AS-REQ Pre-Auth etype 23 [32/64]... (8xOMP) DONE
Many salts:	1358K c/s real, 191170 c/s virtual
Only one salt:	1001K c/s real, 138014 c/s virtual

Benchmarking: mssql, MS SQL [SHA1 256/256 AVX2 8x]... DONE
Many salts:	37361K c/s real, 37361K c/s virtual
Only one salt:	15400K c/s real, 15400K c/s virtual

Benchmarking: mssql05, MS SQL 2005 [SHA1 256/256 AVX2 8x]... DONE
Many salts:	38137K c/s real, 38137K c/s virtual
Only one salt:	28942K c/s real, 28942K c/s virtual

Benchmarking: mssql12, MS SQL 2012/2014 [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Many salts:	14589K c/s real, 1966K c/s virtual
Only one salt:	8708K c/s real, 1188K c/s virtual

Benchmarking: multibit, MultiBit Wallet [MD5/scrypt AES 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 3, cost 2 (kdf [1:MD5 2:scrypt hd 3:scrypt classic]) of 1
Many salts:	1090K c/s real, 153920 c/s virtual
Only one salt:	1953K c/s real, 264051 c/s virtual

Benchmarking: mysqlna, MySQL Network Authentication [SHA1 32/64]... (8xOMP) DONE
Many salts:	3913K c/s real, 539241 c/s virtual
Only one salt:	3510K c/s real, 482180 c/s virtual

Benchmarking: mysql-sha1, MySQL 4.1+ [SHA1 256/256 AVX2 8x]... DONE
Raw:	19873K c/s real, 19873K c/s virtual

Benchmarking: mysql, MySQL pre-4.1 [32/64]... DONE
Raw:	62777K c/s real, 62777K c/s virtual

Benchmarking: net-ah, IPsec AH HMAC-MD5-96 [MD5 32/64]... (8xOMP) DONE
Many salts:	4582K c/s real, 621272 c/s virtual
Only one salt:	3072K c/s real, 424309 c/s virtual

Benchmarking: nethalflm, HalfLM C/R [DES 32/64]... (8xOMP) DONE
Many salts:	9289K c/s real, 1265K c/s virtual
Only one salt:	1313K c/s real, 183555 c/s virtual

Benchmarking: netlm, LM C/R [DES 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 16/256
Many salts:	15679K c/s real, 2261K c/s virtual
Only one salt:	1718K c/s real, 970903 c/s virtual

Benchmarking: netlmv2, LMv2 C/R [MD4 HMAC-MD5 32/64]... (8xOMP) DONE
Many salts:	3341K c/s real, 447297 c/s virtual
Only one salt:	2030K c/s real, 280081 c/s virtual

Benchmarking: net-md5, "Keyed MD5" RIPv2, OSPF, BGP, SNMPv2 [MD5 32/64]... (8xOMP) DONE
Many salts:	10923K c/s real, 10114K c/s virtual
Only one salt:	7529K c/s real, 7529K c/s virtual

Benchmarking: netntlmv2, NTLMv2 C/R [MD4 HMAC-MD5 32/64]... (8xOMP) DONE
Many salts:	3555K c/s real, 471884 c/s virtual
Only one salt:	1794K c/s real, 244420 c/s virtual

Benchmarking: netntlm, NTLMv1 C/R [MD4 DES (ESS MD5) 256/256 AVX2 8x3]... DONE
Many salts:	11134M c/s real, 11134M c/s virtual
Only one salt:	63946K c/s real, 63946K c/s virtual

Benchmarking: netntlm-naive, NTLMv1 C/R [MD4 DES (ESS MD5) DES 256/256 AVX2 naive]... (8xOMP) DONE
Many salts:	274759K c/s real, 37484K c/s virtual
Only one salt:	9051K c/s real, 1252K c/s virtual

Benchmarking: net-sha1, "Keyed SHA1" BFD [SHA1 32/64]... (8xOMP) DONE
Many salts:	11830K c/s real, 11267K c/s virtual
Only one salt:	7922K c/s real, 7922K c/s virtual

Benchmarking: nk, Nuked-Klan CMS [SHA1 MD5 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 25/256
Many salts:	6362K c/s real, 958128 c/s virtual
Only one salt:	6241K c/s real, 900219 c/s virtual

Benchmarking: notes, Apple Notes [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 20000
Raw:	1531 c/s real, 230 c/s virtual

Benchmarking: md5ns, Netscreen [md5($s.$p) (OSC) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	19992K c/s real, 19992K c/s virtual
Only one salt:	13090K c/s real, 13222K c/s virtual

Benchmarking: nsec3, DNSSEC NSEC3 [32/64]... DONE
Raw:	69822 c/s real, 69822 c/s virtual

Benchmarking: NT [MD4 256/256 AVX2 8x3]... DONE
Raw:	71348K c/s real, 71348K c/s virtual

Benchmarking: o10glogon, Oracle 10g-logon protocol [DES-AES128-MD5 32/64]... (8xOMP) DONE
Many salts:	1425K c/s real, 188352 c/s virtual
Only one salt:	843776 c/s real, 116543 c/s virtual

Benchmarking: o3logon, Oracle O3LOGON protocol [SHA1 DES 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 13/256
Many salts:	835262 c/s real, 132088 c/s virtual
Only one salt:	851968 c/s real, 129086 c/s virtual

Benchmarking: o5logon, Oracle O5LOGON protocol [SHA1 AES 32/64]... (8xOMP) DONE
Many salts:	4964K c/s real, 678190 c/s virtual
Only one salt:	2883K c/s real, 407861 c/s virtual

Benchmarking: ODF, OpenDocument Star/Libre/OpenOffice [PBKDF2-SHA1 256/256 AVX2 8x BF/AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1024, cost 2 (crypto [0=Blowfish, 1=AES]) of 0 and 1
Raw:	20928 c/s real, 2890 c/s virtual

Benchmarking: Office, 2007/2010/2013 [SHA1 256/256 AVX2 8x / SHA512 256/256 AVX2 4x AES]... (8xOMP) DONE
Speed for cost 1 (MS Office version) of 2007, cost 2 (iteration count) of 50000
Raw:	2153 c/s real, 301 c/s virtual

Benchmarking: oldoffice, MS Office <= 2003 [MD5/SHA1 RC4 32/64]... (8xOMP) DONE
Speed for cost 1 (hash type) of 1 and 0
Many salts:	1097K c/s real, 154175 c/s virtual
Only one salt:	1077K c/s real, 148585 c/s virtual

Benchmarking: OpenBSD-SoftRAID [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (kdf) of 1, cost 2 (iteration count) of 8192
Raw:	3011 c/s real, 421 c/s virtual

Benchmarking: openssl-enc, OpenSSL "enc" encryption (AES-128, MD5) [32/64]... (8xOMP) DONE
Many salts:	3529K c/s real, 483273 c/s virtual
Only one salt:	2154K c/s real, 297674 c/s virtual

Benchmarking: oracle, Oracle 10 [DES 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 90/256
Many salts:	2949K c/s real, 403436 c/s virtual
Only one salt:	1654K c/s real, 238397 c/s virtual

Benchmarking: oracle11, Oracle 11g [SHA1 256/256 AVX2 8x]... DONE
Many salts:	36944K c/s real, 36944K c/s virtual
Only one salt:	26024K c/s real, 26024K c/s virtual

Benchmarking: Oracle12C [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	2407 c/s real, 363 c/s virtual

Benchmarking: osc, osCommerce [md5($s.$p) (OSC) 256/256 AVX2 8x3]... DONE
Many salts:	30196K c/s real, 30196K c/s virtual
Only one salt:	16578K c/s real, 16578K c/s virtual

Benchmarking: ospf, OSPF / IS-IS [HMAC-SHA-X 32/64]... (8xOMP) DONE
Raw:	4087K c/s real, 553454 c/s virtual

Benchmarking: Padlock [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:	2982 c/s real, 461 c/s virtual

Benchmarking: Palshop, MD5(Palshop) [MD5 + SHA1 32/64]... (8xOMP) DONE
Raw:	6358K c/s real, 866737 c/s virtual

Benchmarking: Panama [Panama 32/64]... (8xOMP) DONE
Raw:	2043K c/s real, 285135 c/s virtual

Benchmarking: PBKDF2-HMAC-MD4 [PBKDF2-MD4 256/256 AVX2 8x3]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	187245 c/s real, 27420 c/s virtual

Benchmarking: PBKDF2-HMAC-MD5 [PBKDF2-MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	112538 c/s real, 16054 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA1 [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	46682 c/s real, 6504 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA256 [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	23363 c/s real, 3251 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA512, GRUB2 / OS X 10.8+ [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:	6526 c/s real, 906 c/s virtual

Benchmarking: PDF [MD5 SHA2 RC4/AES 32/64]... (8xOMP) DONE
Speed for cost 1 (revision) of 4
Raw:	110336 c/s real, 15032 c/s virtual

Benchmarking: PEM, PKCS#8 private key (RSA/DSA/ECDSA) [PBKDF2-SHA1 256/256 AVX2 8x 3DES/AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 4096, cost 2 (cipher [1=3DES, 2/3/4=AES-128/192/256]) of 1
Raw:	14628 c/s real, 2145 c/s virtual

Benchmarking: pfx [PKCS12 PBE (.pfx, .p12) (SHA-1 to SHA-512) 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 2048, cost 2 (mac-type [1:SHA1 224:SHA224 256:SHA256 384:SHA384 512:SHA512]) of 1
Raw:	49230 c/s real, 7314 c/s virtual

Benchmarking: pgpdisk [PGP Disk / Virtual Disk SHA1 64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 16000, cost 2 (algorithm [3=CAST, 4=TwoFish, 5/6/7=AES]) of 5
Raw:	1988 c/s real, 302 c/s virtual

Benchmarking: pgpsda [PGP SDA SHA1 64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 16000
Raw:	5296 c/s real, 842 c/s virtual

Benchmarking: pgpwde [PGP WDE S2K-SHA1 64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 131072
Raw:	5019 c/s real, 749 c/s virtual

Benchmarking: phpass ($P$9) [phpass ($P$ or $H$) 256/256 AVX2 8x3]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Warning: "Many salts" test limited: 106/256
Many salts:	80601 c/s real, 11275 c/s virtual
Only one salt:	61741 c/s real, 8710 c/s virtual

Benchmarking: PHPS [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:	48854K c/s real, 48854K c/s virtual
Only one salt:	12126K c/s real, 12126K c/s virtual

Benchmarking: PHPS2 [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:	49002K c/s real, 49002K c/s virtual
Only one salt:	11880K c/s real, 11880K c/s virtual

Benchmarking: pix-md5, Cisco PIX [md5($p) (Cisco PIX) 256/256 AVX2 8x3]... DONE
Raw:	18543K c/s real, 18543K c/s virtual

Benchmarking: PKZIP [32/64]... (8xOMP) DONE
Many salts:	40615K c/s real, 5459K c/s virtual
Only one salt:	12664K c/s real, 1734K c/s virtual

Benchmarking: po, Post.Office [MD5 32/64]... DONE
Many salts:	3947K c/s real, 3947K c/s virtual
Only one salt:	3869K c/s real, 3869K c/s virtual

Benchmarking: postgres, PostgreSQL C/R [MD5 32/64]... (8xOMP) DONE
Many salts:	6692K c/s real, 915576 c/s virtual
Only one salt:	5390K c/s real, 738402 c/s virtual

Benchmarking: PST, custom CRC-32 [32/64]... DONE
Raw:	86472K c/s real, 86472K c/s virtual

Benchmarking: PuTTY, Private Key (RSA/DSA/ECDSA/ED25519) [SHA1/AES 32/64]... (8xOMP) DONE
Raw:	936228 c/s real, 146941 c/s virtual

Benchmarking: pwsafe, Password Safe [SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:	28006 c/s real, 4634 c/s virtual

Benchmarking: qnx, qnx hash (rounds=1000) [QNX 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (algorithm [5:MD5 256:SHA256 512:SHA512]) of 5
Raw:	120470 c/s real, 18731 c/s virtual

Benchmarking: RACF [DES 32/64]... (8xOMP) DONE
Many salts:	22588K c/s real, 3062K c/s virtual
Only one salt:	5685K c/s real, 798691 c/s virtual

Benchmarking: RACF-KDFAES [KDFAES (DES + HMAC-SHA256/64 + AES-256)]... (8xOMP) DONE
Warning: "Many salts" test limited: 2/256
Many salts:	0.7 c/s real, 0.1 c/s virtual
Only one salt:	0.3 c/s real, 0.0 c/s virtual

Benchmarking: radius, RADIUS authentication [MD5 32/64]... (8xOMP) DONE
Many salts:	12853K c/s real, 1760K c/s virtual
Only one salt:	10551K c/s real, 1451K c/s virtual

Benchmarking: RAdmin, v2.x [MD5 32/64]... (8xOMP) DONE
Raw:	14463K c/s real, 2549K c/s virtual

Benchmarking: RAKP, IPMI 2.0 RAKP (RMCP+) [HMAC-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Warning: "Many salts" test limited: 85/256
Many salts:	22061K c/s real, 3103K c/s virtual
Only one salt:	7889K c/s real, 1179K c/s virtual

Benchmarking: rar, RAR3 (length 5) [SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Raw:	329 c/s real, 47.2 c/s virtual

Benchmarking: RAR5 [PBKDF2-SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 32768
Raw:	939 c/s real, 144 c/s virtual

Benchmarking: Raw-SHA512 [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	8888K c/s real, 1210K c/s virtual

Benchmarking: Raw-Blake2 [BLAKE2b 512 128/128 AVX]... (8xOMP) DONE
Raw:	11534K c/s real, 1558K c/s virtual

Benchmarking: Raw-Keccak [Keccak 512 32/64]... (8xOMP) DONE
Raw:	3983K c/s real, 563555 c/s virtual

Benchmarking: Raw-Keccak-256 [Keccak 256 32/64]... (8xOMP) DONE
Raw:	2794K c/s real, 393759 c/s virtual

Benchmarking: Raw-MD4 [MD4 256/256 AVX2 8x3]... DONE
Raw:	72453K c/s real, 72453K c/s virtual

Benchmarking: Raw-MD5 [MD5 256/256 AVX2 8x3]... DONE
Raw:	61156K c/s real, 61156K c/s virtual

Benchmarking: Raw-MD5u [md5(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:	55687K c/s real, 55687K c/s virtual

Benchmarking: Raw-SHA1 [SHA1 256/256 AVX2 8x]... DONE
Raw:	35802K c/s real, 35802K c/s virtual

Benchmarking: Raw-SHA1-AxCrypt [SHA1 256/256 AVX2 8x]... DONE
Raw:	35640K c/s real, 35640K c/s virtual

Benchmarking: Raw-SHA1-Linkedin [SHA1 256/256 AVX2 8x]... DONE
Raw:	35394K c/s real, 35394K c/s virtual

Benchmarking: Raw-SHA224 [SHA224 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	14008K c/s real, 1940K c/s virtual

Benchmarking: Raw-SHA256 [SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	18874K c/s real, 2614K c/s virtual

Benchmarking: Raw-SHA3 [SHA3 512 32/64]... (8xOMP) DONE
Raw:	4194K c/s real, 580125 c/s virtual

Benchmarking: Raw-SHA384 [SHA384 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	9502K c/s real, 1303K c/s virtual

Benchmarking: ripemd-128, RIPEMD 128 [32/64]... DONE
Raw:	6122K c/s real, 6122K c/s virtual

Benchmarking: ripemd-160, RIPEMD 160 [32/64]... DONE
Raw:	4207K c/s real, 4207K c/s virtual

Benchmarking: rsvp, HMAC-MD5 / HMAC-SHA1, RSVP, IS-IS, OMAPI, RNDC, TSIG [MD5 32/64]... (8xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1 3:SHA224 4:SHA256 5:SHA384 6:SHA512]) of 1 and 2
Many salts:	5554K c/s real, 746529 c/s virtual
Only one salt:	2531K c/s real, 346757 c/s virtual

Benchmarking: Siemens-S7 [HMAC-SHA1 32/64]... (8xOMP) DONE
Many salts:	5562K c/s real, 766393 c/s virtual
Only one salt:	2339K c/s real, 324641 c/s virtual

Benchmarking: Salted-SHA1 [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	39976K c/s real, 5506K c/s virtual
Only one salt:	14061K c/s real, 2000K c/s virtual

Benchmarking: SSHA512, LDAP [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Warning: "Many salts" test limited: 211/256
Many salts:	13828K c/s real, 1878K c/s virtual
Only one salt:	8159K c/s real, 1146K c/s virtual

Benchmarking: sapb, SAP CODVN B (BCODE) [MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Warning: "Many salts" test limited: 152/256
Many salts:	14649K c/s real, 2069K c/s virtual
Only one salt:	11599K c/s real, 1620K c/s virtual

Benchmarking: sapg, SAP CODVN F/G (PASSCODE) [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	10235K c/s real, 1395K c/s virtual
Only one salt:	7999K c/s real, 1108K c/s virtual

Benchmarking: saph, SAP CODVN H (PWDSALTEDHASH) (SHA1x1024) [SHA-1/SHA-2 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256 3:SHA384 4:SHA512]) of 1, cost 2 (iteration count) of 1024
Warning: "Many salts" test limited: 81/256
Many salts:	82122 c/s real, 11409 c/s virtual
Only one salt:	77824 c/s real, 10808 c/s virtual

Benchmarking: sappse [PKCS12 PBE SHA1 256/256 AVX2 8x 3DES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:	17554 c/s real, 2477 c/s virtual

Benchmarking: securezip, PKWARE SecureZIP [SHA1 AES 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 122/256
Many salts:	989528 c/s real, 141161 c/s virtual
Only one salt:	999424 c/s real, 139001 c/s virtual

Benchmarking: 7z, 7-Zip (512K iterations) [SHA256 256/256 AVX2 8x AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 524288, cost 2 (padding size) of 4 and 9, cost 3 (compression type) of 128 and 1
Many salts:	14894 c/s real, 2291 c/s virtual
Only one salt:	119 c/s real, 20.0 c/s virtual

Benchmarking: Signal [Signal Android PKCS12 PBE SHA-1 32/64]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 6024 and 6097
Raw:	1916 c/s real, 266 c/s virtual

Benchmarking: SIP [MD5 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 32/256
Many salts:	8144K c/s real, 1155K c/s virtual
Only one salt:	7967K c/s real, 1123K c/s virtual

Benchmarking: skein-256, Skein 256 [Skein 32/64]... (8xOMP) DONE
Raw:	1735K c/s real, 249372 c/s virtual

Benchmarking: skein-512, Skein 512 [Skein 32/64]... (8xOMP) DONE
Raw:	6272K c/s real, 849661 c/s virtual

Benchmarking: skey, S/Key [MD4/MD5/SHA1/RMD160 32/64]... DONE
Speed for cost 1 (hash type [1:MD4 2:MD5 3:SHA1 4:RMD160]) of 1 and 2, cost 2 (iteration count) of 96 and 99
Raw:	78122 c/s real, 78122 c/s virtual

Benchmarking: SL3, Nokia operator unlock [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	47627K c/s real, 6544K c/s virtual
Only one salt:	14275K c/s real, 2022K c/s virtual

Benchmarking: Snefru-128 [32/64]... (8xOMP) DONE
Raw:	1277K c/s real, 177247 c/s virtual

Benchmarking: Snefru-256 [32/64]... (8xOMP) DONE
Raw:	1395K c/s real, 192752 c/s virtual

Benchmarking: LastPass, sniffed sessions [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 22/256
Many salts:	45056 c/s real, 6625 c/s virtual
Only one salt:	50196 c/s real, 7170 c/s virtual

Benchmarking: SNMP, SNMPv3 USM [HMAC-MD5-96/HMAC-SHA1-96 32/64]... (8xOMP) DONE
Raw:	845 c/s real, 131 c/s virtual

Benchmarking: solarwinds, SolarWinds Orion [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	1203 c/s real, 175 c/s virtual

Benchmarking: SSH [RSA/DSA/EC/OPENSSH (SSH private keys) 32/64]... (8xOMP) DONE
Speed for cost 1 (KDF/cipher [0=MD5/AES 1=MD5/3DES 2=Bcrypt/AES]) of 0 and 1, cost 2 (iteration count) of 1 and 2
Raw:	1163K c/s real, 161904 c/s virtual

Benchmarking: sspr, NetIQ SSPR / Adobe AEM [MD5/SHA1/SHA256/SHA512 32/64]... (8xOMP) DONE
Speed for cost 1 (KDF [0:MD5 1:SHA1 2:SHA1_SALT 3:SHA256_SALT 4:SHA512_SALT]) of 1, cost 2 (iteration count) of 100000
Raw:	226 c/s real, 36.2 c/s virtual

Benchmarking: Stribog-256 [GOST R 34.11-2012 128/128 AVX 1x]... (8xOMP) DONE
Raw:	1026K c/s real, 140800 c/s virtual

Benchmarking: Stribog-512 [GOST R 34.11-2012 128/128 AVX 1x]... (8xOMP) DONE
Raw:	704512 c/s real, 98809 c/s virtual

Benchmarking: STRIP, Password Manager [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	8613 c/s real, 1347 c/s virtual

Benchmarking: SunMD5 [MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:	3011 c/s real, 483 c/s virtual

Benchmarking: SybaseASE, Sybase ASE [SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	12582K c/s real, 1714K c/s virtual
Only one salt:	2666K c/s real, 370537 c/s virtual

Benchmarking: Sybase-PROP [salted FEAL-8 32/64]... (8xOMP) DONE
Many salts:	1211K c/s real, 169662 c/s virtual
Only one salt:	1790K c/s real, 243339 c/s virtual

Benchmarking: tacacs-plus, TACACS+ [MD5 32/64]... (8xOMP) DONE
Many salts:	10371K c/s real, 1438K c/s virtual
Only one salt:	10479K c/s real, 1447K c/s virtual

Benchmarking: tcp-md5, TCP MD5 Signatures, BGP, MSDP [MD5 32/64]... (8xOMP) DONE
Many salts:	7170K c/s real, 1021K c/s virtual
Only one salt:	6521K c/s real, 892873 c/s virtual

Benchmarking: telegram [PBKDF2-SHA1 256/256 AVX2 8x AES]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 4000
Raw:	2461 c/s real, 373 c/s virtual

Benchmarking: tezos, Tezos Key [PBKDF2-SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:	3421 c/s real, 501 c/s virtual

Benchmarking: Tiger [Tiger 32/64]... (8xOMP) DONE
Raw:	10398K c/s real, 1409K c/s virtual

Benchmarking: tc_aes_xts, TrueCrypt AES256_XTS [SHA512/RIPEMD160/WHIRLPOOL 256/256 AVX2 4x]... (8xOMP) DONE
Speed for cost 1 (hash algorithm [1:SHA512 2:RIPEMD160 3:Whirlpool]) of 1
Raw:	10333 c/s real, 1620 c/s virtual

Benchmarking: tc_ripemd160, TrueCrypt AES256_XTS [RIPEMD160 32/64]... (8xOMP) DONE
Raw:	1113 c/s real, 177 c/s virtual

Benchmarking: tc_ripemd160boot, TrueCrypt AES/Twofish/Serpent [RIPEMD160 32/64]... (8xOMP) DONE
Raw:	1845 c/s real, 331 c/s virtual

Benchmarking: tc_sha512, TrueCrypt AES256_XTS [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Raw:	11070 c/s real, 1791 c/s virtual

Benchmarking: tc_whirlpool, TrueCrypt AES256_XTS [WHIRLPOOL 32/64]... (8xOMP) DONE
Raw:	1665 c/s real, 264 c/s virtual

Benchmarking: vdi, VirtualBox-VDI AES_XTS [PBKDF2-SHA256 256/256 AVX2 8x + AES_XTS]... (8xOMP) DONE
Raw:	5437 c/s real, 806 c/s virtual

Benchmarking: OpenVMS, Purdy [32/64]... (8xOMP) DONE
Many salts:	1295K c/s real, 182775 c/s virtual
Only one salt:	1806K c/s real, 250185 c/s virtual

Benchmarking: vmx, VMware VMX [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:	2407 c/s real, 338 c/s virtual

Benchmarking: VNC [DES 32/64]... (8xOMP) DONE
Warning: "Many salts" test limited: 163/256
Many salts:	10682K c/s real, 1447K c/s virtual
Only one salt:	5570K c/s real, 781284 c/s virtual

Benchmarking: vtp, "MD5 based authentication" VTP [MD5 32/64]... (8xOMP) DONE
Many salts:	1855K c/s real, 266474 c/s virtual
Only one salt:	23860 c/s real, 4015 c/s virtual

Benchmarking: wbb3, WoltLab BB3 [SHA1 32/64]... (8xOMP) DONE
Many salts:	3624K c/s real, 491186 c/s virtual
Only one salt:	2461K c/s real, 339076 c/s virtual

Benchmarking: whirlpool [WHIRLPOOL 32/64]... (8xOMP) DONE
Raw:	2850K c/s real, 393759 c/s virtual

Benchmarking: whirlpool0 [WHIRLPOOL-0 32/64]... (8xOMP) DONE
Raw:	2867K c/s real, 400446 c/s virtual

Benchmarking: whirlpool1 [WHIRLPOOL-1 32/64]... (8xOMP) DONE
Raw:	2801K c/s real, 382740 c/s virtual

Benchmarking: wpapsk, WPA/WPA2/PMF/PMKID PSK [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 2
Raw:	5851 c/s real, 826 c/s virtual

Benchmarking: wpapsk-pmk, WPA/WPA2/PMF/PMKID master key [MD5/SHA-1/SHA-2]... (8xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 1 and 2
Many salts:	817152 c/s real, 115580 c/s virtual
Only one salt:	1259K c/s real, 174207 c/s virtual

Benchmarking: xmpp-scram [XMPP SCRAM PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	16221 c/s real, 2572 c/s virtual

Benchmarking: xsha, Mac OS X 10.4 - 10.6 [SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	57611K c/s real, 7981K c/s virtual
Only one salt:	15360K c/s real, 2151K c/s virtual

Benchmarking: xsha512, Mac OS X 10.7 [SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Warning: "Many salts" test limited: 104/256
Many salts:	13496K c/s real, 1857K c/s virtual
Only one salt:	8224K c/s real, 1157K c/s virtual

Benchmarking: ZIP, WinZip [PBKDF2-SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Raw:	72495 c/s real, 11425 c/s virtual

Benchmarking: ZipMonster, MD5(ZipMonster) [MD5-256/256 AVX2 8x3 x 50000]... (8xOMP) DONE
Raw:	4042 c/s real, 614 c/s virtual

Benchmarking: plaintext, $0$ [n/a]... DONE
Raw:	96250K c/s real, 96250K c/s virtual

Benchmarking: has-160 [HAS-160 32/64]... DONE
Raw:	9211K c/s real, 9211K c/s virtual

Benchmarking: HMAC-MD5 [password is key, MD5 256/256 AVX2 8x3]... (8xOMP) DONE
Many salts:	59670K c/s real, 8219K c/s virtual
Only one salt:	8175K c/s real, 1121K c/s virtual

Benchmarking: HMAC-SHA1 [password is key, SHA1 256/256 AVX2 8x]... (8xOMP) DONE
Warning: "Many salts" test limited: 120/256
Many salts:	30840K c/s real, 4256K c/s virtual
Only one salt:	9084K c/s real, 1288K c/s virtual

Benchmarking: HMAC-SHA224 [password is key, SHA224 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	14647K c/s real, 2000K c/s virtual
Only one salt:	4194K c/s real, 580928 c/s virtual

Benchmarking: HMAC-SHA256 [password is key, SHA256 256/256 AVX2 8x]... (8xOMP) DONE
Many salts:	10025K c/s real, 1398K c/s virtual
Only one salt:	6275K c/s real, 847982 c/s virtual

Benchmarking: HMAC-SHA384 [password is key, SHA384 256/256 AVX2 4x]... (8xOMP) DONE
Many salts:	5581K c/s real, 767788 c/s virtual
Only one salt:	1497K c/s real, 209090 c/s virtual

Benchmarking: HMAC-SHA512 [password is key, SHA512 256/256 AVX2 4x]... (8xOMP) DONE
Many salts:	4300K c/s real, 601878 c/s virtual
Only one salt:	2219K c/s real, 305228 c/s virtual

Benchmarking: dynamic_0 [md5($p) (raw-md5) 256/256 AVX2 8x3]... DONE
Raw:	49647K c/s real, 49647K c/s virtual

Benchmarking: dynamic_1 [md5($p.$s) (joomla) 256/256 AVX2 8x3]... DONE
Many salts:	28190K c/s real, 28190K c/s virtual
Only one salt:	15902K c/s real, 15902K c/s virtual

Benchmarking: dynamic_2 [md5(md5($p)) (e107) 256/256 AVX2 8x3]... DONE
Raw:	27269K c/s real, 27269K c/s virtual

Benchmarking: dynamic_3 [md5(md5(md5($p))) 256/256 AVX2 8x3]... DONE
Raw:	18530K c/s real, 18530K c/s virtual

Benchmarking: dynamic_4 [md5($s.$p) (OSC) 256/256 AVX2 8x3]... DONE
Many salts:	31872K c/s real, 31872K c/s virtual
Only one salt:	16396K c/s real, 16396K c/s virtual

Benchmarking: dynamic_5 [md5($s.$p.$s) 256/256 AVX2 8x3]... DONE
Many salts:	22643K c/s real, 22643K c/s virtual
Only one salt:	13261K c/s real, 13261K c/s virtual

Benchmarking: dynamic_6 [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:	48205K c/s real, 48205K c/s virtual
Only one salt:	12102K c/s real, 12102K c/s virtual

Benchmarking: dynamic_8 [md5(md5($s).$p) 256/256 AVX2 8x3]... DONE
Many salts:	32823K c/s real, 32823K c/s virtual
Only one salt:	16937K c/s real, 16937K c/s virtual

Benchmarking: dynamic_9 [md5($s.md5($p)) 256/256 AVX2 8x3]... DONE
Many salts:	31661K c/s real, 31661K c/s virtual
Only one salt:	12052K c/s real, 12052K c/s virtual

Benchmarking: dynamic_10 [md5($s.md5($s.$p)) 256/256 AVX2 8x3]... DONE
Many salts:	15183K c/s real, 15183K c/s virtual
Only one salt:	10627K c/s real, 10627K c/s virtual

Benchmarking: dynamic_11 [md5($s.md5($p.$s)) 256/256 AVX2 8x3]... DONE
Many salts:	15187K c/s real, 15036K c/s virtual
Only one salt:	10778K c/s real, 10778K c/s virtual

Benchmarking: dynamic_12 [md5(md5($s).md5($p)) (IPB) 256/256 AVX2 8x3]... DONE
Many salts:	19844K c/s real, 19844K c/s virtual
Only one salt:	8060K c/s real, 8060K c/s virtual

Benchmarking: dynamic_13 [md5(md5($p).md5($s)) 256/256 AVX2 8x3]... DONE
Many salts:	19998K c/s real, 19998K c/s virtual
Only one salt:	8020K c/s real, 8020K c/s virtual

Benchmarking: dynamic_14 [md5($s.md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:	22942K c/s real, 22942K c/s virtual
Only one salt:	10641K c/s real, 10641K c/s virtual

Benchmarking: dynamic_15 [md5($u.md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:	16420K c/s real, 16420K c/s virtual
Only one salt:	7284K c/s real, 7284K c/s virtual

Benchmarking: dynamic_16 [md5(md5(md5($p).$s).$s2) 256/256 AVX2 8x3]... DONE
Many salts:	10516K c/s real, 10516K c/s virtual
Only one salt:	5920K c/s real, 5920K c/s virtual

Benchmarking: dynamic_18 [md5($s.Y.$p.0xF7.$s) (Post.Office MD5) 32/64 x2]... DONE
Many salts:	4005K c/s real, 4005K c/s virtual
Only one salt:	3628K c/s real, 3628K c/s virtual

Benchmarking: dynamic_19 [md5($p) (Cisco PIX) 256/256 AVX2 8x3]... DONE
Raw:	18261K c/s real, 18261K c/s virtual

Benchmarking: dynamic_20 [md5($p.$s) (Cisco ASA) 256/256 AVX2 8x3]... DONE
Many salts:	27259K c/s real, 27259K c/s virtual
Only one salt:	15664K c/s real, 15664K c/s virtual

Benchmarking: dynamic_22 [md5(sha1($p)) 256/256 AVX2 8x1]... DONE
Raw:	10946K c/s real, 10946K c/s virtual

Benchmarking: dynamic_23 [sha1(md5($p)) 256/256 AVX2 8x1]... DONE
Raw:	14404K c/s real, 14404K c/s virtual

Benchmarking: dynamic_24 [sha1($p.$s) 256/256 AVX2 8x1]... DONE
Many salts:	16625K c/s real, 16625K c/s virtual
Only one salt:	11464K c/s real, 11464K c/s virtual

Benchmarking: dynamic_25 [sha1($s.$p) 256/256 AVX2 8x1]... DONE
Many salts:	16732K c/s real, 16732K c/s virtual
Only one salt:	11434K c/s real, 11434K c/s virtual

Benchmarking: dynamic_26 [sha1($p) raw-sha1 256/256 AVX2 8x1]... DONE
Raw:	17687K c/s real, 17687K c/s virtual

Benchmarking: dynamic_29 [md5(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:	20260K c/s real, 20260K c/s virtual

Benchmarking: dynamic_30 [md4($p) (raw-md4) 256/256 AVX2 8x3]... DONE
Raw:	58507K c/s real, 58507K c/s virtual

Benchmarking: dynamic_31 [md4($s.$p) 256/256 AVX2 8x3]... DONE
Many salts:	37857K c/s real, 37857K c/s virtual
Only one salt:	18651K c/s real, 18651K c/s virtual

Benchmarking: dynamic_32 [md4($p.$s) 256/256 AVX2 8x3]... DONE
Many salts:	32232K c/s real, 32232K c/s virtual
Only one salt:	16847K c/s real, 16847K c/s virtual

Benchmarking: dynamic_33 [md4(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:	21588K c/s real, 21588K c/s virtual

Benchmarking: dynamic_34 [md5(md4($p)) 256/256 AVX2 8x3]... DONE
Raw:	29500K c/s real, 29500K c/s virtual

Benchmarking: dynamic_35 [sha1(uc($u).:.$p) (ManGOS) 256/256 AVX2 8x1]... DONE
Many salts:	13802K c/s real, 13802K c/s virtual
Only one salt:	9945K c/s real, 9945K c/s virtual

Benchmarking: dynamic_36 [sha1($u.:.$p) (ManGOS2) 256/256 AVX2 8x1]... DONE
Many salts:	13829K c/s real, 13829K c/s virtual
Only one salt:	10127K c/s real, 10127K c/s virtual

Benchmarking: dynamic_37 [sha1(lc($u).$p) (SMF) 256/256 AVX2 8x1]... DONE
Many salts:	16833K c/s real, 16833K c/s virtual
Only one salt:	11450K c/s real, 11450K c/s virtual

Benchmarking: dynamic_38 [sha1($s.sha1($s.sha1($p))) (Wolt3BB) 256/256 AVX2 8x1]... DONE
Many salts:	4542K c/s real, 4542K c/s virtual
Only one salt:	4055K c/s real, 4055K c/s virtual

Benchmarking: dynamic_39 [md5($s.pad16($p)) (net-md5) 256/256 AVX2 8x3]... DONE
Many salts:	11793K c/s real, 11793K c/s virtual
Only one salt:	8840K c/s real, 8840K c/s virtual

Benchmarking: dynamic_40 [sha1($s.pad20($p)) (net-sha1) 256/256 AVX2 8x1]... DONE
Many salts:	12230K c/s real, 12230K c/s virtual
Only one salt:	9179K c/s real, 9179K c/s virtual

Benchmarking: dynamic_50 [sha224($p) 256/256 AVX2 8x]... DONE
Raw:	12059K c/s real, 12059K c/s virtual

Benchmarking: dynamic_60 [sha256($p) 256/256 AVX2 8x]... DONE
Raw:	11995K c/s real, 11995K c/s virtual

Benchmarking: dynamic_61 [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:	10113K c/s real, 10113K c/s virtual
Only one salt:	7953K c/s real, 7953K c/s virtual

Benchmarking: dynamic_70 [sha384($p) 256/256 AVX2 4x]... DONE
Raw:	6390K c/s real, 6454K c/s virtual

Benchmarking: dynamic_80 [sha512($p) 256/256 AVX2 4x]... DONE
Raw:	6347K c/s real, 6347K c/s virtual

Benchmarking: dynamic_90 [gost($p) 64/64]... DONE
Raw:	658693 c/s real, 658693 c/s virtual

Benchmarking: dynamic_100 [whirlpool($p) 32/64 OpenSSL]... DONE
Raw:	1982K c/s real, 2002K c/s virtual

Benchmarking: dynamic_110 [tiger($p) 32/64 sph_tiger]... DONE
Raw:	6333K c/s real, 6333K c/s virtual

Benchmarking: dynamic_120 [ripemd128($p) 32/64 sph_ripemd]... DONE
Raw:	6192K c/s real, 6192K c/s virtual

Benchmarking: dynamic_130 [ripemd160($p) 32/64 sph_ripemd]... DONE
Raw:	4092K c/s real, 4092K c/s virtual

Benchmarking: dynamic_140 [ripemd256($p) 32/64 sph_ripemd]... DONE
Raw:	5446K c/s real, 5446K c/s virtual

Benchmarking: dynamic_150 [ripemd320($p) 32/64 sph_ripemd]... DONE
Raw:	3827K c/s real, 3827K c/s virtual

Benchmarking: dynamic_160 [haval128_3($p) 32/64 sph_haval]... DONE
Raw:	4236K c/s real, 4236K c/s virtual

Benchmarking: dynamic_170 [haval128_4($p) 32/64 sph_haval]... DONE
Raw:	3047K c/s real, 3047K c/s virtual

Benchmarking: dynamic_180 [haval128_5($p) 32/64 sph_haval]... DONE
Raw:	2698K c/s real, 2698K c/s virtual

Benchmarking: dynamic_190 [haval160_3($p) 32/64 sph_haval]... DONE
Raw:	4099K c/s real, 4099K c/s virtual

Benchmarking: dynamic_200 [haval160_4($p) 32/64 sph_haval]... DONE
Raw:	3044K c/s real, 3044K c/s virtual

Benchmarking: dynamic_210 [haval160_5($p) 32/64 sph_haval]... DONE
Raw:	2674K c/s real, 2674K c/s virtual

Benchmarking: dynamic_220 [haval192_3($p) 32/64 sph_haval]... DONE
Raw:	4163K c/s real, 4163K c/s virtual

Benchmarking: dynamic_230 [haval192_4($p) 32/64 sph_haval]... DONE
Raw:	3027K c/s real, 3027K c/s virtual

Benchmarking: dynamic_240 [haval192_5($p) 32/64 sph_haval]... DONE
Raw:	2691K c/s real, 2691K c/s virtual

Benchmarking: dynamic_250 [haval224_3($p) 32/64 sph_haval]... DONE
Raw:	4220K c/s real, 4220K c/s virtual

Benchmarking: dynamic_260 [haval224_4($p) 32/64 sph_haval]... DONE
Raw:	3027K c/s real, 3027K c/s virtual

Benchmarking: dynamic_270 [haval224_5($p) 32/64 sph_haval]... DONE
Raw:	2731K c/s real, 2731K c/s virtual

Benchmarking: dynamic_280 [haval256_3($p) 32/64 sph_haval]... DONE
Raw:	4317K c/s real, 4317K c/s virtual

Benchmarking: dynamic_290 [haval256_4($p) 32/64 sph_haval]... DONE
Raw:	3094K c/s real, 3094K c/s virtual

Benchmarking: dynamic_300 [haval256_5($p) 32/64 sph_haval]... DONE
Raw:	2688K c/s real, 2688K c/s virtual

Benchmarking: dynamic_310 [md2($p) 32/64 sph_md2]... DONE
Raw:	208320 c/s real, 206257 c/s virtual

Benchmarking: dynamic_320 [panama($p) 32/64 sph_panama]... DONE
Raw:	1128K c/s real, 1128K c/s virtual

Benchmarking: dynamic_330 [skein224($p) 32/64 sph_skein]... DONE
Raw:	3507K c/s real, 3507K c/s virtual

Benchmarking: dynamic_340 [skein256($p) 32/64 sph_skein]... DONE
Raw:	3474K c/s real, 3474K c/s virtual

Benchmarking: dynamic_350 [skein384($p) 32/64 sph_skein]... DONE
Raw:	3507K c/s real, 3507K c/s virtual

Benchmarking: dynamic_360 [skein512($p) 32/64 sph_skein]... DONE
Raw:	3489K c/s real, 3524K c/s virtual

Benchmarking: dynamic_370 [sha3_224($p) 64/64 keccak]... DONE
Raw:	1797K c/s real, 1797K c/s virtual

Benchmarking: dynamic_380 [sha3_256($p) 64/64 keccak]... DONE
Raw:	1851K c/s real, 1851K c/s virtual

Benchmarking: dynamic_390 [sha3_384($p) 64/64 keccak]... DONE
Raw:	1844K c/s real, 1844K c/s virtual

Benchmarking: dynamic_400 [sha3_512($p) 64/64 keccak]... DONE
Raw:	1851K c/s real, 1851K c/s virtual

Benchmarking: dynamic_410 [keccak_256($p) 64/64 keccak]... DONE
Raw:	1821K c/s real, 1821K c/s virtual

Benchmarking: dynamic_420 [keccak_512($p) 64/64 keccak]... DONE
Raw:	1861K c/s real, 1861K c/s virtual

Benchmarking: dynamic_1001 [md5(md5(md5(md5($p)))) 256/256 AVX2 8x3]... DONE
Raw:	13258K c/s real, 13258K c/s virtual

Benchmarking: dynamic_1002 [md5(md5(md5(md5(md5($p))))) 256/256 AVX2 8x3]... DONE
Raw:	10661K c/s real, 10661K c/s virtual

Benchmarking: dynamic_1003 [md5(md5($p).md5($p)) 256/256 AVX2 8x3]... DONE
Raw:	7932K c/s real, 7932K c/s virtual

Benchmarking: dynamic_1004 [md5(md5(md5(md5(md5(md5($p)))))) 256/256 AVX2 8x3]... DONE
Raw:	8917K c/s real, 8917K c/s virtual

Benchmarking: dynamic_1005 [md5(md5(md5(md5(md5(md5(md5($p))))))) 256/256 AVX2 8x3]... DONE
Raw:	7650K c/s real, 7650K c/s virtual

Benchmarking: dynamic_1006 [md5(md5(md5(md5(md5(md5(md5(md5($p)))))))) 256/256 AVX2 8x3]... DONE
Raw:	6713K c/s real, 6713K c/s virtual

Benchmarking: dynamic_1007 [md5(md5($p).$s) (vBulletin) 256/256 AVX2 8x3]... DONE
Many salts:	49029K c/s real, 49029K c/s virtual
Only one salt:	12153K c/s real, 12153K c/s virtual

Benchmarking: dynamic_1008 [md5($p.$s) (RADIUS User-Password) 256/256 AVX2 8x3]... DONE
Many salts:	29137K c/s real, 29137K c/s virtual
Only one salt:	16114K c/s real, 16114K c/s virtual

Benchmarking: dynamic_1009 [md5($s.$p) (RADIUS Responses) 256/256 AVX2 8x3]... DONE
Many salts:	32592K c/s real, 32592K c/s virtual
Only one salt:	17747K c/s real, 17747K c/s virtual

Benchmarking: dynamic_1010 [md5($p null_padded_to_len_100) RAdmin v2.x MD5 256/256 AVX2 8x3]... DONE
Raw:	16121K c/s real, 16121K c/s virtual

Benchmarking: dynamic_1011 [md5($p.md5($s)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:	12280K c/s real, 12280K c/s virtual
Only one salt:	9250K c/s real, 9250K c/s virtual

Benchmarking: dynamic_1012 [md5($p.md5($s)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:	27219K c/s real, 27219K c/s virtual
Only one salt:	15889K c/s real, 15889K c/s virtual

Benchmarking: dynamic_1013 [md5($p.PMD5(username)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:	27837K c/s real, 27837K c/s virtual
Only one salt:	15946K c/s real, 15946K c/s virtual

Benchmarking: dynamic_1014 [md5($p.$s) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:	12341K c/s real, 12341K c/s virtual
Only one salt:	8678K c/s real, 8678K c/s virtual

Benchmarking: dynamic_1015 [md5(md5($p.$u).$s) (PostgreSQL 'pass the hash') 256/256 AVX2 8x3]... DONE
Many salts:	16077K c/s real, 16077K c/s virtual
Only one salt:	11296K c/s real, 11296K c/s virtual

Benchmarking: dynamic_1016 [md5($p.$s) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:	15822K c/s real, 15822K c/s virtual
Only one salt:	11114K c/s real, 11114K c/s virtual

Benchmarking: dynamic_1017 [md5($s.$p) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:	13268K c/s real, 13268K c/s virtual
Only one salt:	9811K c/s real, 9811K c/s virtual

Benchmarking: dynamic_1018 [md5(sha1(sha1($p))) 256/256 AVX2 8x1]... DONE
Raw:	7230K c/s real, 7230K c/s virtual

Benchmarking: dynamic_1019 [md5(sha1(sha1(md5($p)))) 256/256 AVX2 8x1]... DONE
Raw:	6679K c/s real, 6613K c/s virtual

Benchmarking: dynamic_1020 [md5(sha1(md5($p))) 256/256 AVX2 8x1]... DONE
Raw:	9690K c/s real, 9690K c/s virtual

Benchmarking: dynamic_1021 [md5(sha1(md5(sha1($p)))) 256/256 AVX2 8x1]... DONE
Raw:	5806K c/s real, 5806K c/s virtual

Benchmarking: dynamic_1022 [md5(sha1(md5(sha1(md5($p))))) 256/256 AVX2 8x1]... DONE
Raw:	5369K c/s real, 5369K c/s virtual

Benchmarking: dynamic_1023 [sha1($p) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	17730K c/s real, 17730K c/s virtual

Benchmarking: dynamic_1024 [sha1(md5($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	14820K c/s real, 14820K c/s virtual

Benchmarking: dynamic_1025 [sha1(md5(md5($p))) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	11420K c/s real, 11420K c/s virtual

Benchmarking: dynamic_1026 [sha1(sha1($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	9696K c/s real, 9696K c/s virtual

Benchmarking: dynamic_1027 [sha1(sha1(sha1($p))) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	6548K c/s real, 6548K c/s virtual

Benchmarking: dynamic_1028 [sha1(sha1_raw($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:	9851K c/s real, 9851K c/s virtual

Benchmarking: dynamic_1029 [sha256($p) (hash truncated to length 32) 256/256 AVX2 8x]... DONE
Raw:	8309K c/s real, 8309K c/s virtual

Benchmarking: dynamic_1030 [whirlpool($p) (hash truncated to length 32) 32/64 OpenSSL]... DONE
Raw:	1874K c/s real, 1874K c/s virtual

Benchmarking: dynamic_1031 [gost($p) (hash truncated to length 32) 64/64]... DONE
Raw:	635405 c/s real, 635405 c/s virtual

Benchmarking: dynamic_1032 [sha1_64(utf16($p)) (PeopleSoft) 256/256 AVX2 8x1]... DONE
Raw:	11350K c/s real, 11350K c/s virtual

Benchmarking: dynamic_1034 [md5($p.$u) (PostgreSQL MD5) 256/256 AVX2 8x3]... DONE
Many salts:	29181K c/s real, 29181K c/s virtual
Only one salt:	16148K c/s real, 16148K c/s virtual

Benchmarking: dynamic_1300 [md5(md5_raw($p)) 256/256 AVX2 8x3]... DONE
Raw:	15402K c/s real, 15402K c/s virtual

Benchmarking: dynamic_1350 [md5(md5($s.$p):$s) 256/256 AVX2 8x3]... DONE
Many salts:	14807K c/s real, 14807K c/s virtual
Only one salt:	10530K c/s real, 10530K c/s virtual

Benchmarking: dynamic_1400 [sha1(utf16($p)) (Microsoft CREDHIST) 256/256 AVX2 8x1]... DONE
Raw:	9891K c/s real, 9891K c/s virtual

Benchmarking: dynamic_1401 [md5($u.\nskyper\n.$p) (Skype MD5) 256/256 AVX2 8x3]... DONE
Many salts:	8440K c/s real, 8440K c/s virtual
Only one salt:	6357K c/s real, 6357K c/s virtual

Benchmarking: dynamic_1501 [sha1($s.sha1($p)) (Redmine) 256/256 AVX2 8x1]... DONE
Many salts:	11857K c/s real, 11857K c/s virtual
Only one salt:	5597K c/s real, 5597K c/s virtual

Benchmarking: dynamic_1502 [sha1(sha1($p).$s) (XenForo SHA-1) 256/256 AVX2 8x1]... DONE
Many salts:	20818K c/s real, 20818K c/s virtual
Only one salt:	7378K c/s real, 7378K c/s virtual

Benchmarking: dynamic_1503 [sha256(sha256($p).$s) (XenForo SHA-256) 256/256 AVX2 8x]... DONE
Many salts:	5759K c/s real, 5759K c/s virtual
Only one salt:	3346K c/s real, 3346K c/s virtual

Benchmarking: dynamic_1504 [sha1($s.$p.$s) 256/256 AVX2 8x1]... DONE
Many salts:	13678K c/s real, 13678K c/s virtual
Only one salt:	10006K c/s real, 10006K c/s virtual

Benchmarking: dynamic_1505 [md5($p.$s.md5($p.$s)) 256/256 AVX2 8x3]... DONE
Many salts:	6017K c/s real, 6017K c/s virtual
Only one salt:	5124K c/s real, 5124K c/s virtual

Benchmarking: dynamic_1506 [md5($u.:XDB:.$p) (Oracle 12c "H" hash) 256/256 AVX2 8x3]... DONE
Many salts:	25408K c/s real, 25408K c/s virtual
Only one salt:	14995K c/s real, 14995K c/s virtual

Benchmarking: dynamic_1507 [sha1(utf16($const.$p)) (Mcafee master pass) 256/256 AVX2 8x1]... DONE
Raw:	9898K c/s real, 9898K c/s virtual

Benchmarking: dynamic_1518 [md5(sha1($p).md5($p).sha1($p)) 256/256 AVX2 8x1]... DONE
Raw:	4814K c/s real, 4814K c/s virtual

Benchmarking: dynamic_1528 [sha256($s.$p.$s) (Telegram for Android) 256/256 AVX2 8x]... DONE
Many salts:	10063K c/s real, 10063K c/s virtual
Only one salt:	7936K c/s real, 7936K c/s virtual

Benchmarking: dynamic_1529 [sha1($p null_padded_to_len_32) (DeepSound) 256/256 AVX2 8x1]... DONE
Raw:	11424K c/s real, 11424K c/s virtual

Benchmarking: dynamic_1550 [md5($u.:mongo:.$p) (MONGODB-CR system hash) 256/256 AVX2 8x3]... DONE
Many salts:	21924K c/s real, 21924K c/s virtual
Only one salt:	13913K c/s real, 13913K c/s virtual

Benchmarking: dynamic_1551 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 256/256 AVX2 8x3]... DONE
Many salts:	12032K c/s real, 12032K c/s virtual
Only one salt:	8961K c/s real, 8961K c/s virtual

Benchmarking: dynamic_1552 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 256/256 AVX2 8x3]... DONE
Many salts:	7556K c/s real, 7556K c/s virtual
Only one salt:	6266K c/s real, 6266K c/s virtual

Benchmarking: dynamic_1560 [md5($s.$p.$s2) (SocialEngine) 256/256 AVX2 8x3]... DONE
Many salts:	13436K c/s real, 13436K c/s virtual
Only one salt:	9720K c/s real, 9720K c/s virtual

Benchmarking: dynamic_1588 [sha256($s.sha1($p)) (ColdFusion 11) 256/256 AVX2 8x]... DONE
Many salts:	5366K c/s real, 5419K c/s virtual
Only one salt:	4727K c/s real, 4727K c/s virtual

Benchmarking: dynamic_1590 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 256/256 AVX2 8x1]... DONE
Many salts:	15647K c/s real, 15647K c/s virtual
Only one salt:	10876K c/s real, 10768K c/s virtual

Benchmarking: dynamic_1592 [sha1($s.sha1($s.sha1($p))) (wbb3) 256/256 AVX2 8x1]... DONE
Many salts:	6304K c/s real, 6367K c/s virtual
Only one salt:	3978K c/s real, 3978K c/s virtual

Benchmarking: dynamic_1600 [sha1($s.utf16le($p)) (Oracle PeopleSoft PS_TOKEN) 256/256 AVX2 8x1]... DONE
Many salts:	9139K c/s real, 9139K c/s virtual
Only one salt:	6672K c/s real, 6672K c/s virtual

Benchmarking: dynamic_1602 [sha256(#.$salt.-.$pass) (QAS vas_auth) 256/256 AVX2 8x]... DONE
Many salts:	8067K c/s real, 8067K c/s virtual
Only one salt:	6659K c/s real, 6659K c/s virtual

Benchmarking: dynamic_1608 [sha256(sha256_raw(sha256_raw($p))) (Neo Wallet) 256/256 AVX2 8x]... DONE
Raw:	4146K c/s real, 4146K c/s virtual

Benchmarking: dynamic_2000 [md5($p) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:	21924K c/s real, 21924K c/s virtual

Benchmarking: dynamic_2001 [md5($p.$s) (joomla) (PW > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	20670K c/s real, 20670K c/s virtual
Only one salt:	13332K c/s real, 13332K c/s virtual

Benchmarking: dynamic_2002 [md5(md5($p)) (e107) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:	12542K c/s real, 12542K c/s virtual

Benchmarking: dynamic_2003 [md5(md5(md5($p))) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:	8806K c/s real, 8806K c/s virtual

Benchmarking: dynamic_2004 [md5($s.$p) (OSC) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	20744K c/s real, 20744K c/s virtual
Only one salt:	13251K c/s real, 13251K c/s virtual

Benchmarking: dynamic_2005 [md5($s.$p.$s) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	16292K c/s real, 16292K c/s virtual
Only one salt:	11266K c/s real, 11266K c/s virtual

Benchmarking: dynamic_2006 [md5(md5($p).$s) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	28059K c/s real, 28059K c/s virtual
Only one salt:	9078K c/s real, 9078K c/s virtual

Benchmarking: dynamic_2008 [md5(md5($s).$p) (PW > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	20462K c/s real, 20462K c/s virtual
Only one salt:	13292K c/s real, 13292K c/s virtual

Benchmarking: dynamic_2009 [md5($s.md5($p)) (salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	20546K c/s real, 20546K c/s virtual
Only one salt:	8077K c/s real, 8077K c/s virtual

Benchmarking: dynamic_2010 [md5($s.md5($s.$p)) (PW > 32 or salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	10459K c/s real, 10459K c/s virtual
Only one salt:	8282K c/s real, 8282K c/s virtual

Benchmarking: dynamic_2011 [md5($s.md5($p.$s)) (PW > 32 or salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	10570K c/s real, 10570K c/s virtual
Only one salt:	8245K c/s real, 8163K c/s virtual

Benchmarking: dynamic_2014 [md5($s.md5($p).$s) (PW > 55 or salt > 11 bytes) 256/256 AVX2 8x3]... DONE
Many salts:	16255K c/s real, 16255K c/s virtual
Only one salt:	7284K c/s real, 7284K c/s virtual

Benchmarking: dummy [N/A]... DONE
Raw:	52610K c/s real, 52610K c/s virtual

Benchmarking: crypt, generic crypt(3) [?/64]... (8xOMP) DONE
Speed for cost 1 (algorithm [1:descrypt 2:md5crypt 3:sunmd5 4:bcrypt 5:sha256crypt 6:sha512crypt]) of 1, cost 2 (algorithm specific iterations) of 1
Many salts:	469728 c/s real, 64523 c/s virtual
Only one salt:	241440 c/s real, 33767 c/s virtual

All 407 formats passed self-tests!
```

