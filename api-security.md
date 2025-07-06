Checklist for auditing APIs 

| Category         | ✅ Check Item                                |
| ---------------- | -------------------------------------------  |
| Auth             | ✅ Token-based auth (OAuth2/JWT) implemented |
| Input            | ✅ Input validation & rate limiting          |
| Transport        | ✅ HTTPS enforced (TLS 1.2 or 1.3)           |
| Headers          | ✅ Secure headers in API responses           |
| Docs             | ✅ Swagger/OpenAPI has auth guarded          |
| Rate Limits      | ✅ API Gateway limits defined                |
| Data Leakage     | ✅ No PII/secret info in responses           |
| OWASP API Top 10 | ✅ Tested with Postman/ZAP                   |
| Logging          | ✅ API logs obfuscate sensitive fields       |
