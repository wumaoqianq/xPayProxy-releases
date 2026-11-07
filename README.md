# xPayProxy releases

This public repository contains signed update packages and runtime documentation. Development history is maintained separately.

Download the EXE installer, Windows ZIP, or Debian 12 archive from the matching Release. Online updates require an administrator to check, confirm the exact target version, and enter the current administrator password. Updates are not installed unattended.

The application validates the Ed25519-signed `update-manifest.json` and package hashes. The Release includes the manifest, its detached signature, and `sha256.json`. Do not replace the application's trusted public key using files from an untrusted source.

Version 0.7.0 needs a controlled manual upgrade to 0.8.0 before online updates are available. Back up the complete data directory and `.env` together before a manual upgrade. Runtime installation and recovery instructions are included in each package.

Never upload your database, `.env`, secret key, administrator credentials, or signing private key to this repository.
