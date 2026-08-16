# 🔐 Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| Main | ✅ |
| Older releases | ❌ |

## Authorized Use

This project is intended only for authorized:

- Bitcoin wallet recovery
- Digital forensics
- Security research
- Blockchain verification
- Asset verification

## 🚨 Never Upload Secrets

Never commit:

- `wallet.dat`
- private keys
- WIF
- seed phrases
- mnemonic phrases
- wallet passwords
- master keys
- extended private keys
- authentication credentials

## Reporting a Vulnerability

Please do not disclose security vulnerabilities through public GitHub issues.

Report security issues privately to the repository maintainer.

## Evidence Handling

Sensitive evidence must remain:

- encrypted
- access-controlled
- offline where appropriate
- excluded from the public repository

## Incident Response

If sensitive material is accidentally exposed:

1. Stop distribution immediately.
2. Remove the exposed material.
3. Rotate/revoke affected credentials where applicable.
4. Preserve audit evidence.
5. Review Git history.
6. Assess potential compromise.
7. Document the incident.
