# Diffie-Hellman-Key-Exchange-Protocol
This project implements the Diffie-Hellman Key Exchange Protocol, a cryptographic method for securely establishing a shared secret over an insecure communication channel.

# Introduction

The Diffie-Hellman Key Exchange Protocol is a cryptographic method that allows two parties to securely share a secret key over an insecure channel. This implementation demonstrates the key exchange process and simulates an eavesdropper attempting to intercept the communication.

## Features

Secure Key Exchange: Uses a prime number and a primitive root.

Private and Public Key Computation: Generates keys for secure communication.

Shared Secret Calculation: Demonstrates secure secret key agreement.

Eavesdropper Simulation: Shows an attempted interception.

## Process Flow

Prime Number & Generator Selection: Alice and Bob agree on a prime number and a primitive generator.

Private Key Generation: Both parties generate their private keys.

Public Key Computation: Each party calculates and exchanges their public keys.

Shared Secret Calculation: Alice and Bob compute a common secret key.

Eavesdropping Simulation: Eve attempts to intercept and compute the shared secret.

