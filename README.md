# Hishab PRO releases

Android release files (APKs) for Hishab PRO, the shop app. The app's own
updater downloads them from here and checks each file against a published
SHA-256 before installing it.

There is no source code in this repository. Do not install an APK from
anywhere else: the app only ever updates itself from the release it is told
about, and Android refuses a file that is not signed with the app's own key.
