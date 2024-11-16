# AES GCM using CryptoCell

This is an example of AES GCM performed on Nordic devices that shows how to perform authenticated encryption and decryption operations using the GCM algorithm with CryptoCell.

## The sample performs the following operations:

- Initialization of the Platform Security Architecture (PSA) API.
- Generating a random AES key and importing it into the PSA crypto keystore.
- Encryption and decryption of a plaintext:
  - A random initialization vector (IV) is generated.
  - Authenticated encryption is performed.
  - Authenticated decryption is performed.
- Cleanup:  
  - Removing the AES key from the PSA crypto keystore.
  
## Testing

After programming the sample to your development kit, complete the following steps to test it:

1. Connect terminal.
2. Compile and program the application.
3. Observe the logs from the application using a terminal emulator.