# Chiaki Nanami Pet

Custom pet package inspired by Chiaki Nanami for Codex custom pets.

## Files

- `pet.json`
- `spritesheet.webp`

## Install

Download or clone this repository, then open PowerShell in the repository folder and run:

```powershell
$petDir = Join-Path $env:USERPROFILE ".codex\pets\chiaki-nanami"
New-Item -ItemType Directory -Force -Path $petDir | Out-Null
Copy-Item -Path ".\pet.json", ".\spritesheet.webp" -Destination $petDir -Force
```

Then restart Codex and choose `Chiaki Nanami` from custom pets.

Manual Windows target folder:

```text
%USERPROFILE%\.codex\pets\chiaki-nanami\
```
