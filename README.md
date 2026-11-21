# Privacy Policy — RuleOut Chrome Extension

**Effective Date:** November 20, 2026  
**Last Updated:** November 20, 2026

RuleOut is designed to be privacy-first. We do **not** collect, transmit, sell, or share your personal data or browsing history.

## 1. Data Stored by RuleOut
RuleOut stores only the data you explicitly create while using the extension:
- **Tracked listings:** Canonical listing URLs, titles, price snapshots (initial and latest observed prices), optional thumbnail URLs, Hidden/Shortlisted flags, your personal notes, and optional list/collection names.
- **Extension preferences:** Display preferences (dim vs. collapse mode, button visibility, quick-note tags, list names) and any custom card CSS selectors you create via **Pick Card**.

## 2. Where Your Data Lives
- **Local by default:** All data is stored locally on your device using Chrome's built-in `chrome.storage.local` API. RuleOut does not operate any backend servers and never sends your data to us or to any third party.
- **Optional Chrome Sync:** If you explicitly enable **Sync across Chrome profiles** in the extension popup, RuleOut uses Chrome's built-in `chrome.storage.sync` API so your settings, lists, custom selectors, and recent items sync through your own Google Chrome account according to Google Chrome's sync privacy controls. You can turn this off at any time.
- **Manual Backup & Export:** You can export your data as CSV or JSON files at any time or delete individual items/clear extension storage from Chrome.

## 3. Website Permissions (Opt-In Only)
RuleOut does **not** request broad access to all websites upon installation.
- Host access uses Chrome's `optional_host_permissions`. RuleOut only activates on websites where you explicitly click **Enable on [site]** (or use the context menu / "+ Note URL" action on the current tab).
- You can revoke access for any website at any time from the RuleOut popup (**Disable** or **Notes & Sites → Enabled websites → Remove**) or via `chrome://extensions`.

## 4. Analytics, Tracking, and Third Parties
- **Zero analytics or telemetry.**
- **Zero ads, trackers, or affiliate link injection.**
- **Zero remote code execution.** All extension logic runs locally from the packaged extension bundle.

## 5. Contact
If you have any questions about this Privacy Policy, please open an issue at:  
https://github.com/harsh-mr/ruleout-privacy/issues
