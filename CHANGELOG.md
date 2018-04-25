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

