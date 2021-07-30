```shell
kali$ john --test              
1627610384.951632505
Will run 4 OpenMP threads
Benchmarking: descrypt, traditional crypt(3) [DES 128/128 SSE2]... (4xOMP) DONE
Many salts:     18333K c/s real, 4583K c/s virtual
Only one salt:  16711K c/s real, 4177K c/s virtual

Benchmarking: bsdicrypt, BSDI crypt(3) ("_J9..", 725 iterations) [DES 128/128 SSE2]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 725
Many salts:     586752 c/s real, 147055 c/s virtual
Only one salt:  574464 c/s real, 143616 c/s virtual

Benchmarking: md5crypt, crypt(3) $1$ (and variants) [MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Many salts:     152640 c/s real, 38160 c/s virtual
Only one salt:  152256 c/s real, 38064 c/s virtual

Benchmarking: md5crypt-long, crypt(3) $1$ (and variants) [MD5 32/64]... (4xOMP) DONE
Raw:    29376 c/s real, 7362 c/s virtual

Benchmarking: bcrypt ("$2a$05", 32 iterations) [Blowfish 32/64 X3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32
Raw:    5097 c/s real, 1283 c/s virtual

Benchmarking: scrypt (16384, 8, 1) [Salsa20/8 128/128 SSE2]... (4xOMP) DONE
Speed for cost 1 (N) of 16384, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    149 c/s real, 37.1 c/s virtual

Benchmarking: LM [DES 128/128 SSE2]... (4xOMP) DONE
Raw:    109527K c/s real, 27381K c/s virtual

Benchmarking: AFS, Kerberos AFS [DES 48/64 4K]... DONE
Short:  546048 c/s real, 546048 c/s virtual
Long:   2238K c/s real, 2238K c/s virtual

Benchmarking: tripcode [DES 128/128 SSE2]... (4xOMP) DONE
Raw:    13205K c/s real, 3301K c/s virtual

Benchmarking: AndroidBackup [PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1796 c/s real, 452 c/s virtual

Benchmarking: adxcrypt [IBM/Toshiba 4690 - ADXCRYPT 32/64]... (4xOMP) DONE
Raw:    84934K c/s real, 26625K c/s virtual

Benchmarking: agilekeychain, 1Password Agile Keychain [PBKDF2-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    35136 c/s real, 8740 c/s virtual

Benchmarking: aix-ssha1, AIX LPA {ssha1} [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     507264 c/s real, 126816 c/s virtual
Only one salt:  505216 c/s real, 126304 c/s virtual

Benchmarking: aix-ssha256, AIX LPA {ssha256} [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     217856 c/s real, 54600 c/s virtual
Only one salt:  216448 c/s real, 54112 c/s virtual

Benchmarking: aix-ssha512, AIX LPA {ssha512} [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     88128 c/s real, 22087 c/s virtual
Only one salt:  87065 c/s real, 21929 c/s virtual

Benchmarking: andOTP [SHA256 32/64]... (4xOMP) DONE
Raw:    991232 c/s real, 247808 c/s virtual

Benchmarking: ansible, Ansible Vault [PBKDF2-SHA256 HMAC-256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1489 c/s real, 373 c/s virtual

Benchmarking: argon2 [Blake2 SSE2]... (4xOMP) DONE
Speed for cost 1 (t) of 3, cost 2 (m) of 4096, cost 3 (p) of 1, cost 4 (type [0:Argon2d 1:Argon2i]) of 0 and 1
Raw:    448 c/s real, 112 c/s virtual

Benchmarking: as400-des, AS/400 DES [DES 32/64]... DONE
Raw:    580051 c/s real, 145376 c/s virtual

Benchmarking: as400-ssha1, AS400-SaltedSHA1 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 128/128 SSE2 4x1]... DONE
Many salts:     11395K c/s real, 11395K c/s virtual
Only one salt:  10436K c/s real, 10436K c/s virtual

Benchmarking: asa-md5, Cisco ASA [md5($p.$s) (Cisco ASA) 128/128 SSE2 4x3]... DONE
Many salts:     24771K c/s real, 24771K c/s virtual
Only one salt:  18846K c/s real, 18846K c/s virtual

Benchmarking: AxCrypt [PBKDF2-SHA512/SHA1 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1337 and 60000
Raw:    897 c/s real, 224 c/s virtual

Benchmarking: AzureAD [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     142848 c/s real, 35622 c/s virtual
Only one salt:  142336 c/s real, 35584 c/s virtual

Benchmarking: BestCrypt (SHA-256 + AES XTS mode) [Jetico BestCrypt (.jbc) PKCS12 PBE (Whirlpool / SHA-1 to SHA-512) 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    460 c/s real, 114 c/s virtual

Benchmarking: bfegg, Eggdrop [Blowfish 32/64]... (4xOMP) DONE
Raw:    127746 c/s real, 31857 c/s virtual

Benchmarking: Bitcoin, Bitcoin Core [SHA512 AES 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 177864
Raw:    67.2 c/s real, 16.8 c/s virtual

Benchmarking: BitLocker, BitLocker [SHA-256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1048576
Raw:    7.4 c/s real, 1.8 c/s virtual

Benchmarking: bitshares, BitShares Wallet [SHA-512 64/64]... (4xOMP) DONE
Many salts:     5457K c/s real, 1364K c/s virtual
Only one salt:  5222K c/s real, 1305K c/s virtual

Benchmarking: Bitwarden, Bitwarden Password Manager [PBKDF2-SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    3041 c/s real, 760 c/s virtual

Benchmarking: BKS [PKCS12 PBE 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    34133 c/s real, 8575 c/s virtual

Benchmarking: Blackberry-ES10 (101x) [SHA-512 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     116594 c/s real, 29366 c/s virtual
Only one salt:  114432 c/s real, 28608 c/s virtual

Benchmarking: WoWSRP, Battlenet [SHA1 32/64 GMP-exp]... (4xOMP) DONE
Many salts:     465920 c/s real, 116480 c/s virtual
Only one salt:  463872 c/s real, 115968 c/s virtual

Benchmarking: Blockchain, My Wallet (v2 x5000) [PBKDF2-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    3513 c/s real, 887 c/s virtual

Benchmarking: chap, iSCSI CHAP authentication / EAP-MD5 [MD5 32/64]... (4xOMP) DONE
Many salts:     26722K c/s real, 6663K c/s virtual
Only one salt:  23175K c/s real, 5808K c/s virtual

Benchmarking: Clipperz, SRP [SHA256 32/64 GMP-exp]... (4xOMP) DONE
Raw:    223049 c/s real, 56320 c/s virtual

Benchmarking: cloudkeychain, 1Password Cloud Keychain [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 40000 and 50000
Raw:    130 c/s real, 32.6 c/s virtual

Benchmarking: dynamic=md5($p) [128/128 SSE2 4x3]... DONE
Raw:    35395K c/s real, 35753K c/s virtual

Benchmarking: cq, ClearQuest [CQWeb]... (4xOMP) DONE
Many salts:     345636K c/s real, 86843K c/s virtual
Only one salt:  50462K c/s real, 15432K c/s virtual

Benchmarking: CRC32 [CRC32 32/64 CRC-32C 32/64]... DONE
Speed for cost 1 (version [0:CRC-32 1:CRC-32C]) of 0
Many salts:     156876K c/s real, 156876K c/s virtual
Only one salt:  78209K c/s real, 78209K c/s virtual

Benchmarking: sha1crypt, NetBSD's sha1crypt [PBKDF1-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64000 and 40000
Raw:    691 c/s real, 173 c/s virtual

Benchmarking: sha256crypt, crypt(3) $5$ (rounds=5000) [SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    3531 c/s real, 888 c/s virtual

Benchmarking: sha512crypt, crypt(3) $6$ (rounds=5000) [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    2258 c/s real, 567 c/s virtual

Benchmarking: Citrix_NS10, Netscaler 10 [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     49905K c/s real, 12476K c/s virtual
Only one salt:  37945K c/s real, 9486K c/s virtual

Benchmarking: dahua, "MD5 based authentication" Dahua [MD5 32/64]... DONE
Raw:    6546K c/s real, 6546K c/s virtual

Benchmarking: dashlane, Dashlane Password Manager [AES PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    1706 c/s real, 428 c/s virtual

Benchmarking: diskcryptor, DiskCryptor [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    4256 c/s real, 1178 c/s virtual

Benchmarking: Django (x10000) [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1505 c/s real, 377 c/s virtual

Benchmarking: django-scrypt [Salsa20/8 128/128 SSE2]... (4xOMP) DONE
Speed for cost 1 (N) of 14, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    147 c/s real, 37.2 c/s virtual

Benchmarking: dmd5, DIGEST-MD5 C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     7593K c/s real, 1893K c/s virtual
Only one salt:  7225K c/s real, 1801K c/s virtual

Benchmarking: dmg, Apple DMG [PBKDF2-SHA1 128/128 SSE2 4x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (version) of 2 and 1
Raw:    15504 c/s real, 3876 c/s virtual

Benchmarking: dominosec, Lotus Notes/Domino 6 More Secure Internet Password [8/64]... (4xOMP) DONE
Many salts:     1322K c/s real, 331452 c/s virtual
Only one salt:  883584 c/s real, 220896 c/s virtual

Benchmarking: dominosec8, Lotus Notes/Domino 8 [8/64]... (4xOMP) DONE
Raw:    2832 c/s real, 713 c/s virtual

Benchmarking: DPAPImk, DPAPI masterkey file v1 and v2 [SHA1/MD4 PBKDF2-(SHA1/SHA512)-DPAPI-variant 3DES/AES256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 24000
Raw:    736 c/s real, 184 c/s virtual

Benchmarking: dragonfly3-32, DragonFly BSD $3$ w/ bug, 32-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     13197K c/s real, 3299K c/s virtual
Only one salt:  11880K c/s real, 2977K c/s virtual

Benchmarking: dragonfly3-64, DragonFly BSD $3$ w/ bug, 64-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     13161K c/s real, 3298K c/s virtual
Only one salt:  11823K c/s real, 2963K c/s virtual

Benchmarking: dragonfly4-32, DragonFly BSD $4$ w/ bugs, 32-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     10199K c/s real, 2549K c/s virtual
Only one salt:  9366K c/s real, 2341K c/s virtual

Benchmarking: dragonfly4-64, DragonFly BSD $4$ w/ bugs, 64-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     9859K c/s real, 2470K c/s virtual
Only one salt:  9400K c/s real, 2350K c/s virtual

Benchmarking: Drupal7, $S$ (x16385) [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    720 c/s real, 180 c/s virtual

Benchmarking: eCryptfs (65536 iterations) [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    182 c/s real, 45.7 c/s virtual

Benchmarking: eigrp, EIGRP MD5 / HMAC-SHA-256 authentication [MD5/SHA-256 32/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [2:MD5 3:HMAC-SHA-256]) of 2
Many salts:     16791K c/s real, 4218K c/s virtual
Only one salt:  14819K c/s real, 3704K c/s virtual

Benchmarking: electrum, Electrum Wallet [SHA256 AES / PBKDF2-SHA512 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (kdf [1:SHA256 2:PBKDF2-SHA512]) of 1 and 2
Raw:    9152 c/s real, 2305 c/s virtual

Benchmarking: EncFS [PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 181474
Raw:    98.2 c/s real, 24.7 c/s virtual

Benchmarking: enpass, Enpass Password Manager [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    745 c/s real, 186 c/s virtual

Benchmarking: EPI, EPiServer SID [SHA1 32/64]... (4xOMP) DONE
Many salts:     26656K c/s real, 6664K c/s virtual
Only one salt:  21626K c/s real, 5420K c/s virtual

Benchmarking: EPiServer [SHA1/SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256]) of 1
Many salts:     44572K c/s real, 11143K c/s virtual
Only one salt:  42311K c/s real, 10577K c/s virtual

Benchmarking: ethereum, Ethereum Wallet [PBKDF2-SHA256/scrypt Keccak 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 262144 and 1024, cost 2 (kdf [0:PBKDF2-SHA256 1:scrypt 2:PBKDF2-SHA256 presale]) of 0
Warning: "Many salts" test limited: 8/256
Many salts:     114 c/s real, 28.5 c/s virtual
Only one salt:  57.1 c/s real, 14.4 c/s virtual

Benchmarking: fde, Android FDE [PBKDF2-SHA1 128/128 SSE2 4x SHA256/AES]... (4xOMP) DONE
Raw:    8777 c/s real, 2215 c/s virtual

Benchmarking: Fortigate256, FortiOS256 [SHA256 32/64]... (4xOMP) DONE
Many salts:     13688K c/s real, 3422K c/s virtual
Only one salt:  12410K c/s real, 3110K c/s virtual

Benchmarking: Fortigate, FortiOS [SHA1 32/64]... (4xOMP) DONE
Many salts:     26738K c/s real, 6701K c/s virtual
Only one salt:  22097K c/s real, 5510K c/s virtual

Benchmarking: FormSpring [sha256($s.$p) 128/128 SSE2 4x]... DONE
Many salts:     6165K c/s real, 6165K c/s virtual
Only one salt:  5819K c/s real, 5819K c/s virtual

Benchmarking: FVDE, FileVault 2 [PBKDF2-SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 41000 and 70400
Raw:    261 c/s real, 65.8 c/s virtual

Benchmarking: geli, FreeBSD GELI [PBKDF2-SHA512 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 256 and 512
Raw:    14827 c/s real, 3725 c/s virtual

Benchmarking: gost, GOST R 34.11-94 [64/64]... (4xOMP) DONE
Raw:    2435K c/s real, 610293 c/s virtual

Benchmarking: gpg, OpenPGP / GnuPG Secret Key [32/64]... (4xOMP) DONE
Speed for cost 1 (s2k-count) of 65536, cost 2 (hash algorithm [1:MD5 2:SHA1 3:RIPEMD160 8:SHA256 9:SHA384 10:SHA512 11:SHA224]) of 2, cost 3 (cipher algorithm [1:IDEA 2:3DES 3:CAST5 4:Blowfish 7:AES128 8:AES192 9:AES256 10:Twofish 11:Camellia128 12:Camellia192 13:Camellia256]) of 3
Raw:    34468 c/s real, 8617 c/s virtual

Benchmarking: HAVAL-128-4 [32/64]... DONE
Raw:    3431K c/s real, 3431K c/s virtual

Benchmarking: HAVAL-256-3 [32/64]... DONE
Raw:    4952K c/s real, 4952K c/s virtual

Benchmarking: hdaa, HTTP Digest access authentication [MD5 128/128 SSE2 4x3]... DONE
Many salts:     6268K c/s real, 6268K c/s virtual
Only one salt:  5885K c/s real, 5885K c/s virtual

Benchmarking: hMailServer [sha256($s.$p) 128/128 SSE2 4x]... DONE
Many salts:     6148K c/s real, 6148K c/s virtual
Only one salt:  5733K c/s real, 5733K c/s virtual

Benchmarking: hsrp, "MD5 authentication" HSRP, HSRPv2, VRRP, GLBP [MD5 32/64]... (4xOMP) DONE
Many salts:     16613K c/s real, 4163K c/s virtual
Only one salt:  10141K c/s real, 2529K c/s virtual

Benchmarking: IKE, PSK [HMAC MD5/SHA1 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1]) of 1 and 2
Raw:    2137K c/s real, 535611 c/s virtual

Benchmarking: ipb2, Invision Power Board 2.x [MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Many salts:     31948K c/s real, 7967K c/s virtual
Only one salt:  26984K c/s real, 6763K c/s virtual

Benchmarking: itunes-backup, Apple iTunes Backup [PBKDF2-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (version) of 9 and 10, cost 2 (iteration count) of 10000
Raw:    1694 c/s real, 424 c/s virtual

Benchmarking: iwork, Apple iWork '09 or newer [PBKDF2-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 100000
Raw:    355 c/s real, 89.3 c/s virtual

Benchmarking: KeePass [SHA256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 50000 and 6000, cost 2 (version) of 1 and 2, cost 3 (algorithm [0=AES, 1=TwoFish, 2=ChaCha]) of 0
Raw:    776 c/s real, 195 c/s virtual

Benchmarking: keychain, Mac OS X Keychain [PBKDF2-SHA1 3DES 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    16728 c/s real, 4255 c/s virtual

Benchmarking: keyring, GNOME Keyring [SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3221
Raw:    9353 c/s real, 2355 c/s virtual

Benchmarking: keystore, Java KeyStore [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Warning: "Many salts" test limited: 16/256
Many salts:     2076K c/s real, 519097 c/s virtual
Only one salt:  1997K c/s real, 512751 c/s virtual

Benchmarking: known_hosts, HashKnownHosts HMAC-SHA1 [SHA1 32/64]... (4xOMP) DONE
Many salts:     13709K c/s real, 3435K c/s virtual
Only one salt:  11636K c/s real, 2938K c/s virtual

Benchmarking: krb4, Kerberos v4 TGT [DES 32/64]... DONE
Short:  309760 c/s real, 309760 c/s virtual
Long:   859963 c/s real, 859963 c/s virtual

Benchmarking: krb5, Kerberos v5 TGT [3DES 32/64]... DONE
Raw:    83763 c/s real, 83763 c/s virtual

Benchmarking: krb5asrep, Kerberos 5 AS-REP etype 17/18/23 [MD4 HMAC-MD5 RC4 / PBKDF2 HMAC-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     1573K c/s real, 396316 c/s virtual
Only one salt:  1320K c/s real, 331899 c/s virtual

Benchmarking: krb5pa-sha1, Kerberos 5 AS-REQ Pre-Auth etype 17/18 [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    4306 c/s real, 1089 c/s virtual

Benchmarking: krb5tgs, Kerberos 5 TGS etype 23 [MD4 HMAC-MD5 RC4]... (4xOMP) DONE
Many salts:     2909K c/s real, 747862 c/s virtual
Only one salt:  2163K c/s real, 542283 c/s virtual

Benchmarking: krb5-17, Kerberos 5 DB etype 17 [DES / PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Raw:    8416 c/s real, 2144 c/s virtual

Benchmarking: krb5-18, Kerberos 5 DB etype 18 [DES / PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Raw:    4311 c/s real, 1080 c/s virtual

Benchmarking: krb5-3, Kerberos 5 DB etype 3 [DES / PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Many salts:     5763K c/s real, 1444K c/s virtual
Only one salt:  5173K c/s real, 1293K c/s virtual

Benchmarking: kwallet, KDE KWallet [SHA1 / PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    12928 c/s real, 3240 c/s virtual

Benchmarking: lp, LastPass offline [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 117/256
Many salts:     29655 c/s real, 7469 c/s virtual
Only one salt:  29655 c/s real, 7450 c/s virtual

Benchmarking: lpcli, LastPass CLI [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1234
Many salts:     12016 c/s real, 3011 c/s virtual
Only one salt:  11408 c/s real, 2859 c/s virtual

Benchmarking: leet [SHA-512(128/128 SSE2 2x) + Whirlpool(OpenSSL/64)]... (4xOMP) DONE
Warning: "Many salts" test limited: 72/256
Many salts:     4718K c/s real, 1182K c/s virtual
Only one salt:  4433K c/s real, 1124K c/s virtual

Benchmarking: lotus5, Lotus Notes/Domino 5 [8/64 X3]... (4xOMP) DONE
Raw:    2469K c/s real, 619019 c/s virtual

Benchmarking: lotus85, Lotus Notes/Domino 8.5 [8/64]... (4xOMP) DONE
Many salts:     521472 c/s real, 131023 c/s virtual
Only one salt:  508416 c/s real, 128387 c/s virtual

Benchmarking: LUKS [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    65.5 c/s real, 23.1 c/s virtual

Benchmarking: MD2 [MD2 32/64]... (4xOMP) DONE
Raw:    196096 c/s real, 78125 c/s virtual

Benchmarking: mdc2, MDC-2 [MDC-2DES]... (4xOMP) DONE
Raw:    2265K c/s real, 745094 c/s virtual

Benchmarking: MediaWiki [md5($s.md5($p)) 128/128 SSE2 4x3]... DONE
Many salts:     24472K c/s real, 24972K c/s virtual
Only one salt:  11948K c/s real, 11948K c/s virtual

Benchmarking: monero, monero Wallet [Pseudo-AES / ChaCha / Various 32/64]... (4xOMP) DONE
Raw:    15.0 c/s real, 4.3 c/s virtual

Benchmarking: money, Microsoft Money (2002 to Money Plus) [MD5/SHA1 32/64]... (4xOMP) DONE
Many salts:     4440K c/s real, 1138K c/s virtual
Only one salt:  3805K c/s real, 988359 c/s virtual

Benchmarking: MongoDB, system / network [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (salt type) of 0 and 1
Raw:    16580K c/s real, 4208K c/s virtual

Benchmarking: scram [SCRAM PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    3303 c/s real, 896 c/s virtual

Benchmarking: Mozilla, Mozilla key3.db [SHA1 3DES 32/64]... (4xOMP) DONE
Many salts:     1340K c/s real, 357444 c/s virtual
Only one salt:  625664 c/s real, 213537 c/s virtual

Benchmarking: mscash, MS Cache Hash (DCC) [MD4 32/64]... (4xOMP) DONE
Many salts:     20159K c/s real, 6949K c/s virtual
Only one salt:  17858K c/s real, 4988K c/s virtual

Benchmarking: mscash2, MS Cache Hash 2 (DCC2) [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    2760 c/s real, 809 c/s virtual

Benchmarking: MSCHAPv2, C/R [MD4 DES (ESS MD5) 128/128 SSE2 4x3]... DONE
Many salts:     8460M c/s real, 8545M c/s virtual
Only one salt:  40713K c/s real, 41544K c/s virtual

Benchmarking: mschapv2-naive, MSCHAPv2 C/R [MD4 DES 128/128 SSE2 naive]... (4xOMP) DONE
Many salts:     269860K c/s real, 69731K c/s virtual
Only one salt:  22528K c/s real, 5791K c/s virtual

Benchmarking: krb5pa-md5, Kerberos 5 AS-REQ Pre-Auth etype 23 [32/64]... (4xOMP) DONE
Many salts:     2812K c/s real, 743957 c/s virtual
Only one salt:  1474K c/s real, 410234 c/s virtual

Benchmarking: mssql, MS SQL [SHA1 128/128 SSE2 4x]... DONE
Many salts:     18234K c/s real, 18234K c/s virtual
Only one salt:  12458K c/s real, 12584K c/s virtual

Benchmarking: mssql05, MS SQL 2005 [SHA1 128/128 SSE2 4x]... DONE
Many salts:     18020K c/s real, 18020K c/s virtual
Only one salt:  15732K c/s real, 15732K c/s virtual

Benchmarking: mssql12, MS SQL 2012/2014 [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     9555K c/s real, 2488K c/s virtual
Only one salt:  6385K c/s real, 1829K c/s virtual

Benchmarking: multibit, MultiBit Wallet [MD5/scrypt AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3, cost 2 (kdf [1:MD5 2:scrypt hd 3:scrypt classic]) of 1
Many salts:     3406K c/s real, 866858 c/s virtual
Only one salt:  3113K c/s real, 794244 c/s virtual

Benchmarking: mysqlna, MySQL Network Authentication [SHA1 32/64]... (4xOMP) DONE
Many salts:     5912K c/s real, 1619K c/s virtual
Only one salt:  7315K c/s real, 1870K c/s virtual

Benchmarking: mysql-sha1, MySQL 4.1+ [SHA1 128/128 SSE2 4x]... DONE
Raw:    8578K c/s real, 8578K c/s virtual

Benchmarking: mysql, MySQL pre-4.1 [32/64]... DONE
Raw:    64527K c/s real, 65179K c/s virtual

Benchmarking: net-ah, IPsec AH HMAC-MD5-96 [MD5 32/64]... (4xOMP) DONE
Many salts:     4956K c/s real, 1339K c/s virtual
Only one salt:  2293K c/s real, 762046 c/s virtual

Benchmarking: nethalflm, HalfLM C/R [DES 32/64]... (4xOMP) DONE
Many salts:     2498K c/s real, 889167 c/s virtual
Only one salt:  2097K c/s real, 733269 c/s virtual

Benchmarking: netlm, LM C/R [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 31/256
Many salts:     15934K c/s real, 4032K c/s virtual
Only one salt:  1839K c/s real, 1361K c/s virtual

Benchmarking: netlmv2, LMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     749568 c/s real, 268662 c/s virtual
Only one salt:  2724K c/s real, 742469 c/s virtual

Benchmarking: net-md5, "Keyed MD5" RIPv2, OSPF, BGP, SNMPv2 [MD5 32/64]... (4xOMP) DONE
Many salts:     10021K c/s real, 10021K c/s virtual
Only one salt:  7896K c/s real, 7896K c/s virtual

Benchmarking: netntlmv2, NTLMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     3132K c/s real, 866893 c/s virtual
Only one salt:  2551K c/s real, 691546 c/s virtual

Benchmarking: netntlm, NTLMv1 C/R [MD4 DES (ESS MD5) 128/128 SSE2 4x3]... DONE
Many salts:     9358M c/s real, 9358M c/s virtual
Only one salt:  44281K c/s real, 44281K c/s virtual

Benchmarking: netntlm-naive, NTLMv1 C/R [MD4 DES (ESS MD5) DES 128/128 SSE2 naive]... (4xOMP) DONE
Many salts:     195903K c/s real, 54417K c/s virtual
Only one salt:  24313K c/s real, 6124K c/s virtual

Benchmarking: net-sha1, "Keyed SHA1" BFD [SHA1 32/64]... (4xOMP) DONE
Many salts:     9355K c/s real, 9355K c/s virtual
Only one salt:  8159K c/s real, 8159K c/s virtual

Benchmarking: nk, Nuked-Klan CMS [SHA1 MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 68/256
Many salts:     8912K c/s real, 2333K c/s virtual
Only one salt:  8175K c/s real, 2150K c/s virtual

Benchmarking: notes, Apple Notes [PBKDF2-SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 20000
Raw:    518 c/s real, 182 c/s virtual

Benchmarking: md5ns, Netscreen [md5($s.$p) (OSC) (PW > 31 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     19188K c/s real, 19382K c/s virtual
Only one salt:  16742K c/s real, 16742K c/s virtual

Benchmarking: nsec3, DNSSEC NSEC3 [32/64]... DONE
Raw:    74053 c/s real, 74053 c/s virtual

Benchmarking: NT [MD4 128/128 SSE2 4x3]... DONE
Raw:    49618K c/s real, 49126K c/s virtual

Benchmarking: o10glogon, Oracle 10g-logon protocol [DES-AES128-MD5 32/64]... (4xOMP) DONE
Many salts:     1849K c/s real, 468317 c/s virtual
Only one salt:  1706K c/s real, 452651 c/s virtual

Benchmarking: o3logon, Oracle O3LOGON protocol [SHA1 DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 32/256
Many salts:     1018K c/s real, 257003 c/s virtual
Only one salt:  973306 c/s real, 249502 c/s virtual

Benchmarking: o5logon, Oracle O5LOGON protocol [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     10010K c/s real, 2515K c/s virtual
Only one salt:  9043K c/s real, 2307K c/s virtual

Benchmarking: ODF, OpenDocument Star/Libre/OpenOffice [PBKDF2-SHA1 128/128 SSE2 4x BF/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1024, cost 2 (crypto [0=Blowfish, 1=AES]) of 0 and 1
Raw:    17648 c/s real, 4490 c/s virtual

Benchmarking: Office, 2007/2010/2013 [SHA1 128/128 SSE2 4x / SHA512 128/128 SSE2 2x AES]... (4xOMP) DONE
Speed for cost 1 (MS Office version) of 2007, cost 2 (iteration count) of 50000
Raw:    1408 c/s real, 361 c/s virtual

Benchmarking: oldoffice, MS Office <= 2003 [MD5/SHA1 RC4 32/64]... (4xOMP) DONE
Speed for cost 1 (hash type) of 1 and 0
Many salts:     2125K c/s real, 545083 c/s virtual
Only one salt:  1738K c/s real, 455170 c/s virtual

Benchmarking: OpenBSD-SoftRAID [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (kdf) of 1, cost 2 (iteration count) of 8192
Raw:    2144 c/s real, 538 c/s virtual

Benchmarking: openssl-enc, OpenSSL "enc" encryption (AES-128, MD5) [32/64]... (4xOMP) DONE
Many salts:     7437K c/s real, 1878K c/s virtual
Only one salt:  7197K c/s real, 1803K c/s virtual

Benchmarking: oracle, Oracle 10 [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 255/256
Many salts:     4177K c/s real, 1049K c/s virtual
Only one salt:  3276K c/s real, 821253 c/s virtual

Benchmarking: oracle11, Oracle 11g [SHA1 128/128 SSE2 4x]... DONE
Many salts:     17713K c/s real, 17892K c/s virtual
Only one salt:  14794K c/s real, 14794K c/s virtual

Benchmarking: Oracle12C [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    1411 c/s real, 356 c/s virtual

Benchmarking: osc, osCommerce [md5($s.$p) (OSC) 128/128 SSE2 4x3]... DONE
Many salts:     25277K c/s real, 25532K c/s virtual
Only one salt:  19941K c/s real, 19941K c/s virtual

Benchmarking: ospf, OSPF / IS-IS [HMAC-SHA-X 32/64]... (4xOMP) DONE
Raw:    5612K c/s real, 1420K c/s virtual

Benchmarking: Padlock [PBKDF2-SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1219 c/s real, 367 c/s virtual

Benchmarking: Palshop, MD5(Palshop) [MD5 + SHA1 32/64]... (4xOMP) DONE
Raw:    4112K c/s real, 1777K c/s virtual

Benchmarking: Panama [Panama 32/64]... (4xOMP) DONE
Raw:    2097K c/s real, 720670 c/s virtual

Benchmarking: PBKDF2-HMAC-MD4 [PBKDF2-MD4 128/128 SSE2 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    82707 c/s real, 26304 c/s virtual

Benchmarking: PBKDF2-HMAC-MD5 [PBKDF2-MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    68352 c/s real, 19039 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA1 [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    34048 c/s real, 8576 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA256 [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    14320 c/s real, 3689 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA512, GRUB2 / OS X 10.8+ [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    5808 c/s real, 1462 c/s virtual

Benchmarking: PDF [MD5 SHA2 RC4/AES 32/64]... (4xOMP) DONE
Speed for cost 1 (revision) of 4
Raw:    182016 c/s real, 45847 c/s virtual

Benchmarking: PEM, PKCS#8 private key (RSA/DSA/ECDSA) [PBKDF2-SHA1 128/128 SSE2 4x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4096, cost 2 (cipher [1=3DES, 2/3/4=AES-128/192/256]) of 1
Raw:    7857 c/s real, 1993 c/s virtual

Benchmarking: pfx [PKCS12 PBE (.pfx, .p12) (SHA-1 to SHA-512) 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048, cost 2 (mac-type [1:SHA1 224:SHA224 256:SHA256 384:SHA384 512:SHA512]) of 1
Raw:    32443 c/s real, 8274 c/s virtual

Benchmarking: pgpdisk [PGP Disk / Virtual Disk SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000, cost 2 (algorithm [3=CAST, 4=TwoFish, 5/6/7=AES]) of 5
Raw:    2509 c/s real, 656 c/s virtual

Benchmarking: pgpsda [PGP SDA SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000
Raw:    8861 c/s real, 2236 c/s virtual

Benchmarking: pgpwde [PGP WDE S2K-SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 131072
Raw:    6162 c/s real, 1562 c/s virtual

Benchmarking: phpass ($P$9) [phpass ($P$ or $H$) 128/128 SSE2 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Many salts:     82368 c/s real, 20747 c/s virtual
Only one salt:  81600 c/s real, 20502 c/s virtual

Benchmarking: PHPS [md5(md5($p).$s) 128/128 SSE2 4x3]... DONE
Many salts:     34223K c/s real, 34223K c/s virtual
Only one salt:  12258K c/s real, 12258K c/s virtual

Benchmarking: PHPS2 [md5(md5($p).$s) 128/128 SSE2 4x3]... DONE
Many salts:     34406K c/s real, 34406K c/s virtual
Only one salt:  12149K c/s real, 12149K c/s virtual

Benchmarking: pix-md5, Cisco PIX [md5($p) (Cisco PIX) 128/128 SSE2 4x3]... DONE
Raw:    21557K c/s real, 21557K c/s virtual

Benchmarking: PKZIP [32/64]... (4xOMP) DONE
Many salts:     47915K c/s real, 12069K c/s virtual
Only one salt:  28467K c/s real, 7116K c/s virtual

Benchmarking: po, Post.Office [MD5 32/64]... DONE
Many salts:     4640K c/s real, 4640K c/s virtual
Only one salt:  4414K c/s real, 4414K c/s virtual

Benchmarking: postgres, PostgreSQL C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     12990K c/s real, 3255K c/s virtual
Only one salt:  12376K c/s real, 3101K c/s virtual

Benchmarking: PST, custom CRC-32 [32/64]... DONE
Raw:    91842K c/s real, 92770K c/s virtual

Benchmarking: PuTTY, Private Key (RSA/DSA/ECDSA/ED25519) [SHA1/AES 32/64]... (4xOMP) DONE
Raw:    1212K c/s real, 302348 c/s virtual

Benchmarking: pwsafe, Password Safe [SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    13918 c/s real, 3620 c/s virtual

Benchmarking: qnx, qnx hash (rounds=1000) [QNX 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (algorithm [5:MD5 256:SHA256 512:SHA512]) of 5
Raw:    212831 c/s real, 53601 c/s virtual

Benchmarking: RACF [DES 32/64]... (4xOMP) DONE
Many salts:     33865K c/s real, 8530K c/s virtual
Only one salt:  14495K c/s real, 3642K c/s virtual

Benchmarking: RACF-KDFAES [KDFAES (DES + HMAC-SHA256/64 + AES-256)]... (4xOMP) DONE
Warning: "Many salts" test limited: 2/256
Many salts:     0.6 c/s real, 0.1 c/s virtual
Only one salt:  0.3 c/s real, 0.0 c/s virtual

Benchmarking: radius, RADIUS authentication [MD5 32/64]... (4xOMP) DONE
Many salts:     26013K c/s real, 6585K c/s virtual
Only one salt:  21663K c/s real, 5429K c/s virtual

Benchmarking: RAdmin, v2.x [MD5 32/64]... (4xOMP) DONE
Raw:    13849K c/s real, 4077K c/s virtual

Benchmarking: RAKP, IPMI 2.0 RAKP (RMCP+) [HMAC-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     22126K c/s real, 5615K c/s virtual
Only one salt:  9240K c/s real, 2504K c/s virtual

Benchmarking: rar, RAR3 (length 5) [SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Raw:    308 c/s real, 78.2 c/s virtual

Benchmarking: RAR5 [PBKDF2-SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32768
Raw:    449 c/s real, 113 c/s virtual

Benchmarking: Raw-SHA512 [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    10504K c/s real, 2632K c/s virtual

Benchmarking: Raw-Blake2 [BLAKE2b 512 128/128 SSE2]... (4xOMP) DONE
Raw:    10771K c/s real, 2775K c/s virtual

Benchmarking: Raw-Keccak [Keccak 512 32/64]... (4xOMP) DONE
Raw:    6553K c/s real, 1658K c/s virtual

Benchmarking: Raw-Keccak-256 [Keccak 256 32/64]... (4xOMP) DONE
Raw:    6699K c/s real, 1695K c/s virtual

Benchmarking: Raw-MD4 [MD4 128/128 SSE2 4x3]... DONE
Raw:    50003K c/s real, 50508K c/s virtual

Benchmarking: Raw-MD5 [MD5 128/128 SSE2 4x3]... DONE
Raw:    36543K c/s real, 36543K c/s virtual

Benchmarking: Raw-MD5u [md5(utf16($p)) 128/128 SSE2 4x3]... DONE
Raw:    34757K c/s real, 34757K c/s virtual

Benchmarking: Raw-SHA1 [SHA1 128/128 SSE2 4x]... DONE
Raw:    17581K c/s real, 17581K c/s virtual

Benchmarking: Raw-SHA1-AxCrypt [SHA1 128/128 SSE2 4x]... DONE
Raw:    17517K c/s real, 17517K c/s virtual

Benchmarking: Raw-SHA1-Linkedin [SHA1 128/128 SSE2 4x]... DONE
Raw:    16391K c/s real, 16391K c/s virtual

Benchmarking: Raw-SHA224 [SHA224 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    22274K c/s real, 5596K c/s virtual

Benchmarking: Raw-SHA256 [SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    24870K c/s real, 6248K c/s virtual

Benchmarking: Raw-SHA3 [SHA3 512 32/64]... (4xOMP) DONE
Raw:    6618K c/s real, 1671K c/s virtual

Benchmarking: Raw-SHA384 [SHA384 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    10125K c/s real, 2576K c/s virtual

Benchmarking: ripemd-128, RIPEMD 128 [32/64]... DONE
Raw:    7361K c/s real, 7361K c/s virtual

Benchmarking: ripemd-160, RIPEMD 160 [32/64]... DONE
Raw:    4812K c/s real, 4812K c/s virtual

Benchmarking: rsvp, HMAC-MD5 / HMAC-SHA1, RSVP, IS-IS, OMAPI, RNDC, TSIG [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1 3:SHA224 4:SHA256 5:SHA384 6:SHA512]) of 1 and 2
Many salts:     7802K c/s real, 1955K c/s virtual
Only one salt:  5111K c/s real, 1284K c/s virtual

Benchmarking: Siemens-S7 [HMAC-SHA1 32/64]... (4xOMP) DONE
Many salts:     13647K c/s real, 3437K c/s virtual
Only one salt:  5319K c/s real, 1333K c/s virtual

Benchmarking: Salted-SHA1 [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     56475K c/s real, 14189K c/s virtual
Only one salt:  38305K c/s real, 9600K c/s virtual

Benchmarking: SSHA512, LDAP [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     10960K c/s real, 2753K c/s virtual
Only one salt:  9781K c/s real, 2476K c/s virtual

Benchmarking: sapb, SAP CODVN B (BCODE) [MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Many salts:     30351K c/s real, 7645K c/s virtual
Only one salt:  23101K c/s real, 5833K c/s virtual

Benchmarking: sapg, SAP CODVN F/G (PASSCODE) [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     14426K c/s real, 3661K c/s virtual
Only one salt:  12734K c/s real, 3207K c/s virtual

Benchmarking: saph, SAP CODVN H (PWDSALTEDHASH) (SHA1x1024) [SHA-1/SHA-2 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256 3:SHA384 4:SHA512]) of 1, cost 2 (iteration count) of 1024
Warning: "Many salts" test limited: 229/256
Many salts:     58624 c/s real, 14917 c/s virtual
Only one salt:  59392 c/s real, 14922 c/s virtual

Benchmarking: sappse [PKCS12 PBE SHA1 128/128 SSE2 4x 3DES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    9984 c/s real, 2655 c/s virtual

Benchmarking: securezip, PKWARE SecureZIP [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     1998K c/s real, 537324 c/s virtual
Only one salt:  1802K c/s real, 500622 c/s virtual

Benchmarking: 7z, 7-Zip (512K iterations) [SHA256 128/128 SSE2 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 524288, cost 2 (padding size) of 4 and 9, cost 3 (compression type) of 128 and 1
Many salts:     19140 c/s real, 4899 c/s virtual
Only one salt:  88.8 c/s real, 23.1 c/s virtual

Benchmarking: Signal [Signal Android PKCS12 PBE SHA-1 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 6024 and 6097
Raw:    4572 c/s real, 1151 c/s virtual

Benchmarking: SIP [MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 81/256
Many salts:     10511K c/s real, 2647K c/s virtual
Only one salt:  9961K c/s real, 2502K c/s virtual

Benchmarking: skein-256, Skein 256 [Skein 32/64]... (4xOMP) DONE
Raw:    12466K c/s real, 3124K c/s virtual

Benchmarking: skein-512, Skein 512 [Skein 32/64]... (4xOMP) DONE
Raw:    12482K c/s real, 3128K c/s virtual

Benchmarking: skey, S/Key [MD4/MD5/SHA1/RMD160 32/64]... DONE
Speed for cost 1 (hash type [1:MD4 2:MD5 3:SHA1 4:RMD160]) of 1 and 2, cost 2 (iteration count) of 96 and 99
Raw:    100356 c/s real, 100356 c/s virtual

Benchmarking: SL3, Nokia operator unlock [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     59768K c/s real, 15017K c/s virtual
Only one salt:  28508K c/s real, 7144K c/s virtual

Benchmarking: Snefru-128 [32/64]... (4xOMP) DONE
Raw:    1718K c/s real, 431726 c/s virtual

Benchmarking: Snefru-256 [32/64]... (4xOMP) DONE
Raw:    1714K c/s real, 430697 c/s virtual

Benchmarking: LastPass, sniffed sessions [PBKDF2-SHA256 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 58/256
Many salts:     29401 c/s real, 7405 c/s virtual
Only one salt:  29401 c/s real, 7387 c/s virtual

Benchmarking: SNMP, SNMPv3 USM [HMAC-MD5-96/HMAC-SHA1-96 32/64]... (4xOMP) DONE
Raw:    855 c/s real, 216 c/s virtual

Benchmarking: solarwinds, SolarWinds Orion [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    681 c/s real, 170 c/s virtual

Benchmarking: SSH [RSA/DSA/EC/OPENSSH (SSH private keys) 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF/cipher [0=MD5/AES 1=MD5/3DES 2=Bcrypt/AES]) of 0 and 1, cost 2 (iteration count) of 1 and 2
Raw:    3156K c/s real, 794970 c/s virtual

Benchmarking: sspr, NetIQ SSPR / Adobe AEM [MD5/SHA1/SHA256/SHA512 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF [0:MD5 1:SHA1 2:SHA1_SALT 3:SHA256_SALT 4:SHA512_SALT]) of 1, cost 2 (iteration count) of 100000
Raw:    292 c/s real, 73.4 c/s virtual

Benchmarking: STRIP, Password Manager [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    4347 c/s real, 1097 c/s virtual

Benchmarking: SunMD5 [MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    1846 c/s real, 463 c/s virtual

Benchmarking: SybaseASE, Sybase ASE [SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     12042K c/s real, 3025K c/s virtual
Only one salt:  2875K c/s real, 720649 c/s virtual

Benchmarking: Sybase-PROP [salted FEAL-8 32/64]... (4xOMP) DONE
Many salts:     3484K c/s real, 875545 c/s virtual
Only one salt:  3416K c/s real, 856156 c/s virtual

Benchmarking: tacacs-plus, TACACS+ [MD5 32/64]... (4xOMP) DONE
Many salts:     29239K c/s real, 7346K c/s virtual
Only one salt:  22505K c/s real, 5654K c/s virtual

Benchmarking: tcp-md5, TCP MD5 Signatures, BGP, MSDP [MD5 32/64]... (4xOMP) DONE
Many salts:     28041K c/s real, 7045K c/s virtual
Only one salt:  16343K c/s real, 4085K c/s virtual

Benchmarking: telegram [PBKDF2-SHA1 128/128 SSE2 4x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4000
Raw:    1219 c/s real, 309 c/s virtual

Benchmarking: tezos, Tezos Key [PBKDF2-SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    2788 c/s real, 705 c/s virtual

Benchmarking: Tiger [Tiger 32/64]... (4xOMP) DONE
Raw:    23314K c/s real, 5843K c/s virtual

Benchmarking: tc_aes_xts, TrueCrypt AES256_XTS [SHA512/RIPEMD160/WHIRLPOOL 128/128 SSE2 2x]... (4xOMP) DONE
Speed for cost 1 (hash algorithm [1:SHA512 2:RIPEMD160 3:Whirlpool]) of 1
Raw:    5716 c/s real, 1432 c/s virtual

Benchmarking: tc_ripemd160, TrueCrypt AES256_XTS [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    1122 c/s real, 282 c/s virtual

Benchmarking: tc_ripemd160boot, TrueCrypt AES/Twofish/Serpent [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    2194 c/s real, 556 c/s virtual

Benchmarking: tc_sha512, TrueCrypt AES256_XTS [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Raw:    5688 c/s real, 1432 c/s virtual

Benchmarking: tc_whirlpool, TrueCrypt AES256_XTS [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    2281 c/s real, 571 c/s virtual

Benchmarking: vdi, VirtualBox-VDI AES_XTS [PBKDF2-SHA256 128/128 SSE2 4x + AES_XTS]... (4xOMP) DONE
Raw:    2461 c/s real, 616 c/s virtual

Benchmarking: OpenVMS, Purdy [32/64]... (4xOMP) DONE
Many salts:     4935K c/s real, 1237K c/s virtual
Only one salt:  4770K c/s real, 1198K c/s virtual

Benchmarking: vmx, VMware VMX [PBKDF2-SHA1 AES 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    1710 c/s real, 435 c/s virtual

Benchmarking: VNC [DES 32/64]... (4xOMP) DONE
Many salts:     16973K c/s real, 4264K c/s virtual
Only one salt:  13107K c/s real, 3293K c/s virtual

Benchmarking: vtp, "MD5 based authentication" VTP [MD5 32/64]... (4xOMP) DONE
Many salts:     2759K c/s real, 695957 c/s virtual
Only one salt:  23630 c/s real, 6023 c/s virtual

Benchmarking: wbb3, WoltLab BB3 [SHA1 32/64]... (4xOMP) DONE
Many salts:     7217K c/s real, 1813K c/s virtual
Only one salt:  5328K c/s real, 1342K c/s virtual

Benchmarking: whirlpool [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    7823K c/s real, 1965K c/s virtual

Benchmarking: whirlpool0 [WHIRLPOOL-0 32/64]... (4xOMP) DONE
Raw:    7725K c/s real, 1940K c/s virtual

Benchmarking: whirlpool1 [WHIRLPOOL-1 32/64]... (4xOMP) DONE
Raw:    7577K c/s real, 1908K c/s virtual

Benchmarking: wpapsk, WPA/WPA2/PMF/PMKID PSK [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 2
Raw:    4224 c/s real, 1069 c/s virtual

Benchmarking: wpapsk-pmk, WPA/WPA2/PMF/PMKID master key [MD5/SHA-1/SHA-2]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 1 and 2
Many salts:     2813K c/s real, 705251 c/s virtual
Only one salt:  2922K c/s real, 734295 c/s virtual

Benchmarking: xmpp-scram [XMPP SCRAM PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    8533 c/s real, 2165 c/s virtual

Benchmarking: xsha, Mac OS X 10.4 - 10.6 [SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     59578K c/s real, 14969K c/s virtual
Only one salt:  40060K c/s real, 10040K c/s virtual

Benchmarking: xsha512, Mac OS X 10.7 [SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     10977K c/s real, 2758K c/s virtual
Only one salt:  9961K c/s real, 2502K c/s virtual

Benchmarking: ZIP, WinZip [PBKDF2-SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Raw:    35108 c/s real, 8861 c/s virtual

Benchmarking: ZipMonster, MD5(ZipMonster) [MD5-128/128 SSE2 4x3 x 50000]... (4xOMP) DONE
Raw:    2742 c/s real, 692 c/s virtual

Benchmarking: plaintext, $0$ [n/a]... DONE
Raw:    140411K c/s real, 140411K c/s virtual

Benchmarking: has-160 [HAS-160 32/64]... DONE
Raw:    9852K c/s real, 9852K c/s virtual

Benchmarking: HMAC-MD5 [password is key, MD5 128/128 SSE2 4x3]... (4xOMP) DONE
Many salts:     68861K c/s real, 17301K c/s virtual
Only one salt:  21098K c/s real, 5301K c/s virtual

Benchmarking: HMAC-SHA1 [password is key, SHA1 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     32962K c/s real, 8364K c/s virtual
Only one salt:  11010K c/s real, 2975K c/s virtual

Benchmarking: HMAC-SHA224 [password is key, SHA224 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     14036K c/s real, 3526K c/s virtual
Only one salt:  6254K c/s real, 1567K c/s virtual

Benchmarking: HMAC-SHA256 [password is key, SHA256 128/128 SSE2 4x]... (4xOMP) DONE
Many salts:     14012K c/s real, 3529K c/s virtual
Only one salt:  5910K c/s real, 1515K c/s virtual

Benchmarking: HMAC-SHA384 [password is key, SHA384 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     5200K c/s real, 1306K c/s virtual
Only one salt:  2623K c/s real, 659103 c/s virtual

Benchmarking: HMAC-SHA512 [password is key, SHA512 128/128 SSE2 2x]... (4xOMP) DONE
Many salts:     5092K c/s real, 1282K c/s virtual
Only one salt:  2591K c/s real, 651191 c/s virtual

Benchmarking: dynamic_0 [md5($p) (raw-md5) 128/128 SSE2 4x3]... DONE
Raw:    35091K c/s real, 35446K c/s virtual

Benchmarking: dynamic_1 [md5($p.$s) (joomla) 128/128 SSE2 4x3]... DONE
Many salts:     22532K c/s real, 22759K c/s virtual
Only one salt:  18090K c/s real, 18090K c/s virtual

Benchmarking: dynamic_2 [md5(md5($p)) (e107) 128/128 SSE2 4x3]... DONE
Raw:    17750K c/s real, 17575K c/s virtual

Benchmarking: dynamic_3 [md5(md5(md5($p))) 128/128 SSE2 4x3]... DONE
Raw:    11788K c/s real, 11788K c/s virtual

Benchmarking: dynamic_4 [md5($s.$p) (OSC) 128/128 SSE2 4x3]... DONE
Many salts:     25016K c/s real, 25016K c/s virtual
Only one salt:  18945K c/s real, 18945K c/s virtual

Benchmarking: dynamic_5 [md5($s.$p.$s) 128/128 SSE2 4x3]... DONE
Many salts:     19978K c/s real, 19978K c/s virtual
Only one salt:  15531K c/s real, 15531K c/s virtual

Benchmarking: dynamic_6 [md5(md5($p).$s) 128/128 SSE2 4x3]... DONE
Many salts:     31354K c/s real, 31668K c/s virtual
Only one salt:  11983K c/s real, 11983K c/s virtual

Benchmarking: dynamic_8 [md5(md5($s).$p) 128/128 SSE2 4x3]... DONE
Many salts:     25897K c/s real, 25897K c/s virtual
Only one salt:  20265K c/s real, 20265K c/s virtual

Benchmarking: dynamic_9 [md5($s.md5($p)) 128/128 SSE2 4x3]... DONE
Many salts:     24983K c/s real, 24983K c/s virtual
Only one salt:  11976K c/s real, 11976K c/s virtual

Benchmarking: dynamic_10 [md5($s.md5($s.$p)) 128/128 SSE2 4x3]... DONE
Many salts:     12176K c/s real, 12176K c/s virtual
Only one salt:  10736K c/s real, 10736K c/s virtual

Benchmarking: dynamic_11 [md5($s.md5($p.$s)) 128/128 SSE2 4x3]... DONE
Many salts:     12274K c/s real, 12274K c/s virtual
Only one salt:  10872K c/s real, 10872K c/s virtual

Benchmarking: dynamic_12 [md5(md5($s).md5($p)) (IPB) 128/128 SSE2 4x3]... DONE
Many salts:     15217K c/s real, 15217K c/s virtual
Only one salt:  7785K c/s real, 7785K c/s virtual

Benchmarking: dynamic_13 [md5(md5($p).md5($s)) 128/128 SSE2 4x3]... DONE
Many salts:     15207K c/s real, 15207K c/s virtual
Only one salt:  7766K c/s real, 7766K c/s virtual

Benchmarking: dynamic_14 [md5($s.md5($p).$s) 128/128 SSE2 4x3]... DONE
Many salts:     20383K c/s real, 20383K c/s virtual
Only one salt:  10856K c/s real, 10856K c/s virtual

Benchmarking: dynamic_15 [md5($u.md5($p).$s) 128/128 SSE2 4x3]... DONE
Many salts:     19392K c/s real, 19392K c/s virtual
Only one salt:  8736K c/s real, 8736K c/s virtual

Benchmarking: dynamic_16 [md5(md5(md5($p).$s).$s2) 128/128 SSE2 4x3]... DONE
Many salts:     10360K c/s real, 10360K c/s virtual
Only one salt:  6294K c/s real, 6294K c/s virtual

Benchmarking: dynamic_18 [md5($s.Y.$p.0xF7.$s) (Post.Office MD5) 32/64 x2]... DONE
Many salts:     4712K c/s real, 4712K c/s virtual
Only one salt:  4452K c/s real, 4452K c/s virtual

Benchmarking: dynamic_19 [md5($p) (Cisco PIX) 128/128 SSE2 4x3]... DONE
Raw:    22354K c/s real, 22354K c/s virtual

Benchmarking: dynamic_20 [md5($p.$s) (Cisco ASA) 128/128 SSE2 4x3]... DONE
Many salts:     23760K c/s real, 23760K c/s virtual
Only one salt:  19066K c/s real, 19066K c/s virtual

Benchmarking: dynamic_22 [md5(sha1($p)) 128/128 SSE2 4x1]... DONE
Raw:    8196K c/s real, 8196K c/s virtual

Benchmarking: dynamic_23 [sha1(md5($p)) 128/128 SSE2 4x1]... DONE
Raw:    9401K c/s real, 9401K c/s virtual

Benchmarking: dynamic_24 [sha1($p.$s) 128/128 SSE2 4x1]... DONE
Many salts:     12865K c/s real, 12865K c/s virtual
Only one salt:  11371K c/s real, 11371K c/s virtual

Benchmarking: dynamic_25 [sha1($s.$p) 128/128 SSE2 4x1]... DONE
Many salts:     12882K c/s real, 12882K c/s virtual
Only one salt:  11164K c/s real, 11276K c/s virtual

Benchmarking: dynamic_26 [sha1($p) raw-sha1 128/128 SSE2 4x1]... DONE
Raw:    12757K c/s real, 12757K c/s virtual

Benchmarking: dynamic_29 [md5(utf16($p)) 128/128 SSE2 4x3]... DONE
Raw:    23197K c/s real, 23197K c/s virtual

Benchmarking: dynamic_30 [md4($p) (raw-md4) 128/128 SSE2 4x3]... DONE
Raw:    46159K c/s real, 46159K c/s virtual

Benchmarking: dynamic_31 [md4($s.$p) 128/128 SSE2 4x3]... DONE
Many salts:     32224K c/s real, 32224K c/s virtual
Only one salt:  24086K c/s real, 24086K c/s virtual

Benchmarking: dynamic_32 [md4($p.$s) 128/128 SSE2 4x3]... DONE
Many salts:     28237K c/s real, 28237K c/s virtual
Only one salt:  22029K c/s real, 22029K c/s virtual

Benchmarking: dynamic_33 [md4(utf16($p)) 128/128 SSE2 4x3]... DONE
Raw:    27770K c/s real, 28050K c/s virtual

Benchmarking: dynamic_34 [md5(md4($p)) 128/128 SSE2 4x3]... DONE
Raw:    20028K c/s real, 20028K c/s virtual

Benchmarking: dynamic_35 [sha1(uc($u).:.$p) (ManGOS) 128/128 SSE2 4x1]... DONE
Many salts:     12300K c/s real, 12300K c/s virtual
Only one salt:  11022K c/s real, 11022K c/s virtual

Benchmarking: dynamic_36 [sha1($u.:.$p) (ManGOS2) 128/128 SSE2 4x1]... DONE
Many salts:     12163K c/s real, 12163K c/s virtual
Only one salt:  10928K c/s real, 10928K c/s virtual

Benchmarking: dynamic_37 [sha1(lc($u).$p) (SMF) 128/128 SSE2 4x1]... DONE
Many salts:     12934K c/s real, 12934K c/s virtual
Only one salt:  11469K c/s real, 11469K c/s virtual

Benchmarking: dynamic_38 [sha1($s.sha1($s.sha1($p))) (Wolt3BB) 128/128 SSE2 4x1]... DONE
Many salts:     2756K c/s real, 2756K c/s virtual
Only one salt:  2738K c/s real, 2738K c/s virtual

Benchmarking: dynamic_39 [md5($s.pad16($p)) (net-md5) 128/128 SSE2 4x3]... DONE
Many salts:     10463K c/s real, 10463K c/s virtual
Only one salt:  9542K c/s real, 9542K c/s virtual

Benchmarking: dynamic_40 [sha1($s.pad20($p)) (net-sha1) 128/128 SSE2 4x1]... DONE
Many salts:     10284K c/s real, 10284K c/s virtual
Only one salt:  9264K c/s real, 9357K c/s virtual

Benchmarking: dynamic_50 [sha224($p) 128/128 SSE2 4x]... DONE
Raw:    6684K c/s real, 6684K c/s virtual

Benchmarking: dynamic_60 [sha256($p) 128/128 SSE2 4x]... DONE
Raw:    6651K c/s real, 6651K c/s virtual

Benchmarking: dynamic_61 [sha256($s.$p) 128/128 SSE2 4x]... DONE
Many salts:     6180K c/s real, 6180K c/s virtual
Only one salt:  5822K c/s real, 5822K c/s virtual

Benchmarking: dynamic_70 [sha384($p) 128/128 SSE2 2x]... DONE
Raw:    2965K c/s real, 2965K c/s virtual

Benchmarking: dynamic_80 [sha512($p) 128/128 SSE2 2x]... DONE
Raw:    2959K c/s real, 2959K c/s virtual

Benchmarking: dynamic_90 [gost($p) 64/64]... DONE
Raw:    690480 c/s real, 690480 c/s virtual

Benchmarking: dynamic_100 [whirlpool($p) 32/64 OpenSSL]... DONE
Raw:    2279K c/s real, 2279K c/s virtual

Benchmarking: dynamic_110 [tiger($p) 32/64 sph_tiger]... DONE
Raw:    7449K c/s real, 7449K c/s virtual

Benchmarking: dynamic_120 [ripemd128($p) 32/64 sph_ripemd]... DONE
Raw:    7170K c/s real, 7170K c/s virtual

Benchmarking: dynamic_130 [ripemd160($p) 32/64 sph_ripemd]... DONE
Raw:    4603K c/s real, 4603K c/s virtual

Benchmarking: dynamic_140 [ripemd256($p) 32/64 sph_ripemd]... DONE
Raw:    6202K c/s real, 6202K c/s virtual

Benchmarking: dynamic_150 [ripemd320($p) 32/64 sph_ripemd]... DONE
Raw:    4305K c/s real, 4305K c/s virtual

Benchmarking: dynamic_160 [haval128_3($p) 32/64 sph_haval]... DONE
Raw:    4494K c/s real, 4494K c/s virtual

Benchmarking: dynamic_170 [haval128_4($p) 32/64 sph_haval]... DONE
Raw:    3339K c/s real, 3339K c/s virtual

Benchmarking: dynamic_180 [haval128_5($p) 32/64 sph_haval]... DONE
Raw:    2950K c/s real, 2950K c/s virtual

Benchmarking: dynamic_190 [haval160_3($p) 32/64 sph_haval]... DONE
Raw:    4784K c/s real, 4784K c/s virtual

Benchmarking: dynamic_200 [haval160_4($p) 32/64 sph_haval]... DONE
Raw:    3381K c/s real, 3381K c/s virtual

Benchmarking: dynamic_210 [haval160_5($p) 32/64 sph_haval]... DONE
Raw:    2941K c/s real, 2941K c/s virtual

Benchmarking: dynamic_220 [haval192_3($p) 32/64 sph_haval]... DONE
Raw:    4735K c/s real, 4689K c/s virtual

Benchmarking: dynamic_230 [haval192_4($p) 32/64 sph_haval]... DONE
Raw:    3378K c/s real, 3412K c/s virtual

Benchmarking: dynamic_240 [haval192_5($p) 32/64 sph_haval]... DONE
Raw:    2889K c/s real, 2889K c/s virtual

Benchmarking: dynamic_250 [haval224_3($p) 32/64 sph_haval]... DONE
Raw:    4796K c/s real, 4796K c/s virtual

Benchmarking: dynamic_260 [haval224_4($p) 32/64 sph_haval]... DONE
Raw:    3348K c/s real, 3348K c/s virtual

Benchmarking: dynamic_270 [haval224_5($p) 32/64 sph_haval]... DONE
Raw:    2956K c/s real, 2956K c/s virtual

Benchmarking: dynamic_280 [haval256_3($p) 32/64 sph_haval]... DONE
Raw:    4872K c/s real, 4872K c/s virtual

Benchmarking: dynamic_290 [haval256_4($p) 32/64 sph_haval]... DONE
Raw:    3402K c/s real, 3402K c/s virtual

Benchmarking: dynamic_300 [haval256_5($p) 32/64 sph_haval]... DONE
Raw:    2958K c/s real, 2958K c/s virtual

Benchmarking: dynamic_310 [md2($p) 32/64 sph_md2]... DONE
Raw:    217900 c/s real, 217900 c/s virtual

Benchmarking: dynamic_320 [panama($p) 32/64 sph_panama]... DONE
Raw:    1206K c/s real, 1206K c/s virtual

Benchmarking: dynamic_330 [skein224($p) 32/64 sph_skein]... DONE
Raw:    3942K c/s real, 3942K c/s virtual

Benchmarking: dynamic_340 [skein256($p) 32/64 sph_skein]... DONE
Raw:    3731K c/s real, 3731K c/s virtual

Benchmarking: dynamic_350 [skein384($p) 32/64 sph_skein]... DONE
Raw:    3899K c/s real, 3899K c/s virtual

Benchmarking: dynamic_360 [skein512($p) 32/64 sph_skein]... DONE
Raw:    3842K c/s real, 3880K c/s virtual

Benchmarking: dynamic_370 [sha3_224($p) 64/64 keccak]... DONE
Raw:    1906K c/s real, 1906K c/s virtual

Benchmarking: dynamic_380 [sha3_256($p) 64/64 keccak]... DONE
Raw:    2010K c/s real, 2010K c/s virtual

Benchmarking: dynamic_390 [sha3_384($p) 64/64 keccak]... DONE
Raw:    1985K c/s real, 1985K c/s virtual

Benchmarking: dynamic_400 [sha3_512($p) 64/64 keccak]... DONE
Raw:    1985K c/s real, 1985K c/s virtual

Benchmarking: dynamic_410 [keccak_256($p) 64/64 keccak]... DONE
Raw:    1999K c/s real, 1999K c/s virtual

Benchmarking: dynamic_420 [keccak_512($p) 64/64 keccak]... DONE
Raw:    1994K c/s real, 1994K c/s virtual

Benchmarking: dynamic_1001 [md5(md5(md5(md5($p)))) 128/128 SSE2 4x3]... DONE
Raw:    8699K c/s real, 8699K c/s virtual

Benchmarking: dynamic_1002 [md5(md5(md5(md5(md5($p))))) 128/128 SSE2 4x3]... DONE
Raw:    6909K c/s real, 6909K c/s virtual

Benchmarking: dynamic_1003 [md5(md5($p).md5($p)) 128/128 SSE2 4x3]... DONE
Raw:    7763K c/s real, 7763K c/s virtual

Benchmarking: dynamic_1004 [md5(md5(md5(md5(md5(md5($p)))))) 128/128 SSE2 4x3]... DONE
Raw:    5750K c/s real, 5750K c/s virtual

Benchmarking: dynamic_1005 [md5(md5(md5(md5(md5(md5(md5($p))))))) 128/128 SSE2 4x3]... DONE
Raw:    4883K c/s real, 4932K c/s virtual

Benchmarking: dynamic_1006 [md5(md5(md5(md5(md5(md5(md5(md5($p)))))))) 128/128 SSE2 4x3]... DONE
Raw:    4324K c/s real, 4324K c/s virtual

Benchmarking: dynamic_1007 [md5(md5($p).$s) (vBulletin) 128/128 SSE2 4x3]... DONE
Many salts:     34734K c/s real, 34734K c/s virtual
Only one salt:  12205K c/s real, 12327K c/s virtual

Benchmarking: dynamic_1008 [md5($p.$s) (RADIUS User-Password) 128/128 SSE2 4x3]... DONE
Many salts:     23543K c/s real, 23543K c/s virtual
Only one salt:  18889K c/s real, 18889K c/s virtual

Benchmarking: dynamic_1009 [md5($s.$p) (RADIUS Responses) 128/128 SSE2 4x3]... DONE
Many salts:     25930K c/s real, 26192K c/s virtual
Only one salt:  20830K c/s real, 20830K c/s virtual

Benchmarking: dynamic_1010 [md5($p null_padded_to_len_100) RAdmin v2.x MD5 128/128 SSE2 4x3]... DONE
Raw:    13268K c/s real, 13268K c/s virtual

Benchmarking: dynamic_1011 [md5($p.md5($s)) (webEdition CMS) 128/128 SSE2 4x3]... DONE
Many salts:     10308K c/s real, 10308K c/s virtual
Only one salt:  9303K c/s real, 9303K c/s virtual

Benchmarking: dynamic_1012 [md5($p.md5($s)) (webEdition CMS) 128/128 SSE2 4x3]... DONE
Many salts:     22760K c/s real, 22760K c/s virtual
Only one salt:  18231K c/s real, 18231K c/s virtual

Benchmarking: dynamic_1013 [md5($p.PMD5(username)) (webEdition CMS) 128/128 SSE2 4x3]... DONE
Many salts:     22742K c/s real, 22742K c/s virtual
Only one salt:  18253K c/s real, 18253K c/s virtual

Benchmarking: dynamic_1014 [md5($p.$s) (long salt) 128/128 SSE2 4x3]... DONE
Many salts:     10011K c/s real, 10011K c/s virtual
Only one salt:  8027K c/s real, 8027K c/s virtual

Benchmarking: dynamic_1015 [md5(md5($p.$u).$s) (PostgreSQL 'pass the hash') 128/128 SSE2 4x3]... DONE
Many salts:     12768K c/s real, 12768K c/s virtual
Only one salt:  11116K c/s real, 11116K c/s virtual

Benchmarking: dynamic_1016 [md5($p.$s) (long salt) 128/128 SSE2 4x3]... DONE
Many salts:     17376K c/s real, 17376K c/s virtual
Only one salt:  14851K c/s real, 14851K c/s virtual

Benchmarking: dynamic_1017 [md5($s.$p) (long salt) 128/128 SSE2 4x3]... DONE
Many salts:     11524K c/s real, 11641K c/s virtual
Only one salt:  10619K c/s real, 10619K c/s virtual

Benchmarking: dynamic_1018 [md5(sha1(sha1($p))) 128/128 SSE2 4x1]... DONE
Raw:    4984K c/s real, 4984K c/s virtual

Benchmarking: dynamic_1019 [md5(sha1(sha1(md5($p)))) 128/128 SSE2 4x1]... DONE
Raw:    4373K c/s real, 4373K c/s virtual

Benchmarking: dynamic_1020 [md5(sha1(md5($p))) 128/128 SSE2 4x1]... DONE
Raw:    6676K c/s real, 6676K c/s virtual

Benchmarking: dynamic_1021 [md5(sha1(md5(sha1($p)))) 128/128 SSE2 4x1]... DONE
Raw:    4112K c/s real, 4112K c/s virtual

Benchmarking: dynamic_1022 [md5(sha1(md5(sha1(md5($p))))) 128/128 SSE2 4x1]... DONE
Raw:    3662K c/s real, 3662K c/s virtual

Benchmarking: dynamic_1023 [sha1($p) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    12561K c/s real, 12561K c/s virtual

Benchmarking: dynamic_1024 [sha1(md5($p)) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    9421K c/s real, 9421K c/s virtual

Benchmarking: dynamic_1025 [sha1(md5(md5($p))) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    7482K c/s real, 7482K c/s virtual

Benchmarking: dynamic_1026 [sha1(sha1($p)) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    6434K c/s real, 6434K c/s virtual

Benchmarking: dynamic_1027 [sha1(sha1(sha1($p))) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    4196K c/s real, 4238K c/s virtual

Benchmarking: dynamic_1028 [sha1(sha1_raw($p)) (hash truncated to length 32) 128/128 SSE2 4x1]... DONE
Raw:    6728K c/s real, 6728K c/s virtual

Benchmarking: dynamic_1029 [sha256($p) (hash truncated to length 32) 128/128 SSE2 4x]... DONE
Raw:    5722K c/s real, 5722K c/s virtual

Benchmarking: dynamic_1030 [whirlpool($p) (hash truncated to length 32) 32/64 OpenSSL]... DONE
Raw:    2219K c/s real, 2219K c/s virtual

Benchmarking: dynamic_1031 [gost($p) (hash truncated to length 32) 64/64]... DONE
Raw:    687120 c/s real, 687120 c/s virtual

Benchmarking: dynamic_1032 [sha1_64(utf16($p)) (PeopleSoft) 128/128 SSE2 4x1]... DONE
Raw:    10244K c/s real, 10244K c/s virtual

Benchmarking: dynamic_1034 [md5($p.$u) (PostgreSQL MD5) 128/128 SSE2 4x3]... DONE
Many salts:     23861K c/s real, 23861K c/s virtual
Only one salt:  19059K c/s real, 19059K c/s virtual

Benchmarking: dynamic_1300 [md5(md5_raw($p)) 128/128 SSE2 4x3]... DONE
Raw:    14930K c/s real, 14930K c/s virtual

Benchmarking: dynamic_1350 [md5(md5($s.$p):$s) 128/128 SSE2 4x3]... DONE
Many salts:     12510K c/s real, 12510K c/s virtual
Only one salt:  11066K c/s real, 11066K c/s virtual

Benchmarking: dynamic_1400 [sha1(utf16($p)) (Microsoft CREDHIST) 128/128 SSE2 4x1]... DONE
Raw:    8816K c/s real, 8816K c/s virtual

Benchmarking: dynamic_1401 [md5($u.\nskyper\n.$p) (Skype MD5) 128/128 SSE2 4x3]... DONE
Many salts:     11145K c/s real, 11145K c/s virtual
Only one salt:  8574K c/s real, 8574K c/s virtual

Benchmarking: dynamic_1501 [sha1($s.sha1($p)) (Redmine) 128/128 SSE2 4x1]... DONE
Many salts:     7333K c/s real, 7333K c/s virtual
Only one salt:  4242K c/s real, 4242K c/s virtual

Benchmarking: dynamic_1502 [sha1(sha1($p).$s) (XenForo SHA-1) 128/128 SSE2 4x1]... DONE
Many salts:     13668K c/s real, 13668K c/s virtual
Only one salt:  5987K c/s real, 5987K c/s virtual

Benchmarking: dynamic_1503 [sha256(sha256($p).$s) (XenForo SHA-256) 128/128 SSE2 4x]... DONE
Many salts:     2511K c/s real, 2511K c/s virtual
Only one salt:  1747K c/s real, 1747K c/s virtual

Benchmarking: dynamic_1504 [sha1($s.$p.$s) 128/128 SSE2 4x1]... DONE
Many salts:     12314K c/s real, 12314K c/s virtual
Only one salt:  10831K c/s real, 10940K c/s virtual

Benchmarking: dynamic_1505 [md5($p.$s.md5($p.$s)) 128/128 SSE2 4x3]... DONE
Many salts:     7202K c/s real, 7202K c/s virtual
Only one salt:  6746K c/s real, 6746K c/s virtual

Benchmarking: dynamic_1506 [md5($u.:XDB:.$p) (Oracle 12c "H" hash) 128/128 SSE2 4x3]... DONE
Many salts:     21231K c/s real, 21231K c/s virtual
Only one salt:  17194K c/s real, 17194K c/s virtual

Benchmarking: dynamic_1507 [sha1(utf16($const.$p)) (Mcafee master pass) 128/128 SSE2 4x1]... DONE
Raw:    9698K c/s real, 9698K c/s virtual

Benchmarking: dynamic_1518 [md5(sha1($p).md5($p).sha1($p)) 128/128 SSE2 4x1]... DONE
Raw:    3578K c/s real, 3578K c/s virtual

Benchmarking: dynamic_1528 [sha256($s.$p.$s) (Telegram for Android) 128/128 SSE2 4x]... DONE
Many salts:     6541K c/s real, 6541K c/s virtual
Only one salt:  6135K c/s real, 6135K c/s virtual

Benchmarking: dynamic_1529 [sha1($p null_padded_to_len_32) (DeepSound) 128/128 SSE2 4x1]... DONE
Raw:    10516K c/s real, 10516K c/s virtual

Benchmarking: dynamic_1550 [md5($u.:mongo:.$p) (MONGODB-CR system hash) 128/128 SSE2 4x3]... DONE
Many salts:     19911K c/s real, 19911K c/s virtual
Only one salt:  16425K c/s real, 16425K c/s virtual

Benchmarking: dynamic_1551 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 128/128 SSE2 4x3]... DONE
Many salts:     10646K c/s real, 10646K c/s virtual
Only one salt:  9550K c/s real, 9550K c/s virtual

Benchmarking: dynamic_1552 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 128/128 SSE2 4x3]... DONE
Many salts:     7439K c/s real, 7439K c/s virtual
Only one salt:  7017K c/s real, 7087K c/s virtual

Benchmarking: dynamic_1560 [md5($s.$p.$s2) (SocialEngine) 128/128 SSE2 4x3]... DONE
Many salts:     16107K c/s real, 16107K c/s virtual
Only one salt:  13903K c/s real, 13903K c/s virtual

Benchmarking: dynamic_1588 [sha256($s.sha1($p)) (ColdFusion 11) 128/128 SSE2 4x]... DONE
Many salts:     2814K c/s real, 2814K c/s virtual
Only one salt:  2731K c/s real, 2731K c/s virtual

Benchmarking: dynamic_1590 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 128/128 SSE2 4x1]... DONE
Many salts:     11684K c/s real, 11684K c/s virtual
Only one salt:  10422K c/s real, 10422K c/s virtual

Benchmarking: dynamic_1592 [sha1($s.sha1($s.sha1($p))) (wbb3) 128/128 SSE2 4x1]... DONE
Many salts:     3679K c/s real, 3679K c/s virtual
Only one salt:  2661K c/s real, 2661K c/s virtual

Benchmarking: dynamic_1600 [sha1($s.utf16le($p)) (Oracle PeopleSoft PS_TOKEN) 128/128 SSE2 4x1]... DONE
Many salts:     5552K c/s real, 5552K c/s virtual
Only one salt:  4628K c/s real, 4628K c/s virtual

Benchmarking: dynamic_1602 [sha256(#.$salt.-.$pass) (QAS vas_auth) 128/128 SSE2 4x]... DONE
Many salts:     5876K c/s real, 5876K c/s virtual
Only one salt:  5392K c/s real, 5392K c/s virtual

Benchmarking: dynamic_1608 [sha256(sha256_raw(sha256_raw($p))) (Neo Wallet) 128/128 SSE2 4x]... DONE
Raw:    2254K c/s real, 2254K c/s virtual

Benchmarking: dynamic_2000 [md5($p) (PW > 55 bytes) 128/128 SSE2 4x3]... DONE
Raw:    22004K c/s real, 22004K c/s virtual

Benchmarking: dynamic_2001 [md5($p.$s) (joomla) (PW > 23 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     22335K c/s real, 22335K c/s virtual
Only one salt:  18093K c/s real, 18093K c/s virtual

Benchmarking: dynamic_2002 [md5(md5($p)) (e107) (PW > 55 bytes) 128/128 SSE2 4x3]... DONE
Raw:    10963K c/s real, 10963K c/s virtual

Benchmarking: dynamic_2003 [md5(md5(md5($p))) (PW > 55 bytes) 128/128 SSE2 4x3]... DONE
Raw:    7286K c/s real, 7286K c/s virtual

Benchmarking: dynamic_2004 [md5($s.$p) (OSC) (PW > 31 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     22055K c/s real, 22055K c/s virtual
Only one salt:  17772K c/s real, 17772K c/s virtual

Benchmarking: dynamic_2005 [md5($s.$p.$s) (PW > 31 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     20548K c/s real, 20548K c/s virtual
Only one salt:  16892K c/s real, 16892K c/s virtual

Benchmarking: dynamic_2006 [md5(md5($p).$s) (PW > 55 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     25420K c/s real, 25420K c/s virtual
Only one salt:  9859K c/s real, 9859K c/s virtual

Benchmarking: dynamic_2008 [md5(md5($s).$p) (PW > 23 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     22184K c/s real, 22184K c/s virtual
Only one salt:  18043K c/s real, 18043K c/s virtual

Benchmarking: dynamic_2009 [md5($s.md5($p)) (salt > 23 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     21915K c/s real, 21915K c/s virtual
Only one salt:  9048K c/s real, 9048K c/s virtual

Benchmarking: dynamic_2010 [md5($s.md5($s.$p)) (PW > 32 or salt > 23 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     10451K c/s real, 10347K c/s virtual
Only one salt:  9439K c/s real, 9439K c/s virtual

Benchmarking: dynamic_2011 [md5($s.md5($p.$s)) (PW > 32 or salt > 23 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     9702K c/s real, 9702K c/s virtual
Only one salt:  9401K c/s real, 9401K c/s virtual

Benchmarking: dynamic_2014 [md5($s.md5($p).$s) (PW > 55 or salt > 11 bytes) 128/128 SSE2 4x3]... DONE
Many salts:     20166K c/s real, 20166K c/s virtual
Only one salt:  8791K c/s real, 8791K c/s virtual

Benchmarking: dummy [N/A]... DONE
Raw:    66145K c/s real, 66145K c/s virtual

Benchmarking: crypt, generic crypt(3) [?/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [1:descrypt 2:md5crypt 3:sunmd5 4:bcrypt 5:sha256crypt 6:sha512crypt]) of 1, cost 2 (algorithm specific iterations) of 1
Many salts:     714816 c/s real, 179151 c/s virtual
Only one salt:  388224 c/s real, 114520 c/s virtual

All 405 formats passed self-tests!
1627611087.264650796
```

