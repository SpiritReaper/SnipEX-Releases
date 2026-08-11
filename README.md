# SnipEX Releases

This public repository is the official SnipEX update-feed and release-notes channel. The proprietary application source is stored separately in a private repository and is never published here.

## Current channel status

SnipEX Version 1.0 Stable is the current employee-testing build. Download the guided `SnipEx-1.0.0-win-x64-Setup.exe` from the Releases page for normal installation. IT administrators may use the accompanying `.msi` for managed deployment. Both checksum files are published beside their installers.

Version 1.0 uses a temporary GitHub collaborator gate: users sign in through GitHub and must be active collaborators on the private source repository. Microsoft company sign-in is not included. The packages remain unsigned while Club OS Tech review is pending.

Current clients read the published GitHub Release directly and fall back to `manifest.json` for compatibility. When a newer stable version is available, SnipEX displays its version and compact patch notes, then opens the official release page. Because the current installers replace an earlier build under the same v1.0.0 tag, existing Version 1.0 users must manually reinstall this replacement once.

## Security

Only download SnipEX from a release linked by this repository. Verify the matching SHA-256 checksum before installation. Published packages will be code-signed once the organization-approved certificate is available.