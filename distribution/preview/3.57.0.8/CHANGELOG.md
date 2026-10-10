# 3.57.0.8-preview

Fix public preview update-source compatibility. The original preview endpoint retains its byte-exact 3.57.0.5 v1 manifest, so installed public .5 clients can query successfully and remain up to date for that legacy channel. No new legacy script package is published or delivered.

Existing public 3.57.0.5, 3.57.0.6 and 3.57.0.7 clients require a one-time manual installation of the native .8 installer in their original directory. Native .8 uses updates/native/preview.json with nudou.github-update.channel.v2 and nudou-native-exe-v1. For the exact recognized official legacy route, its daily cache permits one bounded native retry on the same local day. Custom sources retain their original behavior.

Retain existing identity, configuration and data, and keep rollback backups. Follow Windows security prompts; this installer is unsigned. The Extract-And-Run ZIP is a separate pure extraction option. No older-version automatic migration is claimed. Feature behavior is carried forward from .7.
