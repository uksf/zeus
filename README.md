<p align="center">
    <img src="https://github.com/uksf/zeus/blob/master/assets/uksfSource.png" width="256">
</p>
<p align="center">
    <a href="https://github.com/uksf/zeus/issues">
        <img src="https://img.shields.io/github/issues/uksf/zeus.svg?style=flat-square&label=Issues" alt="Issues">
    </a>
    <a href="https://github.com/uksf/zeus/blob/master/LICENSE">
        <img src="https://img.shields.io/badge/license-GPLv3-blue.svg?style=flat-square" alt="License">
    </a>
</p>
<p align="center">
    <sup>Requires the latest version of <a href="https://github.com/CBATeam/CBA_A3/releases">CBA A3</a>.<br>
    Requires the latest version of <a href="https://github.com/acemod/ACE3/releases">ACE 3</a>.</sup>
</p>

# UKSF Zeus

## Curators 
- Adds curators to every mission automatically.
- A loading screen based on the number of curators is displayed to avoid lagspikes from curator inits.
- Players can log in and out of curators via the ACE self-interaction menu.
- Server admin can kick a single user or all users from curators, and can lock access.
- Whitelisted UIDs allows access to kick/lock for more than admin.

## CBA Settings
This mod makes use of CBA settings. These can be configured in `Addon Options > UKSF`
- Maximum Curators:
  - Sets the number of curators that will be available
  - Min 0, max 20, default 5
- Curators Start Locked:
  - Sets whether curator access starts locked to non-admin/whitelist
  - True/False, default False
- UID Whitelist:
  - Sets the UIDs able to access kick/lock features
  - Must be a comma-separate list of UID numbers. No spaces, no quotation marks, no weird characters
  - For example: `76561198041153310,76561198134463722,76561198010664527`

## Bugs, Issues
Use our [Issue Tracker](https://github.com/uksf/zeus/issues) to report a bug, propose a feature, or suggest changes to the existing ones.
