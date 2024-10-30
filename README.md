# Configuration Files

This repository contains several DSC (Desired State Configuration) files for different configurations. Below are the instructions on how to install these DSC files using `winget` and Dev Home.

## Installation Instructions

### Prerequisites
1. Ensure you have `winget` installed on your system. If not, you can install it from the [Microsoft Store](https://aka.ms/getwinget).
2. Ensure you have Dev Home installed on your system. If not, you can install it from the [Microsoft Store](https://aka.ms/getdevhome).

### Steps to Install DSC Files using winget

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

### Steps to Install DSC Files using Dev Home

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ddieppa/configuration-files.git
   cd configuration-files
   ```

2. Open Dev Home.

3. Click on the `Machine Configuration` tab.

4. Click on `Configuration file`.

5. Browse to the location of the cloned repository and select the desired DSC file (e.g., `apps.dsc.yaml`).

6. Dev Home will show you a list of the apps in the file in a summary view. Click on `Agree and Continue`.

7. Select either `Set up as non-admin` or `Set up as admin`.

8. Dev Home will show you a progress screen for all the tasks.

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

You can copy and paste this into the README file in your repository.
