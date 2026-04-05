Privacy Policy for TabBrain
Last updated: April 6, 2026
TabBrain is a Chrome extension that helps you organize, save, and search your browser tabs. We are committed to protecting your privacy. This policy explains what data TabBrain collects, how it is used, and your choices.
Data Stored Locally
By default, all data is stored locally in your browser using Chrome's storage APIs. No data leaves your device unless you explicitly enable cross-device sync.
Tab information: URLs, titles, and favicons of your open tabs are read to enable auto-grouping, session saving, and search functionality. This data is stored locally in your browser.
Page content snippets: When "Index page content" is enabled in Settings, TabBrain extracts up to 2,000 characters of text from web pages you visit. This enables full-text search across your browsing. Content is stored locally and never transmitted externally.
Tab screenshots: TabBrain captures JPEG screenshots of your active tabs to display in the visual tab grid. Screenshots are stored locally with a maximum of 200 cached images. They are never transmitted externally.
Browsing patterns: TabBrain analyzes your tab usage patterns (which domains you visit at what times) to detect browsing routines and surface insights. Pattern data is stored locally and never transmitted.
Sessions and settings: Your saved sessions, tags, custom grouping rules, and preferences are stored locally in your browser.
Data Collected with Google Sign-In (Optional)
If you choose to sign in with Google to enable cross-device sync, the following data is collected:
Personally identifiable information: Your Google account name, email address, and profile photo are retrieved via Google OAuth to display your account in Settings and to authenticate with our sync service.
Session data: When sync is enabled, your saved sessions (tab URLs, titles, favicons, group names, and tags) are stored in Google Firebase Firestore, secured by Firebase Authentication. Only you can access your synced data. Screenshots and page content snippets are never synced.
Settings: Your TabBrain preferences are synced to Firebase Firestore so they apply across all your devices.
Browsing History (Optional)
If you enable "Search browsing history" in Settings, TabBrain requests Chrome's optional history permission to search your browsing history. This data is queried locally using Chrome's History API and is never transmitted or stored externally. You can revoke this permission at any time through Chrome's extension settings.
Website Content
TabBrain uses the scripting permission to inject a content extraction script into web pages you visit. This script reads the visible text content of the page (up to 2,000 characters) for full-text search indexing. The extracted text is stored locally in your browser. It is never transmitted to any external server or third party.
Data We Do NOT Collect

We do not collect health, financial, or payment information
We do not collect authentication credentials or passwords
We do not collect personal communications (emails, messages)
We do not collect location data
We do not perform network monitoring, click tracking, or keystroke logging
We do not use analytics or tracking scripts
We do not display advertisements

Third-Party Services
Google Firebase (only when sync is enabled): Used for authentication (Firebase Auth) and data storage (Cloud Firestore). Firebase is operated by Google and governed by Google's Privacy Policy. TabBrain's Firestore security rules ensure that each user can only access their own data.
Data Retention

Local data persists until you clear it via Settings → Clean Old Data, or uninstall the extension
Screenshots and content cache older than 30 days are automatically purged
Auto-saved sessions are purged based on your retention setting (default: 30 days)
If you sign out of Google sync, your cloud data remains in Firestore until you delete it manually or request deletion

Data Deletion
You can delete all your data at any time:

Local data: Use Settings → Export/Import → or uninstall the extension
Synced data: Sign out from Settings, then delete your data from the Firebase Console, or contact us to request deletion

Your Choices

Content indexing: Can be disabled in Settings → Smart Search → Index page content
Browsing history: Optional permission, can be revoked anytime
Cross-device sync: Completely optional, requires explicit Google sign-in
Auto-save: Can be disabled in Settings → Sessions & Backup
Pattern detection: Can be disabled in Settings → Notifications → Pattern suggestions

Changes to This Policy
We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above. Continued use of TabBrain after changes constitutes acceptance of the updated policy.
Contact
If you have questions about this privacy policy or TabBrain's data practices, please contact:
Email: ayush22081993@gmail.com
Open Source
TabBrain's source code is available for review. We believe in transparency about how your data is handled.
