<div align="center">
  <img src="images/impleo_logo.png" alt="ImpleoTV">
</div>

# KlvInspector 2.0.0

KlvInspector analyzes STANAG 4609 recordings and raw KLV metadata. [Product information](https://impleotv.com/products/applications/klvinspector)

## Download

[Download the signed Windows x64 offline installer ZIP](https://github.com/impleotv/klvinspector-release/releases/download/v2.0.0/KlvInspectorSetup-2.0.0-x64.zip) · [SHA-256 checksum](https://github.com/impleotv/klvinspector-release/releases/download/v2.0.0/KlvInspectorSetup-2.0.0-x64.zip.sha256)

## System requirements

Use an x64 Intel or AMD PC running Windows 10 version 1809 or later, or Windows 11. Setup requires administrator privileges.

## Offline installation

1. Download the ZIP and its checksum on a connected computer and copy them to the target PC. To verify the ZIP, compare the SHA-256 shown by the command below with the value in the checksum file.
2. Extract the ZIP and run `KlvInspectorSetup-2.0.0-x64.exe`.
3. If setup requests a restart, restart Windows and run the same setup again.
4. Open **ImpleoTV → KlvInspector** from the Start menu. Open the bundled manual from **Help → User Guide** or the **KlvInspector User Guide** Start menu shortcut.

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\KlvInspectorSetup-2.0.0-x64.zip
```

Setup installs the bundled .NET Framework 4.8, Visual C++ x64 runtime, and Microsoft Edge WebView2 Runtime as needed. The application and manual can be installed and opened offline. Online map layers require network access.

## Licensing

Open **Options → License** and select **Copy** next to **Node Info**. Include the full identifier when requesting a license. [License request form](https://docs.google.com/forms/d/e/1FAIpQLSd_XW6bDsFce1G1cpds4gMQNlwNax0CvkWzcMbscxZ5rLaIbA/viewform)

Select **Browse…** to import a signed JWT license. To reuse a legacy XML license on the machine it was issued for, browse to the original license file, enter the matching activation key, and select **Apply**.
