# AppListBackup

## About this fork

This repository is a modified fork of [AndroidLabs-org/AppListBackup](https://github.com/AndroidLabs-org/AppListBackup).

Changes in this fork include:

- Configurable backup filename prefix per Android user profile, including GrapheneOS secondary profiles and Private Space.
- Versioned backups can use names such as `Owner-2026-09-26-15-55-00.html`.
- When only one backup is retained, the filename can use the configured prefix directly, for example `Owner.html`.
- Existing legacy `app-list-backup-...` backup filenames remain supported.
- Filename prefixes are stored separately for each Android profile, allowing different profiles to use different backup names.

This fork is independently built and signed and is not an official AndroidLabs release.

## License

This fork is distributed under the GNU General Public License v3.0 only (GPL-3.0-only).

The upstream GitHub repository does not currently include a `LICENSE` file. However, the F-Droid metadata for `org.androidlabs.applistbackup` declares the project as `GPL-3.0-only`, and the original F-Droid submission was made by AndroidLabs Org.

A copy of the GNU GPL v3.0 license is included in this repository in the [`LICENSE`](LICENSE) file.

For the upstream project, see:

- [AndroidLabs-org/AppListBackup](https://github.com/AndroidLabs-org/AppListBackup)
- [F-Droid package metadata for AppListBackup](https://gitlab.com/fdroid/fdroiddata/-/blob/master/metadata/org.androidlabs.applistbackup.yml)

AppListBackup is the ultimate solution for generating a backup list of installed applications on your Android device.

This user-friendly app allows you to automatically create and view a backup list of all your installed apps with just a few taps.

Whether you want to safeguard your list of favorite apps or prepare for a device reset, AppListBackup ensures your apps list is securely backed up and ready to be viewed whenever you need it.

## Key Features:

* Quickly create backup lists of installed apps with ease, including details such as: installation date, version number, package name, app icon and more.
* View your backup lists from any device with an easy to use HTML file including the ability to sort and filter.
* Seamlessly integrate with Tasker, Automate, MacroDroid, and any other apps that support Tasker Plugin, allowing you to automate your backup schedule.
* Trigger backups via Intent Broadcasts, enabling automation with tools like Tasker, ADB, and MacroDroid for even more flexibility.
* Does not need root and zero permissions are required.
* Also includes an easy to click widget, notification bar progress updates, and more.

With AppListBackup, you can have peace of mind knowing an up to date list of your favorite apps is safely backed up. Download and install now to ensure your list of apps is always ready for restoration.

**IMPORTANT:** This app does not back up your actual application APKs or data, it only generates a list of installed applications and allows you to choose where to save it for future reference. Additionally it is the user's responsibility to save/backup the generated HTML file to a safe location in the event their phone is broken or lost, such as, but not limited to, email, remote storage, or a local folder which is synced elsewhere.
