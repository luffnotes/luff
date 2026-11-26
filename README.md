# Luff

Luff is a paged note-taking app for Windows. You can pick a style for each note and switch it later, and any PDF you
export matches what is on screen. Everything stays on your computer and works offline, and the app also opens PDFs and
EPUB books.

This repository is for Luff releases and issues. Luff is closed source and free to download and use under its
[licence](https://luffnotes.com/licence).

## Download

Download Luff from [luffnotes.com](https://luffnotes.com/download) or the [Releases](../../releases/latest) page
(64-bit Windows 10 and 11).

Installed copies update automatically when Automatic updates is on in Settings > About, while the portable version only
tells you when a new release is out. Every update is signed and checked before installing. When Automatic updates is
off, Luff makes no background update requests.

To verify a download manually, compare its SHA-256 hash against `SHA256SUMS.txt` in the release:

```
certutil -hashfile Luff-<version>-setup.exe SHA256
```

## Bugs and ideas

[Open an issue](../../issues/new/choose) and choose Bug or Idea. Check the open issues first in case it has already been
reported, and add a thumbs up if you see it there.

Issues are public. Do not attach notes or `.luff` files, and check screenshots for personal details before uploading
them.

For security issues, email us directly (see [SECURITY.md](SECURITY.md)) and do not open a public issue.
