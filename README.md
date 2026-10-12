# SPLASH Build Doctor

A fast, browser-based Android build log analyzer built to help developers identify common Gradle and Android Studio errors without uploading logs anywhere.

## What it does

SPLASH Build Doctor scans pasted build output for common patterns such as:

- missing Gradle wrapper or project root issues
- missing tasks and task name mismatches
- SDK location / platform configuration errors
- Java / Gradle compatibility issues
- APK output not found or not verified

It then presents:

- a plain-language explanation
- the matched evidence from the log
- verification steps to test in the real project
- an exportable report for sharing or documentation

## Why this exists

Android and Gradle errors are common, noisy, and often ambiguous. This project is built to reduce confusion by turning raw failure text into a fast first-pass diagnosis while keeping everything local in the browser.

## Live app

The app is served as a static website from this repository and can be opened directly in a browser.

## Repository layout

- `index.html` — launch-ready landing page and analyzer UI
- `README.md` — project overview and usage
- `MARKETING_PLAN.md` — product positioning and launch strategy
- `LICENSE` — MIT license for open-source distribution and monetization flexibility

## Quick start

1. Open `index.html` in a browser.
2. Paste a Gradle or Android build error log.
3. Click "Analyze log".
4. Review evidence and next steps.

## Example use

Paste logs like:

- `Android Gradle plugin requires Java 17 to run.`
- `SDK location not found.`
- `Task 'assembleDebug' not found.`

## Product status

Status: Launch-ready MVP

This is a simple, useful diagnostic tool for early users and a strong foundation for a bigger product line.

## License

This project is licensed under the MIT license.

## Support and monetization path

You can monetize this project through:

- optional donations
- premium workflows or advanced detection packs
- paid desktop or web version
- enterprise licensing for teams
- premium support packages

## Roadmap

- expand supported Android/Gradle error rules
- improve structure and evidence extraction
- add template-driven reports
- add optional pro mode and saved analyses
- publish a polished landing page and distribution strategy

## Contact

Developed by Nolan Sands.
