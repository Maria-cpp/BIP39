
add_subdirectory(crypto)
add_executable(main main.cpp crypto/bip39/BIP39.cpp crypto/bip39/BIP39.h)
target_link_libraries(main crypto)

