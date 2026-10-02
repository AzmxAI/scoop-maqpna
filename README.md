# MAQPNA Scoop bucket

[Scoop](https://scoop.sh) manifests for [MAQPNA](https://maqpna.com), the sovereign runtime for AI agents.

```powershell
scoop bucket add maqpna https://github.com/AzmxAI/scoop-maqpna
scoop install maqpna/maqpna
maqpna version
```

Installs `maqpna` and `maqpna-sovereign` from the signed release archives on
[AzmxAI/maqpna-releases](https://github.com/AzmxAI/maqpna-releases/releases). Binaries are Authenticode-signed
(Azure Trusted Signing) and every release asset has a cosign keyless signature; see
[maqpna.com/download](https://maqpna.com/download) for verification steps.

The manifest is generated from the release by `hack/releasegen` in the MAQPNA repository; `checkver` /
`autoupdate` track the latest GitHub release.
