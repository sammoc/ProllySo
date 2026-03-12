# Privacy Policy

**Last updated: March 12, 2026**

---

## Overview

ProllySo is a statistical distribution recommender for macOS. This policy explains what data the app handles, where it stays, and what we never do with it.

**TLDR:** ProllySo processes your data entirely on your device. Nothing you enter or upload is ever transmitted to us or any third party.

---

## Who We Are

ProllySo is an independent app. For privacy questions, contact us at:

**Email:** [prollyso@sammoc.com](mailto:prollyso@sammoc.com)

---

## What Data ProllySo Handles

### Data You Provide

All data you provide is held in memory during the session and never leaves your device.

| Data | Leaves your device? |
|:---|---|
| Imported data files (CSV) | **Never** |
| Numeric values from CSV columns | **Never** |
| Sample mean, variance, etc.  | **Never** |
| Data profile answers<br>(e.g. "continuous", "symmetric") | **Never** |

### Data ProllySo Does NOT Collect

- We do *not* collect analytics or usage telemetry.
- We do *not* use advertising SDKs or tracking frameworks.
- We do *not* create user accounts or profiles.
- We do *not* access your contacts, camera, microphone or location.
- We do *not* use cookies or any web tracking technology.

---

## How Your Data Is Processed

All computation — including MLE parameter estimation, KS goodness-of-fit tests, AIC scoring, and KL-divergence calculations — runs locally on your Mac using Apple's Accelerate framework. No network connection is required or initiated during normal app use.

CSV files you import are read into memory for the duration of your session and are not written to any database, log file, or persistent store by the app.

---

## Data Retention

ProllySo does not persist your data between sessions. When you close the app, all in-memory values (imported CSV data, computed statistics, and profile answers) are discarded automatically. We have no copy of anything you worked with.

---

## Third-Party Services

ProllySo does not integrate with any third-party analytics, advertising, or data-sharing services. The only frameworks used are Apple's own system frameworks (SwiftUI, Swift Charts, Accelerate, etc.).

---

## Apple Platform Privacy

As a macOS app distributed through the App Store, ProllySo is subject to Apple's standard sandboxing and privacy practices. You can review Apple's privacy policy at [apple.com/privacy](https://www.apple.com/privacy/).

File access is granted only when you explicitly choose to import a file via the system file picker. The app does not have broad filesystem access.

---

## Children's Privacy

ProllySo does not knowingly collect any information from anyone, including children under the age of 13. The app contains no data collection mechanisms of any kind.

---

## Changes to This Policy

If we make material changes to this policy, we will update the **Last updated** date at the top of this page. Because we collect no personal data, changes are expected to be minor (such as contact detail updates).

---

## Contact

If you have questions about this privacy policy or the app's data practices, please email:

**[prollyso@sammoc.com](mailto:prollyso@sammoc.com)**

---

*ProllySo — statistical distribution analysis, entirely on your device.*
