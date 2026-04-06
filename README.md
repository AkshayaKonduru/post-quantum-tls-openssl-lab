# Post-Quantum TLS with OpenSSL

## Overview
This project demonstrates the setup of a secure Apache HTTPS server and the implementation of post-quantum cryptography using OpenSSL (OQS). It explores how modern TLS can be enhanced with quantum-resistant algorithms.


## Environment
- Ubuntu 22.04 LTS (DigitalOcean Droplet)
- Apache Server
- OpenSSL with OQS (Open Quantum Safe)


## Apache HTTPS Setup
An Apache web server was configured and secured using HTTPS. The server was successfully accessed via a browser, confirming proper SSL/TLS configuration.


## Security Testing (ImmuniWeb)
The server was tested using ImmuniWeb SSL Security Test.

### Key Results:
- Final Score: **B-**
- TLS 1.3 supported (latest secure protocol)
- Strong cipher suites enabled
- Issue identified: self-signed certificate (untrusted by browsers)

## Post-Quantum TLS Implementation

### OQS Test Server Connection
A connection was established to the Open Quantum Safe test server using `curl`, verifying TLS handshake and post-quantum support.

### TLS Handshake Testing
Secure communication was tested using:
- `s_server`
- `s_client`

The handshake demonstrated successful TLS connection using post-quantum cryptographic algorithms.


## Key Learning Outcomes
- TLS and HTTPS configuration
- Security testing using external tools (ImmuniWeb)
- Understanding of post-quantum cryptography
- OpenSSL-based TLS handshake analysis


## Files
- `post-quantum-openssl-report.pdf` → Full project documentation
- `immuniweb-ssl-security-test-report.pdf` → Security scan results


## Conclusion
This project demonstrates how secure communication protocols can be implemented and tested, and how post-quantum cryptography can be integrated into TLS for future-ready security systems.
