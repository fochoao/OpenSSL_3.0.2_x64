# OpenSSL 3.0.2 x64
# 
## Put the next variables of Environment, and add the folders to path, you can skip however data and private folders.
## Each variable is named on different form but should be:
# 
## OPENSSLDIR which should contain as path: C:\Program Files\Common Files\SSL
## ENGINESDIR with this specific path: C:\Program Files\OpenSSL\lib\engines-3
## MODULESDIR with the path: C:\Program Files\OpenSSL\lib\ossl-modules\
#
## Now point directly in Path, and point these folders:
# 
## C:\Program Files\OpenSSL\lib\engines-3
## C:\Program Files\OpenSSL\lib\ossl-modules
## C:\Program Files\Common Files\SSL\data
## C:\Program Files\Common Files\SSL\certs
## C:\Program Files\Common Files\SSL\misc
## C:\Program Files\Common Files\SSL\private
## C:\Program Files\OpenSSL\bin\
#
## Reboot your computer, or get chocolatey and perform the next command: refreshenv.
## Inside the data folder should be the certificates or however You want to link them.
## As well private folder for private keys such as SSH protocol ones. Or certificates.
## To re-check as well on command line after this, type: openssl version -a
#
## C:\>openssl version -a
## 
## If this is the output You did everything good.
## 
## OpenSSL 3.0.2 15 Mar 2022 (Library: OpenSSL 3.0.2 15 Mar 2022)
## 
## built on: Wed May 4 14:07:31 2022 UTC
## platform: VC-WIN64A
## options: bn(64,64)
## compiler: cl /Zi /Fdossl_static.pdb /Gs0 /GF /Gy /MD /W3 /wd4090 /nologo /O2 -DL_ENDIAN -DOPENSSL_PIC
## 
## OPENSSLDIR: "C:\Program Files\Common Files\SSL"
## ENGINESDIR: "C:\Program Files\OpenSSL\lib\engines-3"
## MODULESDIR: "C:\Program Files\OpenSSL\lib\ossl-modules"
## Seeding source: os-specific
#
## If the version says OpenSSL 3.0.2 x64, you did all the steps well.
## Those are the ones that should be kept at first, in case You need this version, pull them over to the top, to avoid any other version from getting in the way.
## That should do it. It as well, includes all the documentation of this version of OpenSSL.
#
## Compilation done by: Fernando O.
## 04/05/2022
