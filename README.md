# How to Activate Namecheap SSL on a GoDaddy Account

## Step 1: Log in to the GoDaddy Account
1. Navigate to **cPanel → SSL/TLS → Generate CSR**.
2. Copy the generated CSR.

## Step 2: Log in to the Namecheap Account
1. Go to the **SSL** section and select **Issue Certificate**.
2. Paste the CSR into the Certificate Generation field.
3. Select the **Manual File Upload** option.
4. Download the file from the provided dropdown menu.

## Step 3: Upload the Validation File to GoDaddy
1. In the GoDaddy account, navigate to **cPanel → File Manager → public_html → .well-known → pki-validation**.
2. Upload the downloaded validation file to this directory.

## Step 4: Complete the Verification Process in Namecheap
1. Change the verification method to **HTTPS (Domain Control Validation)**.
2. The CRT file will be sent to your email.
3. Download the CRT file from the email.

## Step 5: Install the SSL Certificate on GoDaddy
1. In the GoDaddy account, navigate to **cPanel → SSL/TLS**.
2. Select the **Upload CRT** option.
3. Go to **Manage SSL** and install the certificate.

By following these steps, your Namecheap SSL will be successfully activated on your GoDaddy account.
