# s2a-proto
This repository contains the canonical version of the protocol definitions for the Secure Session Agent. 

The Secure Session Agent is a service that enables a workload to offload select operations from the mTLS handshake and protects a workload's private key material from exfiltration. Specifically, the workload asks the Secure Session Agent for the TLS configuration to use during the handshake, to perform private key operations, and to validate the peer certificate chain. The Secure Session Agent's client libraries enable applications to communicate with the Secure Session Agent during the TLS handshake, and to encrypt traffic to the peer after the TLS handshake is complete.

The Secure Session Agent Go Client is in https://github.com/google/s2a-go
The Secure Session Agent Java Client is in https://github.com/grpc/grpc-java