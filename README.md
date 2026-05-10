# LK XD1000 Virtual Training Device - GitHub Build Version

This repository builds a Windows `.exe` in GitHub Actions, so no Python installation is required on the desktop where the final application will run.

## Build using GitHub

1. Create a new GitHub repository.
2. Upload all files and folders from this package, including `.github/workflows/build-windows-exe.yml`.
3. Commit the files to the `main` branch.
4. Open the repository `Actions` tab.
5. Select **Build Windows EXE**.
6. Click **Run workflow**.
7. After the workflow completes, open the successful run.
8. Download the artifact named **LK_XD1000_Virtual_Training_Device_Windows_EXE**.
9. Extract the artifact ZIP and run `LK_XD1000_Virtual_Training_Device.exe` on Windows.

## Application Scope

This is an MVP Windows desktop simulator for an LK-branded XD1000 virtual training device. It simulates:

- Run / Stop / Fault Reset
- Speed reference input
- ACC / DEC ramp effect
- Output frequency
- Motor current
- Mains voltage
- Status word
- Parameter modification
- Modified-from-factory list
- Recipe save/load

## Important

This is a training simulator. It does not control a real VFD unless Modbus communication functionality is added in a later version.
