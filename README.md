# Error-instalando-pycrypto
inserte el comando pip install pycrypto y me marco esta serie de errores



 ERROR: Command errored out with exit status 1:
     command: 'c:\users\ingch\appdata\local\programs\python\python38\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\ingch\\AppData\\Local\\Temp\\pip-install-ozqt9g7k\\pycrypto\\setup.py'"'"'; __file__='"'"'C:\\Users\\ingch\\AppData\\Local\\Temp\\pip-install-ozqt9g7k\\pycrypto\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\ingch\AppData\Local\Temp\pip-record-853iz17q\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\ingch\appdata\local\programs\python\python38\Include\pycrypto'
         cwd: C:\Users\ingch\AppData\Local\Temp\pip-install-ozqt9g7k\pycrypto\
    Complete output (183 lines):
    running install
    running build
    running build_py
    creating build
    creating build\lib.win-amd64-3.8
    creating build\lib.win-amd64-3.8\Crypto
    copying lib\Crypto\pct_warnings.py -> build\lib.win-amd64-3.8\Crypto
    copying lib\Crypto\__init__.py -> build\lib.win-amd64-3.8\Crypto
    creating build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\hashalgo.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\HMAC.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\MD2.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\MD4.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\MD5.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\RIPEMD.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\SHA.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\SHA224.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\SHA256.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\SHA384.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\SHA512.py -> build\lib.win-amd64-3.8\Crypto\Hash
    copying lib\Crypto\Hash\__init__.py -> build\lib.win-amd64-3.8\Crypto\Hash
    creating build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\AES.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\ARC2.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\ARC4.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\blockalgo.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\Blowfish.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\CAST.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\DES.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\DES3.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\PKCS1_OAEP.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\PKCS1_v1_5.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\XOR.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    copying lib\Crypto\Cipher\__init__.py -> build\lib.win-amd64-3.8\Crypto\Cipher
    creating build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\asn1.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\Counter.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\number.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\py3compat.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\randpool.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\RFC1751.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\winrandom.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\_number_new.py -> build\lib.win-amd64-3.8\Crypto\Util
    copying lib\Crypto\Util\__init__.py -> build\lib.win-amd64-3.8\Crypto\Util
    creating build\lib.win-amd64-3.8\Crypto\Random
    copying lib\Crypto\Random\random.py -> build\lib.win-amd64-3.8\Crypto\Random
    copying lib\Crypto\Random\_UserFriendlyRNG.py -> build\lib.win-amd64-3.8\Crypto\Random
    copying lib\Crypto\Random\__init__.py -> build\lib.win-amd64-3.8\Crypto\Random
    creating build\lib.win-amd64-3.8\Crypto\Random\Fortuna
    copying lib\Crypto\Random\Fortuna\FortunaAccumulator.py -> build\lib.win-amd64-3.8\Crypto\Random\Fortuna
    copying lib\Crypto\Random\Fortuna\FortunaGenerator.py -> build\lib.win-amd64-3.8\Crypto\Random\Fortuna
    copying lib\Crypto\Random\Fortuna\SHAd256.py -> build\lib.win-amd64-3.8\Crypto\Random\Fortuna
    copying lib\Crypto\Random\Fortuna\__init__.py -> build\lib.win-amd64-3.8\Crypto\Random\Fortuna
    creating build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    copying lib\Crypto\Random\OSRNG\fallback.py -> build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    copying lib\Crypto\Random\OSRNG\nt.py -> build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    copying lib\Crypto\Random\OSRNG\posix.py -> build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    copying lib\Crypto\Random\OSRNG\rng_base.py -> build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    copying lib\Crypto\Random\OSRNG\__init__.py -> build\lib.win-amd64-3.8\Crypto\Random\OSRNG
    creating build\lib.win-amd64-3.8\Crypto\SelfTest
    copying lib\Crypto\SelfTest\st_common.py -> build\lib.win-amd64-3.8\Crypto\SelfTest
    copying lib\Crypto\SelfTest\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\common.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_AES.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_ARC2.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_ARC4.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_Blowfish.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_CAST.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_DES.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_DES3.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_pkcs1_15.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_pkcs1_oaep.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\test_XOR.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    copying lib\Crypto\SelfTest\Cipher\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Cipher
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\common.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_HMAC.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_MD2.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_MD4.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_MD5.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_RIPEMD.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_SHA.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_SHA224.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_SHA256.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_SHA384.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\test_SHA512.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    copying lib\Crypto\SelfTest\Hash\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Hash
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    copying lib\Crypto\SelfTest\Protocol\test_AllOrNothing.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    copying lib\Crypto\SelfTest\Protocol\test_chaffing.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    copying lib\Crypto\SelfTest\Protocol\test_KDF.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    copying lib\Crypto\SelfTest\Protocol\test_rfc1751.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    copying lib\Crypto\SelfTest\Protocol\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Protocol
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    copying lib\Crypto\SelfTest\PublicKey\test_DSA.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    copying lib\Crypto\SelfTest\PublicKey\test_ElGamal.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    copying lib\Crypto\SelfTest\PublicKey\test_importKey.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    copying lib\Crypto\SelfTest\PublicKey\test_RSA.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    copying lib\Crypto\SelfTest\PublicKey\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\PublicKey
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Random
    copying lib\Crypto\SelfTest\Random\test_random.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random
    copying lib\Crypto\SelfTest\Random\test_rpoolcompat.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random
    copying lib\Crypto\SelfTest\Random\test__UserFriendlyRNG.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random
    copying lib\Crypto\SelfTest\Random\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Random\Fortuna
    copying lib\Crypto\SelfTest\Random\Fortuna\test_FortunaAccumulator.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\Fortuna
    copying lib\Crypto\SelfTest\Random\Fortuna\test_FortunaGenerator.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\Fortuna
    copying lib\Crypto\SelfTest\Random\Fortuna\test_SHAd256.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\Fortuna
    copying lib\Crypto\SelfTest\Random\Fortuna\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\Fortuna
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\test_fallback.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\test_generic.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\test_nt.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\test_posix.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\test_winrandom.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    copying lib\Crypto\SelfTest\Random\OSRNG\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Random\OSRNG
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    copying lib\Crypto\SelfTest\Util\test_asn1.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    copying lib\Crypto\SelfTest\Util\test_Counter.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    copying lib\Crypto\SelfTest\Util\test_number.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    copying lib\Crypto\SelfTest\Util\test_winrandom.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    copying lib\Crypto\SelfTest\Util\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Util
    creating build\lib.win-amd64-3.8\Crypto\SelfTest\Signature
    copying lib\Crypto\SelfTest\Signature\test_pkcs1_15.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Signature
    copying lib\Crypto\SelfTest\Signature\test_pkcs1_pss.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Signature
    copying lib\Crypto\SelfTest\Signature\__init__.py -> build\lib.win-amd64-3.8\Crypto\SelfTest\Signature
    creating build\lib.win-amd64-3.8\Crypto\Protocol
    copying lib\Crypto\Protocol\AllOrNothing.py -> build\lib.win-amd64-3.8\Crypto\Protocol
    copying lib\Crypto\Protocol\Chaffing.py -> build\lib.win-amd64-3.8\Crypto\Protocol
    copying lib\Crypto\Protocol\KDF.py -> build\lib.win-amd64-3.8\Crypto\Protocol
    copying lib\Crypto\Protocol\__init__.py -> build\lib.win-amd64-3.8\Crypto\Protocol
    creating build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\DSA.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\ElGamal.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\pubkey.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\RSA.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\_DSA.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\_RSA.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\_slowmath.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    copying lib\Crypto\PublicKey\__init__.py -> build\lib.win-amd64-3.8\Crypto\PublicKey
    creating build\lib.win-amd64-3.8\Crypto\Signature
    copying lib\Crypto\Signature\PKCS1_PSS.py -> build\lib.win-amd64-3.8\Crypto\Signature
    copying lib\Crypto\Signature\PKCS1_v1_5.py -> build\lib.win-amd64-3.8\Crypto\Signature
    copying lib\Crypto\Signature\__init__.py -> build\lib.win-amd64-3.8\Crypto\Signature
    Skipping optional fixer: buffer
    Skipping optional fixer: idioms
    Skipping optional fixer: set_literal
    Skipping optional fixer: ws_comma
    running build_ext
    warning: GMP or MPIR library not found; Not building Crypto.PublicKey._fastmath.
    building 'Crypto.Random.OSRNG.winrandom' extension
    creating build\temp.win-amd64-3.8
    creating build\temp.win-amd64-3.8\Release
    creating build\temp.win-amd64-3.8\Release\src
    C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.25.28610\bin\HostX86\x64\cl.exe /c /nologo /Ox /W3 /GL /DNDEBUG /MD -Isrc/ -Isrc/inc-msvc/ -Ic:\users\ingch\appdata\local\programs\python\python38\include -Ic:\users\ingch\appdata\local\programs\python\python38\include "-IC:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.25.28610\ATLMFC\include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.25.28610\include" "-IC:\Program Files (x86)\Windows Kits\NETFXSDK\4.8\include\um" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\shared" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\um" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\winrt" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\cppwinrt" /Tcsrc/winrand.c /Fobuild\temp.win-amd64-3.8\Release\src/winrand.obj
    winrand.c
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(27): error C2061: error de sintaxis: identificador 'intmax_t'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(28): error C2061: error de sintaxis: identificador 'rem'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(28): error C2059: error de sintaxis: ';'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(29): error C2059: error de sintaxis: '}'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(31): error C2061: error de sintaxis: identificador 'imaxdiv_t'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(31): error C2059: error de sintaxis: ';'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(41): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(42): error C2146: error de sintaxis: falta ')' delante del identificador '_Number'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(42): error C2061: error de sintaxis: identificador '_Number'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(42): error C2059: error de sintaxis: ';'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(43): error C2059: error de sintaxis: ')'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(46): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(47): error C2146: error de sintaxis: falta ')' delante del identificador '_Numerator'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(47): error C2061: error de sintaxis: identificador '_Numerator'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(47): error C2059: error de sintaxis: ';'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(47): error C2059: error de sintaxis: ','
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(49): error C2059: error de sintaxis: ')'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(51): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(57): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(64): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(70): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(77): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(83): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(90): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    C:\Program Files (x86)\Windows Kits\10\include\10.0.18362.0\ucrt\inttypes.h(96): error C2143: error de sintaxis: falta '{' delante de '__cdecl'
    error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2019\\Community\\VC\\Tools\\MSVC\\14.25.28610\\bin\\HostX86\\x64\\cl.exe' failed with exit status 2
    ----------------------------------------
ERROR: Command errored out with exit status 1: 'c:\users\ingch\appdata\local\programs\python\python38\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\ingch\\AppData\\Local\\Temp\\pip-install-ozqt9g7k\\pycrypto\\setup.py'"'"'; __file__='"'"'C:\\Users\\ingch\\AppData\\Local\\Temp\\pip-install-ozqt9g7k\\pycrypto\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\ingch\AppData\Local\Temp\pip-record-853iz17q\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\ingch\appdata\local\programs\python\python38\Include\pycrypto' Check the logs for full command output.
