# OpenSSL 1.1.1q x86 for Windows

Drop the folders in binaries:

SSL on Program Files -> Common Files OpenSSL on Program Files

Then set the enivornment varibales

OPENSSLDIR: "C:\Program Files (x86)\Common Files\SSL"

ENGINESDIR: "C:\Program Files (x86)\OpenSSL\lib\engines-1_1"

And add to path variables:

C:\Program Files (x86)\OpenSSL\bin

C:\Program Files\OpenSSL\lib

C:\Program Files\OpenSSL\lib\engines_1-1

C:\Program Files\OpenSSL\include\openssl

C:\Program Files\Common Files\SSL

That would be all.
