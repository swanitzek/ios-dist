# Stefans iOS Dist

Öffentliche SideStore-Source für private Sideload-Apps.

**Source-URL:** `https://swanitzek.github.io/ios-dist/apps.json`

In SideStore hinzufügen: **Browse → Sources → URL eintragen**.

- `apps.json` — Source-Metadaten (von der Build-Pipeline automatisch aktualisiert)
- `ipas/` — unsignierte IPA-Builds (Signierung passiert lokal in SideStore)

Builds kommen aus dem privaten Repo `swanitzek/ios-hello-sideload` (GitHub Actions, macOS-Runner). Jeder neue `v*`-Tag dort veröffentlicht ein frisches IPA + aktualisiert diese Source.
