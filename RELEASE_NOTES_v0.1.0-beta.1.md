# GreenPeas v0.1.0-beta.1

GreenPeas is a desktop DNA sequence editor and cloning workspace. This is the first public beta release for feedback and real-world compatibility testing.

## Highlights

- Open and edit DNA sequence files with sequence and map-oriented views.
- Work with annotations, primers, and restriction enzymes.
- Run alignment-oriented workflows.
- Use cloning tools including fragment handling and Smart Ligation validation.
- Open sequences in additional windows and move sequences between windows.
- Report bugs through a pre-filled support email.

![GreenPeas main window](screenshots/main-window.png)

## Beta Notice

This build is intended for testing and feedback. Do not use it as the only copy of important lab data.

All features are currently open during the public beta. Future paid distribution is planned through Lemon Squeezy, but paid license enforcement is not active in this release.

GreenPeas proprietary code may not be copied, modified, redistributed, or resold. Third-party components remain available under their respective licenses. The release includes `LICENSE` and `THIRD_PARTY_LICENSES.txt`.

## Download

Current macOS artifact:

- `GreenPeas_0.1.0_aarch64.dmg` for Apple Silicon Macs
- SHA-256: `84e0f1327535e405f7cd8aa3e9d1285b1232c89584c8919b2a955f031510f07c`

The current beta app is intentionally distributed without code signing or notarization. Confirm that the download came from the official GreenPeas binary-release repository and verify the SHA-256 checksum before opening it.

## Feedback

- Email: ryuki.abriu@gmail.com

Please include the GreenPeas version, platform, file type, reproduction steps, expected behavior, and actual behavior.

## Known Limitations

- This beta is Apple Silicon only; Intel Mac support is not included in the first public beta.
- File compatibility still needs broader testing with real-world `.gb`, `.gbk`, `.dna`, and `.gp` files.
- The current licensing implementation is a debug-open scaffold, not production Lemon Squeezy validation.
