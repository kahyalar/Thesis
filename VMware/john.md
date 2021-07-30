```shell
kali$ john --test
Will run 4 OpenMP threads
Benchmarking: descrypt, traditional crypt(3) [DES 128/128 AVX]... (4xOMP) DONE
Many salts:     9554K c/s real, 2594K c/s virtual
Only one salt:  9060K c/s real, 2270K c/s virtual

Benchmarking: bsdicrypt, BSDI crypt(3) ("_J9..", 725 iterations) [DES 128/128 AVX]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 725
Many salts:     369664 c/s real, 92185 c/s virtual
Only one salt:  384000 c/s real, 96482 c/s virtual

Benchmarking: md5crypt, crypt(3) $1$ (and variants) [MD5 128/128 AVX 4x3]... (4xOMP) DONE
Many salts:     83904 c/s real, 20923 c/s virtual
Only one salt:  84480 c/s real, 21120 c/s virtual

Benchmarking: md5crypt-long, crypt(3) $1$ (and variants) [MD5 32/64]... (4xOMP) DONE
Raw:    17647 c/s real, 4444 c/s virtual

Benchmarking: bcrypt ("$2a$05", 32 iterations) [Blowfish 32/64 X3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32
Raw:    2576 c/s real, 667 c/s virtual

Benchmarking: scrypt (16384, 8, 1) [Salsa20/8 128/128 AVX]... (4xOMP) DONE
Speed for cost 1 (N) of 16384, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    108 c/s real, 28.5 c/s virtual

Benchmarking: LM [DES 128/128 AVX]... (4xOMP) DONE
Raw:    59129K c/s real, 14819K c/s virtual

Benchmarking: AFS, Kerberos AFS [DES 48/64 4K]... DONE
Short:  411648 c/s real, 411648 c/s virtual
Long:   1694K c/s real, 1694K c/s virtual

Benchmarking: tripcode [DES 128/128 AVX]... (4xOMP) DONE
Raw:    8290K c/s real, 2072K c/s virtual

Benchmarking: AndroidBackup [PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1032 c/s real, 282 c/s virtual

Benchmarking: adxcrypt [IBM/Toshiba 4690 - ADXCRYPT 32/64]... (4xOMP) DONE
Raw:    56581K c/s real, 19774K c/s virtual

Benchmarking: agilekeychain, 1Password Agile Keychain [PBKDF2-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    19648 c/s real, 4924 c/s virtual

Benchmarking: aix-ssha1, AIX LPA {ssha1} [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     286336 c/s real, 71584 c/s virtual
Only one salt:  286592 c/s real, 71827 c/s virtual

Benchmarking: aix-ssha256, AIX LPA {ssha256} [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     129728 c/s real, 32513 c/s virtual
Only one salt:  131136 c/s real, 32784 c/s virtual

Benchmarking: aix-ssha512, AIX LPA {ssha512} [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     53280 c/s real, 13286 c/s virtual
Only one salt:  53920 c/s real, 13480 c/s virtual

Benchmarking: andOTP [SHA256 32/64]... (4xOMP) DONE
Raw:    523152 c/s real, 131438 c/s virtual

Benchmarking: ansible, Ansible Vault [PBKDF2-SHA256 HMAC-256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1077 c/s real, 320 c/s virtual

Benchmarking: argon2 [Blake2 AVX]... (4xOMP) DONE
Speed for cost 1 (t) of 3, cost 2 (m) of 4096, cost 3 (p) of 1, cost 4 (type [0:Argon2d 1:Argon2i]) of 0 and 1
Raw:    316 c/s real, 85.7 c/s virtual

Benchmarking: as400-des, AS/400 DES [DES 32/64]... DONE
Raw:    361400 c/s real, 90576 c/s virtual

Benchmarking: as400-ssha1, AS400-SaltedSHA1 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 128/128 AVX 4x1]... DONE
Many salts:     9389K c/s real, 9389K c/s virtual
Only one salt:  8072K c/s real, 7992K c/s virtual

Benchmarking: asa-md5, Cisco ASA [md5($p.$s) (Cisco ASA) 128/128 AVX 4x3]... DONE
Many salts:     18616K c/s real, 18616K c/s virtual
Only one salt:  13922K c/s real, 13922K c/s virtual

Benchmarking: AxCrypt [PBKDF2-SHA512/SHA1 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1337 and 60000
Raw:    403 c/s real, 107 c/s virtual

Benchmarking: AzureAD [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     84224 c/s real, 21108 c/s virtual
Only one salt:  87445 c/s real, 21970 c/s virtual

Benchmarking: BestCrypt (SHA-256 + AES XTS mode) [Jetico BestCrypt (.jbc) PKCS12 PBE (Whirlpool / SHA-1 to SHA-512) 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    280 c/s real, 79.5 c/s virtual

Benchmarking: bfegg, Eggdrop [Blowfish 32/64]... (4xOMP) DONE
Raw:    99358 c/s real, 25665 c/s virtual

Benchmarking: Bitcoin, Bitcoin Core [SHA512 AES 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 177864
Raw:    47.8 c/s real, 14.0 c/s virtual

Benchmarking: BitLocker, BitLocker [SHA-256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1048576
Raw:    4.9 c/s real, 1.4 c/s virtual

Benchmarking: bitshares, BitShares Wallet [SHA-512 64/64]... (4xOMP) DONE
Many salts:     2816K c/s real, 702244 c/s virtual
Only one salt:  2697K c/s real, 675993 c/s virtual

Benchmarking: Bitwarden, Bitwarden Password Manager [PBKDF2-SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    1932 c/s real, 553 c/s virtual

Benchmarking: BKS [PKCS12 PBE 128/128 AVX 4x]... (4xOMP) DONE
Raw:    22086 c/s real, 6704 c/s virtual

Benchmarking: Blackberry-ES10 (101x) [SHA-512 128/128 AVX 2x]... (4xOMP) DONE
Many salts:     72704 c/s real, 18221 c/s virtual
Only one salt:  72960 c/s real, 18194 c/s virtual

Benchmarking: WoWSRP, Battlenet [SHA1 32/64 GMP-exp]... (4xOMP) DONE
Warning: "Many salts" test limited: 234/256
Many salts:     239616 c/s real, 60662 c/s virtual
Only one salt:  261120 c/s real, 65773 c/s virtual

Benchmarking: Blockchain, My Wallet (v2 x5000) [PBKDF2-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Raw:    2226 c/s real, 640 c/s virtual

Benchmarking: chap, iSCSI CHAP authentication / EAP-MD5 [MD5 32/64]... (4xOMP) DONE
Many salts:     18038K c/s real, 4509K c/s virtual
Only one salt:  15499K c/s real, 3884K c/s virtual

Benchmarking: Clipperz, SRP [SHA256 32/64 GMP-exp]... (4xOMP) DONE
Raw:    103413 c/s real, 27271 c/s virtual

Benchmarking: cloudkeychain, 1Password Cloud Keychain [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 40000 and 50000
Raw:    80.7 c/s real, 25.2 c/s virtual

Benchmarking: dynamic=md5($p) [128/128 AVX 4x3]... DONE
Raw:    27555K c/s real, 27555K c/s virtual

Benchmarking: cq, ClearQuest [CQWeb]... (4xOMP) DONE
Many salts:     145752K c/s real, 36529K c/s virtual
Only one salt:  40501K c/s real, 10800K c/s virtual

Benchmarking: CRC32 [CRC32 32/64 CRC-32C AVX]... DONE
Speed for cost 1 (version [0:CRC-32 1:CRC-32C]) of 0
Many salts:     115343K c/s real, 115343K c/s virtual
Only one salt:  46489K c/s real, 46489K c/s virtual

Benchmarking: sha1crypt, NetBSD's sha1crypt [PBKDF1-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64000 and 40000
Raw:    487 c/s real, 152 c/s virtual

Benchmarking: sha256crypt, crypt(3) $5$ (rounds=5000) [SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    3011 c/s real, 872 c/s virtual

Benchmarking: sha512crypt, crypt(3) $6$ (rounds=5000) [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    1518 c/s real, 430 c/s virtual

Benchmarking: Citrix_NS10, Netscaler 10 [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     28114K c/s real, 7046K c/s virtual
Only one salt:  24592K c/s real, 6148K c/s virtual

Benchmarking: dahua, "MD5 based authentication" Dahua [MD5 32/64]... DONE
Raw:    5003K c/s real, 5003K c/s virtual

Benchmarking: dashlane, Dashlane Password Manager [AES PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    1122 c/s real, 350 c/s virtual

Benchmarking: diskcryptor, DiskCryptor [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    3485 c/s real, 914 c/s virtual

Benchmarking: Django (x10000) [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    900 c/s real, 242 c/s virtual

Benchmarking: django-scrypt [Salsa20/8 128/128 AVX]... (4xOMP) DONE
Speed for cost 1 (N) of 14, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    132 c/s real, 34.2 c/s virtual

Benchmarking: dmd5, DIGEST-MD5 C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     5652K c/s real, 1409K c/s virtual
Only one salt:  5382K c/s real, 1348K c/s virtual

Benchmarking: dmg, Apple DMG [PBKDF2-SHA1 128/128 AVX 4x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (version) of 2 and 1
Raw:    12128 c/s real, 3032 c/s virtual

Benchmarking: dominosec, Lotus Notes/Domino 6 More Secure Internet Password [8/64]... (4xOMP) DONE
Many salts:     1143K c/s real, 286604 c/s virtual
Only one salt:  764198 c/s real, 192000 c/s virtual

Benchmarking: dominosec8, Lotus Notes/Domino 8 [8/64]... (4xOMP) DONE
Raw:    1656 c/s real, 489 c/s virtual

Benchmarking: DPAPImk, DPAPI masterkey file v1 and v2 [SHA1/MD4 PBKDF2-(SHA1/SHA512)-DPAPI-variant 3DES/AES256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 24000
Raw:    426 c/s real, 130 c/s virtual

Benchmarking: dragonfly3-32, DragonFly BSD $3$ w/ bug, 32-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     7932K c/s real, 1983K c/s virtual
Only one salt:  7344K c/s real, 1840K c/s virtual

Benchmarking: dragonfly3-64, DragonFly BSD $3$ w/ bug, 64-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     7304K c/s real, 1826K c/s virtual
Only one salt:  6362K c/s real, 1590K c/s virtual

Benchmarking: dragonfly4-32, DragonFly BSD $4$ w/ bugs, 32-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     5225K c/s real, 1306K c/s virtual
Only one salt:  4618K c/s real, 1154K c/s virtual

Benchmarking: dragonfly4-64, DragonFly BSD $4$ w/ bugs, 64-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     5258K c/s real, 1321K c/s virtual
Only one salt:  4583K c/s real, 1142K c/s virtual

Benchmarking: Drupal7, $S$ (x16385) [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    467 c/s real, 136 c/s virtual

Benchmarking: eCryptfs (65536 iterations) [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Raw:    141 c/s real, 41.8 c/s virtual

Benchmarking: eigrp, EIGRP MD5 / HMAC-SHA-256 authentication [MD5/SHA-256 32/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [2:MD5 3:HMAC-SHA-256]) of 2
Many salts:     10184K c/s real, 2571K c/s virtual
Only one salt:  9228K c/s real, 2307K c/s virtual

Benchmarking: electrum, Electrum Wallet [SHA256 AES / PBKDF2-SHA512 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (kdf [1:SHA256 2:PBKDF2-SHA512]) of 1 and 2
Raw:    5259 c/s real, 1487 c/s virtual

Benchmarking: EncFS [PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 181474
Raw:    55.6 c/s real, 13.8 c/s virtual

Benchmarking: enpass, Enpass Password Manager [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    414 c/s real, 103 c/s virtual

Benchmarking: EPI, EPiServer SID [SHA1 32/64]... (4xOMP) DONE
Many salts:     14630K c/s real, 3657K c/s virtual
Only one salt:  10122K c/s real, 2549K c/s virtual

Benchmarking: EPiServer [SHA1/SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256]) of 1
Many salts:     27262K c/s real, 6832K c/s virtual
Only one salt:  25042K c/s real, 6292K c/s virtual

Benchmarking: ethereum, Ethereum Wallet [PBKDF2-SHA256/scrypt Keccak 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 262144 and 1024, cost 2 (kdf [0:PBKDF2-SHA256 1:scrypt 2:PBKDF2-SHA256 presale]) of 0
Warning: "Many salts" test limited: 6/256
Many salts:     82.0 c/s real, 23.8 c/s virtual
Only one salt:  39.6 c/s real, 11.7 c/s virtual

Benchmarking: fde, Android FDE [PBKDF2-SHA1 128/128 AVX 4x SHA256/AES]... (4xOMP) DONE
Raw:    5389 c/s real, 1647 c/s virtual

Benchmarking: Fortigate256, FortiOS256 [SHA256 32/64]... (4xOMP) DONE
Many salts:     7725K c/s real, 1936K c/s virtual
Only one salt:  6758K c/s real, 1689K c/s virtual

Benchmarking: Fortigate, FortiOS [SHA1 32/64]... (4xOMP) DONE
Many salts:     17149K c/s real, 4298K c/s virtual
Only one salt:  14237K c/s real, 3559K c/s virtual

Benchmarking: FormSpring [sha256($s.$p) 128/128 AVX 4x]... DONE
Many salts:     5419K c/s real, 5419K c/s virtual
Only one salt:  4898K c/s real, 4898K c/s virtual

Benchmarking: FVDE, FileVault 2 [PBKDF2-SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 41000 and 70400
Raw:    211 c/s real, 65.8 c/s virtual

Benchmarking: geli, FreeBSD GELI [PBKDF2-SHA512 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 256 and 512
Raw:    10164 c/s real, 2809 c/s virtual

Benchmarking: gost, GOST R 34.11-94 [64/64]... (4xOMP) DONE
Raw:    1619K c/s real, 408832 c/s virtual

Benchmarking: gpg, OpenPGP / GnuPG Secret Key [32/64]... (4xOMP) DONE
Speed for cost 1 (s2k-count) of 65536, cost 2 (hash algorithm [1:MD5 2:SHA1 3:RIPEMD160 8:SHA256 9:SHA384 10:SHA512 11:SHA224]) of 2, cost 3 (cipher algorithm [1:IDEA 2:3DES 3:CAST5 4:Blowfish 7:AES128 8:AES192 9:AES256 10:Twofish 11:Camellia128 12:Camellia192 13:Camellia256]) of 3
Raw:    18844 c/s real, 4711 c/s virtual

Benchmarking: HAVAL-128-4 [32/64]... DONE
Raw:    2607K c/s real, 2607K c/s virtual

Benchmarking: HAVAL-256-3 [32/64]... DONE
Raw:    3629K c/s real, 3629K c/s virtual

Benchmarking: hdaa, HTTP Digest access authentication [MD5 128/128 AVX 4x3]... DONE
Many salts:     5226K c/s real, 5226K c/s virtual
Only one salt:  5023K c/s real, 5023K c/s virtual

Benchmarking: hMailServer [sha256($s.$p) 128/128 AVX 4x]... DONE
Many salts:     5278K c/s real, 5226K c/s virtual
Only one salt:  4914K c/s real, 4914K c/s virtual

Benchmarking: hsrp, "MD5 authentication" HSRP, HSRPv2, VRRP, GLBP [MD5 32/64]... (4xOMP) DONE
Many salts:     10919K c/s real, 2729K c/s virtual
Only one salt:  6021K c/s real, 1509K c/s virtual

Benchmarking: IKE, PSK [HMAC MD5/SHA1 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1]) of 1 and 2
Raw:    1401K c/s real, 354004 c/s virtual

Benchmarking: ipb2, Invision Power Board 2.x [MD5 128/128 AVX 4x3]... (4xOMP) DONE
Many salts:     19046K c/s real, 4761K c/s virtual
Only one salt:  12926K c/s real, 3231K c/s virtual

Benchmarking: itunes-backup, Apple iTunes Backup [PBKDF2-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (version) of 9 and 10, cost 2 (iteration count) of 10000
Raw:    1046 c/s real, 313 c/s virtual

Benchmarking: iwork, Apple iWork '09 or newer [PBKDF2-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 100000
Raw:    237 c/s real, 72.5 c/s virtual

Benchmarking: KeePass [SHA256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 50000 and 6000, cost 2 (version) of 1 and 2, cost 3 (algorithm [0=AES, 1=TwoFish, 2=ChaCha]) of 0
Raw:    411 c/s real, 118 c/s virtual

Benchmarking: keychain, Mac OS X Keychain [PBKDF2-SHA1 3DES 128/128 AVX 4x]... (4xOMP) DONE
Raw:    10039 c/s real, 2925 c/s virtual

Benchmarking: keyring, GNOME Keyring [SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3221
Raw:    5688 c/s real, 1435 c/s virtual

Benchmarking: keystore, Java KeyStore [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Warning: "Many salts" test limited: 9/256
Many salts:     1167K c/s real, 328592 c/s virtual
Only one salt:  1145K c/s real, 304818 c/s virtual

Benchmarking: known_hosts, HashKnownHosts HMAC-SHA1 [SHA1 32/64]... (4xOMP) DONE
Many salts:     7020K c/s real, 1750K c/s virtual
Only one salt:  6144K c/s real, 1536K c/s virtual

Benchmarking: krb4, Kerberos v4 TGT [DES 32/64]... DONE
Short:  248719 c/s real, 248719 c/s virtual
Long:   675415 c/s real, 675415 c/s virtual

Benchmarking: krb5, Kerberos v5 TGT [3DES 32/64]... DONE
Raw:    63792 c/s real, 63792 c/s virtual

Benchmarking: krb5asrep, Kerberos 5 AS-REP etype 17/18/23 [MD4 HMAC-MD5 RC4 / PBKDF2 HMAC-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     1349K c/s real, 337280 c/s virtual
Only one salt:  1022K c/s real, 256256 c/s virtual

Benchmarking: krb5pa-sha1, Kerberos 5 AS-REQ Pre-Auth etype 17/18 [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    2818 c/s real, 800 c/s virtual

Benchmarking: krb5tgs, Kerberos 5 TGS etype 23 [MD4 HMAC-MD5 RC4]... (4xOMP) DONE
Many salts:     2371K c/s real, 594381 c/s virtual
Only one salt:  1543K c/s real, 386758 c/s virtual

Benchmarking: krb5-17, Kerberos 5 DB etype 17 [DES / PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Raw:    5649 c/s real, 1754 c/s virtual

Benchmarking: krb5-18, Kerberos 5 DB etype 18 [DES / PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Raw:    3103 c/s real, 908 c/s virtual

Benchmarking: krb5-3, Kerberos 5 DB etype 3 [DES / PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Many salts:     3362K c/s real, 842811 c/s virtual
Only one salt:  2924K c/s real, 731136 c/s virtual

Benchmarking: kwallet, KDE KWallet [SHA1 / PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Raw:    7040 c/s real, 1887 c/s virtual

Benchmarking: lp, LastPass offline [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 86/256
Many salts:     22016 c/s real, 6236 c/s virtual
Only one salt:  19074 c/s real, 5258 c/s virtual

Benchmarking: lpcli, LastPass CLI [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1234
Many salts:     7488 c/s real, 1876 c/s virtual
Only one salt:  7344 c/s real, 1836 c/s virtual

Benchmarking: leet [SHA-512(128/128 AVX 2x) + Whirlpool(OpenSSL/64)]... (4xOMP) DONE
Warning: "Many salts" test limited: 36/256
Many salts:     2335K c/s real, 614400 c/s virtual
Only one salt:  2226K c/s real, 583653 c/s virtual

Benchmarking: lotus5, Lotus Notes/Domino 5 [8/64 X3]... (4xOMP) DONE
Raw:    1830K c/s real, 457728 c/s virtual

Benchmarking: lotus85, Lotus Notes/Domino 8.5 [8/64]... (4xOMP) DONE
Many salts:     392704 c/s real, 98422 c/s virtual
Only one salt:  399872 c/s real, 99968 c/s virtual

Benchmarking: LUKS [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    62.1 c/s real, 19.8 c/s virtual

Benchmarking: MD2 [MD2 32/64]... (4xOMP) DONE
Raw:    640256 c/s real, 160064 c/s virtual

Benchmarking: mdc2, MDC-2 [MDC-2DES]... (4xOMP) DONE
Raw:    3964K c/s real, 993716 c/s virtual

Benchmarking: MediaWiki [md5($s.md5($p)) 128/128 AVX 4x3]... DONE
Many salts:     22560K c/s real, 22560K c/s virtual
Only one salt:  9221K c/s real, 9221K c/s virtual

Benchmarking: monero, monero Wallet [Pseudo-AES / ChaCha / Various 32/64]... (4xOMP) DONE
Raw:    9.3 c/s real, 2.6 c/s virtual

Benchmarking: money, Microsoft Money (2002 to Money Plus) [MD5/SHA1 32/64]... (4xOMP) DONE
Many salts:     3710K c/s real, 936960 c/s virtual
Only one salt:  3399K c/s real, 849920 c/s virtual

Benchmarking: MongoDB, system / network [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (salt type) of 0 and 1
Raw:    9700K c/s real, 2437K c/s virtual

Benchmarking: scram [SCRAM PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    3011 c/s real, 919 c/s virtual

Benchmarking: Mozilla, Mozilla key3.db [SHA1 3DES 32/64]... (4xOMP) DONE
Many salts:     1137K c/s real, 285128 c/s virtual
Only one salt:  1076K c/s real, 269056 c/s virtual

Benchmarking: mscash, MS Cache Hash (DCC) [MD4 32/64]... (4xOMP) DONE
Many salts:     62603K c/s real, 15729K c/s virtual
Only one salt:  22286K c/s real, 5585K c/s virtual

Benchmarking: mscash2, MS Cache Hash 2 (DCC2) [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    2154 c/s real, 627 c/s virtual

Benchmarking: MSCHAPv2, C/R [MD4 DES (ESS MD5) 128/128 AVX 4x3]... DONE
Many salts:     7105M c/s real, 7105M c/s virtual
Only one salt:  35901K c/s real, 35901K c/s virtual

Benchmarking: mschapv2-naive, MSCHAPv2 C/R [MD4 DES 128/128 AVX naive]... (4xOMP) DONE
Many salts:     190464K c/s real, 47735K c/s virtual
Only one salt:  14204K c/s real, 3560K c/s virtual

Benchmarking: krb5pa-md5, Kerberos 5 AS-REQ Pre-Auth etype 23 [32/64]... (4xOMP) DONE
Many salts:     3224K c/s real, 808228 c/s virtual
Only one salt:  1700K c/s real, 425088 c/s virtual

Benchmarking: mssql, MS SQL [SHA1 128/128 AVX 4x]... DONE
Many salts:     18042K c/s real, 18042K c/s virtual
Only one salt:  10853K c/s real, 10853K c/s virtual

Benchmarking: mssql05, MS SQL 2005 [SHA1 128/128 AVX 4x]... DONE
Many salts:     17969K c/s real, 17969K c/s virtual
Only one salt:  15189K c/s real, 15189K c/s virtual

Benchmarking: mssql12, MS SQL 2012/2014 [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Many salts:     7131K c/s real, 1782K c/s virtual
Only one salt:  6072K c/s real, 1521K c/s virtual

Benchmarking: multibit, MultiBit Wallet [MD5/scrypt AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3, cost 2 (kdf [1:MD5 2:scrypt hd 3:scrypt classic]) of 1
Many salts:     2270K c/s real, 568946 c/s virtual
Only one salt:  2297K c/s real, 574312 c/s virtual

Benchmarking: mysqlna, MySQL Network Authentication [SHA1 32/64]... (4xOMP) DONE
Many salts:     4737K c/s real, 1187K c/s virtual
Only one salt:  4427K c/s real, 1106K c/s virtual

Benchmarking: mysql-sha1, MySQL 4.1+ [SHA1 128/128 AVX 4x]... DONE
Raw:    8776K c/s real, 8776K c/s virtual

Benchmarking: mysql, MySQL pre-4.1 [32/64]... DONE
Raw:    49064K c/s real, 49064K c/s virtual

Benchmarking: net-ah, IPsec AH HMAC-MD5-96 [MD5 32/64]... (4xOMP) DONE
Many salts:     4276K c/s real, 1074K c/s virtual
Only one salt:  4206K c/s real, 1051K c/s virtual

Benchmarking: nethalflm, HalfLM C/R [DES 32/64]... (4xOMP) DONE
Many salts:     9584K c/s real, 2408K c/s virtual
Only one salt:  2113K c/s real, 648323 c/s virtual

Benchmarking: netlm, LM C/R [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 20/256
Many salts:     10082K c/s real, 2774K c/s virtual
Only one salt:  1416K c/s real, 1034K c/s virtual

Benchmarking: netlmv2, LMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     2950K c/s real, 739512 c/s virtual
Only one salt:  2176K c/s real, 544128 c/s virtual

Benchmarking: net-md5, "Keyed MD5" RIPv2, OSPF, BGP, SNMPv2 [MD5 32/64]... (4xOMP) DONE
Many salts:     7887K c/s real, 7887K c/s virtual
Only one salt:  6711K c/s real, 6711K c/s virtual

Benchmarking: netntlmv2, NTLMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     3262K c/s real, 817660 c/s virtual
Only one salt:  2529K c/s real, 633904 c/s virtual

Benchmarking: netntlm, NTLMv1 C/R [MD4 DES (ESS MD5) 128/128 AVX 4x3]... DONE
Many salts:     7231M c/s real, 7231M c/s virtual
Only one salt:  36320K c/s real, 36320K c/s virtual

Benchmarking: netntlm-naive, NTLMv1 C/R [MD4 DES (ESS MD5) DES 128/128 AVX naive]... (4xOMP) DONE
Many salts:     174309K c/s real, 43686K c/s virtual
Only one salt:  14860K c/s real, 3715K c/s virtual

Benchmarking: net-sha1, "Keyed SHA1" BFD [SHA1 32/64]... (4xOMP) DONE
Many salts:     8218K c/s real, 8218K c/s virtual
Only one salt:  6928K c/s real, 6928K c/s virtual

Benchmarking: nk, Nuked-Klan CMS [SHA1 MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 39/256
Many salts:     5061K c/s real, 1297K c/s virtual
Only one salt:  5268K c/s real, 1492K c/s virtual

Benchmarking: notes, Apple Notes [PBKDF2-SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 20000
Raw:    483 c/s real, 144 c/s virtual

Benchmarking: md5ns, Netscreen [md5($s.$p) (OSC) (PW > 31 bytes) 128/128 AVX 4x3]... DONE
Many salts:     15099K c/s real, 15099K c/s virtual
Only one salt:  11684K c/s real, 11684K c/s virtual

Benchmarking: nsec3, DNSSEC NSEC3 [32/64]... DONE
Raw:    65659 c/s real, 65659 c/s virtual

Benchmarking: NT [MD4 128/128 AVX 4x3]... DONE
Raw:    39055K c/s real, 39055K c/s virtual

Benchmarking: o10glogon, Oracle 10g-logon protocol [DES-AES128-MD5 32/64]... (4xOMP) DONE
Many salts:     1018K c/s real, 257292 c/s virtual
Only one salt:  1011K c/s real, 256000 c/s virtual

Benchmarking: o3logon, Oracle O3LOGON protocol [SHA1 DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 18/256
Many salts:     589824 c/s real, 148196 c/s virtual
Only one salt:  551540 c/s real, 140670 c/s virtual

Benchmarking: o5logon, Oracle O5LOGON protocol [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     4079K c/s real, 1099K c/s virtual
Only one salt:  4513K c/s real, 1125K c/s virtual

Benchmarking: ODF, OpenDocument Star/Libre/OpenOffice [PBKDF2-SHA1 128/128 AVX 4x BF/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1024, cost 2 (crypto [0=Blowfish, 1=AES]) of 0 and 1
Raw:    11664 c/s real, 2916 c/s virtual

Benchmarking: Office, 2007/2010/2013 [SHA1 128/128 AVX 4x / SHA512 128/128 AVX 2x AES]... (4xOMP) DONE
Speed for cost 1 (MS Office version) of 2007, cost 2 (iteration count) of 50000
Raw:    831 c/s real, 213 c/s virtual

Benchmarking: oldoffice, MS Office <= 2003 [MD5/SHA1 RC4 32/64]... (4xOMP) DONE
Speed for cost 1 (hash type) of 1 and 0
Many salts:     1628K c/s real, 409085 c/s virtual
Only one salt:  1525K c/s real, 383356 c/s virtual

Benchmarking: OpenBSD-SoftRAID [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (kdf) of 1, cost 2 (iteration count) of 8192
Raw:    1314 c/s real, 356 c/s virtual

Benchmarking: openssl-enc, OpenSSL "enc" encryption (AES-128, MD5) [32/64]... (4xOMP) DONE
Many salts:     3906K c/s real, 978959 c/s virtual
Only one salt:  3621K c/s real, 912314 c/s virtual

Benchmarking: oracle, Oracle 10 [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 148/256
Many salts:     2400K c/s real, 638113 c/s virtual
Only one salt:  2031K c/s real, 507904 c/s virtual

Benchmarking: oracle11, Oracle 11g [SHA1 128/128 AVX 4x]... DONE
Many salts:     17360K c/s real, 17360K c/s virtual
Only one salt:  13140K c/s real, 13140K c/s virtual

Benchmarking: Oracle12C [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Raw:    869 c/s real, 253 c/s virtual

Benchmarking: osc, osCommerce [md5($s.$p) (OSC) 128/128 AVX 4x3]... DONE
Many salts:     19136K c/s real, 19136K c/s virtual
Only one salt:  14390K c/s real, 14390K c/s virtual

Benchmarking: ospf, OSPF / IS-IS [HMAC-SHA-X 32/64]... (4xOMP) DONE
Raw:    2822K c/s real, 752194 c/s virtual

Benchmarking: Padlock [PBKDF2-SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1003 c/s real, 287 c/s virtual

Benchmarking: Palshop, MD5(Palshop) [MD5 + SHA1 32/64]... (4xOMP) DONE
Raw:    5061K c/s real, 1366K c/s virtual

Benchmarking: Panama [Panama 32/64]... (4xOMP) DONE
Raw:    2506K c/s real, 629837 c/s virtual

Benchmarking: PBKDF2-HMAC-MD4 [PBKDF2-MD4 128/128 AVX 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    67938 c/s real, 19464 c/s virtual

Benchmarking: PBKDF2-HMAC-MD5 [PBKDF2-MD5 128/128 AVX 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    43008 c/s real, 11141 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA1 [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    22685 c/s real, 5905 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA256 [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    9035 c/s real, 2545 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA512, GRUB2 / OS X 10.8+ [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    3600 c/s real, 900 c/s virtual

Benchmarking: PDF [MD5 SHA2 RC4/AES 32/64]... (4xOMP) DONE
Speed for cost 1 (revision) of 4
Raw:    147072 c/s real, 37233 c/s virtual

Benchmarking: PEM, PKCS#8 private key (RSA/DSA/ECDSA) [PBKDF2-SHA1 128/128 AVX 4x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4096, cost 2 (cipher [1=3DES, 2/3/4=AES-128/192/256]) of 1
Raw:    4768 c/s real, 1401 c/s virtual

Benchmarking: pfx [PKCS12 PBE (.pfx, .p12) (SHA-1 to SHA-512) 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048, cost 2 (mac-type [1:SHA1 224:SHA224 256:SHA256 384:SHA384 512:SHA512]) of 1
Raw:    21082 c/s real, 5614 c/s virtual

Benchmarking: pgpdisk [PGP Disk / Virtual Disk SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000, cost 2 (algorithm [3=CAST, 4=TwoFish, 5/6/7=AES]) of 5
Raw:    1540 c/s real, 460 c/s virtual

Benchmarking: pgpsda [PGP SDA SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000
Raw:    4562 c/s real, 1404 c/s virtual

Benchmarking: pgpwde [PGP WDE S2K-SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 131072
Raw:    3548 c/s real, 1026 c/s virtual

Benchmarking: phpass ($P$9) [phpass ($P$ or $H$) 128/128 AVX 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Warning: "Many salts" test limited: 239/256
Many salts:     45888 c/s real, 11617 c/s virtual
Only one salt:  46656 c/s real, 11722 c/s virtual

Benchmarking: PHPS [md5(md5($p).$s) 128/128 AVX 4x3]... DONE
Many salts:     27582K c/s real, 27582K c/s virtual
Only one salt:  9399K c/s real, 9399K c/s virtual

Benchmarking: PHPS2 [md5(md5($p).$s) 128/128 AVX 4x3]... DONE
Many salts:     28082K c/s real, 28082K c/s virtual
Only one salt:  9340K c/s real, 9340K c/s virtual

Benchmarking: pix-md5, Cisco PIX [md5($p) (Cisco PIX) 128/128 AVX 4x3]... DONE
Raw:    16237K c/s real, 16237K c/s virtual

Benchmarking: PKZIP [32/64]... (4xOMP) DONE
Many salts:     32612K c/s real, 8235K c/s virtual
Only one salt:  17891K c/s real, 4461K c/s virtual

Benchmarking: po, Post.Office [MD5 32/64]... DONE
Many salts:     3511K c/s real, 3511K c/s virtual
Only one salt:  3357K c/s real, 3357K c/s virtual

Benchmarking: postgres, PostgreSQL C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     7933K c/s real, 1993K c/s virtual
Only one salt:  7333K c/s real, 1833K c/s virtual

Benchmarking: PST, custom CRC-32 [32/64]... DONE
Raw:    55177K c/s real, 55177K c/s virtual

Benchmarking: PuTTY, Private Key (RSA/DSA/ECDSA/ED25519) [SHA1/AES 32/64]... (4xOMP) DONE
Raw:    636271 c/s real, 172463 c/s virtual

Benchmarking: pwsafe, Password Safe [SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    10413 c/s real, 3118 c/s virtual

Benchmarking: qnx, qnx hash (rounds=1000) [QNX 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (algorithm [5:MD5 256:SHA256 512:SHA512]) of 5
Raw:    125718 c/s real, 35868 c/s virtual

Benchmarking: RACF [DES 32/64]... (4xOMP) DONE
Many salts:     23883K c/s real, 6077K c/s virtual
Only one salt:  7782K c/s real, 1955K c/s virtual

Benchmarking: RACF-KDFAES [KDFAES (DES + HMAC-SHA256/64 + AES-256)]... (4xOMP) DONE
Warning: "Many salts" test limited: 2/256
Many salts:     0.4 c/s real, 0.1 c/s virtual
Only one salt:  0.2 c/s real, 0.0 c/s virtual

Benchmarking: radius, RADIUS authentication [MD5 32/64]... (4xOMP) DONE
Many salts:     16445K c/s real, 4121K c/s virtual
Only one salt:  11767K c/s real, 2949K c/s virtual

Benchmarking: RAdmin, v2.x [MD5 32/64]... (4xOMP) DONE
Raw:    9619K c/s real, 3093K c/s virtual

Benchmarking: RAKP, IPMI 2.0 RAKP (RMCP+) [HMAC-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Warning: "Many salts" test limited: 203/256
Many salts:     13303K c/s real, 3446K c/s virtual
Only one salt:  5645K c/s real, 1672K c/s virtual

Benchmarking: rar, RAR3 (length 5) [SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Raw:    172 c/s real, 51.0 c/s virtual

Benchmarking: RAR5 [PBKDF2-SHA256 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32768
Raw:    280 c/s real, 75.6 c/s virtual

Benchmarking: Raw-SHA512 [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Raw:    6469K c/s real, 1621K c/s virtual

Benchmarking: Raw-Blake2 [BLAKE2b 512 128/128 AVX]... (4xOMP) DONE
Raw:    8305K c/s real, 2231K c/s virtual

Benchmarking: Raw-Keccak [Keccak 512 32/64]... (4xOMP) DONE
Raw:    2955K c/s real, 793330 c/s virtual

Benchmarking: Raw-Keccak-256 [Keccak 256 32/64]... (4xOMP) DONE
Raw:    3260K c/s real, 842484 c/s virtual

Benchmarking: Raw-MD4 [MD4 128/128 AVX 4x3]... DONE
Raw:    42389K c/s real, 42389K c/s virtual

Benchmarking: Raw-MD5 [MD5 128/128 AVX 4x3]... DONE
Raw:    31906K c/s real, 31906K c/s virtual

Benchmarking: Raw-MD5u [md5(utf16($p)) 128/128 AVX 4x3]... DONE
Raw:    29947K c/s real, 29947K c/s virtual

Benchmarking: Raw-SHA1 [SHA1 128/128 AVX 4x]... DONE
Raw:    16414K c/s real, 16414K c/s virtual

Benchmarking: Raw-SHA1-AxCrypt [SHA1 128/128 AVX 4x]... DONE
Raw:    16699K c/s real, 16699K c/s virtual

Benchmarking: Raw-SHA1-Linkedin [SHA1 128/128 AVX 4x]... DONE
Raw:    16379K c/s real, 16379K c/s virtual

Benchmarking: Raw-SHA224 [SHA224 128/128 AVX 4x]... (4xOMP) DONE
Raw:    14557K c/s real, 3648K c/s virtual

Benchmarking: Raw-SHA256 [SHA256 128/128 AVX 4x]... (4xOMP) DONE
Raw:    13369K c/s real, 3350K c/s virtual

Benchmarking: Raw-SHA3 [SHA3 512 32/64]... (4xOMP) DONE
Raw:    2790K c/s real, 735782 c/s virtual

Benchmarking: Raw-SHA384 [SHA384 128/128 AVX 2x]... (4xOMP) DONE
Raw:    7567K c/s real, 1910K c/s virtual

Benchmarking: ripemd-128, RIPEMD 128 [32/64]... DONE
Raw:    5535K c/s real, 5535K c/s virtual

Benchmarking: ripemd-160, RIPEMD 160 [32/64]... DONE
Raw:    3514K c/s real, 3514K c/s virtual

Benchmarking: rsvp, HMAC-MD5 / HMAC-SHA1, RSVP, IS-IS, OMAPI, RNDC, TSIG [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1 3:SHA224 4:SHA256 5:SHA384 6:SHA512]) of 1 and 2
Many salts:     4501K c/s real, 1136K c/s virtual
Only one salt:  3297K c/s real, 824320 c/s virtual

Benchmarking: Siemens-S7 [HMAC-SHA1 32/64]... (4xOMP) DONE
Many salts:     8773K c/s real, 2198K c/s virtual
Only one salt:  3306K c/s real, 824562 c/s virtual

Benchmarking: Salted-SHA1 [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     33652K c/s real, 8455K c/s virtual
Only one salt:  24231K c/s real, 6057K c/s virtual

Benchmarking: SSHA512, LDAP [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Many salts:     8175K c/s real, 2069K c/s virtual
Only one salt:  7634K c/s real, 1913K c/s virtual

Benchmarking: sapb, SAP CODVN B (BCODE) [MD5 128/128 AVX 4x3]... (4xOMP) DONE
Many salts:     17940K c/s real, 4485K c/s virtual
Only one salt:  14917K c/s real, 3729K c/s virtual

Benchmarking: sapg, SAP CODVN F/G (PASSCODE) [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     10588K c/s real, 2653K c/s virtual
Only one salt:  8478K c/s real, 2124K c/s virtual

Benchmarking: saph, SAP CODVN H (PWDSALTEDHASH) (SHA1x1024) [SHA-1/SHA-2 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256 3:SHA384 4:SHA512]) of 1, cost 2 (iteration count) of 1024
Warning: "Many salts" test limited: 159/256
Many salts:     40704 c/s real, 10655 c/s virtual
Only one salt:  43849 c/s real, 11593 c/s virtual

Benchmarking: sappse [PKCS12 PBE SHA1 128/128 AVX 4x 3DES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    6716 c/s real, 1721 c/s virtual

Benchmarking: securezip, PKWARE SecureZIP [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     1224K c/s real, 306943 c/s virtual
Only one salt:  1135K c/s real, 286004 c/s virtual

Benchmarking: 7z, 7-Zip (512K iterations) [SHA256 128/128 AVX 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 524288, cost 2 (padding size) of 4 and 9, cost 3 (compression type) of 128 and 1
Many salts:     11815 c/s real, 3375 c/s virtual
Only one salt:  60.3 c/s real, 16.4 c/s virtual

Benchmarking: Signal [Signal Android PKCS12 PBE SHA-1 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 6024 and 6097
Raw:    2456 c/s real, 617 c/s virtual

Benchmarking: SIP [MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 58/256
Many salts:     7602K c/s real, 1995K c/s virtual
Only one salt:  7067K c/s real, 1887K c/s virtual

Benchmarking: skein-256, Skein 256 [Skein 32/64]... (4xOMP) DONE
Raw:    6105K c/s real, 1530K c/s virtual

Benchmarking: skein-512, Skein 512 [Skein 32/64]... (4xOMP) DONE
Raw:    6047K c/s real, 1511K c/s virtual

Benchmarking: skey, S/Key [MD4/MD5/SHA1/RMD160 32/64]... DONE
Speed for cost 1 (hash type [1:MD4 2:MD5 3:SHA1 4:RMD160]) of 1 and 2, cost 2 (iteration count) of 96 and 99
Raw:    76193 c/s real, 76193 c/s virtual

Benchmarking: SL3, Nokia operator unlock [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     45711K c/s real, 11427K c/s virtual
Only one salt:  21528K c/s real, 5368K c/s virtual

Benchmarking: Snefru-128 [32/64]... (4xOMP) DONE
Raw:    1323K c/s real, 329927 c/s virtual

Benchmarking: Snefru-256 [32/64]... (4xOMP) DONE
Raw:    1335K c/s real, 333824 c/s virtual

Benchmarking: LastPass, sniffed sessions [PBKDF2-SHA256 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 35/256
Many salts:     17920 c/s real, 5033 c/s virtual
Only one salt:  17568 c/s real, 4402 c/s virtual

Benchmarking: SNMP, SNMPv3 USM [HMAC-MD5-96/HMAC-SHA1-96 32/64]... (4xOMP) DONE
Raw:    672 c/s real, 177 c/s virtual

Benchmarking: solarwinds, SolarWinds Orion [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    439 c/s real, 131 c/s virtual

Benchmarking: SSH [RSA/DSA/EC/OPENSSH (SSH private keys) 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF/cipher [0=MD5/AES 1=MD5/3DES 2=Bcrypt/AES]) of 0 and 1, cost 2 (iteration count) of 1 and 2
Raw:    1938K c/s real, 484552 c/s virtual

Benchmarking: sspr, NetIQ SSPR / Adobe AEM [MD5/SHA1/SHA256/SHA512 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF [0:MD5 1:SHA1 2:SHA1_SALT 3:SHA256_SALT 4:SHA512_SALT]) of 1, cost 2 (iteration count) of 100000
Raw:    164 c/s real, 46.0 c/s virtual

Benchmarking: Stribog-256 [GOST R 34.11-2012 128/128 AVX 1x]... (4xOMP) DONE
Raw:    1265K c/s real, 316416 c/s virtual

Benchmarking: Stribog-512 [GOST R 34.11-2012 128/128 AVX 1x]... (4xOMP) DONE
Raw:    903168 c/s real, 225792 c/s virtual

Benchmarking: STRIP, Password Manager [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    3295 c/s real, 1014 c/s virtual

Benchmarking: SunMD5 [MD5 128/128 AVX 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    1324 c/s real, 374 c/s virtual

Benchmarking: SybaseASE, Sybase ASE [SHA256 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     10321K c/s real, 2574K c/s virtual
Only one salt:  2392K c/s real, 599514 c/s virtual

Benchmarking: Sybase-PROP [salted FEAL-8 32/64]... (4xOMP) DONE
Many salts:     2372K c/s real, 594638 c/s virtual
Only one salt:  2425K c/s real, 606336 c/s virtual

Benchmarking: tacacs-plus, TACACS+ [MD5 32/64]... (4xOMP) DONE
Many salts:     22706K c/s real, 5705K c/s virtual
Only one salt:  17221K c/s real, 4316K c/s virtual

Benchmarking: tcp-md5, TCP MD5 Signatures, BGP, MSDP [MD5 32/64]... (4xOMP) DONE
Many salts:     20987K c/s real, 5260K c/s virtual
Only one salt:  14098K c/s real, 3533K c/s virtual

Benchmarking: telegram [PBKDF2-SHA1 128/128 AVX 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4000
Raw:    777 c/s real, 226 c/s virtual

Benchmarking: tezos, Tezos Key [PBKDF2-SHA512 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    1694 c/s real, 458 c/s virtual

Benchmarking: Tiger [Tiger 32/64]... (4xOMP) DONE
Raw:    13402K c/s real, 3358K c/s virtual

Benchmarking: tc_aes_xts, TrueCrypt AES256_XTS [SHA512/RIPEMD160/WHIRLPOOL 128/128 AVX 2x]... (4xOMP) DONE
Speed for cost 1 (hash algorithm [1:SHA512 2:RIPEMD160 3:Whirlpool]) of 1
Raw:    3976 c/s real, 1204 c/s virtual

Benchmarking: tc_ripemd160, TrueCrypt AES256_XTS [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    698 c/s real, 198 c/s virtual

Benchmarking: tc_ripemd160boot, TrueCrypt AES/Twofish/Serpent [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    1706 c/s real, 490 c/s virtual

Benchmarking: tc_sha512, TrueCrypt AES256_XTS [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Raw:    3584 c/s real, 1076 c/s virtual

Benchmarking: tc_whirlpool, TrueCrypt AES256_XTS [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    1103 c/s real, 338 c/s virtual

Benchmarking: vdi, VirtualBox-VDI AES_XTS [PBKDF2-SHA256 128/128 AVX 4x + AES_XTS]... (4xOMP) DONE
Raw:    1692 c/s real, 501 c/s virtual

Benchmarking: OpenVMS, Purdy [32/64]... (4xOMP) DONE
Many salts:     3132K c/s real, 785066 c/s virtual
Only one salt:  3019K c/s real, 754944 c/s virtual

Benchmarking: vmx, VMware VMX [PBKDF2-SHA1 AES 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    982 c/s real, 259 c/s virtual

Benchmarking: VNC [DES 32/64]... (4xOMP) DONE
Many salts:     9568K c/s real, 2392K c/s virtual
Only one salt:  7897K c/s real, 1974K c/s virtual

Benchmarking: vtp, "MD5 based authentication" VTP [MD5 32/64]... (4xOMP) DONE
Many salts:     2191K c/s real, 573654 c/s virtual
Only one salt:  18962 c/s real, 5184 c/s virtual

Benchmarking: wbb3, WoltLab BB3 [SHA1 32/64]... (4xOMP) DONE
Many salts:     3575K c/s real, 896192 c/s virtual
Only one salt:  2744K c/s real, 686080 c/s virtual

Benchmarking: whirlpool [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    4251K c/s real, 1062K c/s virtual

Benchmarking: whirlpool0 [WHIRLPOOL-0 32/64]... (4xOMP) DONE
Raw:    4144K c/s real, 1043K c/s virtual

Benchmarking: whirlpool1 [WHIRLPOOL-1 32/64]... (4xOMP) DONE
Raw:    4196K c/s real, 1051K c/s virtual

Benchmarking: wpapsk, WPA/WPA2/PMF/PMKID PSK [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 2
Raw:    2598 c/s real, 769 c/s virtual

Benchmarking: wpapsk-pmk, WPA/WPA2/PMF/PMKID master key [MD5/SHA-1/SHA-2]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 1 and 2
Many salts:     1608K c/s real, 402176 c/s virtual
Only one salt:  1703K c/s real, 425984 c/s virtual

Benchmarking: xmpp-scram [XMPP SCRAM PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    5796 c/s real, 1796 c/s virtual

Benchmarking: xsha, Mac OS X 10.4 - 10.6 [SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     35962K c/s real, 8990K c/s virtual
Only one salt:  21839K c/s real, 5473K c/s virtual

Benchmarking: xsha512, Mac OS X 10.7 [SHA512 128/128 AVX 2x]... (4xOMP) DONE
Warning: "Many salts" test limited: 232/256
Many salts:     7526K c/s real, 1919K c/s virtual
Only one salt:  6160K c/s real, 1575K c/s virtual

Benchmarking: ZIP, WinZip [PBKDF2-SHA1 128/128 AVX 4x]... (4xOMP) DONE
Raw:    22140 c/s real, 6788 c/s virtual

Benchmarking: ZipMonster, MD5(ZipMonster) [MD5-128/128 AVX 4x3 x 50000]... (4xOMP) DONE
Raw:    1556 c/s real, 438 c/s virtual

Benchmarking: plaintext, $0$ [n/a]... DONE
Raw:    83800K c/s real, 83800K c/s virtual

Benchmarking: has-160 [HAS-160 32/64]... DONE
Raw:    7121K c/s real, 7121K c/s virtual

Benchmarking: HMAC-MD5 [password is key, MD5 128/128 AVX 4x3]... (4xOMP) DONE
Many salts:     43659K c/s real, 10942K c/s virtual
Only one salt:  12238K c/s real, 3059K c/s virtual

Benchmarking: HMAC-SHA1 [password is key, SHA1 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     18874K c/s real, 4754K c/s virtual
Only one salt:  6684K c/s real, 1943K c/s virtual

Benchmarking: HMAC-SHA224 [password is key, SHA224 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     8880K c/s real, 2220K c/s virtual
Only one salt:  4292K c/s real, 1092K c/s virtual

Benchmarking: HMAC-SHA256 [password is key, SHA256 128/128 AVX 4x]... (4xOMP) DONE
Many salts:     11640K c/s real, 2910K c/s virtual
Only one salt:  5021K c/s real, 1252K c/s virtual

Benchmarking: HMAC-SHA384 [password is key, SHA384 128/128 AVX 2x]... (4xOMP) DONE
Many salts:     4457K c/s real, 1120K c/s virtual
Only one salt:  2158K c/s real, 541064 c/s virtual

Benchmarking: HMAC-SHA512 [password is key, SHA512 128/128 AVX 2x]... (4xOMP) DONE
Many salts:     4234K c/s real, 1066K c/s virtual
Only one salt:  2121K c/s real, 530496 c/s virtual

Benchmarking: dynamic_0 [md5($p) (raw-md5) 128/128 AVX 4x3]... DONE
Raw:    27239K c/s real, 27239K c/s virtual

Benchmarking: dynamic_1 [md5($p.$s) (joomla) 128/128 AVX 4x3]... DONE
Many salts:     18333K c/s real, 18333K c/s virtual
Only one salt:  13703K c/s real, 13703K c/s virtual

Benchmarking: dynamic_2 [md5(md5($p)) (e107) 128/128 AVX 4x3]... DONE
Raw:    14847K c/s real, 14847K c/s virtual

Benchmarking: dynamic_3 [md5(md5(md5($p))) 128/128 AVX 4x3]... DONE
Raw:    9945K c/s real, 9945K c/s virtual

Benchmarking: dynamic_4 [md5($s.$p) (OSC) 128/128 AVX 4x3]... DONE
Many salts:     20368K c/s real, 20368K c/s virtual
Only one salt:  14071K c/s real, 14071K c/s virtual

Benchmarking: dynamic_5 [md5($s.$p.$s) 128/128 AVX 4x3]... DONE
Many salts:     15709K c/s real, 15709K c/s virtual
Only one salt:  11056K c/s real, 11056K c/s virtual

Benchmarking: dynamic_6 [md5(md5($p).$s) 128/128 AVX 4x3]... DONE
Many salts:     26216K c/s real, 26216K c/s virtual
Only one salt:  9240K c/s real, 9240K c/s virtual

Benchmarking: dynamic_8 [md5(md5($s).$p) 128/128 AVX 4x3]... DONE
Many salts:     21319K c/s real, 21319K c/s virtual
Only one salt:  15298K c/s real, 15298K c/s virtual

Benchmarking: dynamic_9 [md5($s.md5($p)) 128/128 AVX 4x3]... DONE
Many salts:     20492K c/s real, 20492K c/s virtual
Only one salt:  9434K c/s real, 9434K c/s virtual

Benchmarking: dynamic_10 [md5($s.md5($s.$p)) 128/128 AVX 4x3]... DONE
Many salts:     9881K c/s real, 9881K c/s virtual
Only one salt:  8181K c/s real, 8181K c/s virtual

Benchmarking: dynamic_11 [md5($s.md5($p.$s)) 128/128 AVX 4x3]... DONE
Many salts:     10130K c/s real, 10130K c/s virtual
Only one salt:  8537K c/s real, 8537K c/s virtual

Benchmarking: dynamic_12 [md5(md5($s).md5($p)) (IPB) 128/128 AVX 4x3]... DONE
Many salts:     12225K c/s real, 12225K c/s virtual
Only one salt:  5765K c/s real, 5765K c/s virtual

Benchmarking: dynamic_13 [md5(md5($p).md5($s)) 128/128 AVX 4x3]... DONE
Many salts:     12242K c/s real, 12242K c/s virtual
Only one salt:  5693K c/s real, 5693K c/s virtual

Benchmarking: dynamic_14 [md5($s.md5($p).$s) 128/128 AVX 4x3]... DONE
Many salts:     15946K c/s real, 15946K c/s virtual
Only one salt:  8248K c/s real, 8248K c/s virtual

Benchmarking: dynamic_15 [md5($u.md5($p).$s) 128/128 AVX 4x3]... DONE
Many salts:     11124K c/s real, 11124K c/s virtual
Only one salt:  5345K c/s real, 5345K c/s virtual

Benchmarking: dynamic_16 [md5(md5(md5($p).$s).$s2) 128/128 AVX 4x3]... DONE
Many salts:     7076K c/s real, 7076K c/s virtual
Only one salt:  4193K c/s real, 4193K c/s virtual

Benchmarking: dynamic_18 [md5($s.Y.$p.0xF7.$s) (Post.Office MD5) 32/64 x2]... DONE
Many salts:     3538K c/s real, 3538K c/s virtual
Only one salt:  3336K c/s real, 3336K c/s virtual

Benchmarking: dynamic_19 [md5($p) (Cisco PIX) 128/128 AVX 4x3]... DONE
Raw:    16280K c/s real, 16280K c/s virtual

Benchmarking: dynamic_20 [md5($p.$s) (Cisco ASA) 128/128 AVX 4x3]... DONE
Many salts:     18648K c/s real, 18648K c/s virtual
Only one salt:  13466K c/s real, 13466K c/s virtual

Benchmarking: dynamic_22 [md5(sha1($p)) 128/128 AVX 4x1]... DONE
Raw:    6745K c/s real, 6745K c/s virtual

Benchmarking: dynamic_23 [sha1(md5($p)) 128/128 AVX 4x1]... DONE
Raw:    7862K c/s real, 7862K c/s virtual

Benchmarking: dynamic_24 [sha1($p.$s) 128/128 AVX 4x1]... DONE
Many salts:     9843K c/s real, 9843K c/s virtual
Only one salt:  8233K c/s real, 8233K c/s virtual

Benchmarking: dynamic_25 [sha1($s.$p) 128/128 AVX 4x1]... DONE
Many salts:     9834K c/s real, 9834K c/s virtual
Only one salt:  8090K c/s real, 8090K c/s virtual

Benchmarking: dynamic_26 [sha1($p) raw-sha1 128/128 AVX 4x1]... DONE
Raw:    10652K c/s real, 10652K c/s virtual

Benchmarking: dynamic_29 [md5(utf16($p)) 128/128 AVX 4x3]... DONE
Raw:    17240K c/s real, 17240K c/s virtual

Benchmarking: dynamic_30 [md4($p) (raw-md4) 128/128 AVX 4x3]... DONE
Raw:    35668K c/s real, 35668K c/s virtual

Benchmarking: dynamic_31 [md4($s.$p) 128/128 AVX 4x3]... DONE
Many salts:     24968K c/s real, 24968K c/s virtual
Only one salt:  15595K c/s real, 15595K c/s virtual

Benchmarking: dynamic_32 [md4($p.$s) 128/128 AVX 4x3]... DONE
Many salts:     22994K c/s real, 22994K c/s virtual
Only one salt:  16121K c/s real, 16121K c/s virtual

Benchmarking: dynamic_33 [md4(utf16($p)) 128/128 AVX 4x3]... DONE
Raw:    19671K c/s real, 19671K c/s virtual

Benchmarking: dynamic_34 [md5(md4($p)) 128/128 AVX 4x3]... DONE
Raw:    16338K c/s real, 16338K c/s virtual

Benchmarking: dynamic_35 [sha1(uc($u).:.$p) (ManGOS) 128/128 AVX 4x1]... DONE
Many salts:     8442K c/s real, 8442K c/s virtual
Only one salt:  7405K c/s real, 7405K c/s virtual

Benchmarking: dynamic_36 [sha1($u.:.$p) (ManGOS2) 128/128 AVX 4x1]... DONE
Many salts:     8255K c/s real, 8255K c/s virtual
Only one salt:  7287K c/s real, 7287K c/s virtual

Benchmarking: dynamic_37 [sha1(lc($u).$p) (SMF) 128/128 AVX 4x1]... DONE
Many salts:     9930K c/s real, 9930K c/s virtual
Only one salt:  8368K c/s real, 8368K c/s virtual

Benchmarking: dynamic_38 [sha1($s.sha1($s.sha1($p))) (Wolt3BB) 128/128 AVX 4x1]... DONE
Many salts:     2466K c/s real, 2466K c/s virtual
Only one salt:  2251K c/s real, 2251K c/s virtual

Benchmarking: dynamic_39 [md5($s.pad16($p)) (net-md5) 128/128 AVX 4x3]... DONE
Many salts:     8400K c/s real, 8400K c/s virtual
Only one salt:  7210K c/s real, 7210K c/s virtual

Benchmarking: dynamic_40 [sha1($s.pad20($p)) (net-sha1) 128/128 AVX 4x1]... DONE
Many salts:     7837K c/s real, 7837K c/s virtual
Only one salt:  6859K c/s real, 6859K c/s virtual

Benchmarking: dynamic_50 [sha224($p) 128/128 AVX 4x]... DONE
Raw:    6279K c/s real, 6279K c/s virtual

Benchmarking: dynamic_60 [sha256($p) 128/128 AVX 4x]... DONE
Raw:    6263K c/s real, 6263K c/s virtual

Benchmarking: dynamic_61 [sha256($s.$p) 128/128 AVX 4x]... DONE
Many salts:     5453K c/s real, 5453K c/s virtual
Only one salt:  4939K c/s real, 4939K c/s virtual

Benchmarking: dynamic_70 [sha384($p) 128/128 AVX 2x]... DONE
Raw:    3012K c/s real, 3012K c/s virtual

Benchmarking: dynamic_80 [sha512($p) 128/128 AVX 2x]... DONE
Raw:    2958K c/s real, 2958K c/s virtual

Benchmarking: dynamic_90 [gost($p) 64/64]... DONE
Raw:    525840 c/s real, 525840 c/s virtual

Benchmarking: dynamic_100 [whirlpool($p) 32/64 OpenSSL]... DONE
Raw:    1740K c/s real, 1740K c/s virtual

Benchmarking: dynamic_110 [tiger($p) 32/64 sph_tiger]... DONE
Raw:    5335K c/s real, 5335K c/s virtual

Benchmarking: dynamic_120 [ripemd128($p) 32/64 sph_ripemd]... DONE
Raw:    5139K c/s real, 5139K c/s virtual

Benchmarking: dynamic_130 [ripemd160($p) 32/64 sph_ripemd]... DONE
Raw:    3407K c/s real, 3407K c/s virtual

Benchmarking: dynamic_140 [ripemd256($p) 32/64 sph_ripemd]... DONE
Raw:    4495K c/s real, 4495K c/s virtual

Benchmarking: dynamic_150 [ripemd320($p) 32/64 sph_ripemd]... DONE
Raw:    3170K c/s real, 3170K c/s virtual

Benchmarking: dynamic_160 [haval128_3($p) 32/64 sph_haval]... DONE
Raw:    3311K c/s real, 3311K c/s virtual

Benchmarking: dynamic_170 [haval128_4($p) 32/64 sph_haval]... DONE
Raw:    2452K c/s real, 2452K c/s virtual

Benchmarking: dynamic_180 [haval128_5($p) 32/64 sph_haval]... DONE
Raw:    2168K c/s real, 2168K c/s virtual

Benchmarking: dynamic_190 [haval160_3($p) 32/64 sph_haval]... DONE
Raw:    3385K c/s real, 3385K c/s virtual

Benchmarking: dynamic_200 [haval160_4($p) 32/64 sph_haval]... DONE
Raw:    2430K c/s real, 2430K c/s virtual

Benchmarking: dynamic_210 [haval160_5($p) 32/64 sph_haval]... DONE
Raw:    2140K c/s real, 2140K c/s virtual

Benchmarking: dynamic_220 [haval192_3($p) 32/64 sph_haval]... DONE
Raw:    3363K c/s real, 3363K c/s virtual

Benchmarking: dynamic_230 [haval192_4($p) 32/64 sph_haval]... DONE
Raw:    2486K c/s real, 2486K c/s virtual

Benchmarking: dynamic_240 [haval192_5($p) 32/64 sph_haval]... DONE
Raw:    2167K c/s real, 2167K c/s virtual

Benchmarking: dynamic_250 [haval224_3($p) 32/64 sph_haval]... DONE
Raw:    3405K c/s real, 3405K c/s virtual

Benchmarking: dynamic_260 [haval224_4($p) 32/64 sph_haval]... DONE
Raw:    2422K c/s real, 2422K c/s virtual

Benchmarking: dynamic_270 [haval224_5($p) 32/64 sph_haval]... DONE
Raw:    2163K c/s real, 2163K c/s virtual

Benchmarking: dynamic_280 [haval256_3($p) 32/64 sph_haval]... DONE
Raw:    3407K c/s real, 3407K c/s virtual

Benchmarking: dynamic_290 [haval256_4($p) 32/64 sph_haval]... DONE
Raw:    2511K c/s real, 2511K c/s virtual

Benchmarking: dynamic_300 [haval256_5($p) 32/64 sph_haval]... DONE
Raw:    2200K c/s real, 2200K c/s virtual

Benchmarking: dynamic_310 [md2($p) 32/64 sph_md2]... DONE
Raw:    163058 c/s real, 166320 c/s virtual

Benchmarking: dynamic_320 [panama($p) 32/64 sph_panama]... DONE
Raw:    900480 c/s real, 900480 c/s virtual

Benchmarking: dynamic_330 [skein224($p) 32/64 sph_skein]... DONE
Raw:    2889K c/s real, 2889K c/s virtual

Benchmarking: dynamic_340 [skein256($p) 32/64 sph_skein]... DONE
Raw:    2800K c/s real, 2800K c/s virtual

Benchmarking: dynamic_350 [skein384($p) 32/64 sph_skein]... DONE
Raw:    2682K c/s real, 2682K c/s virtual

Benchmarking: dynamic_360 [skein512($p) 32/64 sph_skein]... DONE
Raw:    2802K c/s real, 2802K c/s virtual

Benchmarking: dynamic_370 [sha3_224($p) 64/64 keccak]... DONE
Raw:    1461K c/s real, 1461K c/s virtual

Benchmarking: dynamic_380 [sha3_256($p) 64/64 keccak]... DONE
Raw:    1448K c/s real, 1448K c/s virtual

Benchmarking: dynamic_390 [sha3_384($p) 64/64 keccak]... DONE
Raw:    1475K c/s real, 1475K c/s virtual

Benchmarking: dynamic_400 [sha3_512($p) 64/64 keccak]... DONE
Raw:    1450K c/s real, 1464K c/s virtual

Benchmarking: dynamic_410 [keccak_256($p) 64/64 keccak]... DONE
Raw:    1485K c/s real, 1485K c/s virtual

Benchmarking: dynamic_420 [keccak_512($p) 64/64 keccak]... DONE
Raw:    1456K c/s real, 1456K c/s virtual

Benchmarking: dynamic_1001 [md5(md5(md5(md5($p)))) 128/128 AVX 4x3]... DONE
Raw:    6726K c/s real, 6726K c/s virtual

Benchmarking: dynamic_1002 [md5(md5(md5(md5(md5($p))))) 128/128 AVX 4x3]... DONE
Raw:    5607K c/s real, 5607K c/s virtual

Benchmarking: dynamic_1003 [md5(md5($p).md5($p)) 128/128 AVX 4x3]... DONE
Raw:    6053K c/s real, 6053K c/s virtual

Benchmarking: dynamic_1004 [md5(md5(md5(md5(md5(md5($p)))))) 128/128 AVX 4x3]... DONE
Raw:    4488K c/s real, 4488K c/s virtual

Benchmarking: dynamic_1005 [md5(md5(md5(md5(md5(md5(md5($p))))))) 128/128 AVX 4x3]... DONE
Raw:    4038K c/s real, 4038K c/s virtual

Benchmarking: dynamic_1006 [md5(md5(md5(md5(md5(md5(md5(md5($p)))))))) 128/128 AVX 4x3]... DONE
Raw:    3573K c/s real, 3573K c/s virtual

Benchmarking: dynamic_1007 [md5(md5($p).$s) (vBulletin) 128/128 AVX 4x3]... DONE
Many salts:     28635K c/s real, 28635K c/s virtual
Only one salt:  9591K c/s real, 9591K c/s virtual

Benchmarking: dynamic_1008 [md5($p.$s) (RADIUS User-Password) 128/128 AVX 4x3]... DONE
Many salts:     19370K c/s real, 19370K c/s virtual
Only one salt:  14073K c/s real, 14073K c/s virtual

Benchmarking: dynamic_1009 [md5($s.$p) (RADIUS Responses) 128/128 AVX 4x3]... DONE
Many salts:     20818K c/s real, 20818K c/s virtual
Only one salt:  15655K c/s real, 15655K c/s virtual

Benchmarking: dynamic_1010 [md5($p null_padded_to_len_100) RAdmin v2.x MD5 128/128 AVX 4x3]... DONE
Raw:    10658K c/s real, 10765K c/s virtual

Benchmarking: dynamic_1011 [md5($p.md5($s)) (webEdition CMS) 128/128 AVX 4x3]... DONE
Many salts:     8292K c/s real, 8292K c/s virtual
Only one salt:  7185K c/s real, 7185K c/s virtual

Benchmarking: dynamic_1012 [md5($p.md5($s)) (webEdition CMS) 128/128 AVX 4x3]... DONE
Many salts:     18700K c/s real, 18700K c/s virtual
Only one salt:  13670K c/s real, 13670K c/s virtual

Benchmarking: dynamic_1013 [md5($p.PMD5(username)) (webEdition CMS) 128/128 AVX 4x3]... DONE
Many salts:     18696K c/s real, 18696K c/s virtual
Only one salt:  13702K c/s real, 13702K c/s virtual

Benchmarking: dynamic_1014 [md5($p.$s) (long salt) 128/128 AVX 4x3]... DONE
Many salts:     7882K c/s real, 7882K c/s virtual
Only one salt:  6195K c/s real, 6195K c/s virtual

Benchmarking: dynamic_1015 [md5(md5($p.$u).$s) (PostgreSQL 'pass the hash') 128/128 AVX 4x3]... DONE
Many salts:     10459K c/s real, 10459K c/s virtual
Only one salt:  8793K c/s real, 8793K c/s virtual

Benchmarking: dynamic_1016 [md5($p.$s) (long salt) 128/128 AVX 4x3]... DONE
Many salts:     11555K c/s real, 11555K c/s virtual
Only one salt:  9371K c/s real, 9371K c/s virtual

Benchmarking: dynamic_1017 [md5($s.$p) (long salt) 128/128 AVX 4x3]... DONE
Many salts:     8470K c/s real, 8470K c/s virtual
Only one salt:  7353K c/s real, 7353K c/s virtual

Benchmarking: dynamic_1018 [md5(sha1(sha1($p))) 128/128 AVX 4x1]... DONE
Raw:    4215K c/s real, 4215K c/s virtual

Benchmarking: dynamic_1019 [md5(sha1(sha1(md5($p)))) 128/128 AVX 4x1]... DONE
Raw:    3732K c/s real, 3732K c/s virtual

Benchmarking: dynamic_1020 [md5(sha1(md5($p))) 128/128 AVX 4x1]... DONE
Raw:    5347K c/s real, 5347K c/s virtual

Benchmarking: dynamic_1021 [md5(sha1(md5(sha1($p)))) 128/128 AVX 4x1]... DONE
Raw:    3435K c/s real, 3435K c/s virtual

Benchmarking: dynamic_1022 [md5(sha1(md5(sha1(md5($p))))) 128/128 AVX 4x1]... DONE
Raw:    3060K c/s real, 3060K c/s virtual

Benchmarking: dynamic_1023 [sha1($p) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    10686K c/s real, 10686K c/s virtual

Benchmarking: dynamic_1024 [sha1(md5($p)) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    8003K c/s real, 8003K c/s virtual

Benchmarking: dynamic_1025 [sha1(md5(md5($p))) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    6172K c/s real, 6172K c/s virtual

Benchmarking: dynamic_1026 [sha1(sha1($p)) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    5451K c/s real, 5451K c/s virtual

Benchmarking: dynamic_1027 [sha1(sha1(sha1($p))) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    3763K c/s real, 3763K c/s virtual

Benchmarking: dynamic_1028 [sha1(sha1_raw($p)) (hash truncated to length 32) 128/128 AVX 4x1]... DONE
Raw:    5794K c/s real, 5794K c/s virtual

Benchmarking: dynamic_1029 [sha256($p) (hash truncated to length 32) 128/128 AVX 4x]... DONE
Raw:    5162K c/s real, 5162K c/s virtual

Benchmarking: dynamic_1030 [whirlpool($p) (hash truncated to length 32) 32/64 OpenSSL]... DONE
Raw:    1577K c/s real, 1577K c/s virtual

Benchmarking: dynamic_1031 [gost($p) (hash truncated to length 32) 64/64]... DONE
Raw:    507326 c/s real, 512400 c/s virtual

Benchmarking: dynamic_1032 [sha1_64(utf16($p)) (PeopleSoft) 128/128 AVX 4x1]... DONE
Raw:    8184K c/s real, 8184K c/s virtual

Benchmarking: dynamic_1034 [md5($p.$u) (PostgreSQL MD5) 128/128 AVX 4x3]... DONE
Many salts:     19244K c/s real, 19244K c/s virtual
Only one salt:  14364K c/s real, 14364K c/s virtual

Benchmarking: dynamic_1300 [md5(md5_raw($p)) 128/128 AVX 4x3]... DONE
Raw:    11534K c/s real, 11534K c/s virtual

Benchmarking: dynamic_1350 [md5(md5($s.$p):$s) 128/128 AVX 4x3]... DONE
Many salts:     10100K c/s real, 10100K c/s virtual
Only one salt:  8425K c/s real, 8425K c/s virtual

Benchmarking: dynamic_1400 [sha1(utf16($p)) (Microsoft CREDHIST) 128/128 AVX 4x1]... DONE
Raw:    6997K c/s real, 6997K c/s virtual

Benchmarking: dynamic_1401 [md5($u.\nskyper\n.$p) (Skype MD5) 128/128 AVX 4x3]... DONE
Many salts:     6795K c/s real, 6795K c/s virtual
Only one salt:  5213K c/s real, 5265K c/s virtual

Benchmarking: dynamic_1501 [sha1($s.sha1($p)) (Redmine) 128/128 AVX 4x1]... DONE
Many salts:     6459K c/s real, 6459K c/s virtual
Only one salt:  3529K c/s real, 3529K c/s virtual

Benchmarking: dynamic_1502 [sha1(sha1($p).$s) (XenForo SHA-1) 128/128 AVX 4x1]... DONE
Many salts:     11341K c/s real, 11341K c/s virtual
Only one salt:  4724K c/s real, 4724K c/s virtual

Benchmarking: dynamic_1503 [sha256(sha256($p).$s) (XenForo SHA-256) 128/128 AVX 4x]... DONE
Many salts:     2469K c/s real, 2469K c/s virtual
Only one salt:  1661K c/s real, 1661K c/s virtual

Benchmarking: dynamic_1504 [sha1($s.$p.$s) 128/128 AVX 4x1]... DONE
Many salts:     8623K c/s real, 8623K c/s virtual
Only one salt:  7388K c/s real, 7388K c/s virtual

Benchmarking: dynamic_1505 [md5($p.$s.md5($p.$s)) 128/128 AVX 4x3]... DONE
Many salts:     4455K c/s real, 4455K c/s virtual
Only one salt:  4110K c/s real, 4110K c/s virtual

Benchmarking: dynamic_1506 [md5($u.:XDB:.$p) (Oracle 12c "H" hash) 128/128 AVX 4x3]... DONE
Many salts:     15912K c/s real, 15912K c/s virtual
Only one salt:  12596K c/s real, 12596K c/s virtual

Benchmarking: dynamic_1507 [sha1(utf16($const.$p)) (Mcafee master pass) 128/128 AVX 4x1]... DONE
Raw:    7281K c/s real, 7281K c/s virtual

Benchmarking: dynamic_1518 [md5(sha1($p).md5($p).sha1($p)) 128/128 AVX 4x1]... DONE
Raw:    3114K c/s real, 3114K c/s virtual

Benchmarking: dynamic_1528 [sha256($s.$p.$s) (Telegram for Android) 128/128 AVX 4x]... DONE
Many salts:     5470K c/s real, 5470K c/s virtual
Only one salt:  4961K c/s real, 4961K c/s virtual

Benchmarking: dynamic_1529 [sha1($p null_padded_to_len_32) (DeepSound) 128/128 AVX 4x1]... DONE
Raw:    8168K c/s real, 8168K c/s virtual

Benchmarking: dynamic_1550 [md5($u.:mongo:.$p) (MONGODB-CR system hash) 128/128 AVX 4x3]... DONE
Many salts:     15624K c/s real, 15624K c/s virtual
Only one salt:  11281K c/s real, 11281K c/s virtual

Benchmarking: dynamic_1551 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 128/128 AVX 4x3]... DONE
Many salts:     8250K c/s real, 8250K c/s virtual
Only one salt:  6995K c/s real, 6995K c/s virtual

Benchmarking: dynamic_1552 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 128/128 AVX 4x3]... DONE
Many salts:     4833K c/s real, 4833K c/s virtual
Only one salt:  4552K c/s real, 4552K c/s virtual

Benchmarking: dynamic_1560 [md5($s.$p.$s2) (SocialEngine) 128/128 AVX 4x3]... DONE
Many salts:     9759K c/s real, 9759K c/s virtual
Only one salt:  8201K c/s real, 8201K c/s virtual

Benchmarking: dynamic_1588 [sha256($s.sha1($p)) (ColdFusion 11) 128/128 AVX 4x]... DONE
Many salts:     2629K c/s real, 2629K c/s virtual
Only one salt:  2528K c/s real, 2528K c/s virtual

Benchmarking: dynamic_1590 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 128/128 AVX 4x1]... DONE
Many salts:     9350K c/s real, 9350K c/s virtual
Only one salt:  7726K c/s real, 7726K c/s virtual

Benchmarking: dynamic_1592 [sha1($s.sha1($s.sha1($p))) (wbb3) 128/128 AVX 4x1]... DONE
Many salts:     3418K c/s real, 3418K c/s virtual
Only one salt:  2284K c/s real, 2284K c/s virtual

Benchmarking: dynamic_1600 [sha1($s.utf16le($p)) (Oracle PeopleSoft PS_TOKEN) 128/128 AVX 4x1]... DONE
Many salts:     4962K c/s real, 4962K c/s virtual
Only one salt:  4058K c/s real, 4058K c/s virtual

Benchmarking: dynamic_1602 [sha256(#.$salt.-.$pass) (QAS vas_auth) 128/128 AVX 4x]... DONE
Many salts:     4673K c/s real, 4673K c/s virtual
Only one salt:  4278K c/s real, 4278K c/s virtual

Benchmarking: dynamic_1608 [sha256(sha256_raw(sha256_raw($p))) (Neo Wallet) 128/128 AVX 4x]... DONE
Raw:    2106K c/s real, 2085K c/s virtual

Benchmarking: dynamic_2000 [md5($p) (PW > 55 bytes) 128/128 AVX 4x3]... DONE
Raw:    16200K c/s real, 16200K c/s virtual

Benchmarking: dynamic_2001 [md5($p.$s) (joomla) (PW > 23 bytes) 128/128 AVX 4x3]... DONE
Many salts:     13873K c/s real, 13873K c/s virtual
Only one salt:  11165K c/s real, 11165K c/s virtual

Benchmarking: dynamic_2002 [md5(md5($p)) (e107) (PW > 55 bytes) 128/128 AVX 4x3]... DONE
Raw:    8282K c/s real, 8282K c/s virtual

Benchmarking: dynamic_2003 [md5(md5(md5($p))) (PW > 55 bytes) 128/128 AVX 4x3]... DONE
Raw:    5782K c/s real, 5782K c/s virtual

Benchmarking: dynamic_2004 [md5($s.$p) (OSC) (PW > 31 bytes) 128/128 AVX 4x3]... DONE
Many salts:     14258K c/s real, 14258K c/s virtual
Only one salt:  11014K c/s real, 11014K c/s virtual

Benchmarking: dynamic_2005 [md5($s.$p.$s) (PW > 31 bytes) 128/128 AVX 4x3]... DONE
Many salts:     11555K c/s real, 11555K c/s virtual
Only one salt:  9419K c/s real, 9419K c/s virtual

Benchmarking: dynamic_2006 [md5(md5($p).$s) (PW > 55 bytes) 128/128 AVX 4x3]... DONE
Many salts:     18409K c/s real, 18409K c/s virtual
Only one salt:  6711K c/s real, 6711K c/s virtual

Benchmarking: dynamic_2008 [md5(md5($s).$p) (PW > 23 bytes) 128/128 AVX 4x3]... DONE
Many salts:     14090K c/s real, 14090K c/s virtual
Only one salt:  11128K c/s real, 11128K c/s virtual

Benchmarking: dynamic_2009 [md5($s.md5($p)) (salt > 23 bytes) 128/128 AVX 4x3]... DONE
Many salts:     13885K c/s real, 13885K c/s virtual
Only one salt:  5920K c/s real, 5920K c/s virtual

Benchmarking: dynamic_2010 [md5($s.md5($s.$p)) (PW > 32 or salt > 23 bytes) 128/128 AVX 4x3]... DONE
Many salts:     6961K c/s real, 6961K c/s virtual
Only one salt:  6118K c/s real, 6118K c/s virtual

Benchmarking: dynamic_2011 [md5($s.md5($p.$s)) (PW > 32 or salt > 23 bytes) 128/128 AVX 4x3]... DONE
Many salts:     6807K c/s real, 6807K c/s virtual
Only one salt:  5905K c/s real, 5905K c/s virtual

Benchmarking: dynamic_2014 [md5($s.md5($p).$s) (PW > 55 or salt > 11 bytes) 128/128 AVX 4x3]... DONE
Many salts:     11208K c/s real, 11208K c/s virtual
Only one salt:  5414K c/s real, 5414K c/s virtual

Benchmarking: dummy [N/A]... DONE
Raw:    63119K c/s real, 63119K c/s virtual

Benchmarking: crypt, generic crypt(3) [?/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [1:descrypt 2:md5crypt 3:sunmd5 4:bcrypt 5:sha256crypt 6:sha512crypt]) of 1, cost 2 (algorithm specific iterations) of 1
Many salts:     499584 c/s real, 124896 c/s virtual
Only one salt:  493056 c/s real, 123572 c/s virtual

All 407 formats passed self-tests!
1627492612.778696601
```

