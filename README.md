# PermissionsManager Android Library

This Android application demonstrates the use of a custom permission management library to handle various Android permissions. It includes features like dynamically requesting permissions, updating permission statuses, and responding to user interactions with permissions.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Permissions](#permissions)

## Features
- **Dynamic Permission Handling**: The app checks and requests Android permissions at runtime.
- **Permission Status Updates**: The app updates the status of permissions dynamically and displays it to the user.
- **Custom Permission Management Library**: The project includes a custom library for managing Android permissions.
- **RecyclerView Interface**: Permissions and their statuses are displayed in a `RecyclerView` with an easy-to-navigate interface.

## Technologies
- **Android SDK**
- **Java**
- **RecyclerView**
- **Custom Permissions Library**
- **Gradle**

## Permissions
The application requests the following permissions:

- `INTERNET`
- `CALL_PHONE`
- `VIBRATE`
- `RECORD_AUDIO`
- `ACCESS_FINE_LOCATION`
- `ACCESS_COARSE_LOCATION`
- `READ_SMS`
- `READ_CONTACTS`
- `CAMERA`
- `READ_CALENDAR`
- `BODY_SENSORS`
- `BLUETOOTH_SCAN`

These permissions are managed using custom `PermissionHandler` and `PermissionHelper` classes. The app dynamically requests permissions and updates their statuses in the UI.



https://github.com/user-attachments/assets/211d811e-7121-43d5-ac81-845fd65ae3e1


