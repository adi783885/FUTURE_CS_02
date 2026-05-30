# Phishing Detection & Awareness Report

[cite_start]An entry-level security analysis evaluating live phishing email samples, identifying critical threat indicators, and providing actionable user prevention guidelines[cite: 8, 9, 12].

---

## 📌 Project Overview
* **Prepared By:** Adithyan. [cite_start]V [cite: 2]
* [cite_start]**Date:** 30 May 2026 [cite: 2]
* [cite_start]**CIN ID:** `FIT/MAY26/CS8390` [cite: 2]
* [cite_start]**Repository Link:** [FUTURE CS 02](https://github.com/adi783885/FUTURE_CS_02) [cite: 169]

---

## 🎯 Objectives & Tools
* [cite_start]**Goal:** Analyze spam ecosystem samples, perform basic email header checks, and calculate threat risk scores[cite: 8, 10, 11].
* [cite_start]**Tools Used:** Gmail Web Client ('Show Original'), MXToolbox (Header Analysis), and MS Word/GitHub[cite: 15].

---

## 🔍 Case Studies Analyzed
[cite_start]The repository inspects three major phishing templates operating on a shared backend infrastructure[cite: 98, 130]:
1. [cite_start]**Sample 1 (Emergency Paisa):** Fake ₹50,000 loan approval using artificial urgency and domain mismatches[cite: 16, 17, 51, 53].
2. [cite_start]**Sample 2 (Bajaj Finserv):** Personal loan eligibility check up to ₹25,00,000 to exploit financial bait[cite: 57, 75, 94].
3. [cite_start]**Sample 3 (HDFC Bank):** Impersonation of TATA HDFC Bank credit cards asking users to confirm sensitive details[cite: 99, 116, 117, 118].

---

## 📊 Risk Scoring Summary
[cite_start]All three analyzed samples scored a perfect **10/10 (High Risk)** based on key security indicators[cite: 137]:

| Indicator | Sample 1 | Sample 2 | Sample 3 | Risk Points |
| :--- | :---: | :---: | :---: | :---: |
| Suspicious Sender Domain | Yes | Yes | Yes | [cite_start]2 [cite: 137] |
| Urgent Language or Deadlines | Yes | Yes | Yes | [cite_start]1 [cite: 137] |
| Hidden or Mismatched Hyperlinks | Yes | Yes | Yes | [cite_start]2 [cite: 137] |
| Unexpected Financial Lure | Yes | Yes | Yes | [cite_start]2 [cite: 137] |
| Generic Greeting / Email Handle | Yes | Yes | Yes | [cite_start]1 [cite: 137] |
| Domain Security Failure (DMARC) | Yes | Yes | Yes | [cite_start]2 [cite: 137] |
| **Total Risk Evaluation Score** | **10/10** | **10/10** | **10/10** | [cite_start]**High Risk** [cite: 137] |

> [cite_start]**Technical Flaw:** The target domain relies on an un-enforced DMARC status (`p=none`), allowing malicious emails to slide past standard inbox controls even when authentication fails[cite: 56, 142].

---

## 💡 Quick Safety Rules
* [cite_start]**DO:** Check the actual email address behind the display name [cite: 150, 151][cite_start], hover over hyperlinks to inspect destination URLs [cite: 152, 153][cite_start], and report unusual deadlines to your IT team[cite: 158].
* [cite_start]**DON'T:** Click 'Unsubscribe' links in obvious spam [cite: 162][cite_start], trust logos blindly [cite: 163][cite_start], or enter passwords/OTPs on pages reached via email links[cite: 164].
