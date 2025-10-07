# Certificate-Based Authentication Setup for GitHub Actions

## Service Principal Details

Your certificate-based service principal has been successfully created:

- **Name**: `gh-actions-demo-cert-20251007`
- **Application ID**: `822cb1d8-fa32-42c3-bb94-0a08993bfcfd`
- **Object ID**: `e31649ba-8beb-4fc8-837e-ec7c51463a8f`
- **Role**: Contributor on subscription `ce9b673a-0158-4c19-9adf-d76a7f63f498`

## Required GitHub Secrets

You need to create the following secrets in your GitHub repository at:
`https://github.com/wasytb72/demo-container-apps-store-api-microservice/settings/secrets/actions`

### 1. AZURE_CLIENT_ID
```
822cb1d8-fa32-42c3-bb94-0a08993bfcfd
```

### 2. AZURE_TENANT_ID
```
16b3c013-d300-468d-ac64-7eda0820b6d3
```

### 3. AZURE_SUBSCRIPTION_ID
```
ce9b673a-0158-4c19-9adf-d76a7f63f498
```

### 4. AZURE_CLIENT_CERTIFICATE
Copy the entire contents of the certificate file (including the `-----BEGIN PRIVATE KEY-----` and `-----END CERTIFICATE-----` markers):

```
-----BEGIN PRIVATE KEY-----
MIIEvAIBADANBgkqhkiG9w0BAQEFAASCBKYwggSiAgEAAoIBAQCU+ywoPwKTIzUB
PCkpQDnwv7YVsF3/2JauceV31mppD9z0kQYFoVTxx5cHNUCn323J4CMbson/Pccd
BJ07Y+gs+/2ZD6OMfGkp9fWQuN4WrJj0Rc3DOFB7RFE6dxcNQelc14o91XFVR99D
UB7yCAL750iv+uNpB+wF5CSr5LkQYbiQLKnsuTZyAkud4CcP/Z4ouL01Zm+nxePW
qmghas09fzCnUOrUEYnyQ6MmwUvjaNbWmd0zmN3SZ1CALqy+CQesG/N7izgvFWBD
d2ZPQ/BwrqlmLOPMPH17fGWm8KTanbC6Do1DNfI0SMQB7L/O1VBw0+XnmVTpYjx7
T42mgVbfAgMBAAECggEAAVdZiGs4zLZObdpqzHJFk0NGkl9qGTmL8boYxMFrZ9K6
vIDpuvc+2oZfd7MlB93dESoxZrhuwZt+xWYbPEOj/XOvTsdzQ3qDP9t1AH6JkU6w
edJ/DbjeEJ4G1S3pSTdEsI9IMVJQmOHywppgDPHBhR8J6nupvHJTz6HEKr/+YoVb
LA4bmX77KK/IVYGaoyg+ZibjB+G7IsBYf8VMYXtqbnGEs1gUpZS7gmbNz41C+8UI
neIX8Eh99rGX2NFRC0W8hm0vduH988qwlkjMibEnXzrElrL/7/4YLr+XAHujrV/y
yEsoI7A/azsijkuqhd0SfAresinW9hq05AkFor7n8QKBgQDP8HZ5dkECk8h1N2Uc
JmKAUJcQYNwcQ4yOc5OkWAhe66fVYicPsOfffN8xekh4IQ5JtQI7ntRxWrVTRwzT
QJ00iG+2yOOKynbgs2xFflMitZcPUOITcDescNE0RiVW9PKlcQokgps3E0PlTGbA
oDR2lKk6KSb3XwDx+HcGV+2gEwKBgQC3ajiCNSIBrhauyk3a2niY5lN+gOa9DatX
EnjClImE8YmgUddrVqHRBHFebYZ6y+RdASz4MoT3qxZrQU4qzqfKZAPukQv6uIRM
zsqN8gz6sJ4wcXUPRy2G6cqKusRK2oyaXd7n86Ltr/cT5EnDghzLfdthiGkzCvVA
pLpMZcW/hQKBgGKs/cvN7jPG5Y2aaATfwkaZ99Xx4QIYnA7NkfafP/mrYs3D8j1j
+eT4YQIdwV4gcaNQnmqkiLPyE7IdOVzWgMN5K2pWEoS+Z4NiIbMoq1MBUVoXS/Fl
g0X1k5F26ClHvA3+go2o3PdZ0RJzGx+15q+PBG2xL+ib0NsCyZjdCQq5AoGASYr3
2Y3AcvgA9Fj92rEbBgPkmqbI3ikq+KDZdvvkIEBRNM1cGRgFji+/3WMBNx+mE3yz
MVngYwZg2OS4mQV/1fFAeloCeaeetMV+Bmh1t9c1tqrnixa5NI1tvy6gInt7QTI+
fLb+L1wNMBarVQ9IyHdQjc0KkYLlT+Q9JwDvx5kCgYBii47Hqk4VyWzcArWSCja5
0G++okiXkaxaNdd/Lw1gKj141Lc9YMdhlhBlB+4HqdwbAkGCBNFGTbr1N8UIyVza
CGhM3Ls2JEjB6cxnTKbTrQi61ap3VfJlDHphbzJo5vURV7ewruTjxa+UcJbl5LKH
UjawT/lpSLTaPrewUnVO9g==
-----END PRIVATE KEY-----
-----BEGIN CERTIFICATE-----
MIICoTCCAYkCAgPoMA0GCSqGSIb3DQEBBQUAMBQxEjAQBgNVBAMMCUNMSS1Mb2dp
bjAiGA8yMDI1MTAwNzA5MjMxNFoYDzIwMjYxMDA3MDkyMzE2WjAUMRIwEAYDVQQD
DAlDTEktTG9naW4wggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEKAoIBAQCU+ywo
PwKTIzUBPCkpQDnwv7YVsF3/2JauceV31mppD9z0kQYFoVTxx5cHNUCn323J4CMb
son/PccdBJ07Y+gs+/2ZD6OMfGkp9fWQuN4WrJj0Rc3DOFB7RFE6dxcNQelc14o9
1XFVR99DUB7yCAL750iv+uNpB+wF5CSr5LkQYbiQLKnsuTZyAkud4CcP/Z4ouL01
Zm+nxePWqmghas09fzCnUOrUEYnyQ6MmwUvjaNbWmd0zmN3SZ1CALqy+CQesG/N7
izgvFWBDd2ZPQ/BwrqlmLOPMPH17fGWm8KTanbC6Do1DNfI0SMQB7L/O1VBw0+Xn
mVTpYjx7T42mgVbfAgMBAAEwDQYJKoZIhvcNAQEFBQADggEBAIIPL1jfRLKT/Ens
t6zCDL1vExfRP7ocf4wzXOmW0Z5IY3zkRpGpQcF5iLEqQ6IgfQJg+EboXvJQCS+8
j8RJYhfEd6MnPfc7d32/+KyCXrrcogSyKVvI953fdalUclHHCFp0DznfSnRENOAR
knJTHWlt2SXMSqU4EP7jOJK2zaucAml0igF+lIC7UccRfLpSbVgRdBhuQUx5EVBJ
qsSR4zaiX4jxue2mcyov0O/2kxUOXUkszpuENMs/x0XIzOjadiACSWjYO6shfwFs
1z2AHHDs3a/Ji7p/fC954gAP86iANQaTIZ937LxuE3GLBGZOO9UOw8ddIVxExqqW
49xJeb0=
-----END CERTIFICATE-----
```

### 5. RESOURCE_GROUP (if not already created)
You'll also need to create this secret for your deployment workflow:
```
demo-container-apps
```

## Certificate File Location

**⚠️ IMPORTANT**: The certificate file is stored at:
```
C:\Users\dawahby\tmp9kk86x22.pem
```

**Please save this file to a secure location and delete it from the temporary directory after you've copied it to GitHub Secrets.**

## How to Add Secrets to GitHub

1. Go to your repository: https://github.com/wasytb72/demo-container-apps-store-api-microservice
2. Click on **Settings** tab
3. In the left sidebar, click **Secrets and variables** → **Actions**
4. Click **New repository secret**
5. Add each secret with the exact name and value as shown above

## Certificate Expiration

Your certificate is valid until: **October 7, 2026** (1 year from creation)

## Security Best Practices

- ✅ Certificate-based authentication is more secure than password-based
- ✅ The service principal has minimal required permissions (Contributor role)
- ✅ Certificate is scoped to your specific subscription
- ⚠️ Store the certificate file securely and delete the temporary copy
- ⚠️ Monitor certificate expiration and renew before it expires

## Testing

After adding the secrets, you can test the authentication by:
1. Pushing a commit to trigger the `test-azure-credentials.yml` workflow
2. Check the workflow run to ensure Azure login succeeds
3. Run the main deployment workflow to verify it can deploy resources

## Troubleshooting

If authentication fails:
1. Verify all secrets are added with correct names and values
2. Ensure the certificate content includes both private key and certificate
3. Check that there are no extra spaces or characters in the secrets
4. Confirm the service principal has the required permissions