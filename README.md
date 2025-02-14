# Conventional Commits Version Calculator

## Requirements
- PowerShell 3 or later

## Usage

1. Download the `.ps1` script
2. Add it to the same folder as the `.git` directory
3. Run the script using the command `.\next_release_version.ps1`

## Parameters
- `-dev` - If you're in the initial development phase (before 1.0.0), you can run the script with this parameter to only increment the Minor and Patch versions, even if they are breaking changes

## Notes
- The script is based on the last tag created in your repository, so if there are no tags, it will use all previous commits as a base
