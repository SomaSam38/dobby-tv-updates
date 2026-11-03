# Dobby TV + optional Casa Home — family downloads

[Download the latest combined Mac installer](https://github.com/SomaSam38/dobby-tv-updates/releases/latest/download/Dobby-TV-Installer-Mac.zip)

This permanent download link follows the latest published installer. It currently downloads **2.0.3**; keep sharing the same link for future versions.

Includes **Dobby TV 1.9.82** and optional **Casa Home 2.6.31**. Intel or Apple silicon, macOS 13+. Developer ID signed and notarised by Apple. No AI, Codex, Terminal, system Python or Tizen Studio needed.

Unzip, move Dobby TV Installer to Applications, open it and follow the setup guide. Allow Local Network access. Keep the Mac and TV on the same home network. Samsung Developer Mode and a Samsung sign-in are part of initial TV setup. Confirm the TV is already on and unused before setup. Open Dobby TV afterwards and enter your own playlist login. No channels or provider accounts are included.

**Skip Intro:** during an episode press OK, choose Intro timing, set its start/end and save for the series or that episode. During the saved range, choose Skip Intro. Timings are set by you; Dobby does not recognise introductions automatically.

**Casa Home is optional.** Choose Add Casa Home if wanted, then choose its separate TV Home screen preference. Keep current is the default: existing choices are retained and a new Casa installation starts with automatic Home takeover off. Existing apps are kept rather than overwritten. Casa setup/backups require the Mac on the same network; the iPhone relay does not install Casa.

**Already have Dobby?** An installation from another Mac needs a verified setup file from Sam and its original signing files before this Mac can update it. An unpaired Casa-only installation needs original-author recovery. Never uninstall/reset either app or replace signing certificates to retry. Keep the private support folder for original certificates and encrypted backups.

Setup remembers its choices and receipts and offers Resume Setup Checks after interruption. Uncertain install acknowledgements never authorise a blind reinstall. Current progress, settings, pairings, alarms and audio are backed up and checked across independent app restarts. Supported Casa backup versions are 2.6.25, 2.6.26, 2.6.29, 2.6.30 and 2.6.31; unsupported versions stop safely. Explicit Home preference changes require Casa 2.6.29, 2.6.30 or 2.6.31.

Enable automatic Dobby update checks to check/download while the Mac is awake. Installation waits for TV-free confirmation and fresh saved-data checks. The Mac is not needed for normal TV viewing. This is not a TV-browser or Samsung Store installer.

**Family beta validation:** 211 installer regression checks and final Intel/Apple silicon package checks pass. Dobby 1.9.82 passed 267 focused TV regression checks and a physical Samsung update with original signing files and fresh encrypted backups. Both a movie and an episode reopened from Recently Watched, Watchlist and Favourites, including new Casa Home clicks into the same paused Dobby title. All Dobby saved-history records matched after restoring the test's own changes and performing an independent cold restart. Casa settings, library, pairings, alarms and audio were preserved. Cancelled older-TV performance changes are excluded. Fresh installation on a separate empty TV and full-power Home startup remain unverified. Samsung certificate/TV support may require opening Casa Home manually after a full restart.

Private accounts, signing keys and encrypted backups stay on the owner’s TV/Mac and are not uploaded here. The installer includes local privacy-safe support export. Do not disable Mac security settings.

Dobby TV is based on [OpenIPTV](https://github.com/shayanline/OpenIPTV); Casa Home and signing tools are based on AeroTizen. MIT and third-party notices are included. TV update metadata is Ed25519 signed; future releases are tested and published by Sam.

Mac ZIP SHA-256: `452bab0755a875227681392596e6431be78bb995b32de1516b1cbf8080e166c3`

[Previous Dobby-only installer 1.4.1](https://github.com/SomaSam38/dobby-tv-updates/releases/download/installer-1.4.1/Dobby-TV-Installer-Mac-1.4.1.zip)

## Publishing future combined installers

Every new latest installer release must include `Dobby-TV-Installer-Mac.zip`, containing the exact signed, notarised and validated versioned ZIP, plus its matching SHA-256 file. Keep the versioned asset for reproducibility. Verify both files have the same SHA-256 and anonymously verify the permanent download link after publication. Only mark a release as latest when the combined installer assets are present; keep other releases from moving this download link. Update the included app versions and validation notes here for each release.


### Playback update — 3 November 2026

The permanent Mac download now bundles Dobby TV **1.9.82** and optional Casa Home **2.6.31**. Dobby resumes partly watched movies and episodes when opened from Recently Watched, Watchlist or Favourites, including a fresh Casa Home click into an already-open Dobby app. Both content types were exercised on a physical Samsung TV; paused same-title Casa handoffs passed. Test changes were removed and Dobby saved history matched exactly after an independent cold restart. Casa settings, library, pairings, audio and alarms were preserved. The cancelled older-TV performance changes are excluded.

Casa Home uses neutral shared bedtime reminders; household-specific messages are local to the matched household and are absent from the download. The Mac installer is Developer ID signed, notarised and stapled, with final extracted-archive checks for Intel and Apple silicon. Developer Mode remains required. A separate clean-TV first install and full-power Casa startup are still not established by this update.
