# Public Repository
This repo is to store public files regarding for Tahiry's projects.

# Hash for PoTS
To generate SHA256 file hash, run
```
$ (Get-FileHash .\file.ext -Algorithm SHA256).hash > .\file.sha256
```

To compare the SHA256 hash of a file with an existing one, run
```
$ (Get-FileHash .\file.ext -Algorithm SHA256).hash -eq (cat .\file.sha256)
```