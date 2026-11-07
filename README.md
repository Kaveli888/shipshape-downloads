# ShipShape Downloads

Public release files for [ShipShape](https://makeshiphappen.tech): it finds, explains and
safely cleans the mess AI coding agents leave on a Mac. Part of the MakeShipHappen family.

The source code is private, in `Kaveli888/shipshape`. This repository only holds releases, so
anyone can download them without a GitHub account.

## Latest release

The [Releases page](https://github.com/Kaveli888/shipshape-downloads/releases/latest) has the
current macOS (Apple silicon) `.dmg`. Each release has these files:

- `ShipShape-<version>.dmg`: the app, signed with Developer ID and notarized by Apple.
- `ShipShape.app.tar.gz` and `.sig`: the signed update that installed copies download.
- `latest.json`: what installed copies read once a day to learn about a new version.
- `ShipShape-<version>.cdx.json`: the SBOM, a list of every component in the release.
- `SHA256SUMS`: checksums of all of the above.

## Updates

ShipShape checks `latest.json` here once a day (you can switch that off in Settings). It sends
nothing about you or your Mac. A new version is only installed when you click Install, and only
if its signature matches the key built into the app.

## Licence

To be chosen before the first public release.
