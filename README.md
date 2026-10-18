# MPMDAS app releases

Android builds of the **Malawi Property Market Data & Analytics System** mobile app.

This repository holds **releases only**, with no source code. Each release is created automatically
by the build pipeline and contains:

- `mpmdas-<version>.apk`, the app;
- `mpmdas-<version>.apk.sha256`, its checksum.

## Installing

1. On your Android phone, open the [latest release](../../releases/latest) and download the `.apk`.
2. When asked, allow your browser to "install unknown apps".
3. Open the downloaded file and install it.

Your organisation's administrator will give you the sign-in details. Updates are offered inside
the app when a new version is published, so you normally only install it once.

**Pre-releases** are test builds for testers. Use the newest release that is *not* marked
pre-release unless you were asked to test.

## Checking the download (optional)

```bash
sha256sum -c mpmdas-<version>.apk.sha256
```

The result should say `OK`.
