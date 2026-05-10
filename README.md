# loupe-releases

Public hosting for [Loupe](https://dev.bharathsrivatsan.com/loupe/privacy)
macOS app DMGs.

This repo exists only to serve binaries — the source code lives in a
separate private repo. GitHub serves private-repo release assets only
to authenticated requests, which breaks both shareable download URLs
and Sparkle auto-update; this public repo's release assets are
reachable anonymously.

Auto-updates point at the [appcast on
dev.bharathsrivatsan.com](https://dev.bharathsrivatsan.com/loupe/appcast.xml),
whose `<enclosure url>` references the latest release here.

## Latest

See the [Releases](https://github.com/bsrivatsan/loupe-releases/releases)
tab. Each release ships a notarized, Sparkle-EdDSA-signed
`Loupe-X.Y.Z.dmg`.
