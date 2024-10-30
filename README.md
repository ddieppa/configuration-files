# Configuration Files

This repository contains several DSC (Desired State Configuration) files for different configurations. Below are the instructions on how to install these DSC files using `winget`.

## Installation Instructions

### Prerequisites
1. Ensure you have `winget` installed on your system. If not, you can install it from the [Microsoft Store](https://aka.ms/getwinget).

### Steps to Install DSC Files

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ddieppa/configuration-files.git
   cd configuration-files
   ```

2. Open PowerShell with administrative privileges.

3. Apply the desired DSC configuration using the following command, replacing `<FileName>` with the name of the DSC file you want to apply:
   ```powershell
   winget import -i .\<FileName>
   ```

### Example
To apply the `apps.dsc.yaml` configuration, use:
```powershell
winget import -i .\apps.dsc.yaml
```

## Available DSC Files
- `qnap.dsc.yaml`
- `sandbox.dsc.yaml`
- `devtools.dsc.yaml`
- `winget.settings.dsc.yaml`
- `windows.settings.dsc.yaml`
- `apps.dsc.yaml`

Each file contains specific configurations tailored to different environments or applications.

## Contributing
Feel free to open issues or submit pull requests if you have suggestions for improvements or find any issues.

## License
This project is licensed under the MIT License.

Would you like to add or modify any section before I commit this README file to the repository?
