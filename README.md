# Aclass VPN Updates

Canal publico de actualizacion para Aclass VPN Client.

Este repositorio no contiene codigo fuente del producto. Solo mantiene:

- `latest.json`: manifiesto de la ultima version disponible.
- GitHub Releases: instaladores `AclassVPNClientSetup.exe`.

La app consulta:

```text
https://raw.githubusercontent.com/aclass-webs/AclassVPNUpdates/main/latest.json
```

Cada instalador publicado debe validarse con SHA256 desde el manifest.

Versión actual: `0.4.16`.

Release: https://github.com/aclass-webs/AclassVPNUpdates/releases/tag/v0.4.16
