# Security

If you find a security issue in Luff, email **hello@luffnotes.com** with "Security" in the subject, and do not open a
public issue. This includes running code from a note or style pack, or bypassing update signature checks.

Include your Luff version (from Settings > About) and the steps or a sample file to reproduce the issue. We aim to reply
within a week and release a fix once it is ready. Let us know if you would like credit in the release notes.

Security fixes go to the latest version only. Installed copies update automatically unless you turn off Automatic
updates in Settings > About.

## Updates

Each release has a `latest.json` manifest signed with Ed25519 in `latest.json.sig`. Luff checks the signature and
verifies each downloaded file against its SHA-256 hash before installing, and it will not downgrade to an older version.
