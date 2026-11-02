# Validation — 2026-11-02

- Package JSON parsing, referenced paths, marketplace/plugin name consistency: PASS.
- Registered App mapping matches the original installed Sites plugin: PASS.
- Secret-pattern scan of all8 distribution files: PASS. No user media, database, cookies, API keys or subscription tokens included.
- Public GitHub repository created and main pushed: https://github.com/cdj1990/swing-lab-plugins
- Actual local command `codex plugin marketplace add cdj1990/swing-lab-plugins --json`: PASS, marketplaceName=swing-lab-plugins, alreadyAdded=false.
- Actual local command `codex plugin add swing-lab-pilot@swing-lab-plugins --json`: PASS, version0.1.0, authPolicy=ON_INSTALL.
- Installation was performed on the current Windows Codex host. It was NOT an isolated fresh-machine test or a test under the second Plus account.
- Second personal Plus account App authentication, tool discovery and data isolation: NOT VERIFIED.
- Existing Sites App mapping is reused. A GitHub installation does not grant permission to this private App. If a second account is denied, the package has not solved the platform authorization restriction.
- No new Site, server deployment, paid API, auth bypass or token copying was introduced. Existing owner plugin connections were not removed.
