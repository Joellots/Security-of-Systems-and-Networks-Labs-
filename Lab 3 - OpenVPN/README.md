# Lab 3 - OpenVPN

## Objective:
The objective of this lab is to configure and secure an OpenVPN setup using Public Key Infrastructure (PKI). The lab focuses on the process of certificate generation, Diffie-Hellman parameters, TLS authentication, and establishing secure connections between a server and client.

## Tasks Covered:
1. **Install and Initialize PKI**: Set up Public Key Infrastructure (PKI) using EasyRSA, including the generation of CA certificates and Diffie-Hellman parameters.
2. **Generate Server and Client Keys**: Create the key pairs for both the server and client, including certificates signed by the CA.
3. **Generate Diffie-Hellman Parameters**: Generate parameters for secure key exchange during OpenVPN communication.
4. **Generate TLS Authentication (TA) Keys**: Produce TLS authentication keys for both server and client to enhance the security of the handshake process.
5. **Create and Sign Server and Client Certificates**: Generate and sign the server and client certificates using the CA.
6. **Configure OpenVPN Server and Client**: Configure both the server and client to use the generated keys and certificates, then verify secure communication.

## Key Learnings:
- **PKI Setup**: Setting up a PKI infrastructure is essential for securely managing encryption keys and certificates for authentication and encryption in OpenVPN.
- **Diffie-Hellman**: Diffie-Hellman key exchange allows the server and client to securely agree on a shared key, even over an insecure network.
- **TLS Authentication**: The TLS Authentication (TA) key provides an additional layer of security by preventing unauthorized connections during the handshake.
- **OpenVPN Configuration**: Proper configuration of OpenVPN involves ensuring that both server and client certificates are signed by the same CA and that the correct keys and parameters are used for secure communication.

## Setup Overview:
1. **PKI Initialization**: Using EasyRSA to create the certificate authority (CA) and generate server and client certificates.
2. **TLS Authentication Key Generation**: Generating and configuring a shared key between server and client for enhanced security.
3. **OpenVPN Server Configuration**: Setting up the OpenVPN server to require certificates and keys for both the server and clients, enabling encryption and authentication.
4. **Client Configuration**: Configuring the OpenVPN client with the necessary certificates and keys to connect to the server securely.

## Lab Report:
The full lab report is available in PDF format with detailed steps, configurations, and explanations of key concepts such as Diffie-Hellman key exchange, PKI, and the role of TLS Authentication in OpenVPN. [Lab_Report_3.pdf](Lab_Report_3.pdf).
