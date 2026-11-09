# winCapture releases

Downloads for **winCapture**, a Windows screenshot app (still screenshots first, screen recording later).

- Get the latest build from the [Releases](https://github.com/davideAurum/winCapture-releases/releases) page: a setup (`-setup.exe`) or a portable zip. Both need the .NET 10 Desktop Runtime (x64).
- Alpha builds are unfinished, unsigned (Windows SmartScreen may warn) and may lose data. Keep backups of anything important.
- Each release lists the SHA-256 of its files. Check a download with `Get-FileHash <file> -Algorithm SHA256`.
- `latest.json` is the small file winCapture reads when you click **Check for updates**. It names the newest release and the size and SHA-256 its download must match.
- The licence is in [LICENSE.txt](LICENSE.txt).

The source code is not published here.
