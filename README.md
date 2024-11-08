# Encryption-API

This project is a secure API for message encryption and decryption built with Rust. It allows users to encrypt messages, which can then only be decrypted with the correct decryption key, ensuring data confidentiality and access control. This makes it ideal for applications that need to protect sensitive information in transit or storage.

# Key Tools and Technologies Used

- Rust: A powerful language known for its safety and performance, forming the backbone of the API.
- Actix Web: A robust web framework for handling HTTP requests and building APIs.
- RSA Encryption (using the rsa crate): Provides public-key cryptography, ensuring that messages are securely encrypted and can only be decrypted with the correct private key.
- Serde and JSON: For easy JSON serialization and deserialization, enabling smooth communication with clients.
- dotenv: Manages environment variables for securely handling sensitive data, like private keys.
In essence, this API provides a secure and efficient way to handle message encryption and decryption, offering robust data protection for web applications.
