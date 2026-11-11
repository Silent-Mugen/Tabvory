Tabvory Privacy Policy

**Last updated:** November 12, 2026  
**Developer:** Silent Mugen 
**Applies to:** Tabvory desktop browser extension, including version 1.1.1

1. Introduction

Tabvory is a browser extension for managing tabs, browser tab groups, workspaces, saved sessions, duplicate tabs, and tab memory usage. It also provides appearance settings, import and export, and optional backups.

This policy explains the information Tabvory accesses, how it uses and stores that information, and how users can manage or remove it.

2. Information Tabvory Accesses

To provide its features, Tabvory may access information made available through browser extension APIs, including:

- Open tab URLs, page titles, website domains, and favicons when available.
- Tab and window details, such as order, active status, pinned status, and tab grouping information.
- Saved workspaces and browsing sessions, including website addresses and titles.
- User-defined grouping categories, domain rules, and tab-protection preferences.
- Extension settings such as language, theme, accent colors, and interface density.

Tabvory uses this information for tab management, grouping, workspace and session management, duplicate detection, tab protection, and optional inactive-tab unloading. It is not designed to read passwords, form entries, or the contents of webpages.

3. Local Processing and Storage

Tabvory processes and stores extension information locally using browser-provided storage APIs. Depending on the features used, locally stored information may include settings, grouping rules, protected tabs or domains, saved workspaces, and manually or automatically saved sessions.

This information remains associated with the user's browser profile unless the user exports, copies, or otherwise transfers it. An account or sign-in is not required to use Tabvory's core features.

For website icons, Tabvory uses favicons provided by the browser or its local favicon facilities when available. Tabvory does not use a third-party favicon lookup service to send visited website addresses to an external icon provider.

4. Collection, Transmission, and Sharing

Tabvory operates locally and does not send users' browsing information to servers operated by the developer. It does not include developer-operated analytics, advertising trackers, or user-profiling services, and it does not sell browsing information to advertisers or data brokers.

Tabvory does not require users to submit their browsing history, saved sessions, or personal information to the developer. Normal browser activity and network requests made by websites the user visits are separate from Tabvory's local tab-management functions.

If a user voluntarily contacts the developer or submits a GitHub issue, information that the user chooses to include in that communication is handled through the communication platform and subject to that platform's policies. Users should not include private browsing details, backup files, or sensitive information in public support reports.

5. Private Browsing

The Firefox version of Tabvory is configured not to operate in Firefox private browsing windows (`"incognito": "not_allowed"`). Tabvory does not access or save information from those Firefox private browsing windows.

Private/incognito behavior in other supported desktop browsers is governed by the relevant browser's extension permissions and settings. This policy does not claim identical private-browsing behavior across all browsers.

6. Automatic Session Saving and JSON Backups

When enabled, automatic session saving periodically stores session information locally based on user settings.

Separately, Tabvory can generate JSON backups through the browser's download functionality. Scheduled backups are generally generated about once every 24 hours, and a backup may also be created shortly after the schedule is initialized. Depending on the browser's download settings, backup files may be saved under `Downloads/Tabvory/backups/` or another configured location.

Backup and export files may contain saved website URLs and titles, browsing session information, workspace configurations, grouping rules, protected-domain settings, and extension preferences. This information can reveal personal interests or browsing activity.

**Tabvory does not encrypt exported or automatically downloaded JSON backup files.** Keep backup files secure and do not share them with untrusted parties. If a downloaded file is stored in a folder synchronized by the operating system or a third-party cloud service, that service may process the file according to its own settings and privacy policy. Tabvory does not control such synchronization.

Tabvory does not upload these backups to developer-operated servers.

7. Retention and Deletion

Locally stored extension data generally remains until the user changes or removes it, resets or uninstalls Tabvory, or the browser removes the associated data. Users can manage supported saved information using Tabvory's controls.

Uninstalling Tabvory generally removes its browser-managed extension storage, subject to browser behavior. **Previously downloaded or exported JSON backups are not automatically removed** when the extension is reset or uninstalled. Users must delete those files separately if they no longer want to retain them. Importing an old backup can restore previously removed information.

The developer does not maintain a server-side database of users' workspaces or saved browsing sessions.

8. Browser Permissions

Tabvory requests permissions needed to operate its tab-management features. Permissions vary by browser and may include:

- **Tabs:** access and manage tabs, URLs, titles, and tab state.
- **Tab groups:** organize tabs into native browser groups where supported.
- **Storage:** save settings, rules, workspaces, and sessions locally.
- **Alarms:** schedule optional session-saving, backups, and inactive-tab checks.
- **Downloads:** create manually requested exports and optional JSON backups.
- **Context menus:** provide tab-management actions from browser menus.
- **Side panel:** display Tabvory in the browser's side panel where supported.
- **Favicon:** display website icons from supported browser-provided favicon facilities where available.

The permissions used by each browser build depend on its supported extension APIs. They are intended to support the features described in Tabvory's official store listings.

9. Data Security

Tabvory is designed to minimize unnecessary collection and to rely on local browser storage instead of developer-operated servers. However, no software or local storage system can guarantee absolute security. Users should secure their devices and browser profiles and take particular care with unencrypted export and backup files.

10. Children's Privacy

Tabvory is a general-purpose browser productivity extension and is not specifically directed at children. It does not require personal registration or operate an advertising or social-networking service. The developer does not knowingly collect children's personal information through developer-operated services.

11. Changes to This Policy

This policy may be updated to reflect changes in Tabvory's features, data practices, or applicable requirements. The update date at the top will be changed when the policy is revised.

12. Contact and Official Links

Tabvory is developed and maintained by Silent Mugen.

- Support and privacy questions: [GitHub Issues](https://github.com/Silent-Mugen/Tabvory/issues)
- Project page: [Tabvory on GitHub](https://github.com/Silent-Mugen/Tabvory)
- Firefox listing: [Tabvory on Mozilla Add-ons](https://addons.mozilla.org/ru/firefox/addon/tabvory/)

For sensitive privacy inquiries, avoid publishing confidential information in a public GitHub issue. Contact the developer through an appropriate private support channel if one is provided on the official store listing.
