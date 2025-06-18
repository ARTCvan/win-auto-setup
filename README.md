# win-auto-setup
Automated script to setup Windows devices as per certain requirements. 

Currently a work in progress, goals are to be:
1. Get automated app install working (use script for winget)
2. Get basic system settings included into script (eg network, power)
3. Get app settings included into script
4. Get advanced system settings included into script (eg performance)
5. Create different requirements of script (eg Basic install, full install)

## Usage
To use win-auto-setup:
- Launch PowerShell as administrator
- Install git via  `winget install --id Git.Git -e --source winget `
- Then clone the repo with `git clone https://github.com/ARTCvan/win-auto-setup`
- Change directory to the repo with `cd win-auto-setup`
- Run `winget import -i apps.json` to install apps via winget.

Quick reminder (again) that this is a work in progress.
