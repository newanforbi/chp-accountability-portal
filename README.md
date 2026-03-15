# CHP Accountability Portal

**Newanforbi v. Meza-Gonzalez** — A structured accountability tracker for the November 1, 2024 incident on I-580, Livermore, CA.

🔗 **Live Site: [newanforbi.github.io/chp-accountability-portal](https://newanforbi.github.io/chp-accountability-portal/)**

---

## What This Is

A self-contained web app for tracking all active accountability and legal remedies against CHP Officer Santiago Meza-Gonzalez (Badge #023295) arising from the unlawful detention, search, and arrest on November 1, 2024.

The portal organizes six parallel accountability tracks, a dashcam evidence matrix, and a critical case timeline — all in one place.

---

## Accountability Tracks

| Track | Description | Deadline |
|---|---|---|
| ⚖️ **Criminal Prosecution** | Felony perjury referrals to Alameda County DA and CA Attorney General | 3 years (tolled by discovery rule) |
| 🛡️ **POST Decertification (SB 2)** | Permanent revocation of peace officer certification | File ASAP — CHP must report within 10 days |
| 📋 **CHP Internal Affairs** | Civilian complaint (Form 240B) triggering POBRA investigation | 1 year (tolled by civil litigation) |
| 🚗 **DMV Investigation** | Challenge the fraudulent DS-367 and APS CDL suspension | Tied to APS hearing outcome |
| 🏛️ **Alameda County Grand Jury** | Independent citizen body with subpoena power | No strict deadline |
| 🇺🇸 **Federal Civil Rights (Active)** | 42 USC §1983 lawsuit — Case 2:25-cv-01460-DC-CSK | Filed May 27, 2025 ✓ |

---

## Key Evidence

The portal's Evidence Matrix documents five critical contradictions between Officer Meza-Gonzalez's sworn DS-367 statements and the dashcam transcript:

- **Fabricated alcohol odor** — Only urine was identified; officer refused to smell the substance himself
- **False admission of driving** — Plaintiff stated he was parked 5–7 minutes; no contemporaneous DUI driving was admitted
- **Illegal vehicle search** — Rear compartment searched 12 minutes before parole status was known (Sanders violation)
- **Unconstitutional vehicle entry** — Door opened before welfare check justification; officer stated criminal investigation motive
- **Retaliatory arrest for PAS refusal** — Arrest occurred seconds after a lawful refusal the officer acknowledged was optional

> The Dublin CHP Area Office issued a **PC §849(b)(1) Detention Certificate** on November 5, 2024 — formally acknowledging *"insufficient grounds for making a criminal complaint"* — while the falsified DS-367 was simultaneously used to suspend the plaintiff's CDL.

---

## Case References

| | |
|---|---|
| **Plaintiff** | Brendan Ngehsi Newanforbi |
| **Officer** | Santiago Meza-Gonzalez, Badge #023295 |
| **Partner** | Jose Melano, Badge #023054 |
| **CHP Case** | RJ68845 |
| **Federal Case** | 2:25-cv-01460-DC-CSK (E.D. Cal.) |
| **Incident Date** | November 1, 2024 |
| **Location** | I-580 East, Livermore, Alameda County, CA |

---

## Technical Notes

Built as a single `index.html` file — no build step, no dependencies to install. Uses React 18 and Babel via CDN. Progress checkboxes persist across sessions via `localStorage`.

---

*This portal is for organizational reference only and is not legal advice. Always consult a licensed attorney before taking legal action.*
