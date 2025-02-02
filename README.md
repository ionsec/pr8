# Sample Project

This is a sample project meant for testing GitHub Advanced Security features. The file contains fake sensitive information, such as hardcoded credentials, API keys, and other sensitive data patterns, to trigger security alerts.

## Overview

This project serves as a testbed for demonstrating and verifying the capabilities of GitHub's security scanning tools, including secret scanning and code scanning.

## Fake Sensitive Information

Below are some examples of fake sensitive data:

### API Keys

- Google API Key: `AIzaSyD3m0-FakeAPIKey12345-AbCdEfGhIjKlMnOpQrStUv`
- AWS Access Key ID: `AKIAIOSFODNN7FAKEKEY`
- AWS Secret Access Key: `wJalrXUtnFEMI/K7MDENG/bPxRfiCYFAKESECRETKEY`
- Azure Connection String: `DefaultEndpointsProtocol=https;AccountName=myfakeaccount;AccountKey=FakeKey12345==;EndpointSuffix=core.windows.net`

### Database Credentials

```bash
DB_USER='admin'
DB_PASS='SuperSecretPassword123'
DB_HOST='localhost'
DB_PORT='5432'
DB_NAME='sample_db'
-----BEGIN PRIVATE KEY-----
MIIEvAIBADANBgkqhkiG9w0BAQEFAASCAmIwggJeAgEAAoGBALFakePrivateKey/
12345AbCdEfGhIjKlMnOpQrStUvWxYz12345AbCdEfGhIjKlMnOpQrStUvWxYzA==
-----END PRIVATE KEY-----
# Hardcoded password
user_password = "P@ssw0rd1234!"

# Another example
admin_password = "AdminSecret123!"
