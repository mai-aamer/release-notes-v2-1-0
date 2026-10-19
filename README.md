# SampleApp Release Notes: Version 2.1.0

![SampleApp Release Notes cover](images/banner.svg)

[View screenshots of the Confluence page](#screenshots-of-the-confluence-page)

**Release date:** 2026-10-11  |  **Type:** Minor release  |  **Upgrade:** Automatic, no action needed

## Highlights
Version 2.1.0 adds task due dates, a dark theme and faster loading. It also fixes the login bug reported in September.

## New features
| Feature | Description | Plan |
|---------|-------------|------|
| Due dates | Add a due date to any task and sort by it | All plans |
| Dark theme | Switch theme in **Settings > Appearance** | All plans |
| CSV export | Export your task list as a `.csv` file | Pro |

## Improvements
- Dashboard loads **40% faster** on average.
- Search now finds words inside task descriptions.
- Clearer error messages when a password is too weak.

## Bug fixes
| ID | Problem | Status |
|----|---------|--------|
| BUG-311 | Login failed after password reset | Fixed |
| BUG-327 | Tasks showed the wrong time zone | Fixed |
| BUG-334 | Export button hidden on small screens | Fixed |
| BUG-341 | Rare crash when deleting many tasks | Known issue, planned for 2.1.1 |

## Dashboard load time
```mermaid
xychart-beta
    title "Average dashboard load time (seconds)"
    x-axis ["v1.8", "v1.9", "v2.0", "v2.1"]
    y-axis "Seconds" 0 --> 5
    bar [4.2, 3.6, 3.0, 1.8]
```

## Where the work went
```mermaid
pie showData
    title Work items in v2.1.0
    "New features" : 3
    "Improvements" : 3
    "Bug fixes" : 3
```

## Breaking changes
**None.** Your existing tasks and settings work without change.

## Upgrade notes
1. Refresh your browser to load the new version.
2. See the [Profile Settings Reference](https://github.com/mai-aamer/profile-settings-reference) for the new Appearance options.
3. Report problems at `support@sampleapp.example`.

## Version history
| Version | Date | Summary |
|---------|------|---------|
| 2.1.0 | 2026-10-11 | Due dates, dark theme, faster loading |
| 2.0.0 | 2026-07-01 | New dashboard and sharing |
| 1.9.0 | 2026-04-15 | Search and tags |

*Format follows the [Keep a Changelog](https://keepachangelog.com/) idea.*

## Screenshots of the Confluence page

These release notes were designed and published in Confluence. The screenshots below show the final page, from top to bottom.

![Confluence page, part 1 of 7](confluence-preview-sampleapp-release-notes/01.png)

![Confluence page, part 2 of 7](confluence-preview-sampleapp-release-notes/02.png)

![Confluence page, part 3 of 7](confluence-preview-sampleapp-release-notes/03.png)

![Confluence page, part 4 of 7](confluence-preview-sampleapp-release-notes/04.png)

![Confluence page, part 5 of 7](confluence-preview-sampleapp-release-notes/05.png)

![Confluence page, part 6 of 7](confluence-preview-sampleapp-release-notes/06.png)

![Confluence page, part 7 of 7](confluence-preview-sampleapp-release-notes/07.png)
