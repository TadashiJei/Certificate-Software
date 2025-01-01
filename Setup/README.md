# Certificate Generator Installer

This is the installer project for the Certificate Generator application, a tool for creating and managing certificates from templates.

## System Requirements

- Operating System: Windows 7 SP1 or later
- Processor: 1 GHz or faster
- Memory: 2 GB RAM minimum
- Disk Space: 100 MB available
- .NET Framework 4.7.2 or later
- Screen Resolution: 1024x768 or higher

## Dependencies

The installer includes all necessary dependencies:
- BouncyCastle.Crypto.dll
- LumenWorks.Framework.IO.dll
- cs-pdf-to-image.dll
- itextsharp.dll

## Installation Instructions

1. Double-click CertificateGenerator.msi
2. Follow the installation wizard prompts
3. Choose installation directory (default is Program Files)
4. Wait for installation to complete
5. Launch from desktop shortcut or start menu

## Features

- Certificate template management
- PDF and image format support
- Batch certificate generation
- Custom text placement and formatting
- Export to various formats

## Post-Installation

After installation, you'll find:
- Desktop shortcut
- Start menu entry
- Program files in installation directory
- Configuration files in AppData

## Troubleshooting

If you encounter any issues:
1. Verify system requirements
2. Ensure .NET Framework is installed
3. Run as administrator if needed
4. Check Windows Event Viewer for error logs

## Version History

- 1.0.0: Initial release
  - Basic certificate generation
  - Template management
  - PDF support
  - CSV data import
