# Certificate Generator Software

A Windows desktop application for generating certificates in bulk using customizable templates. This application streamlines the process of creating multiple certificates by importing data from CSV files and applying them to PDF templates.

## 🌟 Features

- **Bulk Certificate Generation**: Generate multiple certificates at once using CSV data
- **PDF Template Support**: Use custom PDF templates for certificate generation
- **CSV Data Import**: Import participant data from CSV files
- **Progress Tracking**: Real-time progress monitoring during certificate generation
- **Custom Text Positioning**: Flexible text placement on certificates
- **Output Format Control**: Generate certificates in both PDF and PNG formats

## 📋 Prerequisites

- Windows Operating System
- .NET Framework 4.5 or higher
- Microsoft Visual Studio (for development)

## 🚀 Installation

1. **Download the Latest Release**
   - Download the latest release from the [Releases](https://github.com/TadashiJei/Certificate-Software/releases) page
   - Or clone the repository:
     ```
     git clone https://github.com/TadashiJei/Certificate-Software.git
     ```

2. **Build from Source**
   - Open `certificate-generator.sln` in Visual Studio
   - Restore NuGet packages
   - Build the solution

## 📝 Usage Guide

### Setting Up Your Certificate Template

1. **Prepare Your PDF Template**
   - Create a PDF template for your certificates
   - Note the coordinates where you want to place text
   - Save the template in an accessible location

2. **Prepare Your CSV Data**
   - Create a CSV file with participant information
   - Required columns: Name, Date, or any other fields you want to include
   - Save the CSV file in an accessible location

### Using the Application

1. **Launch the Application**
   - Run the Certificate Generator executable

2. **Load Template and Data**
   - Click "Browse" to select your PDF template
   - Click "Import CSV" to load your participant data
   - Preview the template and data mapping

3. **Configure Text Placement**
   - Set X and Y coordinates for each text field
   - Adjust font size and style as needed
   - Use the preview feature to verify placement

4. **Generate Certificates**
   - Click "Generate Certificates" to start the process
   - Choose output location for generated certificates
   - Monitor progress in the progress window

## 🛠️ Technical Details

### Dependencies

- iTextSharp (v5.5.13.2) - PDF processing
- BouncyCastle (v1.8.6.1) - Security and cryptography
- LumenWorks.Framework.IO (v4.0.0) - CSV file handling
- Pdf2Png (v1.0.2) - PDF to PNG conversion

### Project Structure

- `Form1.cs` - Main application window and logic
- `Progress.cs` - Progress tracking window
- `Tools.cs` - Utility functions and helpers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the terms of the license included in the repository. See [License.txt](License.txt) for more details.

## 🐛 Known Issues

- PNG conversion may take longer for complex templates
- Memory usage increases with large batch processing

## 📞 Support

If you encounter any issues or have questions, please:
1. Check the [Issues](https://github.com/TadashiJei/Certificate-Software/issues) page
2. Create a new issue if your problem isn't already listed

## ✨ Acknowledgments

- Thanks to all contributors who have helped with the development
- Special thanks to the open-source community for the libraries used in this project
