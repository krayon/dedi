# DEDI - Desk Exercise Drill Instructor

## Application to encourage you to exercise at your desk

----
## Introduction

For a list of authors and contributors, see [AUTHORS](AUTHORS.md) /
[CONTRIBUTORS](CONTRIBUTORS.md) .

For more information on contributing (new feature, bug fix, pull request etc),
please see [CONTRIBUTING](CONTRIBUTING.md) .



----
## Availability

The most current release is TBA.

Files will be signed with my GPG key (
[231A 94F4 81EC F212](http://pgp.mit.edu/pks/lookup?op=get&search=0x231A94F481ECF212)
).

Binary signature files end in .asc and can be verified using
[gpg/gpg2](https://www.gnupg.org/)
thus:

```console
$ gpg --verify files.tar.gz.asc
    gpg: assuming signed data in `files.tar.gz'
    gpg: Signature made 2018-05-01T01:00:52 AEST using RSA key ID 81ECF212
    gpg: Good signature from "Krayon (Code Signing Key) <krayon.git@qdnx.org>"
    gpg: WARNING: This key is not certified with a trusted signature!
    gpg:          There is no indication that the signature belongs to the owner.
    Primary key fingerprint: CDEC 1051 0874 06FB 8323  46DC 231A 94F4 81EC F212
```

You may first need to retrieve my public key if you haven't already done so:

```console
$ gpg --recv-keys 81ECF212
    gpg: keyring `/home/krayon/.gnupg/secring.gpg' created
    gpg: requesting key 81ECF212 from hkp server keys.gnupg.net
    gpg: /home/krayon/.gnupg/trustdb.gpg: trustdb created
    gpg: key 81ECF212: public key "Krayon (Code Signing Key) <krayon.git@qdnx.org>" imported
    gpg: no ultimately trusted keys found
    gpg: Total number processed: 1
    gpg:               imported: 1  (RSA: 1)
```

Source is available on
[GitHub](https://github.com/krayon/dedi)
.



----
## Bug Tracker

Bugs are tracked on [GitHub](https://github.com/krayon/dedi/issues)
.



----
## Flashing

TBA



----
## TODO

* Document all the things



----
[//]: # ( vim: set ts=4 sw=4 et cindent tw=80 ai si syn=markdown ft=markdown: )
