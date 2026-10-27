# PCAPNG Analyzer for Windows, macOS and Linux

Desktop downloads of [PCAPNG Analyzer](https://pcapnganalyzer.com): drop
in a pcap or pcapng capture and get a plain-English diagnosis (slow DNS,
failing connections, suspicious hosts) with the evidence. It runs on your
own computer and opens in your browser. Your captures stay on your
machine.

**[Download the latest release](https://github.com/stumat1/pcapng-analyzer-desktop/releases/latest)**

| System | File |
|---|---|
| Windows 10/11 (x64) | `pcapng-analyzer-<version>-windows-x64.zip` |
| macOS 11+ (Apple silicon and Intel) | `pcapng-analyzer-<version>-macos-universal.zip` |
| Linux x64 (glibc 2.28+) | `pcapng-analyzer-<version>-linux-x64.tar.gz` |
| Linux arm64 (glibc 2.28+) | `pcapng-analyzer-<version>-linux-arm64.tar.gz` |

Unpack it and run `pcapng-analyzer`. Your browser opens, already signed
in. The `README.txt` inside covers the first-run security prompts, where
your data lives, and updating.

Or install it with a package manager, which also skips the first-run
security prompts and makes updating one command:

```sh
# Windows, with Scoop
scoop bucket add pcapng-analyzer https://github.com/stumat1/scoop-pcapng-analyzer
scoop install pcapng-analyzer/pcapng-analyzer

# macOS or Linux, with Homebrew
brew install stumat1/pcapng-analyzer/pcapng-analyzer
```

Free to use; a [Pro licence](https://pcapnganalyzer.com/pricing.html)
unlocks the rest in the same download. For a server that several people
use, there's also a [Docker image](https://hub.docker.com/r/smathieson/pcapng-analyzer).

This repository holds releases only. PCAPNG Analyzer is commercial,
source-available software: see the
[licence agreement](https://pcapnganalyzer.com/license.html).

Support: support@stumatapps.com
