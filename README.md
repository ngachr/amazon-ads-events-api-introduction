# Amazon Ads Events API - Python Integration Scripts

[![Amazon Ads](https://img.shields.io/badge/Amazon%20Ads-Events%20API%20v2-orange)](https://advertising.amazon.com/API/docs/en-us/guides/events/events)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

Python scripts to help advertisers and integrators get started with the **Amazon Ads Events API** (Conversions API v2) — server-to-server integration for sending real-time or offline conversion events, bypassing browser-based tracking limitations (ad blockers, cookies, privacy settings).

📺 **[Video Walkthrough](https://youtu.be/nKxD_EyR1P8)**

---

## Key Capabilities

- **Automatic Conversion Definition Creation** — No pre-setup required
- **Dataset Organization** — Group events via Ads Data Manager (ADM)
- **Custom Attributes** — 10 named attributes + `brand`, `productId`, `category` (queryable in AMC)
- **Batch Processing** — Up to 500 events/request
- **Consent Support** — TCF, Amazon Consent String, GPP

---

## Prerequisites

1. **LwA Credentials** — Client ID, Client Secret, and Refresh Token
2. **Amazon Ads T&Cs** — Accept "Conversion Tracking" terms
3. **Profile ID & Advertiser ID** — Via Profile API and Advertisers API
4. **Permissions** — Event Manager Edit access

---

## Quick Start

```bash
git clone https://github.com/amzn/amazon-ads-events-api-scripts.git
cd amazon-ads-events-api-scripts
pip install -r requirements.txt

