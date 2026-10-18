# BioSense Guardian AI — Prototype

A small, responsive browser dashboard concept for a wearable health-monitoring project. It demonstrates how heart rate, SpO₂, temperature, a basic trend chart, and caregiver-alert previews could be presented.

## Current status

**Software demo only.** The dashboard uses simulated values generated in the browser. It does not connect to a sensor, provide medical advice, store health data, or send real notifications. Do not present its simulated output as measured test evidence.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser. No package installation is required.
3. Click **Update readings**, **Pause simulation**, and **Test alert** to demonstrate the interface.

For best results during a presentation, open the page in Chrome and use full-screen mode.

## Prototype features

- Vital-sign cards for heart rate, SpO₂, and temperature.
- Simple illustrative heart-rate trend chart.
- Rule-based demo status labels.
- Local event log and a test-alert preview.
- Responsive layout for laptop and mobile screens.
- Visible notice distinguishing simulated readings from real measurements.

## Suggested next development steps

1. Choose and document the actual sensors and microcontroller.
2. Read sensor values and validate them against suitable reference equipment.
3. Connect the device to a local API using a defined data format.
4. Add authentication, encrypted transport, access controls, and consent before any real health data is handled.
5. Implement a real caregiver notification service only after safety and reliability testing.
6. Conduct usability testing with informed consent and record actual results accurately.

## Repository structure

```text
biosense-guardian-ai-prototype/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   └── prototype-status.md
└── firmware/
    └── README.md
```

## GitHub Pages

This is a static website, so it can be hosted with GitHub Pages:
1. Create a new repository on GitHub, for example `biosense-guardian-ai-prototype`.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under the build/deployment source, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site; use the URL shown in Settings → Pages.

## Safety and privacy

This is an educational prototype, not a medical device. Thresholds are illustrative and do not account for a person's medical history or circumstances. It must not be used to diagnose, treat, or make emergency decisions. Do not commit personal health records, API keys, passwords, or identifiable patient information.
