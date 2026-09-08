# Kingdoms & Caravans 0.3.2 — Compatibility installer

Version 0.2.1 can now upgrade through its existing menu. The previous 0.3.0 download exceeded that client's limits; this release supplies a small first-stage installer that downloads and verifies the full game.

## Upgrade an existing game

1. In the old game, open the menu and select **Check for updates**.
2. Choose **Download update**, then **Restart with update**. The old game saves your kingdom before switching.
3. The compatibility installer downloads the full game and starts it with your kingdom.

The initial download is 38.1 MB; the full game download is 164.9 MB. Existing installs, version-2 saves and backups are preserved. Cancelling or failing the second download removes only the activation of the incomplete installer so the previous shortcut stays usable. After a successful installation, the same shortcut opens the verified game offline.

## Fresh or offline installation

Extract `KingdomsAndCaravans-windows.zip`, run the executable and choose **Install and play**. For a full offline package, download `KingdomsAndCaravans-full-windows.zip` on a connected PC and extract it on the playing PC. The release checksum file covers both ZIPs.

## Checks

The original published 0.2.1 updater code accepted, verified and installed the small candidate package. Fifteen installer checks passed, covering URL/save-format validation, missing and corrupted cached games, cancellation cleanup and preservation of saves and other version activations. The full build checks passed, including the paid economy playthrough. The full Windows executable loaded the old save and ran natively.

Gameplay is the 0.3.0 construction-and-defense playtest. This remains an early, unsigned Windows x64 preview; broader hardware testing is still needed. Version 0.1 saves require their old build.

The final installer also restores shortcut forwarding after a successful retry and recognizes verified recovery folders after a damaged installation. It does not overwrite the damaged copy or another version activation.
