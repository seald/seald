# 13/12/2018 v0.1.26
* Opening a Seald file in your browser mistakenly (for example clicking in Chrome download bar) will now be properly forwarded to the Seald app
* In the web decryption interface, adding the ability to reply to emails (when sent by a premium user)
* In the Outlook plugin, adding the ability to encrypt only the attachments or everything, and new interface
* Adding a tab in the preference window to show the last connexions to your account
* Sending security alerts by email when certain events happen on your account
* Opening a Seald file in the GMail previewer mistakenly now shows a correct error message
* In the web decryption interface, disabling PPTX preview because of security issues
* In the web decryption interface, errors are now more verbose and clearer
* In the Outlook plugin, the name of the attachment containing the encrypted email body is now clearer (based on email subject)
* Fix some interface issues on Linux
* Interface details & minor bugs

# 25/10/2018 v0.1.25
* When opening an encrypted file, it will now automatically open in the default app, and will be saved in encrypted format automatically when any modifications happen
* In web decryption interface, add support for previewing images
* In web decryption interface, allow drag&drop-ing a file to decrypt
* In web decryption interface, session is now persistent and you do not have to re-authenticate each time
* Use new, cleaner URLs for web decryption interface & premium dashboard
* Auto-update is now more stable, and proposes a manual update when it fails
* Outlook plugin is now faster to open emails
* Add hidden config option to completely disable registry on windows (file association & auto-launch will not happen)
* Interface details & minor bugs

# 25/09/2018 v0.1.24
* Fix detection of Outlook installation on some setups

# 20/09/2018 v0.1.23
* Fix detection of Outlook installation on some setups
* Show notification when a contact first reads a message (premium accounts only)
* Show error when account is revoked
* Significant improvements on the Outlook plugin, new design & bug fixes
* Interface details & minor bugs

# 27/08/2018 v0.1.22
* Add logs to help debugging
* New version of the Outlook plugin, more streamlined workflow & correcting bugs

# 09/08/2018 v0.1.21
* Registration is now much faster & displays more information in case of a problem
* Enhance security of the Seald Mail previewer
* Add a link to the Dashboard
* Fix display of files with a given recipient & geolocation in the Dashboard
* Interface details & minor bugs

# 02/07/2018 v0.1.20
* Adding ability to save contacts who do not have Seald yet
* Adding a progress dialog when decrypting files
* On Windows, using a close button to hide the window instead of hiding it when losing focus, so drag&drop-ing files works much better
* Translating the decrypt webpage for people who do not have Seald yet (translation of the app & more languages soon)
* Add automatic check for file association on app startup & in preference window
* Fixing a bug for contacts without Seald where previewing a PDF file could fail
* Fix a glitch where the app could tell you it just updated when it had not
* Remove notifications when automatic update check fails for trivial reasons (like no internet connectivity)
* Interface details & minor bugs

# 18/05/2018 v0.1.19
* Fix a bug where the app could re-open the wizard and re-create an account in rare cases
* Fix a bug where the app could skip wizard even if it was not finished
* Fix issues with email validation when asking to resend email

# 16/05/2018 v0.1.18
* Fix corruption of attached images when sending a feedback
* Fix a bug where encryption in explorer context menu on windows would fail
* Enhancements to web decryption client (when you do not have seald)
* Removing a few obsolete features
* Large internal changes in prevision of future features
* Interface details & minor bugs

# 25/04/2018 v0.1.16
* Decrypting files when you do not have Seald is now safer and updatable
* Large internal changes in prevision of future features
* Interface details & minor bugs

# 26/03/2018 v0.1.15
* No more beta keys !
* Adding ability to view Seald email files with desktop app
* Contacts are now displayed sorted alphabetically
* New PDF previewer for users without Seald
* Fix macOS problem on file registration
* Fix handling of emails containing images & ability to encrypt in answer panel in Outlook plugin
* Fix encryption progress bar
* Interface details & minor bugs

# 25/02/2018 v0.1.14
* Fix opening of old Seald files
* Fix macOS not knowing Seald can open certain files
* Fix weird error message after update on Windows
* Fix opening of encrypted files for non-Seald users on IE
* Fix a few bugs on Outlook plugin
* Interface details

# 16/02/2018 v0.1.13
* Fix opening of new file format on macOS after update
* Fix memory leak on Windows
* Interface details

# 14/02/2018 v0.1.12
* Adding ability to encrypt for people who do not have Seald installed, and new file format
* Adding plugin for Outlook
* Adding compatibility with Linux (experimental)
* Adding config option to toggle auto-start on boot
* Interface details
* Correcting a few quirks here and there
* Dropping compatibility with Slack desktop app
* Deprecating ability to encrypt messages inline with right-click & current Chrome extension

# 03/04/2017 v0.1.11
* Adding 'Extensions' tab in preferences
* Adding extension for Slack desktop app

# 29/03/2017 v0.1.10
* Fully compatible with proxy
* Merging 'Contact-List' and 'Add Contacts' screen. Having both created lots of confusion
* Adding confirmation when you encrypt for yourself only
* Multiple design tweaks and small bug fixes

# 16/03/2017 v0.1.9
* Added basic preference window
* Added option to have multiple email addresses linked to your account
* Changed how file-encryption works: encrypting multiple files will now by default result in one encrypted archive instead of multiple encrypted files
* Added setting to control this file-encryption behaviour
* Multiple design tweaks and small bug fixes

# 08/03/2017 v0.1.8
* Implemented optional silent updates
* Changed pixelated Windows taskbar icon
* Implemented contact suggestions
* Many design tweaks

# 01/03/2017 v0.1.7
* Update contact list when contact automatically added with Chrome extension
* Allow to add a contact from a contact search
* Enhanced duplicate contacts warning window
* Fixed a bug in bug report window
* Automatically hide the main window after contacts have been selected
* Implemented a heartbeat
* Many design tweaks

# 20/02/2017 v0.1.6
* Added check for update option in context menu
* Compatibility with system-wide proxy settings
* Bumped dependencies
* Changed the whole interface
* Fixed slow startup bug on Windows 7

# 30/01/2017 v0.1.5

* Auto-launcher didn't work after the migration to NSIS
* The feedback window in-app didn't work

# 23/01/2017 v0.1.4

* Migration from Squirrel.Windows to NSIS for installer to build x86/x64 installers for Windows.
* Tried a workaround for slow machines for the drag&drop on Windows.
* Switched to winreg for writing in Windows registry to register .seald extension.

