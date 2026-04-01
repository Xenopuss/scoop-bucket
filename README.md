# scoop-bucket

A custom [Scoop](https://scoop.sh/) bucket for various tools and applications.

## How to use this bucket

To add this bucket to your Scoop installation, run the following command in PowerShell:

```powershell
scoop bucket add scoop-bucket https://github.com/<your-username>/scoop-bucket
```

*Note: Replace `<your-username>` with your actual GitHub username.*

## Installing packages

Once the bucket is added, you can install packages using:

```powershell
scoop install scoop-bucket/<package-name>
```

Example:
```powershell
scoop install scoop-bucket/msvc
```
