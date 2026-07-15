# NativePDF Privacy Notice

Effective for NativePDF 1.0.0

Publisher: {{LEGAL_PUBLISHER}}

## Local processing

NativePDF is designed to process PDFs, images, passwords, visual signatures, revisions, and exports on the user's Windows device. It does not include telemetry, analytics, advertising, account sign-in, cloud upload, crash upload, or an automatic update feed.

Normal document use does not require a network connection. The NSIS installer can contact Microsoft only to obtain the WebView2 Evergreen Runtime when it is missing or outdated. Downloading NativePDF, requesting support, or visiting {{OFFICIAL_URL}} occurs outside the application and is governed by the website or email provider involved.

## Local data

- Recent-file entries store local paths and timestamps in NativePDF WebView storage.
- Reusable visual signatures are stored locally only after explicit consent.
- Working PDF revisions and password response files use `%TEMP%\NativePDF`. Revisions are bounded and cleaned on tab close or orphan cleanup; password files are overwritten and removed immediately after use.
- Application WebView data is stored under the Windows local application-data area associated with `app.NativePDF.desktop`.
- Source and exported documents remain in locations chosen by the user.

The operating system, storage device, backup software, endpoint security software, and file-system journaling may retain copies beyond NativePDF's control. Securely manage the device, backups, pagefile, crash dumps, and deleted-file recovery according to your sensitivity requirements.

## User choices

Remove Recent entries inside NativePDF, delete saved visual signatures in the signature workspace, close document tabs to remove active revisions, and uninstall NativePDF through Windows Settings. Uninstalling the application may leave user-created PDFs and local WebView data; see `USER_GUIDE.md` for optional manual cleanup.

Privacy questions: {{SUPPORT_EMAIL}}
