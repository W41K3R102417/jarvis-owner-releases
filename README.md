# Jarvis Owner Releases

Production Android application packages (APKs) for the **Jarvis Owner app**
(administration console for a Jarvis owner).

- Package: `com.jarvis.mobile.owner`
- Current release: **v0.4.0** (versionCode 14)

## Current release (v0.4.0)

| Field | Value |
|---|---|
| File | `jarvis-owner.apk` |
| Package | `com.jarvis.mobile.owner` |
| versionCode / versionName | 14 / 0.4.0 |
| Size | 8,604,433 bytes |
| SHA-256 | `6CFA63603CA75C3C80E863F9AB1A04388C6DDADAF6F79AD8C6966935725AADC5` |
| Signing certificate SHA-256 | `40AB151ED71726AE94B3E9E54E82C7A06F8FFA830CF8D4E9F7E2725BF15841C9` |
| Min Android | 8.0 (API 26) |

## Verify before installing

Compare the downloaded file's SHA-256 with the value above, and
confirm the signer with:

```text
apksigner verify --print-certs jarvis-owner.apk
```

## Authorization note

Possessing or installing this APK does **not** grant Owner
authorization. All roles, permissions, and administrative operations
remain authoritative on the Jarvis Core server, which verifies the
paired device and user account independently of the app variant.

## Update model

Same verified-update design as the User app: authenticated release
feed, anonymous HTTPS download, cryptographic verification, and
installation only through Android's package installer with your
confirmation.

## Release history

- **v0.4.0** — production release (see CHANGELOG.md).
