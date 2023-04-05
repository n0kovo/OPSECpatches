# OPSECpatches
A collection of common InfoSec tools patched to be more stealth.

- **Nmap** - Modified User-Agents and removed `nmap` string from probes.
  - Repo: [n0kovo/nmap_opsecpatch](https://github.com/n0kovo/nmap_opsecpatch)
  - Patch: [nmap_opsec.patch](nmap_opsec.patch)
  - Credit: [@soaj1664ashar](https://twitter.com/soaj1664ashar/status/1070026414961946626)

- **Gophish** - Modified `ServerName`, added custom 404, removed `Gophish` string from headers.
  - Repo: [n0kovo/gophish_opsecpatch](https://github.com/n0kovo/gophish_opsecpatch)
  - Patch: [gophish_opsec.patch](gophish_opsec.patch)
  - Credit: [sneaky_gophish](https://github.com/puzzlepeaches/sneaky_gophish)
