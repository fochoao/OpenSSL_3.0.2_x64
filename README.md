# OpenSSL 3.0.2 x64

 Put the next variables in Path Environment.

 Each variable is named should be set, first one is, OPENSSLDIR which should contain as path: C:\Program Files\Common Files\SSL,
 Next one is, ENGINESDIR with this specific path: C:\Program Files\OpenSSL\lib\engines-3,
 Next is, MODULESDIR with the path: C:\Program Files\OpenSSL\lib\ossl-modules

 OPENSSLDIR: "C:\Program Files\Common Files\SSL"
 ENGINESDIR: "C:\Program Files\OpenSSL\lib\engines-3"
 MODULESDIR: "C:\Program Files\OpenSSL\lib\ossl-modules"

 Now point directly in Path, these folders.

 C:\Program Files\OpenSSL\lib\engines-3\
 C:\Program Files\OpenSSL\lib\ossl-modules\
 C:\Program Files\Common Files\SSL\data\
 C:\Program Files\OpenSSL\bin\

 Now reboot, or get chocolatey and on command line issue: refreshenv.

 Then: openssl version -a

 If the version says OpenSSL 3.0.2 x64, You did all the steps well.

 Those are the ones that should be kept at first, in case You need this version, pull them over to the top, to avoid any other version from running.
 That should do it. It as well, includes all the documentation of this version of OpenSSL.

 Compilation done by: Fernando O.
 04/05/2022
