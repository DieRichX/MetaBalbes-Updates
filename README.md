# MetaBalbes Updates

This public repository distributes MetaBalbes installers and update packages only. It does not contain the application's source code.

## Download

Download the latest [MetaBalbes installer from Releases](https://github.com/DieRichX/MetaBalbes-Updates/releases/latest). Run it to install MetaBalbes or update an existing installation.

Profiles and macros are stored in the user's application-data folder, outside the installation directory. Updates replace application files and keep profile data.

## In-app update assets

Every stable release must include:

- `MetaBalbes-Setup.exe`
- `MetaBalbes-Setup.exe.sha256`

MetaBalbes checks the latest stable GitHub Release, verifies the SHA-256 checksum, and starts the installer in update mode. The updater keeps the previous application files until the new version confirms that its startup window opened. If startup fails, it restores the previous files.
