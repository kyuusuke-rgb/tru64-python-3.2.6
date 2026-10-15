======================================================================
 Python 3.2.6 + OpenSSL 1.1.1 Porting Record for Tru64 UNIX v5.1B
======================================================================

[ Environment ]
- Hardware : DEC Alpha (EV56)
- System   : Compaq Tru64 UNIX v5.1B (OSF/1)
- Toolchain: GCC 4.7.4, Native Archiver (/usr/ccs/bin/ar)
- OpenSSL  : 1.1.1 (Installed in /usr/local/ssl)

[ Accomplishments ]
1. Python 3.2.6 fully compiled and operating on Tru64 UNIX v5.1B.
2. Patched Modules/_ssl.c and Modules/_hashopenssl.c to adapt to 
   OpenSSL 1.1.1 Opaque API changes (EVP_MD_CTX_new, X509_NAME_ENTRY_set).
3. Verified HTTPS / TLS 1.2+ communication (urllib -> Google HTTPS 200 OK).

[ Files Included in Archive ]
- /usr/local/bin/python3*
- /usr/local/lib/python3.2/
- /usr/local/ssl/ (OpenSSL 1.1.1)

======================================================================
