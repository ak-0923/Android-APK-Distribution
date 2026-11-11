# Android APK Distribution

This public repository is dedicated to distributing **APK binaries only** for four independently maintained Android apps.

| App | Private source repository | Release asset prefix |
| --- | --- | --- |
| LifeCalendar | LifeCalendar-App | LifeCalendar |
| Kuraberu | LifeCalendar-App (separate app/branch) | Kuraberu |
| CCNA Vocab Trainer | CCNAVocabTrainer | CCNA |
| Juggler Counter | JugglerCounter | Juggler |

## Release policy
- Source repositories stay private. Do not upload source code, signing keys, keystores, secrets, logs, or user data.
- Only upload APKs after successful build, file validation, package ID/version checks, and signing-certificate compatibility checks.
- Keep release assets immutable by using distinct tags such as `lifecalendar-vX.Y.Z`, `kuraberu-vX.Y.Z`, `ccna-vX.Y.Z`, and `juggler-vX.Y.Z`.
- Publish distinct asset names: `LifeCalendar-vX.Y.Z.apk`, `Kuraberu-vX.Y.Z.apk`, `CCNA-vX.Y.Z.apk`, and `Juggler-vX.Y.Z.apk`.
- Verify the asset exists in the public release and its URL resolves before sharing it.
- The repository is public: APKs are downloadable by anyone. Do not embed credentials or private configuration in APKs.

## Current status
The distribution repository is initialized. **No APK publication is implied by this document.** Each private source repository needs a separately reviewed build-and-publish workflow and a narrowly scoped credential for uploading release assets. Existing application IDs, signing identities, and user data compatibility must remain unchanged.
