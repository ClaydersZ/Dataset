# Gaussian-AD Dataset

Dataset for Gaussian-AD, distributed as a ZIP archive through GitHub Releases.

## Download

[Download Dataset.zip](https://github.com/ClaydersZ/Gaussian-AD/releases/download/dataset-v1.0/Dataset.zip)

[Download SHA-256 checksum](https://github.com/ClaydersZ/Gaussian-AD/releases/download/dataset-v1.0/Dataset.zip.sha256)

[View the release](https://github.com/ClaydersZ/Gaussian-AD/releases/tag/dataset-v1.0)

## Directory structure

```text
Dataset/
  Training/  # 602 PNG images
  Testing/   # 2,993 PNG images
```

The archive contains 3,595 images and preserves the original filenames and directory structure.
Extract the ZIP into your project directory to create the `Dataset` folder.

## Verify the download

On Windows PowerShell:

```powershell
Get-FileHash .\Dataset.zip -Algorithm SHA256
```

Expected SHA-256:

```text
5157a2c6e6fd0fa44427c0ccb711ecabe674d0ecdca286afcf7d72ea2441d811
```
