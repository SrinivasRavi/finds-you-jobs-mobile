# finds-you-jobs-mobile

The phone companion for [finds-you-jobs](https://github.com/SrinivasRavi/finds-you-jobs), the open-source desktop app that finds jobs, scores them, and tailors your resume and cover letter.

Pair your phone with the desktop app by QR code, then triage the job board by swiping:

- **Right** saves the job to your tracker.
- **Up** saves it to Seeking Referral.
- **Left** sends it to Trash.

The desktop does the heavy work, using its own settings to decide whether to generate artifacts. Your API keys never leave the computer, and there's no finds-you-jobs server in between: phone and desktop talk directly over your own Wi-Fi.

## Status

Design phase. No code yet. The screens, states and behaviour are in [`docs/design-brief.md`](docs/design-brief.md).

Planned: iOS (App Store, TestFlight first), Android (Google Play and an APK on GitHub releases). Built with Expo, React Native and TypeScript.

## License

[Apache-2.0](LICENSE). The desktop app is AGPL-3.0-only; this companion talks to it over HTTP and carries none of its code.
