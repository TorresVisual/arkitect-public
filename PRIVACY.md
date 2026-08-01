# Privacy Policy

**Last updated: 2026-08-01**

This policy covers Arkitect (the desktop app) and the Arkitect Pro purchase/activation flow. It does not cover ARK: Survival Evolved itself, Steam, Discord, or Ko-fi — each of those has its own privacy policy, linked below.

## Who we are

Arkitect is developed by an independent small developer team ("we", "us"). Contact: **arkitect.pro.app@gmail.com**.

## What we collect

**If you never buy Pro or link Discord:** nothing leaves your computer. Arkitect's free features (macros, INI presets, crosshair, etc.) run entirely locally and store their settings in a local JSON file on your machine. We do not collect telemetry from the free app.

**If you buy Arkitect Pro on Ko-fi:**
- The email address you used to check out (from the Ko-fi payment notification), so we can send you a license key.
- The purchase/transaction ID, to prevent duplicate key issuance if Ko-fi resends the same notification.
- The license key itself and whether it has been sent/activated.

**If you link your Discord account (required to activate Pro):**
- Your Discord user ID and username, obtained via Discord's OAuth login — used only to bind your Pro license to your Discord identity and to check Pro status on app startup.
- We do not receive or store your Discord password, email, or message content.

We do not collect payment details (card numbers, etc.) ourselves — Ko-fi processes payment and never shares full payment details with us.

## Why we process this data

- To deliver the product you paid for (send/validate a license key) — performance of the purchase contract.
- To prevent fraud/abuse (duplicate key claims, shared/leaked keys) — legitimate interest.
- To provide support when you email us about a license issue.

## Where it's stored

- License/binding records (key, Discord ID, purchase email, transaction ID, timestamps) are stored in a Turso (libSQL) database operated for this app.
- Transactional emails (sending you your key) are delivered via Brevo.
- Ko-fi and Discord each independently process and store data under their own privacy policies:
  - [Ko-fi Privacy Policy](https://more.ko-fi.com/privacy-policy)
  - [Discord Privacy Policy](https://discord.com/privacy)

Some of these providers may process data outside your country, including in the United States, under their own standard safeguards (e.g. the EU–US Data Privacy Framework where applicable).

## How long we keep it

We keep purchase and license-binding records for as long as your license is active plus a reasonable period for support and fraud-prevention purposes, and as needed to meet our own accounting/tax record-keeping obligations. You can ask us to delete your data at any time (see below) — this deactivates your license.

## Your rights

If you're in the EU/EEA/UK (or a jurisdiction with similar protections), you have the right to:
- Access the personal data we hold about you
- Correct inaccurate data
- Request deletion ("right to be forgotten")
- Restrict or object to processing
- Receive your data in a portable format
- Lodge a complaint with your local data protection authority

To exercise any of these, email **arkitect.pro.app@gmail.com**. We'll respond within a reasonable time and may need to verify your identity (e.g. via the Discord account or purchase email on file) before acting on the request.

## Children

Arkitect Pro's activation flow requires a Discord account, and Discord itself requires users to meet its own minimum age requirement (13, or higher in some countries). We do not knowingly collect data from anyone below that threshold.

## Security

License data is stored in a managed database with restricted access; the HMAC secret used to validate keys is never bundled in the app or committed to source control. No system is perfectly secure, and we can't guarantee absolute protection against all attacks.

## Changes to this policy

We may update this policy as the app changes. Material changes will be reflected in the "Last updated" date above; check back periodically.
