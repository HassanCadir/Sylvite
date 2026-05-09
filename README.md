Sylvite: A modern, memory-safe C++20 wrapper for libsodium.

Sylvite provides a high-level, type-safe API for cryptographic operations while enforcing strict memory security. It abstracts the complexities of libsodium into intuitive classes, ensuring that sensitive data is always protected by locked, zero-on-destruction memory.  

* Zero-Copy & Secure Memory: Built-in s_alloc uses sodium_malloc for 16-byte aligned, non-swappable memory.
* Type-Safe Primitives: Dedicated classes for Key, Nonce, and Salt to prevent size-mismatch errors.
* Modern Cryptography: Native support for XChaCha20-Poly1305, Argon2id, and Ed25519.
* Post-Quantum Ready: Integrated ML-KEM768 and XWing hybrid KEM.
