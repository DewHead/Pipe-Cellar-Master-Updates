# Pipe Cellar Master - Release Notes










## Version 1.18.52+230 (2026-03-05)

### Improvements
- AI Model Update: Standardized on Gemini 3.1 Flash Lite for all operations; Updated configuration and documentation to reflect the latest model.
## Version 1.18.51+229 (2026-03-04)

### Advanced Filtering & Sorting System
- **Advanced Filtering:** New multi-select filter bar with persistent state and support for Brand, Blend, Type, and more.
- **Inventory UI Overhaul:** Streamlined Cellar and Wishlist screens with sticky headers and improved layout.
- **Individual Tin Weight Tracking:** Track tobacco weight at the individual tin level for better accuracy.
- **Enhanced Analytics:** Statistics updated to use precise per-tin weights.
- **Advanced AI Scanner:** Gemini model overrides and photo saving options.
- **Stability Improvements:** Improved backup, restore, and import logic with better duplicate detection.
## Version 1.18.50+228 (2026-03-04)

### Improvements
- Individual Tin Weight Tracking: Tobacco weight is now tracked at the individual tin level.
- Improved Analytics: Dashboard statistics now use individual tin weights.
- Advanced Scanner Features: Added Gemini model overrides and photo saving options.
- Enhanced Data Reliability: Improved backup, restore, and import logic with better duplicate detection.
- UI Polish: Relocated the Cellar/Wishlist sort button and updated tin count styling.
## Version 1.18.49+227 (2026-03-03)

### Improvements
- Added alphabetical and date sorting options to Cellar and Wishlist screens.
## Version 1.18.48+226 (2026-03-03)

### Improvements
- Scanner UI: Added 'Save Photo' option for camera-captured images, allowing users to keep a local copy of their tobacco tins.
- AI Analysis: Updated GeminiService to support specific model overrides, ensuring more robust and optimized tobacco analysis.
- UI Polish: Minor layout improvements in the scanner screen.
## Version 1.18.47+225 (2026-03-03)

### Improvements
- AI Scanner: Improved error handling for blocked or unclear image analysis. Added specific safety filter feedback.
- Scanner UI: Enhanced state persistence during failed analysis for better visibility of error messages.
- Error Handling: Implemented a robust error sanitizer to provide clearer, human-readable messages across the application.
- Data Management: Optimized isolate-based backup restoration for better stability with large collections.
## Version 1.18.46+224 (2026-03-03)

### Improvements
- Export File Extensions: Fixed redundant .txt suffix on JSON/CSV/PDF exports for better cross-platform compatibility.
## Version 1.18.45+223 (2026-03-03)

### Improvements
- Restore & Import Reliability: Added robust logging and improved isolate performance for large collection restorations. Enhanced feedback during cloud backup preparation.
## Version 1.18.44+222 (2026-03-03)

### Improvements
- Data Management Refinement: Simplified the export flow by replacing the bottom sheet with direct CSV/PDF export options in settings. Renamed Local Backup section to Data Management for clarity.
## Version 1.18.43+221 (2026-03-03)

### Improvements
- Data Management Overhaul: Merged Local Backup and Data Export/Import into a unified experience.
- Tin Quantity Display: Now shows total quantity on each tin card in groups.
- Improved Tobacco Search: Unified and more reliable search for both Cellar and Wishlist.
- AI Performance: Optimized Gemini models for faster tobacco analysis.
- General Maintenance: Bug fixes for timeline navigation and scanner stability.
## Version 1.18.42+220 (2026-03-03)

### Improvements
- **Data Management Overhaul:** Merged Local Backup and Data Export/Import into a unified Data Management section in settings. This provides a streamlined user experience for backup, restore, and data export functionalities. The new section includes options for creating and restoring local backups, exporting data to CSV and PDF formats, and importing data from various sources.
- **Tin Quantity Display:** The  now displays the total quantity of each tin item within a group, providing users with at-a-glance information. A chip indicating the total count (e.g., 2 Total) appears if the quantity is greater than one.
## Version 1.18.41+219 (2026-03-03)

### Improvements
- New Features:
- Local Backup/Restore: Create ZIP backups with data + images, restore from device
- AI Model Update: Standardized on gemini-3.1-flash-lite for all operations; Virtual Blending now honestly reports when cellar lacks suitable tobaccos
- UI Enhancements: Recommendation reasons display on separate lines; "Tin added to cellar" snackbar when moving from wishlist; Scanner search refactored to fix crashes
- Pipe Model Field: Added optional "Model" field to pipes with full CRUD support and search integration
Bug Fixes:
- Timeline navigation: Fixed blank screen crash for ungrouped tins; now routes correctly to individual or group detail screens
- TinGroupDetailScreen: Graceful error handling for missing groups
- Scanner manual search: Fixed Exception: No parts in search response content crash
Technical:
- Database migration v21 (adds pipes.model column)
- Refactored WishlistSearchBottomSheet → reusable TobaccoSearchBottomSheet
- Centralized AI model constant in ApiConfig
- Export format enum updated: JSON → ZIP
## Version 1.18.40+218 (2026-03-02)

### Improvements
- Changed Gemini model to 2.5 Flash Light for faster responses and quota concers.
## Version 1.18.39+217 (2026-03-02)

### Improvements
- Minor bug fixes. Updated local backup to backup images like cloud backup does.
## Version 1.18.38+216 (2026-03-02)

### Improvements
- AI Configuration: Centralized the Gemini model ID in ApiConfig and unified its usage across the scanner service. Code Quality: Removed unused logging components in the import service and resolved static analysis warnings in the integration test suite for better maintainability.
## Version 1.18.37+215 (2026-03-02)

### Improvements
- Update Reliability: Improved the reliability of the in-app update mechanism and prioritized Google Play Store signals for better version detection. UI Enhancements: Added a currency selection dropdown to the edit tin screen for improved international support. Date Formatting: Centralized date formatting across the application to ensure consistency. System Refinements: Enhanced logging and general UI refinements for a more stable experience.
## Version 1.18.36+214 (2026-03-02)

### Improvements
- Improved update reliability by prioritizing Google Play Store signals over GitHub metadata for update availability.
## Version 1.18.35+213 (2026-03-02)

### Improvements
- Enhanced log file generation with automatic indexing, refined background analysis UI (removed redundant notifications), improved file naming consistency for exports and logs, and reduced logging noise for background tasks.
## Version 1.18.34+212 (2026-03-02)

### Improvements
- Centralized Date Formatting, Google Play Update Reliability, Currency Support, and Pipe Image Cropping Fix.
## Version 1.18.33+211 (2026-03-02)

### Improvements
- Centralized date formatting for consistent display across all screens.
- Improved UpdateService reliability and simplified logic by removing redundant URLs.
- Added ProGuard rules for the in_app_update plugin to ensure consistent background updates in production.
- UI refinements for edit screens and analytics dashboard.
## Version 1.18.32+210 (2026-03-02)

### Improvements
- Google Play In-App Update Reliability: Added ProGuard rules for the in_app_update plugin to ensure consistent background updates in production.
## Version 1.18.31+209 (2026-03-02)

### Improvements
- Google Play In-App Update Reliability: Added ProGuard rules for the in_app_update plugin to ensure consistent background updates in production.
## Version 1.18.30+208 (2026-03-02)

### Improvements
- Currency Support: Added currency selection dropdown in the Edit Tin screen, allowing users to specify the purchase currency per tin.
## Version 1.18.29+207 (2026-03-02)

### Improvements
- Google Play In-App Update Reliability: Added explicit Play Core dependencies and ProGuard rules. Simplified UpdateService logic.
## Version 1.18.28+206 (2026-03-02)

### Improvements
- Fix: Prevent pipe image cropping by using BoxFit.contain and fixing height constraints.
## Version 1.18.27+205 (2026-03-02)

### Improvements
- UI refinements for pipe and tin images in edit screens. Fixed store URL in update service. Improved UpdateService testability.
## Version 1.18.26+204 (2026-03-02)

### Improvements
- Refactor UpdateService for improved testability and decoupled from Riverpod. Minor UI refinement for pipe images.
## Version 1.18.25+203 (2026-03-02)

### Improvements
- UI scaling for pipe images and improved background placeholder visibility.
## Version 1.18.24+202 (2026-03-02)

### Improvements
- Enhanced update flow with progress tracking, background sync, and fallback to store URL if flexible update fails.
## Version 1.18.23+201 (2026-03-02)

### Improvements
- Branding Improvements: Increased visibility of the application logo on the About screen for a more premium look and feel.
## Version 1.18.22+200 (2026-03-02)

### Improvements
- UI Accessibility and Update Reliability
- Added 'Starting update' state for smoother transitions.
- Improved progress indicators and status messages during the update process.
- Fixed update state handling to ensure consistent UI across different parts of the app.
## Version 1.18.21+199 (2026-03-02)

### Improvements
- UI Accessibility: Moved 'Add Tin' and 'Update Tin' buttons to a persistent bottom navigation bar for better accessibility. Refactored UpdateService for improved reliability and faster version checks.
## Version 1.18.20+198 (2026-03-02)

### Improvements
- Fixed timeline update reflection issue. Added prominent 'Add Tin' and 'Update Tin' buttons for better accessibility. Moved AI Pairing button to tin details screen for improved discoverability.
## Version 1.18.19+197 (2026-03-02)

### Improvements
- Accessibility Improvements: Added prominent 'Add Tin' and 'Update Tin' buttons at the bottom of the scanner edit screens for better visibility and a more intuitive primary action.
## Version 1.18.18+196 (2026-03-02)

### Improvements
- Improved update notification logic to allow dismissing specific versions while ensuring future updates remain visible. Enhanced update banners and dialogs with persistent version-aware dismissal tracking.
## Version 1.18.17+195 (2026-03-02)

### Improvements
- Enhanced update reliability with GitHub metadata integration to bypass Play Store lag, moved AI Pairings button to tin detail screen for better accessibility, and performed maintenance cleanup of test mocks.
## Version 1.18.16+194 (2026-03-02)

### Improvements
- Enhanced Update Reliability and GitHub Metadata Integration: Fetches GitHub metadata first to bypass Play Core lag. Improved update detection logic to show updates as soon as they are available on GitHub or Play Store. Updated notification banner to clearly indicate when an update is downloaded and ready for installation. Maintenance: Cleaned up orphaned test mocks.
## Version 1.18.15+193 (2026-03-02)

### Improvements
- Fixed inventory state invalidation for immediate UI updates and enhanced app update reliability with improved Play Core instance management.
## Version 1.18.14+192 (2026-03-02)

### Improvements
- Refined pipe shape icons and improved default material settings. General code formatting and stability improvements.
## Version 1.18.13+191 (2026-03-02)

### Improvements
- Maintenance and stability improvements.
## Version 1.18.12+190 (2026-03-02)

### Improvements
- Major UI Enhancements & Update System Reliability
- New background update progress bar with percentage
- Visual update badge on Settings icon
- Dismissible update banners with 'Later' button
- Optimized date display: Manufactured Date prioritized over Cellar Date
- Visual tin group selection with images
- Switched to 'in_app_update_me' for improved reliability
## Version 1.18.11+189 (2026-03-02)

### Improvements
- Maintenance and stability improvements.
## Version 1.18.10+188 (2026-03-01)

### Improvements
- Background App Updates: Added real-time progress bars and restart buttons for a seamless update experience.
## Version 1.18.9+187 (2026-03-01)

### Features
- **Vertical Timeline**: Introduced a new vertical timeline layout for the cellar, providing a chronological view of tobacco history and aging.
- **Pipe Selection UI**: Enhanced the smoke logging experience with a new PipeSelectionBottomSheet for easier pipe discovery and selection.
### Improvements
- **Recommendation Engine**: Refined the 'What Should I Smoke?' engine with improved logic and UI for better tobacco suggestions.
- **Settings & UI**: Added new preference settings for display modes and polished the overall app shell navigation.
- **App Update Indication**: Integrated visual cues for pending updates within the settings and main navigation.
## Version 1.18.8+186 (2026-03-01)

### Maintenance
- Code quality and performance improvements
- Minor UI refinements and layout polish
- Updated and verified all tests for the latest changes
## Version 1.18.7+185 (2026-03-01)

### Features
- **Pipe Shape Icons**: Major SVG path refinements and added 6 new shapes (Bent Billiard, Bent Apple, Bent Dublin, Rhodesian, Cherrywood, Prince).
- **Wishlist UI**: Enhanced search and type filters with improved list tile layouts.
### Improvements
- **AI Optimization**: Improved pairing suggestions and background analysis handling.
- **Auto-Update**: Added check for updates when the app is resumed.
- **Pipe Management**: Default material set to 'Briar' for new pipes.
### Technical
- **Bug Fixes**: Improved AsyncNotifier handling and fixed long flavor tags UI.
## Version 1.18.6+184 (2026-03-01)

### Features
- **Pipe Collection Enhancements**: Standardized Brand and Shape dropdowns with custom icons for all major shapes (Billiard, Bulldog, Apple, etc.).
- **Wishlist UI Refinement**: Compact PopupMenu for actions and improved search bottom sheet for easier wishlist navigation.
- **AI Integration**: Optimized Gemini prompts for more concise and focused Pairing/Flavor insights.
- **Maintenance**: Cleaned up unused assets and added SVG support for enhanced iconography.
## Version 1.18.5+183 (2026-03-01)

### Features
- **AI Pairings Enhancement**: Dedicated PairingsBottomSheet for better organization and reusable AI logic.
- **Enhanced Release Notes**: Real-time updates from GitHub with version comparison and local fallback.
- **Pipe Management**: 'Unsaved Changes' protection in EditPipeScreen and 'Pipe Resting Period' info in PipeListScreen.
- **UI/UX Refinements**: Persistent update banners in AppShell and consolidated flavor visualization settings.
## Version 1.18.4+182 (2026-03-01)

### Improvements
- Recommendation Engine: Refined AI-generated recommendation logic with improved grammar and phrasing.
- Enhanced Trending Analytics: Optimized GeminiService with caching and streamlined data schemas for trending tobaccos.
- Deep Tobacco Details: New ability to fetch comprehensive specifications and flavor profiles for individual blends.
- Official Blending Data: Integrated official GL Pease blend descriptions for superior data accuracy.
- UI/UX Polish: Mirrored iconography and improved visual balance in navigation and detail screens.
## Version 1.18.3+181 (2026-03-01)

### Improvements
- **Dynamic Release Notes**: Real-time fetching from GitHub with local asset fallback for transparency.
- **Enhanced Release Automation**: Updated release-manager skill with GitHub manifest upload workflow.
- **Improved UI/UX**: Polished loading states and synchronization for release notes viewer.
## Version 1.18.2+180 (2026-03-01)

### Improvements
- UI: Replaced generic pipe icons with more specific smoking pipe iconography.
- AI: Refined prompts and temperature settings for more concise and focused blending and pairing recommendations.
## Version 1.18.1+179 (2026-03-01)

### Features
- Direct In-App Updates: Integrated 'in_app_update' for seamless Google Play managed updates (Immediate & Flexible).
- Detailed Changelog Manifest: Fetch rich release notes from the dedicated Updates repository for enhanced transparency.
- Test Maintenance: Updated mocks and stability for Gemini service and Settings features.
## Version 1.18.0+178 (2026-03-01)

### Features
- Virtual Blending: Use Gemini AI to create custom blends from your existing cellar inventory.
- AI Pairings: Personalized beverage and activity suggestions based on tobacco flavor profiles.
### Improvements
- UI refinements for cellar and detail screens.
- Enhanced Gemini service error handling and integration tests.
## Version 1.17.0+177 (2026-03-01)

### Features
- **Pipe Collection**: Manage your physical pipes with brand, model, and material tracking.
- **Smoke Sessions**: Track what you smoke and in which pipe for a complete history.
- **Rotation Management**: Monitor pipe rest times and usage history.
- **In-App Updates**: Stay up to date with the latest features via automatic update checks.

### Improvements
- Enhanced backup/restore reliability.
- Refined data export/import for large collections.
- Polished Material 3 navigation and UI components.
## Version 1.16.2+176 (2026-03-01)

### Features
- **Trending Tobaccos**: Discover popular tobacco blends in real-time with Gemini AI and Google Search integration.
- **Recommendation Insights**: Added an info icon to the 'What Should I Smoke?' engine explaining the selection criteria (Open status, Aging, Time of Day).
## Version 1.16.1+175 (2026-02-28)

### Features
- **'What Should I Smoke?' Engine**: Intelligent, context-aware tobacco recommendations from your cellar based on Time of Day, Aging, and Open items.
- **Interactive Recommendations**: A new 'Casino' action in the Cellar screen that triggers a beautiful bottom sheet with 'Roll Again' and 'Let's Smoke' functionality.

### Improvements
- **Smart Scoring**: Logic that prioritizes open tins, optimally aged blends, and current time-of-day preferences (Morning, Afternoon, Evening).
- **Navigation Shortcuts**: Jump directly to the recommended blend's detail screen with one tap.
## Version 1.16.0+174 (2026-02-28)

### Features
- **Advanced Analytics:** Introduced daily consumption tracking and sophisticated aging analytics for better inventory management.
- **Import Reliability:** Enhanced duplicate detection for JSON imports and fixed edge cases in data validation.

### Improvements
- **Auth & Connectivity:** Refined OAuth 2.0 flows and improved cloud backup sorting with localized display times.
- **Data Integrity:** Database refinements to support consumption history and improved AI scanner reliability.
## Version 1.15.5+171 (2026-02-28)

### Improvements
- Integrated grounded search in Gemini scanner and finalized multi-currency support for analytics.
## Version 1.15.4+170 (2026-02-28)

### Improvements
- Fixed missing flavor wheel (radar chart) for new tins.
- Enhanced Gemini AI prompts for more consistent flavor data.
- Added \"Fetch AI Flavor Profile\" button as a fallback.
- Improved flavor data parsing and normalization.
## Version 1.15.3+169 (2026-02-28)

### Improvements
- Improved cloud backup sorting with localized display times.
- Fixed JSON import to allow partial success on validation errors.
- Refined AI scanner grounding and hallucination prevention.
- Enhanced duplicate detection for blends during import.
## Version 1.15.2+168 (2026-02-28)

### Improvements
- Refined AI scanner grounding and hallucination prevention.
- Enhanced cloud backup sorting with localized display times.
- Finalized Currency Support and Analytics enhancements.

## Version 1.15.1+167 (2026-02-28)

### Improvements
- Finalized Currency Support and Analytics enhancements.
- Minor build refinements and dependency synchronization.
- Improved AI scanner grounding and hallucination prevention.
- Enhanced cloud backup sorting with localized display times.
## Version 1.15.0+166 (2026-02-28)

### Features
- Currency Support: Integrated multi-currency handling (USD, EUR, ILS) for tin prices and analytics totals.
- Analytics Enhancements: Added currency-based valuation filtering and localized formatting.

### Improvements
- AI Reliability: Enhanced hallucination prevention in scanner logic and improved brand/manufacturer distinction.
- Data Integrity: Database migration to v18 to support currency tracking.
- Improved Scraper: Revamped G.L. Pease description scraping for higher accuracy.
- Cloud Backup: Improved sorting with localized display times.
- JSON Import: Enhanced robustness to allow partial success on validation errors.
## Version 1.14.0+164 (2026-02-28)

### Improvements
- AI Search Enrichment: Mandatory web verification for identified tobacco blends to eliminate hallucinations.
- AI Search Analysis: Search-enabled flavor analysis for more accurate intensity profiles.
- Data Integrity: Automatic cleanup of orphaned tin groups during import/restore.
- Authentication: Improved user preference handling for automatic Google Sign-In prompts.
- Testing: Updated comprehensive integration tests and mocks for AI services.


## Version 1.13.5+163 (2026-02-28)


### AI & Scanner
- Added Google Search fallback to Gemini scanner for improved blend identification.
- Prioritized authoritative data sources (TobaccoReviews, SmokingPipes) for AI extraction.

### Cloud & Backup
- Robust cloud backup listing with name-based sorting and localized times.
- Fixed restoration hang using SQLite Batch API for large collections.

### Performance & Integrity
- Database migrated to v17 with orphaned group cleanup and case-insensitive indexing.
- Offloaded diagnostic log generation to background isolates to ensure UI responsiveness.

### UI & UX
- Added Safe Area support for backup selection sheets.
- Enhanced import summary with detailed cellar vs wishlist counts.
## Version 1.13.4+162 (2026-02-28)

### Bug Fixes
- Fixed robust cloud backup listing with name-based sorting and localized display times.
- Improved backup entry display with localized time formats for better readability.
## Version 1.13.3+161 (2026-02-28)

### Improvements
- Fix Cloud Restore issue: Ensure newly created backups appear correctly by using modifiedTime for deterministic folder and file selection in Google Drive. Verified with comprehensive integration tests.
## Version 1.13.2+160 (2026-02-28)

### Performance & Integrity
- Fixed 'Processing database updates...' hang during restore using the SQLite Batch API.
- Optimized import performance for large collections via a new group-lookup cache.
- Parallelized physical image restoration for significantly faster recovery.
- Updated database to v16 with case-insensitive indexing for faster searches.

### Bug Fixes
- Fixed a critical issue where tin quantities were reset to 1 during restoration.

### Quality & Testing
- Implemented comprehensive E2E integration tests for the full backup/restore lifecycle (local and cloud).
## Version 1.13.1+159 (2026-02-27)

### Improvements
- Allow partial imports on validation errors and improve total count accuracy.
## Version 1.13.0+158 (2026-02-27)

### New Features
- **📊 Cellar Analytics Dashboard**: Get visual insights into your collection with pie charts for blend types, bar charts for top brands, and key metrics like total value and weight.
- **💰 Price Tracking**: Record the purchase price of your tins to track collection value over time.

### Refactors & Upgrades
- Upgraded project dependencies to latest compatible major versions (Riverpod 3.x, fl_chart 1.x, googleapis 16.x)
- Refactored core application controllers (Settings, Import, Notifications) to comply with Riverpod 3.x Notifier patterns
- Replaced the discontinued `flutter_markdown` package with `flutter_markdown_plus` for better stability and performance
- Updated the entire test suite (132 tests) to accommodate `Ref` class sealing and new `Notifier` override APIs
- Verified system stability with 100% test pass rate post-refactor

## Version 1.12.5+157 (2026-02-27)

### Improvements
- Integrated search functionality for app information and refined flavor profile visualizations
## Version 1.12.4+156 (2026-02-27)

### Features
- Integrated search functionality into the Release Notes and Open Source Licenses screens
- Created a custom searchable Open Source Licenses screen replacing the default system page

### Improvements
- Enhanced flavor profile visualization by forcing the radar chart in detail screens
- Added integration tests to verify search functionality in info screens
## Version 1.12.3+155 (2026-02-27)

### Improvements
- Maintenance and feature synchronization
- Refined About screen and branding consistency
- Synchronized assets for Android and iOS
## Version 1.12.2+154 (2026-02-27)

### Improvements
- Upgraded splash screen to sharp high-quality image
- Updated app launcher icons to a premium design (adaptive for Android)
- Refreshed branding in About screen for a more polished aesthetic

## Version 1.12.1+153 (2026-02-27)

### Improvements
- Implemented a dedicated About screen with Design Philosophy and Resources & Legal sections.
- Added a Release Notes viewer with Markdown support.
- Integrated flutter_markdown dependency and bundled RELEASE_NOTES.md as an asset.
- Updated settings navigation to include the new About page.

## Version 1.12.0+152 (2026-02-27)

### New Features
- **Material 3 \"About\" Screen**: A beautiful new information hub with mission statements, AI capabilities, and privacy transparency.
- **Integrated Release Notes**: Browse the full history of Pipe Cellar Master updates directly within the app, ensuring you're always up to speed with new features.
- **UI Polish**: Added high-fidelity Hero animations and standardized Material 3 \"Lounge\" design tokens across the settings experience.

## Version 1.11.0+151 (2026-02-27)

### Improvements
- **Finalized Google Play Bundle**: This version prepares the app for its official storefront debut.
- **Improved Performance**: Internal build refinements for a smoother scanning and inventory management experience.

## Version 1.10.0+150 (2026-02-27)

### Improvements
- **Finalized Stable Release**: This version marks a stable production milestone, consolidating recent major features including the Google Drive cloud backup system and a polished AI scanning experience.
- **Improved Settings**: Standardized the Cloud Backup and Restore interfaces into `ListTile` entries for better discoverability and consistency.
- **Technical Refinements**: Implemented `rootNavigator` for all modal progress dialogs to prevent UI deadlocks during complex data operations.
- **Maintenance**: General performance optimizations and build refinements for Google Play Console deployment.
