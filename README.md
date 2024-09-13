# Windows Bloatware Removal and Telemetry Disabling Script

This batch script automates the removal of unwanted pre-installed applications (bloatware) and disables Windows telemetry to enhance privacy and reduce resource usage. It uses a combination of PowerShell commands and registry edits to achieve these tasks.

## Features

- **Removes bloatware**: Automatically uninstalls common pre-installed Windows apps like 3D Builder, Xbox, and Solitaire.
- **Disables telemetry**: Stops Windows from sending diagnostic and usage data to Microsoft.
- **Disables customer experience tasks**: Disables scheduled tasks related to the Customer Experience Improvement Program (CEIP).
- **Disables remote assistance**: Prevents remote assistance requests.

## Usage

1. **Download the script**: Save the batch script as `RemoveBloatwareAndTelemetry.bat`.
2. **Run as administrator**: Right-click the `.bat` file and select "Run as administrator."
3. **Follow prompts**: The script will execute the removal and telemetry disabling commands. A system reboot is recommended after running the script.

## Customization

- **Bloatware Removal**: Modify the list of apps in the script to include or exclude specific applications. The default script removes:
  - 3D Builder
  - Xbox
  - Solitaire
  - Bing News
  - Zune Music
  - People
  - OneNote
  
- **Telemetry**: The script disables telemetry by modifying Windows registry keys and disabling relevant scheduled tasks. Adjustments can be made if a different telemetry level is preferred.

## Disclaimer

Use this script at your own risk. Removing certain apps or modifying telemetry settings may affect system functionality. It is recommended to back up important data before running the script.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
