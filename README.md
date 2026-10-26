<img src="bboxy.png" width="120" align="right" alt="bboxy450">

# bboxy450-term releases

Signed builds of **bboxy450-term**, the GPU terminal for running agent swarms.

## Install

```sh
brew install --cask bboxy450/tap/bboxy450-term
```

Or download `bboxy450-term-<version>-macos-arm64.zip` from [Releases](https://github.com/bboxy450/bboxy450-term-releases/releases).

## Verify

Every release ships a SHA-256 and a detached GPG signature from key `9B07E849480C68328CA20684844ECC0587DE7AB0` (Boxy, bboxy450).

```sh
gpg --verify bboxy450-term-<version>-macos-arm64.zip.asc bboxy450-term-<version>-macos-arm64.zip
shasum -a 256 -c bboxy450-term-<version>-macos-arm64.zip.sha256
```

The crates are on [crates.io](https://crates.io/users/bboxy450) under the same version.

## Platforms

macOS on Apple silicon first. Linux follows.
