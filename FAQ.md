# Frequently Asked Questions (FAQ)

---

# PRIVATGRAM®

**Secure Enterprise Messaging Platform**

Frequently Asked Questions

Version 1.0

---

# General

---

## What is PRIVATGRAM?

PRIVATGRAM® is a secure enterprise messaging platform designed for organizations requiring confidential communications, centralized administration and private infrastructure deployment.

The platform is intended for government institutions, banks, enterprises and operators of critical information infrastructure.

---

## Who is PRIVATGRAM designed for?

Typical organizations include:

- Government Institutions
- Banks
- Financial Organizations
- Healthcare
- Energy
- Telecommunications
- Manufacturing
- Large Enterprises

---

## Is PRIVATGRAM a public messenger?

No.

PRIVATGRAM is designed as an enterprise communication platform rather than a public social messaging application.

Organizations deploy and manage their own communication infrastructure.

---

# Security

---

## Are messages encrypted?

Yes.

PRIVATGRAM protects message content using end-to-end encryption.

Transport communication is additionally protected using TLS.

---

## Which cryptographic technologies are used?

The platform architecture includes:

- X3DH
- Double Ratchet
- Curve25519
- HKDF
- AES-256-GCM
- TLS 1.3

Implementation details remain proprietary.

---

## Can administrators read encrypted messages?

Administrative functions are logically separated from message protection.

System administration is designed to manage organizations, users, devices and policies without providing direct access to protected communication content.

---

## Where are cryptographic keys stored?

Private cryptographic material is generated and stored locally on endpoint devices.

Platform-specific secure storage mechanisms are used whenever supported.

Examples include:

- Android Keystore
- Apple Keychain
- Protected local desktop storage

---

## Does the server store plaintext messages?

The platform architecture is designed so that secure communication content is protected independently of transport security.

Operational metadata required for message delivery and administration may be processed according to deployment configuration.

---

# Enterprise

---

## Can PRIVATGRAM be deployed inside our organization?

Yes.

Supported deployment models include:

- On-Premises
- Private Cloud
- Dedicated Enterprise Infrastructure

Organizations maintain control over deployment architecture.

---

## Does PRIVATGRAM support multiple organizations?

Yes.

Organizations are logically separated.

Each organization maintains its own users, departments, devices and administrative configuration.

---

## Can departments be managed separately?

Yes.

Department management supports:

- Organizational structure
- Administrative delegation
- User grouping
- Access management

---

## Does PRIVATGRAM support Role-Based Access Control?

Yes.

The platform implements Role-Based Access Control (RBAC).

Organizations define administrative roles according to operational requirements.

---

## Can individual devices be revoked?

Yes.

Administrators may revoke a single compromised device without affecting other authorized devices.

---

# Deployment

---

## Which operating systems are supported?

Desktop:

- Windows
- Linux
- macOS

Mobile:

- Android
- iOS

Availability depends on product release stage.

---

## Which database is recommended?

The reference deployment uses PostgreSQL.

Organizations may deploy according to their operational requirements.

---

## Can PRIVATGRAM operate without Internet access?

Yes.

Organizations may deploy the platform entirely within private internal networks.

Deployment architecture depends on organizational requirements.

---

## Is Internet access required for secure messaging?

Not necessarily.

Organizations deploying PRIVATGRAM inside private infrastructure may operate independently from public cloud messaging services.

---

# Administration

---

## Can user accounts be disabled?

Yes.

Administrators may:

- Disable users
- Suspend users
- Delete users
- Reset credentials

---

## Can sessions be terminated remotely?

Yes.

Authorized administrators may invalidate active sessions according to organizational policies.

---

## Are administrative actions logged?

Administrative operations may be recorded through audit logging.

Typical events include:

- Authentication
- Device registration
- User management
- Policy changes
- Administrative operations

---

# Mobile

---

## Can I use multiple devices?

Yes.

Each authorized device maintains an independent cryptographic identity and secure session state.

---

## What happens if I lose my phone?

Notify your administrator immediately.

The affected device may be revoked without impacting other registered devices.

---

## Is local data encrypted?

Sensitive cryptographic material is protected using platform security mechanisms whenever available.

---

# Development

---

## Is the source code public?

No.

The PRIVATGRAM software platform is proprietary.

Public repositories contain documentation and selected technical materials only.

---

## Why is only documentation published?

The public repository is intended to provide:

- Technical documentation
- Deployment guidance
- Security overview
- Product information

Proprietary implementation details remain confidential.

---

## Is an API available?

Yes.

The platform includes REST-based enterprise interfaces.

Public API documentation is published separately.

---

# Compliance

---

## Can PRIVATGRAM be used in regulated industries?

The platform is designed with enterprise security and administrative control in mind.

Organizations remain responsible for compliance with applicable regulations.

---

## Does PRIVATGRAM support audit requirements?

Administrative audit capabilities are provided to support governance and operational oversight.

---

# Support

---

## How can technical support be obtained?

Support procedures depend on organizational deployment.

Users should contact their organization's IT department or designated system administrator.

---

## How should security vulnerabilities be reported?

Responsible disclosure is encouraged.

Please contact:

info@privatgram.com

Provide:

- affected component
- impact
- reproduction steps
- supporting evidence

---

# Future Development

---

## Which features are planned?

Future development includes:

- Voice Calls
- Video Calls
- Screen Sharing
- Enterprise Federation
- AI Security Assistant
- SIEM Integration
- Compliance Automation

---

## Is the roadmap subject to change?

Yes.

Product development is continuously improved according to customer requirements, technological progress and organizational priorities.

---

# Additional Documentation

See also:

- Product Overview
- Architecture
- Security
- Deployment Guide
- Administrator Guide
- User Guide
- API Documentation

---

© PRIVATGRAM®

All Rights Reserved.
