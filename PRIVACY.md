# Privacy Policy

**THE ONE** — Solana jackpot game
**Effective date**: 2026-04-25
**Operator**: DuckerForge ("we", "us", "our")

This Privacy Policy explains what data **THE ONE** (the "App", Android
package `com.duckerforge.theone`) collects, why we collect it, where it
is stored, and what choices you have. The App is a non-custodial Solana
dApp; we never hold your private keys, your funds, or your personal
identity.

---

## 1. Summary in plain English

- We do **not** ask for your name, email, phone number, address, or any
  other personal identifier.
- We identify you only by your **Solana wallet public address**, which
  is also published on the Solana blockchain and is therefore already
  public.
- We store a **device push token** if you grant notification permission,
  so the App can alert you about jackpot milestones and draw events.
- We never sell, rent, or share your data with third-party advertisers.
- All transactions happen on Solana mainnet. Solana is a public ledger.

---

## 2. Data we collect

### 2.1 Wallet address
When you tap **Connect Wallet**, your Solana wallet (Phantom, Solflare,
or any Mobile Wallet Adapter compatible wallet) authorizes the App.
The App receives your public address (e.g.
`qXhoL96gkzqe2KFMpVPseEWVzyzVUibw7YcXknUJQ85`) and uses it as your
unique account identifier.

### 2.2 Push notification token
If you allow notifications on Android, the App registers a Firebase
Cloud Messaging (FCM) device token and stores it under your wallet key
in our database. This token is only usable to send pushes to your
device.

### 2.3 Game activity
Stored against your wallet address:
- Number of tickets purchased
- Points earned (tickets, achievements, chests)
- Achievement unlock timestamps
- Daily free-chest usage marker
- Paid-chest count
- Solana transaction signatures of your purchases (for anti-cheat)

### 2.4 On-chain data
All ticket / chest / badge purchases happen on the Solana blockchain.
Transaction details (sender, amount, timestamp, recipient) are publicly
visible to anyone via any Solana block explorer. We do not control or
store this data — Solana does.

### 2.5 Diagnostic logs
Cloud Functions log technical events (errors, function invocations,
performance) for stability and abuse prevention. These logs may include
your wallet address but no other personal data, and are retained for
30 days by Google Cloud Logging defaults.

---

## 3. What we do NOT collect

- ❌ Your real name
- ❌ Your email address
- ❌ Your phone number or contacts
- ❌ Your geographic location, GPS, or IP address (beyond what Google
  Cloud automatically logs for incoming requests)
- ❌ Your wallet's private key or seed phrase — these never leave your
  wallet app
- ❌ Browsing history, advertising IDs, or behavioral profiling
- ❌ Camera, microphone, photos, or files

---

## 4. How we use your data

| Purpose                                | Data used                            |
| -------------------------------------- | ------------------------------------ |
| Identify your account                  | Wallet address                       |
| Track your rank and points             | Wallet address, game activity        |
| Verify on-chain payments (anti-cheat)  | Transaction signatures               |
| Send jackpot / draw notifications      | Push token                           |
| Process the prize draw                 | Wallet addresses, points, tickets    |
| Improve stability                      | Diagnostic logs                      |

We do **not** use your data for advertising, profiling, marketing
analytics, or training machine-learning models.

---

## 5. Where the data is stored

- **Firebase Realtime Database** (Google Cloud, US region) — wallet
  game state, push tokens, prize pool, leaderboard, draw settings.
  Project ID: `onetreasure-3f3ff`.
- **Cloud Functions logs** — Google Cloud Logging, US region.
- **Solana mainnet** — all on-chain transactions; not under our control.

Google Cloud is GDPR-compliant and certified ISO 27001 / SOC 2.

---

## 6. Data retention

- **Per draw cycle**: at the end of each draw, the leaderboard,
  participant points, ticket counts, processed-transaction markers, and
  notification flags are reset. Historical winners are preserved.
- **Push tokens**: kept for as long as you keep the App installed and
  active. Tokens that become invalid (e.g. uninstall, OS revoke) are
  deleted automatically the next time we attempt to send a push.
- **Diagnostic logs**: 30 days (Google Cloud default) and then purged.
- **On-chain data**: permanent on Solana, outside our control.

---

## 7. Your rights and choices

Because we identify you only by a public wallet address, you can
exercise most rights yourself, instantly:

- **Stop using the App**: tap **Disconnect** in the Profile tab. The
  App immediately signs out and deletes your push token from our
  database.
- **Revoke notifications**: revoke the notification permission in
  Android system settings.
- **Delete your participation record**: contact us (see §10) with your
  wallet address and request removal. We will erase your participant
  record, push token, and any logged identifiers within 14 days. We
  cannot remove on-chain transactions.
- **Access your data**: all your data is already visible in-app
  (leaderboard, profile). Cloud Function logs related to your wallet
  can be requested via the contact channels in §10.

If you are an EU/EEA resident, you also have the right to lodge a
complaint with your national data protection authority.

---

## 8. Security

- Authentication uses Firebase Custom Tokens issued only after a
  successful Solana Mobile Wallet Adapter authorization round-trip.
- All purchase reports go through Cloud Functions that verify the
  on-chain transaction (sender, amount, recipient) before crediting any
  points. The client cannot directly write to the participant or pool
  records — server-side rules forbid it.
- All transport is HTTPS.
- We never see, store, or transmit your private key.

No system is perfectly secure. Report suspected vulnerabilities via
GitHub issues (see §10).

---

## 9. Children

THE ONE involves real Solana cryptocurrency and is **not intended for
users under 18**. Do not use the App if you are under 18 or under the
legal age of majority in your jurisdiction. We do not knowingly collect
data from minors; if we discover a minor has used the App, we will
delete the related account on request.

---

## 10. Contact

Privacy questions, deletion requests, takedowns:

- **GitHub Issues**: https://github.com/DuckerForge/TheOne/issues
- **X / Twitter**: https://x.com/skrburn
- **Telegram**: https://t.me/skrburn

We aim to respond within 7 business days.

---

## 11. Changes to this policy

If we change how the App handles data, we will update this document and
push a notification through the App's broadcast system. The "Effective
date" at the top will reflect the latest version.

Older versions of this policy are available in the GitHub commit
history of this repository.

---

© 2026 DuckerForge. Distributed under the MIT License.
