# Multi-Factor Authentication

## What is Multi-Factor Authentication (MFA)?

The protection of personal data, in particular health information, is a major key in
data security. Authentication to verify the identity of the individual that is about
to access a data system holding this sensitive information is crucial. The most
common factor used to authenticate the user and grant that access is a password,
often in combination with a username or email address. But if this knowledge is
stolen, the relevant user account is compromised.

For higher protection, MFA requires at least two authentication factors out of the
following list:

- Something you know, such as a password, PIN, etc.,
- Something you have, such as a security token, card, key, etc.,
- Something you are, such as your fingerprint, eye iris, etc.

For our purpose and in-house developed web applications, we make use of two
different factors, the password on one hand (something you know) and a
randomly generated token from a mobile phone app (something you have). In this
scenario, even if one of both factors is compromised, the account and
consequently the access to the protected information are still secured. When using
two factors, we can also speak of “Two-Factor Authentication”.

## How to activate MFA in SDMS?

1. Log in to SDMS using your username and password.

2. When the QR code is displayed, open the **Microsoft Authenticator** app on your mobile device and tap the **plus (+)
   ** icon to add a new account.

3. Before proceeding, review the document titled **“Installation of an Authenticator App on your Mobile”**, which
   provides detailed installation steps for both Android and iOS devices.

4. If you do not already have an authenticator app installed, you can download **Microsoft Authenticator** using the
   links below:
    - **Apple App Store:** [https://apps.apple.com/us/app/microsoft-authenticator/id983156458](https://apps.apple.com/us/app/microsoft-authenticator/id983156458)
    - **Google Play Store:** [https://play.google.com/store/apps/details?id=com.azure.authenticator](https://play.google.com/store/apps/details?id=com.azure.authenticator)

   Microsoft Authenticator is free to use. You may alternatively use any authenticator app that supports standard *
   *Time-Based One-Time Password (TOTP)** codes for MFA in SDMS.

5. Configure your app as follows:
    - Open the authenticator app on your mobile and follow the prompts to register a new account (see Figure 6.9 below).
    - If the app includes a QR scanner, scan the QR code displayed on SDMS.
    - If the app does not support QR scanning, click **“Show Secret”** on the SDMS screen and manually enter the
      provided key into your app.
    - Once configured, the app will begin generating 6-digit codes that refresh every 30 seconds.

6. Confirm the setup:
    - To verify that your Authenticator app is correctly configured, enter the current 6-digit code displayed in your
      app into the SDMS dialog box and click **Activate**.
    - On successful verification, SDMS will confirm that **Multi-Factor Authentication (MFA)** is now active for your
      user account.
    - You may then continue to use SDMS as usual.

<figure>
    <img class="screenshot" src="_img/figures/6.9-multi-factor-authentication-activation-page.png" alt="Multi-Factor Authentication - Activation Page">
    <figcaption>Figure 6.9: Multi-Factor Authentication - Activation Page</figcaption>
</figure>

## How to Access SDMS Using MFA

1. Open the SDMS login page and sign in using your username and password as usual.

2. Once your login details are verified, you will be prompted to enter your MFA token.
    - Open your Authenticator app on your mobile device.
    - Locate the SDMS account entry and enter the 6-digit code currently displayed into the MFA token field on the SDMS
      login page.
    - Click **Confirm** to continue.

3. If the code is valid, you will be redirected to the SDMS Welcome page, where you can access the various modules and
   features.

Note: SDMS will prompt you to re-enter your MFA token every four (4) days as part of ongoing security verification.

## FAQs

**Q:** Is Multi-Factor Authentication (MFA) mandatory in SDMS?
**A:** Yes. MFA is required for all SDMS users to ensure account and data security. It cannot be disabled or bypassed.

**Q:** I closed the browser or logged out before scanning the QR code. What should I do?  
**A:** If you leave the page displaying the QR code before completing setup, SDMS will still generate an internal secret
linked to your account. As a result, the same QR code will not appear again. To avoid this issue, complete the
activation process in one continuous session on the same device. If you are unable to continue, contact SDMS Support for
a reset.

**Q:** I am experiencing technical issues. What should I do?  
**A:** If you continue to experience problems after following the instructions, please take a screenshot of the error
message and send it to **[mailto:sdmsadmin@paralympic.org](mailto:sdmsadmin@paralympic.org)**. Include your username and a short description of what you were
doing when the issue occurred.

**Q:** Can I deactivate MFA on my SDMS account?  
**A:** No. MFA is mandatory for all accounts. This policy helps protect both user and organisational data from
unauthorised access.

**Q:** The code from my Authenticator app is not being accepted. Why?  
**A:** If SDMS reports that your MFA token is invalid, ensure that your mobile device’s time and date settings are
accurate. MFA tokens are time-based and rely on Coordinated Universal Time (UTC). However, if the issue persists, remove
the SDMS entry from your Authenticator app and repeat the activation process from the beginning.

**Q:** Can I use a different MFA app than Microsoft Authenticator?  
**A:** Yes. SDMS supports any authenticator app that supports standard Time-Based One-Time Password (TOTP) codes for
MFA.

**Q:** I lost my mobile device or uninstalled the Authenticator app. What should I do?  
**A:** Contact **[mailto:sdmsadmin@paralympic.org](mailto:sdmsadmin@paralympic.org)** using the same email address registered with your SDMS user account. The
support team will reset your MFA configuration so that you can re-activate MFA on your new device.


