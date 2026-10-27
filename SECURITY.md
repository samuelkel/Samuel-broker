# Security Notes

This prototype intentionally does not accept real money or sensitive identity data. The demo profile stores only an email label in browser localStorage and does not authenticate a real user. Do not deploy it as a real financial service without replacing the demo flows.

Production requirements:
- Managed authentication, secure sessions, MFA/passkeys and account recovery
- Server-side authorization and admin role controls
- No private keys or secrets in frontend code
- KYC/AML provider integration with privacy controls
- Audited transaction ledger and reconciliation
- Rate limiting, abuse monitoring, secure headers, dependency review and backups
- Clear risk disclosures and no guaranteed-return claims
