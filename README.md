# Ghostboard releases

Native Apple Silicon Mac workspace: Ghostty terminals, files and Vim, system monitoring, browser tiles, and team chat.

[Download the latest release](https://github.com/kaushal07wick/ghostboard-releases/releases/latest)

This repository contains app downloads and signed update metadata. The source code is maintained separately in a private repository.

## Install and update

Requires an Apple Silicon Mac and macOS 14 or later. Download the DMG, drag Ghostboard into Applications, then open it. Save terminal work before quitting an older copy.

Builds are ad-hoc signed and not Apple-notarized. For a trusted download blocked by macOS, use System Settings → Privacy & Security → Open Anyway.

Ghostboard 0.6+ checks for signed updates hourly and asks before installing. **Ghostboard → Check for Updates…** checks immediately. Older versions require a one-time manual installation of 0.6 or later.

## Team chat

Use Chat's compose menu to invite a colleague or join with a private invitation. Both Macs need the current app. Nearby Macs use LAN discovery; different networks need reachable saved IPs, such as WireGuard addresses. TCP port 45991 must be reachable.

Groups are relayed by their creator's Mac, which must remain online. Files have no app-imposed size cap; available disk space, filesystem limits, and network speed apply. Folders are sent as ZIP archives. Downloads resume after interruption.

Allow Ghostboard in System Settings → Notifications for received-message alerts. There is no cloud push service while the app is closed. Voice and video calls are not included.

Pairing invitations contain private keys. Never post invitations, chat history, or credentials in this repository. Local messages and attachment snapshots are plaintext; transport is encrypted. The messenger has not had an independent security audit.
