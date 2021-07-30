```shell
kali$ john --test
1627509416.828506084
Will run 4 OpenMP threads
Benchmarking: descrypt, traditional crypt(3) [DES 256/256 AVX2]... (4xOMP) DONE
Many salts:     23216K c/s real, 5862K c/s virtual
Only one salt:  21151K c/s real, 5327K c/s virtual

Benchmarking: bsdicrypt, BSDI crypt(3) ("_J9..", 725 iterations) [DES 256/256 AVX2]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 725
Many salts:     893211 c/s real, 225536 c/s virtual
Only one salt:  764928 c/s real, 191711 c/s virtual

Benchmarking: md5crypt, crypt(3) $1$ (and variants) [MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Many salts:     238764 c/s real, 59543 c/s virtual
Only one salt:  240000 c/s real, 60150 c/s virtual

Benchmarking: md5crypt-long, crypt(3) $1$ (and variants) [MD5 32/64]... (4xOMP) DONE
Raw:    23968 c/s real, 6007 c/s virtual

Benchmarking: bcrypt ("$2a$05", 32 iterations) [Blowfish 32/64 X3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32
Raw:    3564 c/s real, 893 c/s virtual

Benchmarking: scrypt (16384, 8, 1) [Salsa20/8 128/128 AVX]... (4xOMP) DONE
Speed for cost 1 (N) of 16384, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    150 c/s real, 37.7 c/s virtual

Benchmarking: LM [DES 256/256 AVX2]... (4xOMP) DONE
Raw:    112541K c/s real, 28205K c/s virtual

Benchmarking: AFS, Kerberos AFS [DES 48/64 4K]... DONE
Short:  490201 c/s real, 471527 c/s virtual
Long:   2008K c/s real, 2028K c/s virtual

Benchmarking: tripcode [DES 256/256 AVX2]... (4xOMP) DONE
Raw:    15466K c/s real, 3866K c/s virtual

Benchmarking: AndroidBackup [PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    3657 c/s real, 975 c/s virtual

Benchmarking: adxcrypt [IBM/Toshiba 4690 - ADXCRYPT 32/64]... (4xOMP) DONE
Raw:    73711K c/s real, 18473K c/s virtual

Benchmarking: agilekeychain, 1Password Agile Keychain [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    52480 c/s real, 13120 c/s virtual

Benchmarking: aix-ssha1, AIX LPA {ssha1} [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     855424 c/s real, 213856 c/s virtual
Only one salt:  739072 c/s real, 185231 c/s virtual

Benchmarking: aix-ssha256, AIX LPA {ssha256} [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     364544 c/s real, 91136 c/s virtual
Only one salt:  374272 c/s real, 93802 c/s virtual

Benchmarking: aix-ssha512, AIX LPA {ssha512} [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64
Many salts:     166208 c/s real, 41552 c/s virtual
Only one salt:  146176 c/s real, 36362 c/s virtual

Benchmarking: andOTP [SHA256 32/64]... (4xOMP) DONE
Raw:    770534 c/s real, 194074 c/s virtual

Benchmarking: ansible, Ansible Vault [PBKDF2-SHA256 HMAC-256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    2920 c/s real, 731 c/s virtual

Benchmarking: argon2 [Blake2 AVX]... (4xOMP) DONE
Speed for cost 1 (t) of 3, cost 2 (m) of 4096, cost 3 (p) of 1, cost 4 (type [0:Argon2d 1:Argon2i]) of 0 and 1
Raw:    384 c/s real, 97.9 c/s virtual

Benchmarking: as400-des, AS/400 DES [DES 32/64]... DONE
Raw:    547455 c/s real, 137551 c/s virtual

Benchmarking: as400-ssha1, AS400-SaltedSHA1 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 256/256 AVX2 8x1]... DONE
Many salts:     14348K c/s real, 14491K c/s virtual
Only one salt:  11077K c/s real, 10968K c/s virtual

Benchmarking: asa-md5, Cisco ASA [md5($p.$s) (Cisco ASA) 256/256 AVX2 8x3]... DONE
Many salts:     30727K c/s real, 31037K c/s virtual
Only one salt:  18829K c/s real, 18643K c/s virtual

Benchmarking: AxCrypt [PBKDF2-SHA512/SHA1 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1337 and 60000
Raw:    705 c/s real, 191 c/s virtual

Benchmarking: AzureAD [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     262144 c/s real, 65372 c/s virtual
Only one salt:  254464 c/s real, 63616 c/s virtual

Benchmarking: BestCrypt (SHA-256 + AES XTS mode) [Jetico BestCrypt (.jbc) PKCS12 PBE (Whirlpool / SHA-1 to SHA-512) 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    412 c/s real, 103 c/s virtual

Benchmarking: bfegg, Eggdrop [Blowfish 32/64]... (4xOMP) DONE
Raw:    119635 c/s real, 29908 c/s virtual

Benchmarking: Bitcoin, Bitcoin Core [SHA512 AES 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 177864
Raw:    137 c/s real, 36.4 c/s virtual

Benchmarking: BitLocker, BitLocker [SHA-256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1048576
Raw:    7.4 c/s real, 2.0 c/s virtual

Benchmarking: bitshares, BitShares Wallet [SHA-512 64/64]... (4xOMP) DONE
Many salts:     3776K c/s real, 944128 c/s virtual
Only one salt:  4048K c/s real, 1012K c/s virtual

Benchmarking: Bitwarden, Bitwarden Password Manager [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    6144 c/s real, 1674 c/s virtual

Benchmarking: BKS [PKCS12 PBE 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    51697 c/s real, 13446 c/s virtual

Benchmarking: Blackberry-ES10 (101x) [SHA-512 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     225280 c/s real, 56039 c/s virtual
Only one salt:  228352 c/s real, 57088 c/s virtual

Benchmarking: WoWSRP, Battlenet [SHA1 32/64 GMP-exp]... (4xOMP) DONE
Many salts:     340992 c/s real, 85248 c/s virtual
Only one salt:  290978 c/s real, 73288 c/s virtual

Benchmarking: Blockchain, My Wallet (v2 x5000) [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    7027 c/s real, 1921 c/s virtual

Benchmarking: chap, iSCSI CHAP authentication / EAP-MD5 [MD5 32/64]... (4xOMP) DONE
Many salts:     21315K c/s real, 5342K c/s virtual
Only one salt:  17063K c/s real, 4255K c/s virtual

Benchmarking: Clipperz, SRP [SHA256 32/64 GMP-exp]... (4xOMP) DONE
Raw:    166273 c/s real, 41775 c/s virtual

Benchmarking: cloudkeychain, 1Password Cloud Keychain [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 40000 and 50000
Raw:    286 c/s real, 74.8 c/s virtual

Benchmarking: dynamic=md5($p) [256/256 AVX2 8x3]... DONE
Raw:    45233K c/s real, 44790K c/s virtual

Benchmarking: cq, ClearQuest [CQWeb]... (4xOMP) DONE
Many salts:     228921K c/s real, 57802K c/s virtual
Only one salt:  44171K c/s real, 11070K c/s virtual

Benchmarking: CRC32 [CRC32 32/64 CRC-32C AVX]... DONE
Speed for cost 1 (version [0:CRC-32 1:CRC-32C]) of 0
Many salts:     137256K c/s real, 137256K c/s virtual
Only one salt:  62259K c/s real, 62259K c/s virtual

Benchmarking: sha1crypt, NetBSD's sha1crypt [PBKDF1-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 64000 and 40000
Raw:    1383 c/s real, 382 c/s virtual

Benchmarking: sha256crypt, crypt(3) $5$ (rounds=5000) [SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    7249 c/s real, 1969 c/s virtual

Benchmarking: sha512crypt, crypt(3) $6$ (rounds=5000) [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    4697 c/s real, 1299 c/s virtual

Benchmarking: Citrix_NS10, Netscaler 10 [SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     81559K c/s real, 20440K c/s virtual
Only one salt:  47808K c/s real, 11922K c/s virtual

Benchmarking: dahua, "MD5 based authentication" Dahua [MD5 32/64]... DONE
Raw:    5820K c/s real, 5879K c/s virtual

Benchmarking: dashlane, Dashlane Password Manager [AES PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    3446 c/s real, 955 c/s virtual

Benchmarking: diskcryptor, DiskCryptor [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    11328 c/s real, 2846 c/s virtual

Benchmarking: Django (x10000) [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    2661 c/s real, 663 c/s virtual

Benchmarking: django-scrypt [Salsa20/8 128/128 AVX]... (4xOMP) DONE
Speed for cost 1 (N) of 14, cost 2 (r) of 8, cost 3 (p) of 1
Raw:    141 c/s real, 35.2 c/s virtual

Benchmarking: dmd5, DIGEST-MD5 C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     6258K c/s real, 1564K c/s virtual
Only one salt:  5864K c/s real, 1480K c/s virtual

Benchmarking: dmg, Apple DMG [PBKDF2-SHA1 256/256 AVX2 8x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (version) of 2 and 1
Raw:    24064 c/s real, 6016 c/s virtual

Benchmarking: dominosec, Lotus Notes/Domino 6 More Secure Internet Password [8/64]... (4xOMP) DONE
Many salts:     1169K c/s real, 292416 c/s virtual
Only one salt:  791040 c/s real, 198255 c/s virtual

Benchmarking: dominosec8, Lotus Notes/Domino 8 [8/64]... (4xOMP) DONE
Raw:    2328 c/s real, 582 c/s virtual

Benchmarking: DPAPImk, DPAPI masterkey file v1 and v2 [SHA1/MD4 PBKDF2-(SHA1/SHA512)-DPAPI-variant 3DES/AES256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 24000
Raw:    1380 c/s real, 377 c/s virtual

Benchmarking: dragonfly3-32, DragonFly BSD $3$ w/ bug, 32-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     11672K c/s real, 2918K c/s virtual
Only one salt:  9153K c/s real, 2288K c/s virtual

Benchmarking: dragonfly3-64, DragonFly BSD $3$ w/ bug, 64-bit [SHA256 32/64]... (4xOMP) DONE
Many salts:     11541K c/s real, 2892K c/s virtual
Only one salt:  10476K c/s real, 2606K c/s virtual

Benchmarking: dragonfly4-32, DragonFly BSD $4$ w/ bugs, 32-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     8422K c/s real, 2126K c/s virtual
Only one salt:  6648K c/s real, 1662K c/s virtual

Benchmarking: dragonfly4-64, DragonFly BSD $4$ w/ bugs, 64-bit [SHA512 64/64]... (4xOMP) DONE
Many salts:     8298K c/s real, 2079K c/s virtual
Only one salt:  7657K c/s real, 1914K c/s virtual

Benchmarking: Drupal7, $S$ (x16385) [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16384
Raw:    1425 c/s real, 357 c/s virtual

Benchmarking: eCryptfs (65536 iterations) [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    382 c/s real, 104 c/s virtual

Benchmarking: eigrp, EIGRP MD5 / HMAC-SHA-256 authentication [MD5/SHA-256 32/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [2:MD5 3:HMAC-SHA-256]) of 2
Many salts:     14215K c/s real, 3553K c/s virtual
Only one salt:  12470K c/s real, 3125K c/s virtual

Benchmarking: electrum, Electrum Wallet [SHA256 AES / PBKDF2-SHA512 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (kdf [1:SHA256 2:PBKDF2-SHA512]) of 1 and 2
Raw:    12672 c/s real, 3144 c/s virtual

Benchmarking: EncFS [PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 181474
Raw:    193 c/s real, 52.9 c/s virtual

Benchmarking: enpass, Enpass Password Manager [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    1435 c/s real, 384 c/s virtual

Benchmarking: EPI, EPiServer SID [SHA1 32/64]... (4xOMP) DONE
Many salts:     21938K c/s real, 5484K c/s virtual
Only one salt:  17000K c/s real, 4281K c/s virtual

Benchmarking: EPiServer [SHA1/SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256]) of 1
Many salts:     54788K c/s real, 13697K c/s virtual
Only one salt:  50692K c/s real, 12704K c/s virtual

Benchmarking: ethereum, Ethereum Wallet [PBKDF2-SHA256/scrypt Keccak 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 262144 and 1024, cost 2 (kdf [0:PBKDF2-SHA256 1:scrypt 2:PBKDF2-SHA256 presale]) of 0
Warning: "Many salts" test limited: 8/256
Many salts:     243 c/s real, 64.3 c/s virtual
Only one salt:  115 c/s real, 31.6 c/s virtual

Benchmarking: fde, Android FDE [PBKDF2-SHA1 256/256 AVX2 8x SHA256/AES]... (4xOMP) DONE
Raw:    16168 c/s real, 4495 c/s virtual

Benchmarking: Fortigate256, FortiOS256 [SHA256 32/64]... (4xOMP) DONE
Many salts:     11296K c/s real, 2824K c/s virtual
Only one salt:  10682K c/s real, 2670K c/s virtual

Benchmarking: Fortigate, FortiOS [SHA1 32/64]... (4xOMP) DONE
Many salts:     19505K c/s real, 4888K c/s virtual
Only one salt:  17932K c/s real, 4471K c/s virtual

Benchmarking: FormSpring [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:     9408K c/s real, 9314K c/s virtual
Only one salt:  7963K c/s real, 7963K c/s virtual

Benchmarking: FVDE, FileVault 2 [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 41000 and 70400
Raw:    528 c/s real, 140 c/s virtual

Benchmarking: geli, FreeBSD GELI [PBKDF2-SHA512 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 256 and 512
Raw:    28416 c/s real, 7104 c/s virtual

Benchmarking: gost, GOST R 34.11-94 [64/64]... (4xOMP) DONE
Raw:    2002K c/s real, 500736 c/s virtual

Benchmarking: gpg, OpenPGP / GnuPG Secret Key [32/64]... (4xOMP) DONE
Speed for cost 1 (s2k-count) of 65536, cost 2 (hash algorithm [1:MD5 2:SHA1 3:RIPEMD160 8:SHA256 9:SHA384 10:SHA512 11:SHA224]) of 2, cost 3 (cipher algorithm [1:IDEA 2:3DES 3:CAST5 4:Blowfish 7:AES128 8:AES192 9:AES256 10:Twofish 11:Camellia128 12:Camellia192 13:Camellia256]) of 3
Raw:    31544 c/s real, 7866 c/s virtual

Benchmarking: HAVAL-128-4 [32/64]... DONE
Raw:    3036K c/s real, 3066K c/s virtual

Benchmarking: HAVAL-256-3 [32/64]... DONE
Raw:    4247K c/s real, 4247K c/s virtual

Benchmarking: hdaa, HTTP Digest access authentication [MD5 256/256 AVX2 8x3]... DONE
Many salts:     8462K c/s real, 8462K c/s virtual
Only one salt:  7734K c/s real, 7734K c/s virtual

Benchmarking: hMailServer [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:     9302K c/s real, 9394K c/s virtual
Only one salt:  8087K c/s real, 8007K c/s virtual

Benchmarking: hsrp, "MD5 authentication" HSRP, HSRPv2, VRRP, GLBP [MD5 32/64]... (4xOMP) DONE
Many salts:     12705K c/s real, 3184K c/s virtual
Only one salt:  8346K c/s real, 2102K c/s virtual

Benchmarking: IKE, PSK [HMAC MD5/SHA1 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1]) of 1 and 2
Raw:    2165K c/s real, 542796 c/s virtual

Benchmarking: ipb2, Invision Power Board 2.x [MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Many salts:     35536K c/s real, 8884K c/s virtual
Only one salt:  23018K c/s real, 5797K c/s virtual

Benchmarking: itunes-backup, Apple iTunes Backup [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (version) of 9 and 10, cost 2 (iteration count) of 10000
Raw:    3081 c/s real, 840 c/s virtual

Benchmarking: iwork, Apple iWork '09 or newer [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 100000
Raw:    609 c/s real, 173 c/s virtual

Benchmarking: KeePass [SHA256 AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 50000 and 6000, cost 2 (version) of 1 and 2, cost 3 (algorithm [0=AES, 1=TwoFish, 2=ChaCha]) of 0
Raw:    590 c/s real, 155 c/s virtual

Benchmarking: keychain, Mac OS X Keychain [PBKDF2-SHA1 3DES 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    32950 c/s real, 8237 c/s virtual

Benchmarking: keyring, GNOME Keyring [SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3221
Raw:    17066 c/s real, 4605 c/s virtual

Benchmarking: keystore, Java KeyStore [SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Warning: "Many salts" test limited: 16/256
Many salts:     3956K c/s real, 1067K c/s virtual
Only one salt:  3893K c/s real, 1024K c/s virtual

Benchmarking: known_hosts, HashKnownHosts HMAC-SHA1 [SHA1 32/64]... (4xOMP) DONE
Many salts:     11448K c/s real, 2862K c/s virtual
Only one salt:  8908K c/s real, 2232K c/s virtual

Benchmarking: krb4, Kerberos v4 TGT [DES 32/64]... DONE
Short:  286657 c/s real, 275737 c/s virtual
Long:   796455 c/s real, 796455 c/s virtual

Benchmarking: krb5, Kerberos v5 TGT [3DES 32/64]... DONE
Raw:    74736 c/s real, 75484 c/s virtual

Benchmarking: krb5asrep, Kerberos 5 AS-REP etype 17/18/23 [MD4 HMAC-MD5 RC4 / PBKDF2 HMAC-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     1408K c/s real, 351194 c/s virtual
Only one salt:  1113K c/s real, 278272 c/s virtual

Benchmarking: krb5pa-sha1, Kerberos 5 AS-REQ Pre-Auth etype 17/18 [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    8947 c/s real, 2431 c/s virtual

Benchmarking: krb5tgs, Kerberos 5 TGS etype 23 [MD4 HMAC-MD5 RC4]... (4xOMP) DONE
Many salts:     2774K c/s real, 691774 c/s virtual
Only one salt:  1765K c/s real, 442450 c/s virtual

Benchmarking: krb5-17, Kerberos 5 DB etype 17 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Raw:    17808 c/s real, 4837 c/s virtual

Benchmarking: krb5-18, Kerberos 5 DB etype 18 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Raw:    8904 c/s real, 2452 c/s virtual

Benchmarking: krb5-3, Kerberos 5 DB etype 3 [DES / PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Many salts:     4341K c/s real, 1093K c/s virtual
Only one salt:  4079K c/s real, 1027K c/s virtual

Benchmarking: kwallet, KDE KWallet [SHA1 / PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    10899 c/s real, 2718 c/s virtual

Benchmarking: lp, LastPass offline [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 108/256
Many salts:     55296 c/s real, 13789 c/s virtual
Only one salt:  47651 c/s real, 11912 c/s virtual

Benchmarking: lpcli, LastPass CLI [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1234
Many salts:     19776 c/s real, 4956 c/s virtual
Only one salt:  22048 c/s real, 5484 c/s virtual

Benchmarking: leet [SHA-512(256/256 AVX2 4x) + Whirlpool(OpenSSL/64)]... (4xOMP) DONE
Warning: "Many salts" test limited: 36/256
Many salts:     4671K c/s real, 1209K c/s virtual
Only one salt:  4112K c/s real, 1061K c/s virtual

Benchmarking: lotus5, Lotus Notes/Domino 5 [8/64 X3]... (4xOMP) DONE
Raw:    2211K c/s real, 551581 c/s virtual

Benchmarking: lotus85, Lotus Notes/Domino 8.5 [8/64]... (4xOMP) DONE
Many salts:     464128 c/s real, 116322 c/s virtual
Only one salt:  446464 c/s real, 111616 c/s virtual

Benchmarking: LUKS [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    186 c/s real, 50.6 c/s virtual

Benchmarking: MD2 [MD2 32/64]... (4xOMP) DONE
Raw:    736000 c/s real, 184461 c/s virtual

Benchmarking: mdc2, MDC-2 [MDC-2DES]... (4xOMP) DONE
Raw:    4704K c/s real, 1179K c/s virtual

Benchmarking: MediaWiki [md5($s.md5($p)) 256/256 AVX2 8x3]... DONE
Many salts:     36437K c/s real, 36437K c/s virtual
Only one salt:  14637K c/s real, 14784K c/s virtual

Benchmarking: monero, monero Wallet [Pseudo-AES / ChaCha / Various 32/64]... (4xOMP) DONE
Raw:    10.3 c/s real, 2.8 c/s virtual

Benchmarking: money, Microsoft Money (2002 to Money Plus) [MD5/SHA1 32/64]... (4xOMP) DONE
Many salts:     4349K c/s real, 1090K c/s virtual
Only one salt:  3858K c/s real, 962202 c/s virtual

Benchmarking: MongoDB, system / network [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (salt type) of 0 and 1
Raw:    13598K c/s real, 3391K c/s virtual

Benchmarking: scram [SCRAM PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    5688 c/s real, 1697 c/s virtual

Benchmarking: Mozilla, Mozilla key3.db [SHA1 3DES 32/64]... (4xOMP) DONE
Many salts:     1249K c/s real, 313102 c/s virtual
Only one salt:  1325K c/s real, 330437 c/s virtual

Benchmarking: mscash, MS Cache Hash (DCC) [MD4 32/64]... (4xOMP) DONE
Many salts:     63307K c/s real, 15826K c/s virtual
Only one salt:  22614K c/s real, 5653K c/s virtual

Benchmarking: mscash2, MS Cache Hash 2 (DCC2) [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    6149 c/s real, 1537 c/s virtual

Benchmarking: MSCHAPv2, C/R [MD4 DES (ESS MD5) 256/256 AVX2 8x3]... DONE
Many salts:     10464M c/s real, 10464M c/s virtual
Only one salt:  58729K c/s real, 59316K c/s virtual

Benchmarking: mschapv2-naive, MSCHAPv2 C/R [MD4 DES 256/256 AVX2 naive]... (4xOMP) DONE
Many salts:     437731K c/s real, 109432K c/s virtual
Only one salt:  19287K c/s real, 4870K c/s virtual

Benchmarking: krb5pa-md5, Kerberos 5 AS-REQ Pre-Auth etype 23 [32/64]... (4xOMP) DONE
Many salts:     3308K c/s real, 829080 c/s virtual
Only one salt:  1868K c/s real, 464684 c/s virtual

Benchmarking: mssql, MS SQL [SHA1 256/256 AVX2 8x]... DONE
Many salts:     36881K c/s real, 36881K c/s virtual
Only one salt:  17049K c/s real, 17049K c/s virtual

Benchmarking: mssql05, MS SQL 2005 [SHA1 256/256 AVX2 8x]... DONE
Many salts:     37878K c/s real, 38257K c/s virtual
Only one salt:  28965K c/s real, 28965K c/s virtual

Benchmarking: mssql12, MS SQL 2012/2014 [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     22097K c/s real, 5538K c/s virtual
Only one salt:  14168K c/s real, 3542K c/s virtual

Benchmarking: multibit, MultiBit Wallet [MD5/scrypt AES 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 3, cost 2 (kdf [1:MD5 2:scrypt hd 3:scrypt classic]) of 1
Many salts:     2706K c/s real, 678279 c/s virtual
Only one salt:  2810K c/s real, 707946 c/s virtual

Benchmarking: mysqlna, MySQL Network Authentication [SHA1 32/64]... (4xOMP) DONE
Many salts:     7045K c/s real, 1765K c/s virtual
Only one salt:  6719K c/s real, 1679K c/s virtual

Benchmarking: mysql-sha1, MySQL 4.1+ [SHA1 256/256 AVX2 8x]... DONE
Raw:    18101K c/s real, 18101K c/s virtual

Benchmarking: mysql, MySQL pre-4.1 [32/64]... DONE
Raw:    58266K c/s real, 58266K c/s virtual

Benchmarking: net-ah, IPsec AH HMAC-MD5-96 [MD5 32/64]... (4xOMP) DONE
Many salts:     5603K c/s real, 1404K c/s virtual
Only one salt:  5353K c/s real, 1335K c/s virtual

Benchmarking: nethalflm, HalfLM C/R [DES 32/64]... (4xOMP) DONE
Many salts:     11632K c/s real, 2908K c/s virtual
Only one salt:  2367K c/s real, 591872 c/s virtual

Benchmarking: netlm, LM C/R [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 25/256
Many salts:     12725K c/s real, 3196K c/s virtual
Only one salt:  1651K c/s real, 1103K c/s virtual

Benchmarking: netlmv2, LMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     3949K c/s real, 989866 c/s virtual
Only one salt:  2771K c/s real, 692864 c/s virtual

Benchmarking: net-md5, "Keyed MD5" RIPv2, OSPF, BGP, SNMPv2 [MD5 32/64]... (4xOMP) DONE
Many salts:     11182K c/s real, 10856K c/s virtual
Only one salt:  9098K c/s real, 9189K c/s virtual

Benchmarking: netntlmv2, NTLMv2 C/R [MD4 HMAC-MD5 32/64]... (4xOMP) DONE
Many salts:     3657K c/s real, 914432 c/s virtual
Only one salt:  2443K c/s real, 612346 c/s virtual

Benchmarking: netntlm, NTLMv1 C/R [MD4 DES (ESS MD5) 256/256 AVX2 8x3]... DONE
Many salts:     10459M c/s real, 10670M c/s virtual
Only one salt:  53537K c/s real, 53537K c/s virtual

Benchmarking: netntlm-naive, NTLMv1 C/R [MD4 DES (ESS MD5) DES 256/256 AVX2 naive]... (4xOMP) DONE
Many salts:     345718K c/s real, 86214K c/s virtual
Only one salt:  14385K c/s real, 3605K c/s virtual

Benchmarking: net-sha1, "Keyed SHA1" BFD [SHA1 32/64]... (4xOMP) DONE
Many salts:     10886K c/s real, 10467K c/s virtual
Only one salt:  8813K c/s real, 8813K c/s virtual

Benchmarking: nk, Nuked-Klan CMS [SHA1 MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 49/256
Many salts:     6358K c/s real, 1593K c/s virtual
Only one salt:  6810K c/s real, 1711K c/s virtual

Benchmarking: notes, Apple Notes [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 20000
Raw:    1408 c/s real, 380 c/s virtual

Benchmarking: md5ns, Netscreen [md5($s.$p) (OSC) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     19424K c/s real, 19424K c/s virtual
Only one salt:  14601K c/s real, 14457K c/s virtual

Benchmarking: nsec3, DNSSEC NSEC3 [32/64]... DONE
Raw:    78274 c/s real, 78274 c/s virtual

Benchmarking: NT [MD4 256/256 AVX2 8x3]... DONE
Raw:    72200K c/s real, 72929K c/s virtual

Benchmarking: o10glogon, Oracle 10g-logon protocol [DES-AES128-MD5 32/64]... (4xOMP) DONE
Many salts:     1350K c/s real, 339232 c/s virtual
Only one salt:  1529K c/s real, 386176 c/s virtual

Benchmarking: o3logon, Oracle O3LOGON protocol [SHA1 DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 26/256
Many salts:     827153 c/s real, 208815 c/s virtual
Only one salt:  819200 c/s real, 206287 c/s virtual

Benchmarking: o5logon, Oracle O5LOGON protocol [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     6791K c/s real, 1697K c/s virtual
Only one salt:  7233K c/s real, 1812K c/s virtual

Benchmarking: ODF, OpenDocument Star/Libre/OpenOffice [PBKDF2-SHA1 256/256 AVX2 8x BF/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1024, cost 2 (crypto [0=Blowfish, 1=AES]) of 0 and 1
Raw:    31904 c/s real, 7995 c/s virtual

Benchmarking: Office, 2007/2010/2013 [SHA1 256/256 AVX2 8x / SHA512 256/256 AVX2 4x AES]... (4xOMP) DONE
Speed for cost 1 (MS Office version) of 2007, cost 2 (iteration count) of 50000
Raw:    2502 c/s real, 632 c/s virtual

Benchmarking: oldoffice, MS Office <= 2003 [MD5/SHA1 RC4 32/64]... (4xOMP) DONE
Speed for cost 1 (hash type) of 1 and 0
Many salts:     1955K c/s real, 490185 c/s virtual
Only one salt:  1867K c/s real, 471445 c/s virtual

Benchmarking: OpenBSD-SoftRAID [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (kdf) of 1, cost 2 (iteration count) of 8192
Raw:    3833 c/s real, 965 c/s virtual

Benchmarking: openssl-enc, OpenSSL "enc" encryption (AES-128, MD5) [32/64]... (4xOMP) DONE
Many salts:     5752K c/s real, 1441K c/s virtual
Only one salt:  5347K c/s real, 1333K c/s virtual

Benchmarking: oracle, Oracle 10 [DES 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 213/256
Many salts:     3489K c/s real, 872448 c/s virtual
Only one salt:  2539K c/s real, 634880 c/s virtual

Benchmarking: oracle11, Oracle 11g [SHA1 256/256 AVX2 8x]... DONE
Many salts:     35743K c/s real, 35743K c/s virtual
Only one salt:  25045K c/s real, 25045K c/s virtual

Benchmarking: Oracle12C [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    2880 c/s real, 720 c/s virtual

Benchmarking: osc, osCommerce [md5($s.$p) (OSC) 256/256 AVX2 8x3]... DONE
Many salts:     29645K c/s real, 29944K c/s virtual
Only one salt:  19461K c/s real, 19657K c/s virtual

Benchmarking: ospf, OSPF / IS-IS [HMAC-SHA-X 32/64]... (4xOMP) DONE
Raw:    4521K c/s real, 1130K c/s virtual

Benchmarking: Padlock [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    2461 c/s real, 717 c/s virtual

Benchmarking: Palshop, MD5(Palshop) [MD5 + SHA1 32/64]... (4xOMP) DONE
Raw:    6942K c/s real, 1740K c/s virtual

Benchmarking: Panama [Panama 32/64]... (4xOMP) DONE
Raw:    3072K c/s real, 768000 c/s virtual

Benchmarking: PBKDF2-HMAC-MD4 [PBKDF2-MD4 256/256 AVX2 8x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    192752 c/s real, 49398 c/s virtual

Benchmarking: PBKDF2-HMAC-MD5 [PBKDF2-MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    133829 c/s real, 33540 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA1 [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    67584 c/s real, 16938 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA256 [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    25344 c/s real, 6304 c/s virtual

Benchmarking: PBKDF2-HMAC-SHA512, GRUB2 / OS X 10.8+ [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000
Raw:    11024 c/s real, 2762 c/s virtual

Benchmarking: PDF [MD5 SHA2 RC4/AES 32/64]... (4xOMP) DONE
Speed for cost 1 (revision) of 4
Raw:    168576 c/s real, 42144 c/s virtual

Benchmarking: PEM, PKCS#8 private key (RSA/DSA/ECDSA) [PBKDF2-SHA1 256/256 AVX2 8x 3DES/AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4096, cost 2 (cipher [1=3DES, 2/3/4=AES-128/192/256]) of 1
Raw:    13292 c/s real, 3430 c/s virtual

Benchmarking: pfx [PKCS12 PBE (.pfx, .p12) (SHA-1 to SHA-512) 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048, cost 2 (mac-type [1:SHA1 224:SHA224 256:SHA256 384:SHA384 512:SHA512]) of 1
Raw:    64512 c/s real, 16087 c/s virtual

Benchmarking: pgpdisk [PGP Disk / Virtual Disk SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000, cost 2 (algorithm [3=CAST, 4=TwoFish, 5/6/7=AES]) of 5
Raw:    2281 c/s real, 611 c/s virtual

Benchmarking: pgpsda [PGP SDA SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 16000
Raw:    6576 c/s real, 1787 c/s virtual

Benchmarking: pgpwde [PGP WDE S2K-SHA1 64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 131072
Raw:    5069 c/s real, 1406 c/s virtual

Benchmarking: phpass ($P$9) [phpass ($P$ or $H$) 256/256 AVX2 8x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Many salts:     149376 c/s real, 37437 c/s virtual
Only one salt:  146756 c/s real, 36963 c/s virtual

Benchmarking: PHPS [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:     49899K c/s real, 49899K c/s virtual
Only one salt:  12606K c/s real, 12606K c/s virtual

Benchmarking: PHPS2 [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:     51287K c/s real, 51287K c/s virtual
Only one salt:  14208K c/s real, 14208K c/s virtual

Benchmarking: pix-md5, Cisco PIX [md5($p) (Cisco PIX) 256/256 AVX2 8x3]... DONE
Raw:    22864K c/s real, 22864K c/s virtual

Benchmarking: PKZIP [32/64]... (4xOMP) DONE
Many salts:     42975K c/s real, 10770K c/s virtual
Only one salt:  22272K c/s real, 5609K c/s virtual

Benchmarking: po, Post.Office [MD5 32/64]... DONE
Many salts:     4081K c/s real, 4122K c/s virtual
Only one salt:  4000K c/s real, 3961K c/s virtual

Benchmarking: postgres, PostgreSQL C/R [MD5 32/64]... (4xOMP) DONE
Many salts:     10823K c/s real, 2712K c/s virtual
Only one salt:  9910K c/s real, 2477K c/s virtual

Benchmarking: PST, custom CRC-32 [32/64]... DONE
Raw:    81088K c/s real, 81088K c/s virtual

Benchmarking: PuTTY, Private Key (RSA/DSA/ECDSA/ED25519) [SHA1/AES 32/64]... (4xOMP) DONE
Raw:    858966 c/s real, 222855 c/s virtual

Benchmarking: pwsafe, Password Safe [SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    28998 c/s real, 8051 c/s virtual

Benchmarking: qnx, qnx hash (rounds=1000) [QNX 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 1000, cost 2 (algorithm [5:MD5 256:SHA256 512:SHA512]) of 5
Raw:    155091 c/s real, 39152 c/s virtual

Benchmarking: RACF [DES 32/64]... (4xOMP) DONE
Many salts:     25907K c/s real, 6509K c/s virtual
Only one salt:  11526K c/s real, 2881K c/s virtual

Benchmarking: RACF-KDFAES [KDFAES (DES + HMAC-SHA256/64 + AES-256)]... (4xOMP) DONE
Warning: "Many salts" test limited: 2/256
Many salts:     0.7 c/s real, 0.1 c/s virtual
Only one salt:  0.3 c/s real, 0.0 c/s virtual

Benchmarking: radius, RADIUS authentication [MD5 32/64]... (4xOMP) DONE
Many salts:     22364K c/s real, 5605K c/s virtual
Only one salt:  16592K c/s real, 4148K c/s virtual

Benchmarking: RAdmin, v2.x [MD5 32/64]... (4xOMP) DONE
Raw:    11650K c/s real, 3328K c/s virtual

Benchmarking: RAKP, IPMI 2.0 RAKP (RMCP+) [HMAC-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Warning: "Many salts" test limited: 249/256
Many salts:     32636K c/s real, 8179K c/s virtual
Only one salt:  10381K c/s real, 2608K c/s virtual

Benchmarking: rar, RAR3 (length 5) [SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Raw:    340 c/s real, 92.3 c/s virtual

Benchmarking: RAR5 [PBKDF2-SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 32768
Raw:    869 c/s real, 242 c/s virtual

Benchmarking: Raw-SHA512 [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    17304K c/s real, 4336K c/s virtual

Benchmarking: Raw-Blake2 [BLAKE2b 512 128/128 AVX]... (4xOMP) DONE
Raw:    10223K c/s real, 2562K c/s virtual

Benchmarking: Raw-Keccak [Keccak 512 32/64]... (4xOMP) DONE
Raw:    4671K c/s real, 1176K c/s virtual

Benchmarking: Raw-Keccak-256 [Keccak 256 32/64]... (4xOMP) DONE
Raw:    4931K c/s real, 1229K c/s virtual

Benchmarking: Raw-MD4 [MD4 256/256 AVX2 8x3]... DONE
Raw:    68921K c/s real, 68921K c/s virtual

Benchmarking: Raw-MD5 [MD5 256/256 AVX2 8x3]... DONE
Raw:    56229K c/s real, 56229K c/s virtual

Benchmarking: Raw-MD5u [md5(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:    52808K c/s real, 53336K c/s virtual

Benchmarking: Raw-SHA1 [SHA1 256/256 AVX2 8x]... DONE
Raw:    33022K c/s real, 32368K c/s virtual

Benchmarking: Raw-SHA1-AxCrypt [SHA1 256/256 AVX2 8x]... DONE
Raw:    32931K c/s real, 32605K c/s virtual

Benchmarking: Raw-SHA1-Linkedin [SHA1 256/256 AVX2 8x]... DONE
Raw:    32598K c/s real, 32598K c/s virtual

Benchmarking: Raw-SHA224 [SHA224 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    36208K c/s real, 9052K c/s virtual

Benchmarking: Raw-SHA256 [SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    33161K c/s real, 8290K c/s virtual

Benchmarking: Raw-SHA3 [SHA3 512 32/64]... (4xOMP) DONE
Raw:    4784K c/s real, 1190K c/s virtual

Benchmarking: Raw-SHA384 [SHA384 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    15106K c/s real, 3776K c/s virtual

Benchmarking: ripemd-128, RIPEMD 128 [32/64]... DONE
Raw:    6300K c/s real, 6300K c/s virtual

Benchmarking: ripemd-160, RIPEMD 160 [32/64]... DONE
Raw:    4165K c/s real, 4165K c/s virtual

Benchmarking: rsvp, HMAC-MD5 / HMAC-SHA1, RSVP, IS-IS, OMAPI, RNDC, TSIG [MD5 32/64]... (4xOMP) DONE
Speed for cost 1 (hash algorithm used for hmac [1:MD5 2:SHA1 3:SHA224 4:SHA256 5:SHA384 6:SHA512]) of 1 and 2
Many salts:     6615K c/s real, 1653K c/s virtual
Only one salt:  4096K c/s real, 1034K c/s virtual

Benchmarking: Siemens-S7 [HMAC-SHA1 32/64]... (4xOMP) ^[cDONE
Many salts:     11090K c/s real, 2772K c/s virtual
Only one salt:  4218K c/s real, 1057K c/s virtual

Benchmarking: Salted-SHA1 [SHA1 256/256 AVX2 8x]... (4xOMP) ^[wDONE
Many salts:     76274K c/s real, 19259K c/s virtual
Only one salt:  40697K c/s real, 10199K c/s virtual

Benchmarking: SSHA512, LDAP [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     18317K c/s real, 4579K c/s virtual
Only one salt:  12393K c/s real, 3106K c/s virtual

Benchmarking: sapb, SAP CODVN B (BCODE) [MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Many salts:     25362K c/s real, 6356K c/s virtual
Only one salt:  21184K c/s real, 5282K c/s virtual

Benchmarking: sapg, SAP CODVN F/G (PASSCODE) [SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     17833K c/s real, 4458K c/s virtual
Only one salt:  14180K c/s real, 3553K c/s virtual

Benchmarking: saph, SAP CODVN H (PWDSALTEDHASH) (SHA1x1024) [SHA-1/SHA-2 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (hash type [1:SHA1 2:SHA256 3:SHA384 4:SHA512]) of 1, cost 2 (iteration count) of 1024
Warning: "Many salts" test limited: 183/256
Many salts:     93696 c/s real, 23365 c/s virtual
Only one salt:  106496 c/s real, 26491 c/s virtual

Benchmarking: sappse [PKCS12 PBE SHA1 256/256 AVX2 8x 3DES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    22016 c/s real, 5504 c/s virtual

Benchmarking: securezip, PKWARE SecureZIP [SHA1 AES 32/64]... (4xOMP) DONE
Many salts:     1867K c/s real, 466944 c/s virtual
Only one salt:  1576K c/s real, 395228 c/s virtual

Benchmarking: 7z, 7-Zip (512K iterations) [SHA256 256/256 AVX2 8x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 524288, cost 2 (padding size) of 4 and 9, cost 3 (compression type) of 128 and 1
Many salts:     22546 c/s real, 6113 c/s virtual
Only one salt:  109 c/s real, 30.8 c/s virtual

Benchmarking: Signal [Signal Android PKCS12 PBE SHA-1 32/64]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 6024 and 6097
Raw:    3736 c/s real, 936 c/s virtual

Benchmarking: SIP [MD5 32/64]... (4xOMP) DONE
Warning: "Many salts" test limited: 67/256
Many salts:     8609K c/s real, 2168K c/s virtual
Only one salt:  8519K c/s real, 2114K c/s virtual

Benchmarking: skein-256, Skein 256 [Skein 32/64]... (4xOMP) DONE
Raw:    9260K c/s real, 2332K c/s virtual

Benchmarking: skein-512, Skein 512 [Skein 32/64]... (4xOMP) DONE
Raw:    8695K c/s real, 2179K c/s virtual

Benchmarking: skey, S/Key [MD4/MD5/SHA1/RMD160 32/64]... DONE
Speed for cost 1 (hash type [1:MD4 2:MD5 3:SHA1 4:RMD160]) of 1 and 2, cost 2 (iteration count) of 96 and 99
Raw:    89319 c/s real, 90213 c/s virtual

Benchmarking: SL3, Nokia operator unlock [SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     88014K c/s real, 22003K c/s virtual
Only one salt:  31275K c/s real, 7877K c/s virtual

Benchmarking: Snefru-128 [32/64]... (4xOMP) DONE
Raw:    1542K c/s real, 384574 c/s virtual

Benchmarking: Snefru-256 [32/64]... (4xOMP) DONE
Raw:    1560K c/s real, 390144 c/s virtual

Benchmarking: LastPass, sniffed sessions [PBKDF2-SHA256 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 500
Warning: "Many salts" test limited: 55/256
Many salts:     55215 c/s real, 13837 c/s virtual
Only one salt:  55215 c/s real, 13906 c/s virtual

Benchmarking: SNMP, SNMPv3 USM [HMAC-MD5-96/HMAC-SHA1-96 32/64]... (4xOMP) DONE
Raw:    760 c/s real, 192 c/s virtual

Benchmarking: solarwinds, SolarWinds Orion [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    1317 c/s real, 332 c/s virtual

Benchmarking: SSH [RSA/DSA/EC/OPENSSH (SSH private keys) 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF/cipher [0=MD5/AES 1=MD5/3DES 2=Bcrypt/AES]) of 0 and 1, cost 2 (iteration count) of 1 and 2
Raw:    2836K c/s real, 710841 c/s virtual

Benchmarking: sspr, NetIQ SSPR / Adobe AEM [MD5/SHA1/SHA256/SHA512 32/64]... (4xOMP) DONE
Speed for cost 1 (KDF [0:MD5 1:SHA1 2:SHA1_SALT 3:SHA256_SALT 4:SHA512_SALT]) of 1, cost 2 (iteration count) of 100000
Raw:    254 c/s real, 68.0 c/s virtual

Benchmarking: Stribog-256 [GOST R 34.11-2012 128/128 AVX 1x]... (4xOMP) DONE
Raw:    1359K c/s real, 339968 c/s virtual

Benchmarking: Stribog-512 [GOST R 34.11-2012 128/128 AVX 1x]... (4xOMP) DONE
Raw:    1490K c/s real, 372736 c/s virtual

Benchmarking: STRIP, Password Manager [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    8369 c/s real, 2266 c/s virtual

Benchmarking: SunMD5 [MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 5000
Raw:    2844 c/s real, 775 c/s virtual

Benchmarking: SybaseASE, Sybase ASE [SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     18628K c/s real, 4657K c/s virtual
Only one salt:  5062K c/s real, 1262K c/s virtual

Benchmarking: Sybase-PROP [salted FEAL-8 32/64]... (4xOMP) DONE
Many salts:     2553K c/s real, 638336 c/s virtual
Only one salt:  2707K c/s real, 678560 c/s virtual

Benchmarking: tacacs-plus, TACACS+ [MD5 32/64]... (4xOMP) DONE
Many salts:     24580K c/s real, 6160K c/s virtual
Only one salt:  19134K c/s real, 4783K c/s virtual

Benchmarking: tcp-md5, TCP MD5 Signatures, BGP, MSDP [MD5 32/64]... (4xOMP) DONE
Many salts:     21659K c/s real, 5428K c/s virtual
Only one salt:  15245K c/s real, 3811K c/s virtual

Benchmarking: telegram [PBKDF2-SHA1 256/256 AVX2 8x AES]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 4000
Raw:    2407 c/s real, 638 c/s virtual

Benchmarking: tezos, Tezos Key [PBKDF2-SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 2048
Raw:    5440 c/s real, 1360 c/s virtual

Benchmarking: Tiger [Tiger 32/64]... (4xOMP) DONE
Raw:    17235K c/s real, 4319K c/s virtual

Benchmarking: tc_aes_xts, TrueCrypt AES256_XTS [SHA512/RIPEMD160/WHIRLPOOL 256/256 AVX2 4x]... (4xOMP) DONE
Speed for cost 1 (hash algorithm [1:SHA512 2:RIPEMD160 3:Whirlpool]) of 1
Raw:    11043 c/s real, 2918 c/s virtual

Benchmarking: tc_ripemd160, TrueCrypt AES256_XTS [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    939 c/s real, 254 c/s virtual

Benchmarking: tc_ripemd160boot, TrueCrypt AES/Twofish/Serpent [RIPEMD160 32/64]... (4xOMP) DONE
Raw:    1878 c/s real, 497 c/s virtual

Benchmarking: tc_sha512, TrueCrypt AES256_XTS [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Raw:    10830 c/s real, 2940 c/s virtual

Benchmarking: tc_whirlpool, TrueCrypt AES256_XTS [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    1476 c/s real, 440 c/s virtual

Benchmarking: vdi, VirtualBox-VDI AES_XTS [PBKDF2-SHA256 256/256 AVX2 8x + AES_XTS]... (4xOMP) DONE
Raw:    4654 c/s real, 1312 c/s virtual

Benchmarking: OpenVMS, Purdy [32/64]... (4xOMP) DONE
Many salts:     3791K c/s real, 950343 c/s virtual
Only one salt:  3535K c/s real, 883968 c/s virtual

Benchmarking: vmx, VMware VMX [PBKDF2-SHA1 AES 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (iteration count) of 10000
Raw:    3360 c/s real, 840 c/s virtual

Benchmarking: VNC [DES 32/64]... (4xOMP) DONE
Many salts:     13533K c/s real, 3374K c/s virtual
Only one salt:  9895K c/s real, 2473K c/s virtual

Benchmarking: vtp, "MD5 based authentication" VTP [MD5 32/64]... (4xOMP) DONE
Many salts:     2519K c/s real, 645907 c/s virtual
Only one salt:  21557 c/s real, 5560 c/s virtual

Benchmarking: wbb3, WoltLab BB3 [SHA1 32/64]... (4xOMP) DONE
Many salts:     5818K c/s real, 1458K c/s virtual
Only one salt:  3899K c/s real, 972416 c/s virtual

Benchmarking: whirlpool [WHIRLPOOL 32/64]... (4xOMP) DONE
Raw:    5061K c/s real, 1274K c/s virtual

Benchmarking: whirlpool0 [WHIRLPOOL-0 32/64]... (4xOMP) DONE
Raw:    5349K c/s real, 1337K c/s virtual

Benchmarking: whirlpool1 [WHIRLPOOL-1 32/64]... (4xOMP) DONE
Raw:    5303K c/s real, 1325K c/s virtual

Benchmarking: wpapsk, WPA/WPA2/PMF/PMKID PSK [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 2
Raw:    7152 c/s real, 1801 c/s virtual

Benchmarking: wpapsk-pmk, WPA/WPA2/PMF/PMKID master key [MD5/SHA-1/SHA-2]... (4xOMP) DONE
Speed for cost 1 (key version [0:PMKID 1:WPA 2:WPA2 3:802.11w]) of 1 and 2
Many salts:     2504K c/s real, 627745 c/s virtual
Only one salt:  2491K c/s real, 622764 c/s virtual

Benchmarking: xmpp-scram [XMPP SCRAM PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    16738 c/s real, 4440 c/s virtual

Benchmarking: xsha, Mac OS X 10.4 - 10.6 [SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     95408K c/s real, 23852K c/s virtual
Only one salt:  49115K c/s real, 12309K c/s virtual

Benchmarking: xsha512, Mac OS X 10.7 [SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     18284K c/s real, 4559K c/s virtual
Only one salt:  14664K c/s real, 3693K c/s virtual

Benchmarking: ZIP, WinZip [PBKDF2-SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Raw:    70892 c/s real, 19351 c/s virtual

Benchmarking: ZipMonster, MD5(ZipMonster) [MD5-256/256 AVX2 8x3 x 50000]... (4xOMP) DONE
Raw:    2292 c/s real, 1003 c/s virtual

Benchmarking: plaintext, $0$ [n/a]... DONE
Raw:    88329K c/s real, 89221K c/s virtual

Benchmarking: has-160 [HAS-160 32/64]... DONE
Raw:    8572K c/s real, 8572K c/s virtual

Benchmarking: HMAC-MD5 [password is key, MD5 256/256 AVX2 8x3]... (4xOMP) DONE
Many salts:     116981K c/s real, 29172K c/s virtual
Only one salt:  16809K c/s real, 4223K c/s virtual

Benchmarking: HMAC-SHA1 [password is key, SHA1 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     42598K c/s real, 10623K c/s virtual
Only one salt:  11679K c/s real, 2927K c/s virtual

Benchmarking: HMAC-SHA224 [password is key, SHA224 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     26296K c/s real, 6574K c/s virtual
Only one salt:  10092K c/s real, 2523K c/s virtual

Benchmarking: HMAC-SHA256 [password is key, SHA256 256/256 AVX2 8x]... (4xOMP) DONE
Many salts:     23543K c/s real, 5885K c/s virtual
Only one salt:  9830K c/s real, 2463K c/s virtual

Benchmarking: HMAC-SHA384 [password is key, SHA384 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     9249K c/s real, 2318K c/s virtual
Only one salt:  4085K c/s real, 1024K c/s virtual

Benchmarking: HMAC-SHA512 [password is key, SHA512 256/256 AVX2 4x]... (4xOMP) DONE
Many salts:     9555K c/s real, 2394K c/s virtual
Only one salt:  4685K c/s real, 1171K c/s virtual

Benchmarking: dynamic_0 [md5($p) (raw-md5) 256/256 AVX2 8x3]... DONE
Raw:    45908K c/s real, 45908K c/s virtual

Benchmarking: dynamic_1 [md5($p.$s) (joomla) 256/256 AVX2 8x3]... DONE
Many salts:     26955K c/s real, 27488K c/s virtual
Only one salt:  18557K c/s real, 18744K c/s virtual

Benchmarking: dynamic_2 [md5(md5($p)) (e107) 256/256 AVX2 8x3]... DONE
Raw:    25356K c/s real, 25609K c/s virtual

Benchmarking: dynamic_3 [md5(md5(md5($p))) 256/256 AVX2 8x3]... DONE
Raw:    17193K c/s real, 17193K c/s virtual

Benchmarking: dynamic_4 [md5($s.$p) (OSC) 256/256 AVX2 8x3]... DONE
Many salts:     30286K c/s real, 30286K c/s virtual
Only one salt:  18664K c/s real, 18664K c/s virtual

Benchmarking: dynamic_5 [md5($s.$p.$s) 256/256 AVX2 8x3]... DONE
Many salts:     22081K c/s real, 22304K c/s virtual
Only one salt:  14437K c/s real, 14437K c/s virtual

Benchmarking: dynamic_6 [md5(md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:     46485K c/s real, 46485K c/s virtual
Only one salt:  13866K c/s real, 13866K c/s virtual

Benchmarking: dynamic_8 [md5(md5($s).$p) 256/256 AVX2 8x3]... DONE
Many salts:     33677K c/s real, 33343K c/s virtual
Only one salt:  20542K c/s real, 20748K c/s virtual

Benchmarking: dynamic_9 [md5($s.md5($p)) 256/256 AVX2 8x3]... DONE
Many salts:     31321K c/s real, 31321K c/s virtual
Only one salt:  13459K c/s real, 13594K c/s virtual

Benchmarking: dynamic_10 [md5($s.md5($s.$p)) 256/256 AVX2 8x3]... DONE
Many salts:     14637K c/s real, 14637K c/s virtual
Only one salt:  11793K c/s real, 11793K c/s virtual

Benchmarking: dynamic_11 [md5($s.md5($p.$s)) 256/256 AVX2 8x3]... DONE
Many salts:     15062K c/s real, 15062K c/s virtual
Only one salt:  12116K c/s real, 11996K c/s virtual

Benchmarking: dynamic_12 [md5(md5($s).md5($p)) (IPB) 256/256 AVX2 8x3]... DONE
Many salts:     19468K c/s real, 19662K c/s virtual
Only one salt:  8178K c/s real, 8097K c/s virtual

Benchmarking: dynamic_13 [md5(md5($p).md5($s)) 256/256 AVX2 8x3]... DONE
Many salts:     19171K c/s real, 19171K c/s virtual
Only one salt:  8349K c/s real, 8266K c/s virtual

Benchmarking: dynamic_14 [md5($s.md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:     23273K c/s real, 22807K c/s virtual
Only one salt:  11549K c/s real, 11663K c/s virtual

Benchmarking: dynamic_15 [md5($u.md5($p).$s) 256/256 AVX2 8x3]... DONE
Many salts:     14730K c/s real, 14730K c/s virtual
Only one salt:  7066K c/s real, 6996K c/s virtual

Benchmarking: dynamic_16 [md5(md5(md5($p).$s).$s2) 256/256 AVX2 8x3]... DONE
Many salts:     10335K c/s real, 10335K c/s virtual
Only one salt:  5855K c/s real, 5855K c/s virtual

Benchmarking: dynamic_18 [md5($s.Y.$p.0xF7.$s) (Post.Office MD5) 32/64 x2]... DONE
Many salts:     4198K c/s real, 4240K c/s virtual
Only one salt:  3951K c/s real, 3951K c/s virtual

Benchmarking: dynamic_19 [md5($p) (Cisco PIX) 256/256 AVX2 8x3]... DONE
Raw:    23029K c/s real, 23029K c/s virtual

Benchmarking: dynamic_20 [md5($p.$s) (Cisco ASA) 256/256 AVX2 8x3]... DONE
Many salts:     27985K c/s real, 27985K c/s virtual
Only one salt:  18496K c/s real, 18313K c/s virtual

Benchmarking: dynamic_22 [md5(sha1($p)) 256/256 AVX2 8x1]... DONE
Raw:    10529K c/s real, 10634K c/s virtual

Benchmarking: dynamic_23 [sha1(md5($p)) 256/256 AVX2 8x1]... DONE
Raw:    13967K c/s real, 13967K c/s virtual

Benchmarking: dynamic_24 [sha1($p.$s) 256/256 AVX2 8x1]... DONE
Many salts:     15731K c/s real, 15731K c/s virtual
Only one salt:  12334K c/s real, 12334K c/s virtual

Benchmarking: dynamic_25 [sha1($s.$p) 256/256 AVX2 8x1]... DONE
Many salts:     15589K c/s real, 15744K c/s virtual
Only one salt:  12331K c/s real, 12331K c/s virtual

Benchmarking: dynamic_26 [sha1($p) raw-sha1 256/256 AVX2 8x1]... DONE
Raw:    16786K c/s real, 17119K c/s virtual

Benchmarking: dynamic_29 [md5(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:    23798K c/s real, 23798K c/s virtual

Benchmarking: dynamic_30 [md4($p) (raw-md4) 256/256 AVX2 8x3]... DONE
Raw:    53666K c/s real, 54203K c/s virtual

Benchmarking: dynamic_31 [md4($s.$p) 256/256 AVX2 8x3]... DONE
Many salts:     37146K c/s real, 37146K c/s virtual
Only one salt:  21368K c/s real, 21796K c/s virtual

Benchmarking: dynamic_32 [md4($p.$s) 256/256 AVX2 8x3]... DONE
Many salts:     33065K c/s real, 32738K c/s virtual
Only one salt:  20825K c/s real, 20408K c/s virtual

Benchmarking: dynamic_33 [md4(utf16($p)) 256/256 AVX2 8x3]... DONE
Raw:    25385K c/s real, 25888K c/s virtual

Benchmarking: dynamic_34 [md5(md4($p)) 256/256 AVX2 8x3]... DONE
Raw:    27222K c/s real, 27222K c/s virtual

Benchmarking: dynamic_35 [sha1(uc($u).:.$p) (ManGOS) 256/256 AVX2 8x1]... DONE
Many salts:     13171K c/s real, 13171K c/s virtual
Only one salt:  10709K c/s real, 10815K c/s virtual

Benchmarking: dynamic_36 [sha1($u.:.$p) (ManGOS2) 256/256 AVX2 8x1]... DONE
Many salts:     13023K c/s real, 13023K c/s virtual
Only one salt:  10436K c/s real, 10436K c/s virtual

Benchmarking: dynamic_37 [sha1(lc($u).$p) (SMF) 256/256 AVX2 8x1]... DONE
Many salts:     15648K c/s real, 15805K c/s virtual
Only one salt:  12109K c/s real, 11989K c/s virtual

Benchmarking: dynamic_38 [sha1($s.sha1($s.sha1($p))) (Wolt3BB) 256/256 AVX2 8x1]... DONE
Many salts:     4111K c/s real, 4111K c/s virtual
Only one salt:  3749K c/s real, 3786K c/s virtual

Benchmarking: dynamic_39 [md5($s.pad16($p)) (net-md5) 256/256 AVX2 8x3]... DONE
Many salts:     12008K c/s real, 12008K c/s virtual
Only one salt:  9930K c/s real, 9930K c/s virtual

Benchmarking: dynamic_40 [sha1($s.pad20($p)) (net-sha1) 256/256 AVX2 8x1]... DONE
Many salts:     12062K c/s real, 11942K c/s virtual
Only one salt:  9671K c/s real, 9767K c/s virtual

Benchmarking: dynamic_50 [sha224($p) 256/256 AVX2 8x]... DONE
Raw:    11510K c/s real, 11510K c/s virtual

Benchmarking: dynamic_60 [sha256($p) 256/256 AVX2 8x]... DONE
Raw:    11470K c/s real, 11470K c/s virtual

Benchmarking: dynamic_61 [sha256($s.$p) 256/256 AVX2 8x]... DONE
Many salts:     9231K c/s real, 9324K c/s virtual
Only one salt:  8090K c/s real, 8010K c/s virtual

Benchmarking: dynamic_70 [sha384($p) 256/256 AVX2 4x]... DONE
Raw:    5981K c/s real, 6041K c/s virtual

Benchmarking: dynamic_80 [sha512($p) 256/256 AVX2 4x]... DONE
Raw:    6081K c/s real, 6081K c/s virtual

Benchmarking: dynamic_90 [gost($p) 64/64]... DONE
Raw:    598811 c/s real, 604800 c/s virtual

Benchmarking: dynamic_100 [whirlpool($p) 32/64 OpenSSL]... DONE
Raw:    2002K c/s real, 2022K c/s virtual

Benchmarking: dynamic_110 [tiger($p) 32/64 sph_tiger]... DONE
Raw:    6078K c/s real, 6078K c/s virtual

Benchmarking: dynamic_120 [ripemd128($p) 32/64 sph_ripemd]... DONE
Raw:    6041K c/s real, 5981K c/s virtual

Benchmarking: dynamic_130 [ripemd160($p) 32/64 sph_ripemd]... DONE
Raw:    3895K c/s real, 3857K c/s virtual

Benchmarking: dynamic_140 [ripemd256($p) 32/64 sph_ripemd]... DONE
Raw:    5281K c/s real, 5281K c/s virtual

Benchmarking: dynamic_150 [ripemd320($p) 32/64 sph_ripemd]... DONE
Raw:    3682K c/s real, 3682K c/s virtual

Benchmarking: dynamic_160 [haval128_3($p) 32/64 sph_haval]... DONE
Raw:    4058K c/s real, 4058K c/s virtual

Benchmarking: dynamic_170 [haval128_4($p) 32/64 sph_haval]... DONE
Raw:    2925K c/s real, 2896K c/s virtual

Benchmarking: dynamic_180 [haval128_5($p) 32/64 sph_haval]... DONE
Raw:    2544K c/s real, 2570K c/s virtual

Benchmarking: dynamic_190 [haval160_3($p) 32/64 sph_haval]... DONE
Raw:    4075K c/s real, 4075K c/s virtual

Benchmarking: dynamic_200 [haval160_4($p) 32/64 sph_haval]... DONE
Raw:    2837K c/s real, 2866K c/s virtual

Benchmarking: dynamic_210 [haval160_5($p) 32/64 sph_haval]... DONE
Raw:    2540K c/s real, 2540K c/s virtual

Benchmarking: dynamic_220 [haval192_3($p) 32/64 sph_haval]... DONE
Raw:    4058K c/s real, 4058K c/s virtual

Benchmarking: dynamic_230 [haval192_4($p) 32/64 sph_haval]... DONE
Raw:    2944K c/s real, 2944K c/s virtual

Benchmarking: dynamic_240 [haval192_5($p) 32/64 sph_haval]... DONE
Raw:    2513K c/s real, 2513K c/s virtual

Benchmarking: dynamic_250 [haval224_3($p) 32/64 sph_haval]... DONE
Raw:    4035K c/s real, 3996K c/s virtual

Benchmarking: dynamic_260 [haval224_4($p) 32/64 sph_haval]... DONE
Raw:    2915K c/s real, 2915K c/s virtual

Benchmarking: dynamic_270 [haval224_5($p) 32/64 sph_haval]... DONE
Raw:    2568K c/s real, 2593K c/s virtual

Benchmarking: dynamic_280 [haval256_3($p) 32/64 sph_haval]... DONE
Raw:    4166K c/s real, 4166K c/s virtual

Benchmarking: dynamic_290 [haval256_4($p) 32/64 sph_haval]... DONE
Raw:    2980K c/s real, 2980K c/s virtual

Benchmarking: dynamic_300 [haval256_5($p) 32/64 sph_haval]... DONE
Raw:    2570K c/s real, 2570K c/s virtual

Benchmarking: dynamic_310 [md2($p) 32/64 sph_md2]... DONE
Raw:    194880 c/s real, 192950 c/s virtual

Benchmarking: dynamic_320 [panama($p) 32/64 sph_panama]... DONE
Raw:    1044K c/s real, 1065K c/s virtual

Benchmarking: dynamic_330 [skein224($p) 32/64 sph_skein]... DONE
Raw:    3360K c/s real, 3360K c/s virtual

Benchmarking: dynamic_340 [skein256($p) 32/64 sph_skein]... DONE
Raw:    3363K c/s real, 3363K c/s virtual

Benchmarking: dynamic_350 [skein384($p) 32/64 sph_skein]... DONE
Raw:    3323K c/s real, 3323K c/s virtual

Benchmarking: dynamic_360 [skein512($p) 32/64 sph_skein]... DONE
Raw:    3290K c/s real, 3290K c/s virtual

Benchmarking: dynamic_370 [sha3_224($p) 64/64 keccak]... DONE
Raw:    1676K c/s real, 1693K c/s virtual

Benchmarking: dynamic_380 [sha3_256($p) 64/64 keccak]... DONE
Raw:    1723K c/s real, 1723K c/s virtual

Benchmarking: dynamic_390 [sha3_384($p) 64/64 keccak]... DONE
Raw:    1746K c/s real, 1764K c/s virtual

Benchmarking: dynamic_400 [sha3_512($p) 64/64 keccak]... DONE
Raw:    1769K c/s real, 1733K c/s virtual

Benchmarking: dynamic_410 [keccak_256($p) 64/64 keccak]... DONE
Raw:    1747K c/s real, 1747K c/s virtual

Benchmarking: dynamic_420 [keccak_512($p) 64/64 keccak]... DONE
Raw:    1719K c/s real, 1737K c/s virtual

Benchmarking: dynamic_1001 [md5(md5(md5(md5($p)))) 256/256 AVX2 8x3]... DONE
Raw:    12395K c/s real, 12395K c/s virtual

Benchmarking: dynamic_1002 [md5(md5(md5(md5(md5($p))))) 256/256 AVX2 8x3]... DONE
Raw:    9856K c/s real, 9953K c/s virtual

Benchmarking: dynamic_1003 [md5(md5($p).md5($p)) 256/256 AVX2 8x3]... DONE
Raw:    9198K c/s real, 9198K c/s virtual

Benchmarking: dynamic_1004 [md5(md5(md5(md5(md5(md5($p)))))) 256/256 AVX2 8x3]... DONE
Raw:    8396K c/s real, 8396K c/s virtual

Benchmarking: dynamic_1005 [md5(md5(md5(md5(md5(md5(md5($p))))))) 256/256 AVX2 8x3]... DONE
Raw:    7106K c/s real, 7106K c/s virtual

Benchmarking: dynamic_1006 [md5(md5(md5(md5(md5(md5(md5(md5($p)))))))) 256/256 AVX2 8x3]... DONE
Raw:    6273K c/s real, 6273K c/s virtual

Benchmarking: dynamic_1007 [md5(md5($p).$s) (vBulletin) 256/256 AVX2 8x3]... DONE
Many salts:     51152K c/s real, 51152K c/s virtual
Only one salt:  14095K c/s real, 14095K c/s virtual

Benchmarking: dynamic_1008 [md5($p.$s) (RADIUS User-Password) 256/256 AVX2 8x3]... DONE
Many salts:     29158K c/s real, 29158K c/s virtual
Only one salt:  19211K c/s real, 19404K c/s virtual

Benchmarking: dynamic_1009 [md5($s.$p) (RADIUS Responses) 256/256 AVX2 8x3]... DONE
Many salts:     32471K c/s real, 32471K c/s virtual
Only one salt:  21218K c/s real, 21218K c/s virtual

Benchmarking: dynamic_1010 [md5($p null_padded_to_len_100) RAdmin v2.x MD5 256/256 AVX2 8x3]... DONE
Raw:    15755K c/s real, 15599K c/s virtual

Benchmarking: dynamic_1011 [md5($p.md5($s)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:     12055K c/s real, 11934K c/s virtual
Only one salt:  9966K c/s real, 10066K c/s virtual

Benchmarking: dynamic_1012 [md5($p.md5($s)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:     27675K c/s real, 27403K c/s virtual
Only one salt:  18503K c/s real, 18688K c/s virtual

Benchmarking: dynamic_1013 [md5($p.PMD5(username)) (webEdition CMS) 256/256 AVX2 8x3]... DONE
Many salts:     27625K c/s real, 27901K c/s virtual
Only one salt:  18570K c/s real, 18570K c/s virtual

Benchmarking: dynamic_1014 [md5($p.$s) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:     11633K c/s real, 11633K c/s virtual
Only one salt:  8792K c/s real, 8880K c/s virtual

Benchmarking: dynamic_1015 [md5(md5($p.$u).$s) (PostgreSQL 'pass the hash') 256/256 AVX2 8x3]... DONE
Many salts:     15792K c/s real, 15949K c/s virtual
Only one salt:  12653K c/s real, 12653K c/s virtual

Benchmarking: dynamic_1016 [md5($p.$s) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:     14636K c/s real, 14636K c/s virtual
Only one salt:  11783K c/s real, 11899K c/s virtual

Benchmarking: dynamic_1017 [md5($s.$p) (long salt) 256/256 AVX2 8x3]... DONE
Many salts:     12631K c/s real, 12757K c/s virtual
Only one salt:  10701K c/s real, 10489K c/s virtual

Benchmarking: dynamic_1018 [md5(sha1(sha1($p))) 256/256 AVX2 8x1]... DONE
Raw:    6755K c/s real, 7025K c/s virtual

Benchmarking: dynamic_1019 [md5(sha1(sha1(md5($p)))) 256/256 AVX2 8x1]... DONE
Raw:    6310K c/s real, 6310K c/s virtual

Benchmarking: dynamic_1020 [md5(sha1(md5($p))) 256/256 AVX2 8x1]... DONE
Raw:    9344K c/s real, 9160K c/s virtual

Benchmarking: dynamic_1021 [md5(sha1(md5(sha1($p)))) 256/256 AVX2 8x1]... DONE
Raw:    5507K c/s real, 5452K c/s virtual

Benchmarking: dynamic_1022 [md5(sha1(md5(sha1(md5($p))))) 256/256 AVX2 8x1]... DONE
Raw:    4976K c/s real, 4976K c/s virtual

Benchmarking: dynamic_1023 [sha1($p) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    17310K c/s real, 17310K c/s virtual

Benchmarking: dynamic_1024 [sha1(md5($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    13563K c/s real, 13563K c/s virtual

Benchmarking: dynamic_1025 [sha1(md5(md5($p))) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    10831K c/s real, 10831K c/s virtual

Benchmarking: dynamic_1026 [sha1(sha1($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    8932K c/s real, 8932K c/s virtual

Benchmarking: dynamic_1027 [sha1(sha1(sha1($p))) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    6414K c/s real, 6414K c/s virtual

Benchmarking: dynamic_1028 [sha1(sha1_raw($p)) (hash truncated to length 32) 256/256 AVX2 8x1]... DONE
Raw:    9367K c/s real, 9367K c/s virtual

Benchmarking: dynamic_1029 [sha256($p) (hash truncated to length 32) 256/256 AVX2 8x]... DONE
Raw:    8531K c/s real, 8531K c/s virtual

Benchmarking: dynamic_1030 [whirlpool($p) (hash truncated to length 32) 32/64 OpenSSL]... DONE
Raw:    1922K c/s real, 1904K c/s virtual

Benchmarking: dynamic_1031 [gost($p) (hash truncated to length 32) 64/64]... DONE
Raw:    605465 c/s real, 605465 c/s virtual

Benchmarking: dynamic_1032 [sha1_64(utf16($p)) (PeopleSoft) 256/256 AVX2 8x1]... DONE
Raw:    12203K c/s real, 12203K c/s virtual

Benchmarking: dynamic_1034 [md5($p.$u) (PostgreSQL MD5) 256/256 AVX2 8x3]... DONE
Many salts:     29877K c/s real, 30178K c/s virtual
Only one salt:  19603K c/s real, 19407K c/s virtual

Benchmarking: dynamic_1300 [md5(md5_raw($p)) 256/256 AVX2 8x3]... DONE
Raw:    17774K c/s real, 17952K c/s virtual

Benchmarking: dynamic_1350 [md5(md5($s.$p):$s) 256/256 AVX2 8x3]... DONE
Many salts:     15254K c/s real, 15103K c/s virtual
Only one salt:  12126K c/s real, 12126K c/s virtual

Benchmarking: dynamic_1400 [sha1(utf16($p)) (Microsoft CREDHIST) 256/256 AVX2 8x1]... DONE
Raw:    10056K c/s real, 10056K c/s virtual

Benchmarking: dynamic_1401 [md5($u.\nskyper\n.$p) (Skype MD5) 256/256 AVX2 8x3]... DONE
Many salts:     8243K c/s real, 8161K c/s virtual
Only one salt:  6219K c/s real, 6343K c/s virtual

Benchmarking: dynamic_1501 [sha1($s.sha1($p)) (Redmine) 256/256 AVX2 8x1]... DONE
Many salts:     11537K c/s real, 11652K c/s virtual
Only one salt:  5836K c/s real, 5836K c/s virtual

Benchmarking: dynamic_1502 [sha1(sha1($p).$s) (XenForo SHA-1) 256/256 AVX2 8x1]... DONE
Many salts:     20156K c/s real, 19957K c/s virtual
Only one salt:  7549K c/s real, 7549K c/s virtual

Benchmarking: dynamic_1503 [sha256(sha256($p).$s) (XenForo SHA-256) 256/256 AVX2 8x]... DONE
Many salts:     5376K c/s real, 5376K c/s virtual
Only one salt:  3290K c/s real, 3323K c/s virtual

Benchmarking: dynamic_1504 [sha1($s.$p.$s) 256/256 AVX2 8x1]... DONE
Many salts:     13363K c/s real, 13363K c/s virtual
Only one salt:  10848K c/s real, 10848K c/s virtual

Benchmarking: dynamic_1505 [md5($p.$s.md5($p.$s)) 256/256 AVX2 8x3]... DONE
Many salts:     5525K c/s real, 5580K c/s virtual
Only one salt:  5124K c/s real, 5124K c/s virtual

Benchmarking: dynamic_1506 [md5($u.:XDB:.$p) (Oracle 12c "H" hash) 256/256 AVX2 8x3]... DONE
Many salts:     25016K c/s real, 24521K c/s virtual
Only one salt:  16674K c/s real, 16839K c/s virtual

Benchmarking: dynamic_1507 [sha1(utf16($const.$p)) (Mcafee master pass) 256/256 AVX2 8x1]... DONE
Raw:    10289K c/s real, 10392K c/s virtual

Benchmarking: dynamic_1518 [md5(sha1($p).md5($p).sha1($p)) 256/256 AVX2 8x1]... DONE
Raw:    4926K c/s real, 4976K c/s virtual

Benchmarking: dynamic_1528 [sha256($s.$p.$s) (Telegram for Android) 256/256 AVX2 8x]... DONE
Many salts:     9351K c/s real, 9444K c/s virtual
Only one salt:  8286K c/s real, 8369K c/s virtual

Benchmarking: dynamic_1529 [sha1($p null_padded_to_len_32) (DeepSound) 256/256 AVX2 8x1]... DONE
Raw:    12183K c/s real, 12183K c/s virtual

Benchmarking: dynamic_1550 [md5($u.:mongo:.$p) (MONGODB-CR system hash) 256/256 AVX2 8x3]... DONE
Many salts:     22176K c/s real, 22176K c/s virtual
Only one salt:  15892K c/s real, 15892K c/s virtual

Benchmarking: dynamic_1551 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 256/256 AVX2 8x3]... DONE
Many salts:     11773K c/s real, 11656K c/s virtual
Only one salt:  9571K c/s real, 9571K c/s virtual

Benchmarking: dynamic_1552 [md5($s.$u.(md5($u.:mongo:.$p)) (MONGODB-CR network hash) 256/256 AVX2 8x3]... DONE
Many salts:     7146K c/s real, 7146K c/s virtual
Only one salt:  6201K c/s real, 6201K c/s virtual

Benchmarking: dynamic_1560 [md5($s.$p.$s2) (SocialEngine) 256/256 AVX2 8x3]... DONE
Many salts:     12576K c/s real, 12451K c/s virtual
Only one salt:  10359K c/s real, 10463K c/s virtual

Benchmarking: dynamic_1588 [sha256($s.sha1($p)) (ColdFusion 11) 256/256 AVX2 8x]... DONE
Many salts:     4914K c/s real, 4963K c/s virtual
Only one salt:  4616K c/s real, 4526K c/s virtual

Benchmarking: dynamic_1590 [sha1(utf16be(space_pad_10(uc($s)).$p)) (IBM AS/400 SHA1) 256/256 AVX2 8x1]... DONE
Many salts:     14405K c/s real, 14547K c/s virtual
Only one salt:  11689K c/s real, 11689K c/s virtual

Benchmarking: dynamic_1592 [sha1($s.sha1($s.sha1($p))) (wbb3) 256/256 AVX2 8x1]... DONE
Many salts:     6179K c/s real, 6179K c/s virtual
Only one salt:  3880K c/s real, 3880K c/s virtual

Benchmarking: dynamic_1600 [sha1($s.utf16le($p)) (Oracle PeopleSoft PS_TOKEN) 256/256 AVX2 8x1]... DONE
Many salts:     8672K c/s real, 8672K c/s virtual
Only one salt:  6676K c/s real, 6676K c/s virtual

Benchmarking: dynamic_1602 [sha256(#.$salt.-.$pass) (QAS vas_auth) 256/256 AVX2 8x]... DONE
Many salts:     7657K c/s real, 7581K c/s virtual
Only one salt:  6736K c/s real, 6736K c/s virtual

Benchmarking: dynamic_1608 [sha256(sha256_raw(sha256_raw($p))) (Neo Wallet) 256/256 AVX2 8x]... DONE
Raw:    4018K c/s real, 4018K c/s virtual

Benchmarking: dynamic_2000 [md5($p) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:    21997K c/s real, 21997K c/s virtual

Benchmarking: dynamic_2001 [md5($p.$s) (joomla) (PW > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     19924K c/s real, 20126K c/s virtual
Only one salt:  15056K c/s real, 15208K c/s virtual

Benchmarking: dynamic_2002 [md5(md5($p)) (e107) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:    12314K c/s real, 12314K c/s virtual

Benchmarking: dynamic_2003 [md5(md5(md5($p))) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Raw:    8841K c/s real, 8928K c/s virtual

Benchmarking: dynamic_2004 [md5($s.$p) (OSC) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     19585K c/s real, 19585K c/s virtual
Only one salt:  14709K c/s real, 14562K c/s virtual

Benchmarking: dynamic_2005 [md5($s.$p.$s) (PW > 31 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     15755K c/s real, 15755K c/s virtual
Only one salt:  12512K c/s real, 12388K c/s virtual

Benchmarking: dynamic_2006 [md5(md5($p).$s) (PW > 55 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     25232K c/s real, 25232K c/s virtual
Only one salt:  9541K c/s real, 9636K c/s virtual

Benchmarking: dynamic_2008 [md5(md5($s).$p) (PW > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     20696K c/s real, 20489K c/s virtual
Only one salt:  14507K c/s real, 14365K c/s virtual

Benchmarking: dynamic_2009 [md5($s.md5($p)) (salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     19700K c/s real, 19897K c/s virtual
Only one salt:  8200K c/s real, 8200K c/s virtual

Benchmarking: dynamic_2010 [md5($s.md5($s.$p)) (PW > 32 or salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     10083K c/s real, 10184K c/s virtual
Only one salt:  8582K c/s real, 8582K c/s virtual

Benchmarking: dynamic_2011 [md5($s.md5($p.$s)) (PW > 32 or salt > 23 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     10059K c/s real, 10059K c/s virtual
Only one salt:  8477K c/s real, 8393K c/s virtual

Benchmarking: dynamic_2014 [md5($s.md5($p).$s) (PW > 55 or salt > 11 bytes) 256/256 AVX2 8x3]... DONE
Many salts:     15582K c/s real, 15582K c/s virtual
Only one salt:  7495K c/s real, 7495K c/s virtual

Benchmarking: dummy [N/A]... DONE
Raw:    66952K c/s real, 66952K c/s virtual

Benchmarking: crypt, generic crypt(3) [?/64]... (4xOMP) DONE
Speed for cost 1 (algorithm [1:descrypt 2:md5crypt 3:sunmd5 4:bcrypt 5:sha256crypt 6:sha512crypt]) of 1, cost 2 (algorithm specific iterations) of 1
Many salts:     644640 c/s real, 161563 c/s virtual
Only one salt:  678144 c/s real, 169536 c/s virtual

All 407 formats passed self-tests!
1627510126.978769866
```

