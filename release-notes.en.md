# SkyWay Android SDK release notes

[日本語](./release-notes.md)

## [Version 1.0.6](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.6)

### Fixed

- Fixed bug that causes crush of the app when call getUserMedia() after calling Peer.destroy().
- Fixed bug that rarely causes crash of the app when failed to connect the server by the other factor of v1.0.5. 

## [Version 1.0.5](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.5)

### Fixed

- Fixed bug that rarely causes crash of the app when connection to server fails.

## [Version 1.0.4](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.4)

### Fixed

- Fixed bug that causes crash of the app when call destroy after calling disconnect.

## [Version 1.0.3](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.3)

### Fixed

- Fixed bug in reconnect method.
- Fixed bug in listAllPeers method when the API fails.
- Fixed bug in finalizing process of DataConnection.
- Fixed possible memory leak in DataConnection.
- Fixed bug that causes crash of the app when connecting DataConnection.
- Fixed bug that re-joining to the same room after leaving it may fail.

## [Version 1.0.2](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.2)

### Fixed

- Fixed bug that the application halts when the device doesn't have a front camera
- Fixed bug that the debugging log level is ignored
- Fixed bug in an IPv6 environment

## [Version 1.0.1](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.1)

### Fixed

- Fixed bug that metadata on Media/DataConnection class was not set.

## [Version 1.0.0](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.0)

- first release
