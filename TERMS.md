# Terms of Service

**THE ONE** — Solana jackpot game
**Effective date**: 2026-04-25
**Operator**: DuckerForge ("we", "us", "our")

By installing, opening, or using **THE ONE** (the "App", Android
package `com.duckerforge.theone`), you accept these Terms of Service
("Terms"). If you do not accept them, uninstall the App and stop using
it.

---

## 1. What THE ONE is

THE ONE is a non-custodial Solana dApp. Players spend SOL on tickets,
chests, and badges. Spent SOL is split between an on-chain prize pool
and a fixed operator fee. At a publicly announced "Draw Day", the prize
pool is distributed by an automated, server-side function:

- **50%** to a single ticket holder, picked at random with probability
  proportional to the number of tickets they hold.
- **30%** split equally between the top 5 wallets by points.
- **20%** split equally between wallets ranked #6 to #10 by points.

Points come from tickets, chests, and badges. The split percentages and
the draw mechanism are visible in the open-source code at
https://github.com/DuckerForge/TheOne.

THE ONE is not affiliated with, endorsed by, or sponsored by Solana
Labs, Solana Mobile, Google, Firebase, or any third-party brand.

---

## 2. Eligibility — read this carefully

Use of THE ONE involves real cryptocurrency, randomized prize
distribution, and ticket-based participation. Depending on where you
live, this may be classified as gambling, a sweepstakes, a skill-based
contest, an unregulated promotional draw, or as outright prohibited.
**It is YOUR responsibility — not ours — to verify the legality of THE
ONE in your jurisdiction before using it.**

By using the App you represent and warrant that, at the time of every
session and every transaction:

1. You are **at least 18 years old**, or the legal age of majority in
   your country / state / province, whichever is higher.
2. You are physically located in, and a tax resident of, a
   jurisdiction where participating in a non-custodial Solana
   ticket-based prize draw with the mechanics described in §1 is
   **legal**, **not subject to a license you do not hold**, and **not
   prohibited** by any applicable law, regulation, sanction, or court
   order.
3. You are **not** located in, a citizen of, or a resident of any
   country, region, state, or jurisdiction where:
   - online gambling, lotteries, sweepstakes, or prize draws are
     prohibited, restricted, or require an operator license that
     DuckerForge does not hold;
   - participation in the App would violate any sanction, embargo, or
     export-control regime (including, without limitation, those
     administered by the United Nations, the European Union, OFAC, HM
     Treasury, or any equivalent national authority).
4. You are using the App **of your own free will, with your own funds,
   for your own account**, and you are **not** acting on behalf of any
   regulated, prohibited, or sanctioned third party.
5. You authorize yourself to bear all financial, legal, and tax
   consequences of using the App. You will not seek any refund,
   chargeback, reversal, or compensation from DuckerForge for losses
   arising from your participation.

If you cannot truthfully make all of the above representations, **do
not use the App**. Continued use is a continued representation that all
the above remain true.

We do not pre-screen your jurisdiction. We do not verify your age. The
App does not know where you are. Self-certification through use is the
basis on which the App is offered.

---

## 3. Italy and other restricted jurisdictions

The Operator is aware that real-money prize draws operated without a
local license are restricted or prohibited in several jurisdictions,
including but not limited to **Italy** (where ADM/AAMS authorization is
required) and various U.S. states.

THE ONE is **not licensed** under Italian law (D.Lgs. 41/2024 / TUEF /
Decreto Direttoriale ADM) and is **not offered to residents of Italy**.
If you are a resident of Italy, of any U.S. state where unlicensed
sweepstakes are prohibited, of mainland China, of any country sanctioned
by OFAC, or of any other jurisdiction listed in §2.3, **you are not
eligible to use the App**, regardless of any technical means by which
you might access it (VPN, proxy, mirror, side-loading, etc.).

Using the App from a restricted jurisdiction is a violation of these
Terms and may also be a violation of your local law. The Operator does
not waive any defense available to it under §2 of these Terms based on
the Operator's lack of presence in your jurisdiction.

---

## 4. Non-custodial nature and on-chain finality

- THE ONE never holds, custodies, or has access to your private keys
  or your funds.
- All transactions are executed on Solana mainnet from your wallet,
  signed by your wallet app. Once you approve and broadcast a
  transaction, it is **final and irreversible**.
- We cannot reverse a Solana transaction, refund SOL, or recover funds
  sent to a wrong address, lost wallet, or compromised seed phrase.
- The on-chain pool address (`FpB34UK6yY4K5B378U5K7PCU9V9DLXjb5bCRo6XvCbQg`)
  and the operator fee address (`qXhoL96gkzqe2KFMpVPseEWVzyzVUibw7YcXknUJQ85`)
  are fixed. Any payment sent to other addresses while attempting to
  use the App is your sole responsibility.

---

## 5. Operator fee

A fixed **10% of every payment** (tickets, paid chests, paid badges)
is sent to the operator address as an infrastructure fee that funds
hosting, Firebase usage, RPC calls, push notifications, development,
and ongoing maintenance. The remaining **90%** is added to the on-chain
prize pool and is distributed at the next Draw Day.

The fee is non-refundable and is collected at the moment of the
on-chain transaction.

---

## 6. The Draw

- The Draw is triggered by the Operator at the publicly announced Draw
  Day.
- The randomized winner selection runs server-side in a Cloud Function
  (`triggerDraw`) whose source is public in the GitHub repository.
- Once the Draw runs, the leaderboard, points, tickets, and processed
  transactions are reset for the next round.
- Prize transfers to winners may be performed manually by the Operator
  on-chain, in batched transactions, within 30 days of the Draw.
- The Operator reserves the right to **postpone the Draw** if a
  technical issue, exploit, RPC outage, or sanctioned party in the
  participant pool would compromise its integrity. Postponement does
  not entitle any participant to a refund.

---

## 7. Prohibited conduct

You agree not to, and not to attempt to:

- Use the App while not eligible under §2.
- Submit fraudulent, replayed, spoofed, or manipulated Solana
  transactions.
- Abuse achievements, chests, or badges via collusion or bots.
- Reverse-engineer, exploit, or attempt to break the server-side
  verification logic.
- Spam, harass, threaten, or send unsolicited messages to the Operator
  or the broader player base.
- Use the App for money laundering, sanctions evasion, terrorist
  financing, or any unlawful purpose.

The Operator may, at its sole discretion and without notice, ban any
wallet that engages in the above. Banned wallets forfeit any unrealized
prize, points, ticket count, or accumulated bonuses.

---

## 8. Service availability

The App is provided **"as is"**, on a best-effort basis. We do not
guarantee continuous availability. Outages of Solana mainnet, Firebase,
Helius RPC, FCM, the Google Play Store, or any dependency may degrade
or interrupt the service. Scheduled maintenance, security patches, or
draw operations may temporarily disable purchases.

We may shut the App down, freeze deposits, or migrate to a successor
project, with at least **14 days' notice** through the in-app broadcast
system, the GitHub repository, and the contact channels in §13. In
that case, the remaining on-chain pool will be distributed in
accordance with §6.

---

## 9. No warranty — DISCLAIMER

THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT ANY WARRANTY OF
ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE,
NON-INFRINGEMENT, ACCURACY, SECURITY, OR FREEDOM FROM HARMFUL CODE.

WE DO NOT WARRANT THAT THE APP WILL OPERATE UNINTERRUPTED, ERROR-FREE,
OR FREE FROM SECURITY VULNERABILITIES. WE DO NOT WARRANT ANY OUTCOME
OF YOUR PARTICIPATION, INCLUDING WINNING ANY PRIZE.

---

## 10. Limitation of liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW:

- THE OPERATOR'S TOTAL AGGREGATE LIABILITY ARISING FROM OR RELATED TO
  YOUR USE OF THE APP IS CAPPED AT **THE TOTAL OPERATOR FEE
  (10% PORTION) WE ACTUALLY RECEIVED FROM YOUR WALLET IN THE 90 DAYS
  PRECEDING THE EVENT GIVING RISE TO THE CLAIM**, OR USD 100,
  WHICHEVER IS LOWER.
- IN NO EVENT WILL THE OPERATOR BE LIABLE FOR INDIRECT, INCIDENTAL,
  SPECIAL, CONSEQUENTIAL, EXEMPLARY, OR PUNITIVE DAMAGES, INCLUDING
  LOST PROFITS, LOST OPPORTUNITY, LOSS OF CRYPTOCURRENCY, LOSS OF
  GOODWILL, OR LOSS OF DATA, EVEN IF ADVISED OF THE POSSIBILITY.
- THE OPERATOR IS NOT RESPONSIBLE FOR ACTIONS OR INACTIONS OF SOLANA
  VALIDATORS, RPC PROVIDERS, WALLET APPLICATIONS, FIREBASE / GOOGLE
  CLOUD, OR ANY OTHER THIRD PARTY.

---

## 11. Indemnification

You agree to indemnify, defend, and hold harmless DuckerForge, its
contributors, and its agents from any claim, demand, loss, liability,
or expense (including reasonable legal fees) arising from:

- Your use of the App;
- Your violation of these Terms;
- Your violation of any law, regulation, sanction, or third-party
  right; or
- Your false certification under §2.

---

## 12. Governing law and disputes

These Terms are governed by the laws of the **British Virgin Islands**,
without regard to conflict-of-law principles. Any dispute arising out
of or relating to these Terms shall be resolved exclusively by binding
arbitration administered under the rules of an internationally
recognized arbitration body (e.g. ICC, LCIA, JAMS), seated in a neutral
jurisdiction, conducted in English. You waive any right to participate
in a class action or class arbitration to the maximum extent permitted
by law.

If any provision of these Terms is held unenforceable, the remaining
provisions remain in full force.

---

## 13. Contact

- **GitHub**: https://github.com/DuckerForge/TheOne
- **GitHub Issues**: https://github.com/DuckerForge/TheOne/issues
- **X / Twitter**: https://x.com/skrburn
- **Telegram**: https://t.me/skrburn

---

## 14. Changes to these Terms

We may revise these Terms at any time. The "Effective date" above
reflects the most recent version. Material changes will be announced
in-app via the broadcast system at least **14 days before** taking
effect, except where a shorter notice is required by law, court order,
or to address an active security incident.

Your continued use of the App after the effective date of an updated
Terms is deemed acceptance.

---

© 2026 DuckerForge. Distributed under the MIT License (see `LICENSE.md`).
