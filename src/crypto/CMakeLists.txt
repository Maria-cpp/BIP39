
add_subdirectory(bip39)
add_library(crypto
        base58.cpp
        sha224.cpp
        sha256.cpp
        sha384.cpp
        sha512.cpp
        ripemd160.cpp
        hmac.cpp
        pbkdf2.cpp
        sha3.cpp
        mathencodings.cpp
        strencodings.cpp
        bip39/utils.cpp
        bip39/wordlist.cpp
        bip39/mnemonic.cpp
        )
