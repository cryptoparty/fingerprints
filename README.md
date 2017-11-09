# Fingerprints of Signing Keys

This list is useful when using PGP to verify downloads. This involves what's called signatures and the Torproject has an explanation of [How to verify signatures](https://www.torproject.org/docs/verifying-signatures.html.en).

**Disclaimer**

Please keep in mind that there is no guarantee for the correctness of any of the fingerprints below! You still have to verify them independently!

Working towards improved trust in this list the source file has been signed by one or more people in the community (see *.asc files in this directory).

This is an example on to verify the file's signature on the terminal:

```
gpg2 --verify README.md.dawning_sun.sig README.md
```

| Software/Project  | Fingerprint                       | Download     | Other Links  |
|:------------------|:----------------------------------|:-------------|:-------------|
| [Enigmail](https://www.enigmail.net/index.php/en/download) | `4F9F 89F5 505A C1D1 A260 631C DB11 87B9 DD5F 693B` | [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x4F9F89F5505AC1D1A260631CDB1187B9DD5F693B) | [official instructions](https://www.enigmail.net/index.php/en/verify-signature) |
| [Gpg4Win](https://gpg4win.org/download.html)               | `13E3 CE81 AFEA 6F68 3E46 6E0D 42D8 7608 2688 DA1A` | [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x13E3CE81AFEA6F683E466E0D42D876082688DA1A) | [official instructions](https://gpg4win.org/package-integrity.html) |
| [GPG Suite](https://gpgtools.org/)                         | `85E3 8F69 046B 44C1 EC9F B07B 76D7 8F05 00D0 26C4` | [gpgtools.org](https://gpgtools.org/GPGTools-00D026C4.asc); [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x85E38F69046B44C1EC9FB07B76D78F0500D026C4) | |
| [Tails](https://tails.boum.org/)                           | `A490 D0F4 D311 A415 3E2B B7CA DBB8 02B2 58AC D84F` | [tails.boum.org](https://tails.boum.org/tails-signing.key); [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0xA490D0F4D311A4153E2BB7CADBB802B258ACD84F) | [official instructions](https://tails.boum.org/install/download/openpgp/index.en.html) |
| [Torbirdy](https://trac.torproject.org/projects/tor/wiki/torbirdy)        | `E4AC D397 5427 A5BA 8450 A1BE B01C 8B00 6DA7 7FAA` | [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0xE4ACD3975427A5BA8450A1BEB01C8B006DA77FAA) | [official instructions](https://trac.torproject.org/projects/tor/wiki/torbirdy#VerifyingtheXPI) |
| [Tor Browser](https://www.torproject.org/download/download-easy.html.en)  | `EF6E 286D DA85 EA2A 4BA7 DE68 4E2C 6E87 9329 8290` | [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0xEF6E286DDA85EA2A4BA7DE684E2C6E8793298290) | [official instructions](https://www.torproject.org/docs/verifying-signatures.html.en) |
| [Tor Messenger](https://trac.torproject.org/projects/tor/wiki/doc/TorMessenger)  | `E4AC D397 5427 A5BA 8450 A1BE B01C 8B00 6DA7 7FAA` | [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0xE4ACD3975427A5BA8450A1BEB01C8B006DA77FAA) | [official instructions](https://trac.torproject.org/projects/tor/wiki/doc/TorMessenger#Downloads) |
| [Veracrypt](https://www.veracrypt.fr/en/Home.html)         | `993B 7D7E 8E41 3809 828F 0F29 EB55 9C7C 54DD D393` | [idrix.fr](https://www.idrix.fr/VeraCrypt/VeraCrypt_PGP_public_key.asc); [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x993B7D7E8E413809828F0F29EB559C7C54DDD393) | [official instructions](https://www.veracrypt.fr/en/Digital%20Signatures.html) |
| [QubesOS 3.2](https://www.qubes-os.org/downloads/)         | `C522 61BE 0A82 3221 D94C A1D1 CB11 CA1D 03FA 5082` | [qubes-os.org](https://keys.qubes-os.org/keys/qubes-master-signing-key.asc); [keyserver](https://pgp.mit.edu/pks/lookup?op=vindex&search=0xC52261BE0A823221D94CA1D1CB11CA1D03FA5082) | [official instructions](https://www.qubes-os.org/security/verifying-signatures/) |

