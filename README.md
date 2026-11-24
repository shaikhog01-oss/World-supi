# WorldUPI — personal family payments prototype

## Run locally
Open `index.html` in a browser. For install/PWA testing, serve this folder over HTTPS or localhost, for example:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Included
- Responsive web dashboard for desktop and mobile
- PWA manifest and service worker (installable where supported)
- Demo send/receive records, family profiles, bank-name directory, currency calculator and CSV export
- Browser-local storage

## Important limitations
This is a functional front-end prototype, **not a live payment app**. It does not connect to UPI, banks, SWIFT, remittance providers, or live exchange-rate feeds. It cannot move money, create a valid payment QR, or verify transactions. Sample FX rates are illustrative. Never enter bank passwords, full account numbers, card details, UPI PINs or OTPs.

Before real payments: work with participating regulated banks and authorised payment providers; obtain required onboarding/approvals; complete legal review for RBI/FEMA, KYC/AML, tax, data protection and security; implement a secure server-side architecture, authentication, encryption, audit logs, fraud controls, signed webhooks, reconciliation and provider sandbox testing. International sending and receiving are separate regulated flows and must be enabled only where the provider and bank support them. Since the intended account holder is under 18, an eligible adult/guardian and provider-specific age rules will be necessary for financial onboarding.
