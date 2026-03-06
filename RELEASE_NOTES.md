# Pipe Cellar Master - Release Notes
























## Version 1.18.67+245 (2026-03-07)

### Improvements
- **⚙️ Diagnostic Logging**: Added information icon to 'Enable Debug Logging' to assist with issue reporting.
- **🔄 Manual Update Check**: Added a 'Check for update' button in settings.
- **📦 Data Export/Import**: Enhanced backup/restore with more fields (quantities, finished date, etc.) and better metadata handling.
- **🧪 Testing**: Added comprehensive E2E tests for cloud backup and restore lifecycle.
## Version 1.18.66+244 (2026-03-06)

### Improvements
- **⚙️ Diagnostic Logging**: Added information icon to 'Enable Debug Logging' to assist with issue reporting.
- **🔄 Manual Update Check**: Added a 'Check for update' button in settings for better control over update discovery.
## Version 1.18.65+243 (2026-03-06)

### Improvements
- Refined Bulk Analysis persistence and added AI Preview screen.
## Version 1.18.64+242 (2026-03-06)

### New Features
- **📦 Incremental Bulk Analysis**: AI analysis of your collection is now more responsive, providing real-time UI updates as each group is processed.\n- **🔄 Automatic Data Sync**: Adding a tin with AI-scanned characteristics now automatically updates the associated brand/blend group for a more unified view.
### Improvements
- **⚙️ State Management**: Refined the inventory state logic to ensure the UI remains snappy during long-running bulk operations.
## Version 1.18.63+241 (2026-03-06)

### Improvements
- **⚙️ AI Data Sanitization**: Added robustness to Gemini service for parsing tobacco characteristics from AI output.\n- **🎨 UI Polish**: Improved stability in the Edit Tin screen with safer integer handling.
## Version 1.18.62+240 (2026-03-06)

### New Features
- **📦 Tobacco Characteristics in Tin Groups**: Added Strength, Flavoring, Room Note and Taste visualization to the Tin Group screen.
### Improvements
- **⚙️ AI Analysis UI**: Refined Settings screen for clearer bulk analysis progress.\n- **🔄 Data Import**: Enhanced validation and handling of tobacco characteristics during JSON imports.
## Version 1.18.61+239 (2026-03-06)

### Fixes
- UI: Improved readability of flavor chips when in non-interactive mode.
## Version 1.18.60+238 (2026-03-06)

### Improvements
- UI: Refined the Blend Details view in the Tin Group screen to be always visible and better organized.
## Version 1.18.59+237 (2026-03-06)

### New Features
- **📊 Tobacco Characteristics**: Added a new visualization for tobacco strength, flavor intensity, and room note, giving you deeper insights into your collection.\n- **🔄 Dynamic Filter Bar**: Introduced a more intuitive filter chip system for the inventory screens.\n- **📦 Improved Tin Grouping**: Added collapsible sections for tin groups and a refined group detail view for better organization.
### Improvements
- **⚖️ Weight Display**: Cleaned up the weight display by removing redundant parentheses.\n- **⚙️ Settings Refinement**: Simplified preference settings by removing redundant sorting options.\n- **🚀 System Reliability**: Improved the robustness of data import and restoration workflows.
## Version 1.18.58+236 (2026-03-06)

### Improvements
- AI: Upgraded scanner models to Gemini 3.1 Standard for improved accuracy.\n- Timeline: Redesigned aging progression for a more intuitive view of your collection.\n- Inventory: Comprehensive filtering and sorting options for both Cellar and Wishlist.\n- Scanner: Added photo saving and manual model selection overrides for advanced users.\n- System: Enhanced reliability for backup, restore, and import workflows with core performance updates.
## Version 1.18.57+235 (2026-03-05)

### Improvements
- AI: Upgraded scanner models to Gemini 3.1 Standard.\n- Timeline: Redesigned aging progression.\n- Inventory: Advanced filtering and sorting for Cellar and Wishlist.\n- Scanner: Added photo saving and model selection overrides.\n- System: Core performance updates and UI polish.
## Version 1.18.56+234 (2026-03-05)

### Improvements
- **Comprehensive Sorting**: New sorting options for Cellar and Wishlist (Name A-Z/Z-A, Newest/Oldest).\n- **Global Date Selection**: Choose between Manufacture Date or Cellared Date as your primary tracking date throughout the app.\n- **Improved Tin Visualization**: Tin cards now display the selected date (Mfg or Cellared) for better inventory tracking.\n- **Settings Consolidation**: Simplified preference settings with a unified Global Date Source selector.\n- **Enhanced Reliability**: Updated internal data models and database logic for consistent cross-screen sorting and display.
## Version 1.18.55+233 (2026-03-05)

### Improvements
- AI Model Upgrade: Standardized on Gemini 3.1 Flash Lite Preview for improved extraction speed and accuracy.\n- Timeline Enhancements: Added new 'Sub-group by Month' option for the Vertical Timeline layout.\n- UI Refinements: Improved weight display formatting and refined timeline settings.\n- Reliability: Updated tests and internal logic for smoother navigation and data presentation.
## Version 1.18.54+232 (2026-03-05)

### Improvements
- AI Model Upgrade: Standardized on Gemini 3.1 Flash Lite Preview for all operations, improving speed and extraction accuracy.
## Version 1.18.53+231 (2026-03-05)

### Improvements
- AI Model Update: Standardized on Gemini 3.1 Flash Lite for all operations; Updated configuration and documentation to reflect the latest model.
## Version 1.18.51+229 (2026-03-04)

### Advanced Filtering & Sorting System
- **Advanced Filtering:** New multi-select filter bar with persistent state and support for Brand, Blend, Type, and more.\n- **Inventory UI Overhaul:** Streamlined Cellar and Wishlist screens with sticky headers and improved layout.\n- **Individual Tin Weight Tracking:** Track tobacco weight at the individual tin level for better accuracy.\n- **Enhanced Analytics:** Statistics updated to use precise per-tin weights.\n- **Advanced AI Scanner:** Gemini model overrides and photo saving options.\n- **Stability Improvements:** Improved backup, restore, and import logic with better duplicate detection.
## Version 1.18.50+228 (2026-03-04)

### Improvements
- Individual Tin Weight Tracking: Tobacco weight is now tracked at the individual tin level.\n- Improved Analytics: Dashboard statistics now use individual tin weights.\n- Advanced Scanner Features: Added Gemini model overrides and photo saving options.\n- Enhanced Data Reliability: Improved backup, restore, and import logic with better duplicate detection.\n- UI Polish: Relocated the Cellar/Wishlist sort button and updated tin count styling.
## Version 1.18.49+227 (2026-03-03)

### Improvements
- Added alphabetical and date sorting options to Cellar and Wishlist screens.
## Version 1.18.48+226 (2026-03-03)

### Improvements
- Scanner UI: Added 'Save Photo' option for camera-captured images, allowing users to keep a local copy of their tobacco tins.\n- AI Analysis: Updated GeminiService to support specific model overrides, ensuring more robust and optimized tobacco analysis.\n- UI Polish: Minor layout improvements in the scanner screen.
## Version 1.18.47+225 (2026-03-03)

### Improvements
- AI Scanner: Improved error handling for blocked or unclear image analysis. Added specific safety filter feedback.\n- Scanner UI: Enhanced state persistence during failed analysis for better visibility of error messages.\n- Error Handling: Implemented a robust error sanitizer to provide clearer, human-readable messages across the application.\n- Data Management: Optimized isolate-based backup restoration for better stability with large collections.
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
- Data Management Overhaul: Merged Local Backup and Data Export/Import into a unified experience.\n- Tin Quantity Display: Now shows total quantity on each tin card in groups.\n- Improved Tobacco Search: Unified and more reliable search for both Cellar and Wishlist.\n- AI Performance: Optimized Gemini models for faster tobacco analysis.\n- General Maintenance: Bug fixes for timeline navigation and scanner stability.
## Version 1.18.42+220 (2026-03-03)

### Improvements
- **Data Management Overhaul:** Merged Local Backup and Data Export/Import into a unified Data Management section in settings. This provides a streamlined user experience for backup, restore, and data export functionalities. The new section includes options for creating and restoring local backups, exporting data to CSV and PDF formats, and importing data from various sources.\n- **Tin Quantity Display:** The  now displays the total quantity of each tin item within a group, providing users with at-a-glance information. A chip indicating the total count (e.g., 2 Total) appears if the quantity is greater than one.
## Version 1.18.41+219 (2026-03-03)

### Improvements
- New Features:\n- Local Backup/Restore: Create ZIP backups with data + images, restore from device\n- AI Model Update: Standardized on gemini-3.1-flash-lite-preview for all operations; Virtual Blending now honestly reports when cellar lacks suitable tobaccos\n- UI Enhancements: Recommendation reasons display on separate lines; \"Tin added to cellar\" snackbar when moving from wishlist; Scanner search refactored to fix crashes\n- Pipe Model Field: Added optional \"Model\" field to pipes with full CRUD support and search integration\nBug Fixes:\n- Timeline navigation: Fixed blank screen crash for ungrouped tins; now routes correctly to individual or group detail screens\n- TinGroupDetailScreen: Graceful error handling for missing groups\n- Scanner manual search: Fixed Exception: No parts in search response content crash\nTechnical:\n- Database migration v21 (adds pipes.model column)\n- Refactored WishlistSearchBottomSheet → reusable TobaccoSearchBottomSheet\n- Centralized AI model constant in ApiConfig\n- Export format enum updated: JSON → ZIP
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
- Centralized date formatting for consistent display across all screens.\n- Improved UpdateService reliability and simplified logic by removing redundant URLs.\n- Added ProGuard rules for the in_app_update plugin to ensure consistent background updates in production.\n- UI refinements for edit screens and analytics dashboard.
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
- UI Accessibility and Update Reliability\n- Added 'Starting update' state for smoother transitions.\n- Improved progress indicators and status messages during the update process.\n- Fixed update state handling to ensure consistent UI across different parts of the app.
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
- Major UI Enhancements & Update System Reliability\n- New background update progress bar with percentage\n- Visual update badge on Settings icon\n- Dismissible update banners with 'Later' button\n- Optimized date display: Manufactured Date prioritized over Cellar Date\n- Visual tin group selection with images\n- Switched to 'in_app_update_me' for improved reliability
## Version 1.18.11+189 (2026-03-02)

### Improvements
- Maintenance and stability improvements.
## Version 1.18.10+188 (2026-03-01)

### Improvements
- Background App Updates: Added real-time progress bars and restart buttons for a seamless update experience.
## Version 1.18.9+187 (2026-03-01)

### Features
- **Vertical Timeline**: Introduced a new vertical timeline layout for the cellar, providing a chronological view of tobacco history and aging.\n- **Pipe Selection UI**: Enhanced the smoke logging experience with a new PipeSelectionBottomSheet for easier pipe discovery and selection.
### Improvements
- **Recommendation Engine**: Refined the 'What Should I Smoke?' engine with improved logic and UI for better tobacco suggestions.\n- **Settings & UI**: Added new preference settings for display modes and polished the overall app shell navigation.\n- **App Update Indication**: Integrated visual cues for pending updates within the settings and main navigation.
## Version 1.18.8+186 (2026-03-01)

### Maintenance
- Code quality and performance improvements\n- Minor UI refinements and layout polish\n- Updated and verified all tests for the latest changes
## Version 1.18.7+185 (2026-03-01)

### Features
- **Pipe Shape Icons**: Major SVG path refinements and added 6 new shapes (Bent Billiard, Bent Apple, Bent Dublin, Rhodesian, Cherrywood, Prince).\n- **Wishlist UI**: Enhanced search and type filters with improved list tile layouts.
### Improvements
- **AI Optimization**: Improved pairing suggestions and background analysis handling.\n- **Auto-Update**: Added check for updates when the app is resumed.\n- **Pipe Management**: Default material set to 'Briar' for new pipes.
### Technical
- **Bug Fixes**: Improved AsyncNotifier handling and fixed long flavor tags UI.
## Version 1.18.6+184 (2026-03-01)

### Features
- **Pipe Collection Enhancements**: Standardized Brand and Shape dropdowns with custom icons for all major shapes (Billiard, Bulldog, Apple, etc.).\n- **Wishlist UI Refinement**: Compact PopupMenu for actions and improved search bottom sheet for easier wishlist navigation.\n- **AI Integration**: Optimized Gemini prompts for more concise and focused Pairing/Flavor insights.\n- **Maintenance**: Cleaned up unused assets and added SVG support for enhanced iconography.
## Version 1.18.5+183 (2026-03-01)

### Features
- **AI Pairings Enhancement**: Dedicated PairingsBottomSheet for better organization and reusable AI logic.\n- **Enhanced Release Notes**: Real-time updates from GitHub with version comparison and local fallback.\n- **Pipe Management**: 'Unsaved Changes' protection in EditPipeScreen and 'Pipe Resting Period' info in PipeListScreen.\n- **UI/UX Refinements**: Persistent update banners in AppShell and consolidated flavor visualization settings.
## Version 1.18.4+182 (2026-03-01)

### Improvements
- Recommendation Engine: Refined AI-generated recommendation logic with improved grammar and phrasing.\n- Enhanced Trending Analytics: Optimized GeminiService with caching and streamlined data schemas for trending tobaccos.\n- Deep Tobacco Details: New ability to fetch comprehensive specifications and flavor profiles for individual blends.\n- Official Blending Data: Integrated official GL Pease blend descriptions for superior data accuracy.\n- UI/UX Polish: Mirrored iconography and improved visual balance in navigation and detail screens.
## Version 1.18.3+181 (2026-03-01)

### Improvements
- **Dynamic Release Notes**: Real-time fetching from GitHub with local asset fallback for transparency.\n- **Enhanced Release Automation**: Updated release-manager skill with GitHub manifest upload workflow.\n- **Improved UI/UX**: Polished loading states and synchronization for release notes viewer.
## Version 1.18.2+180 (2026-03-01)

### Improvements
- UI: Replaced generic pipe icons with more specific smoking pipe iconography.\n- AI: Refined prompts and temperature settings for more concise and focused blending and pairing recommendations.
## Version 1.18.1+179 (2026-03-01)

### Features
- Direct In-App Updates: Integrated 'in_app_update' for seamless Google Play managed updates (Immediate & Flexible).\n- Detailed Changelog Manifest: Fetch rich release notes from the dedicated Updates repository for enhanced transparency.\n- Test Maintenance: Updated mocks and stability for Gemini service and Settings features.
## Version 1.18.0+178 (2026-03-01)

### Features
- Virtual Blending: Use Gemini AI to create custom blends from your existing cellar inventory.\n- AI Pairings: Personalized beverage and activity suggestions based on tobacco flavor profiles.
### Improvements
- UI refinements for cellar and detail screens.\n- Enhanced Gemini service error handling and integration tests.
## Version 1.17.0+177 (2026-03-01)

### Features
- **Pipe Collection**: Manage your physical pipes with brand, model, and material tracking.\n- **Smoke Sessions**: Track what you smoke and in which pipe for a complete history.\n- **Rotation Management**: Monitor pipe rest times and usage history.\n- **In-App Updates**: Stay up to date with the latest features via automatic update checks.

### Improvements
- Enhanced backup/restore reliability.\n- Refined data export/import for large collections.\n- Polished Material 3 navigation and UI components.
## Version 1.16.2+176 (2026-03-01)

### Features
- **Trending Tobaccos**: Discover popular tobacco blends in real-time with Gemini AI and Google Search integration.\n- **Recommendation Insights**: Added an info icon to the 'What Should I Smoke?' engine explaining the selection criteria (Open status, Aging, Time of Day).
## Version 1.16.1+175 (2026-02-28)

### Features
- **'What Should I Smoke?' Engine**: Intelligent, context-aware tobacco recommendations from your cellar based on Time of Day, Aging, and Open items.\n- **Interactive Recommendations**: A new 'Casino' action in the Cellar screen that triggers a beautiful bottom sheet with 'Roll Again' and 'Let's Smoke' functionality.

### Improvements
- **Smart Scoring**: Logic that prioritizes open tins, optimally aged blends, and current time-of-day preferences (Morning, Afternoon, Evening).\n- **Navigation Shortcuts**: Jump directly to the recommended blend's detail screen with one tap.
## Version 1.16.0+174 (2026-02-28)

### Features
- **Advanced Analytics:** Introduced daily consumption tracking and sophisticated aging analytics for better inventory management.\n- **Import Reliability:** Enhanced duplicate detection for JSON imports and fixed edge cases in data validation.

### Improvements
- **Auth & Connectivity:** Refined OAuth 2.0 flows and improved cloud backup sorting with localized display times.\n- **Data Integrity:** Database refinements to support consumption history and improved AI scanner reliability.
## Version 1.15.5+171 (2026-02-28)

### Improvements
- Integrated grounded search in Gemini scanner and finalized multi-currency support for analytics.
## Version 1.15.4+170 (2026-02-28)

### Improvements
- Fixed missing flavor wheel (radar chart) for new tins.\n- Enhanced Gemini AI prompts for more consistent flavor data.\n- Added \"Fetch AI Flavor Profile\" button as a fallback.\n- Improved flavor data parsing and normalization.
## Version 1.15.3+169 (2026-02-28)

### Improvements
- Improved cloud backup sorting with localized display times.\n- Fixed JSON import to allow partial success on validation errors.\n- Refined AI scanner grounding and hallucination prevention.\n- Enhanced duplicate detection for blends during import.
## Version 1.15.2+168 (2026-02-28)

### Improvements
- Refined AI scanner grounding and hallucination prevention.\n- Enhanced cloud backup sorting with localized display times.\n- Finalized Currency Support and Analytics enhancements.

## Version 1.15.1+167 (2026-02-28)

### Improvements
- Finalized Currency Support and Analytics enhancements.\n- Minor build refinements and dependency synchronization.\n- Improved AI scanner grounding and hallucination prevention.\n- Enhanced cloud backup sorting with localized display times.
## Version 1.15.0+166 (2026-02-28)

### Features
- Currency Support: Integrated multi-currency handling (USD, EUR, ILS) for tin prices and analytics totals.\n- Analytics Enhancements: Added currency-based valuation filtering and localized formatting.

### Improvements
- AI Reliability: Enhanced hallucination prevention in scanner logic and improved brand/manufacturer distinction.\n- Data Integrity: Database migration to v18 to support currency tracking.\n- Improved Scraper: Revamped G.L. Pease description scraping for higher accuracy.\n- Cloud Backup: Improved sorting with localized display times.\n- JSON Import: Enhanced robustness to allow partial success on validation errors.
## Version 1.14.0+164 (2026-02-28)

### Improvements
- AI Search Enrichment: Mandatory web verification for identified tobacco blends to eliminate hallucinations.\n- AI Search Analysis: Search-enabled flavor analysis for more accurate intensity profiles.\n- Data Integrity: Automatic cleanup of orphaned tin groups during import/restore.\n- Authentication: Improved user preference handling for automatic Google Sign-In prompts.\n- Testing: Updated comprehensive integration tests and mocks for AI services.


## Version 1.13.5+163 (2026-02-28)


### AI & Scanner
- Added Google Search fallback to Gemini scanner for improved blend identification.\n- Prioritized authoritative data sources (TobaccoReviews, SmokingPipes) for AI extraction.

### Cloud & Backup
- Robust cloud backup listing with name-based sorting and localized times.\n- Fixed restoration hang using SQLite Batch API for large collections.

### Performance & Integrity
- Database migrated to v17 with orphaned group cleanup and case-insensitive indexing.\n- Offloaded diagnostic log generation to background isolates to ensure UI responsiveness.

### UI & UX
- Added Safe Area support for backup selection sheets.\n- Enhanced import summary with detailed cellar vs wishlist counts.
## Version 1.13.4+162 (2026-02-28)

### Bug Fixes
- Fixed robust cloud backup listing with name-based sorting and localized display times.\n- Improved backup entry display with localized time formats for better readability.
## Version 1.13.3+161 (2026-02-28)

### Improvements
- Fix Cloud Restore issue: Ensure newly created backups appear correctly by using modifiedTime for deterministic folder and file selection in Google Drive. Verified with comprehensive integration tests.
## Version 1.13.2+160 (2026-02-28)

### Performance & Integrity
- Fixed 'Processing database updates...' hang during restore using the SQLite Batch API.\n- Optimized import performance for large collections via a new group-lookup cache.\n- Parallelized physical image restoration for significantly faster recovery.\n- Updated database to v16 with case-insensitive indexing for faster searches.

### Bug Fixes
- Fixed a critical issue where tin quantities were reset to 1 during restoration.

### Quality & Testing
- Implemented comprehensive E2E integration tests for the full backup/restore lifecycle (local and cloud).
## Version 1.13.1+159 (2026-02-27)

### Improvements
- Allow partial imports on validation errors and improve total count accuracy.
## Version 1.13.0+158 (2026-02-27)

### New Features
- **📊 Cellar Analytics Dashboard**: Get visual insights into your collection with pie charts for blend types, bar charts for top brands, and key metrics like total value and weight.\n- **💰 Price Tracking**: Record the purchase price of your tins to track collection value over time.

### Refactors & Upgrades
- Upgraded project dependencies to latest compatible major versions (Riverpod 3.x, fl_chart 1.x, googleapis 16.x)\n- Refactored core application controllers (Settings, Import, Notifications) to comply with Riverpod 3.x Notifier patterns\n- Replaced the discontinued `flutter_markdown` package with `flutter_markdown_plus` for better stability and performance\n- Updated the entire test suite (132 tests) to accommodate `Ref` class sealing and new `Notifier` override APIs\n- Verified system stability with 100% test pass rate post-refactor

## Version 1.12.5+157 (2026-02-27)

### Improvements
- Integrated search functionality for app information and refined flavor profile visualizations
## Version 1.12.4+156 (2026-02-27)

### Features
- Integrated search functionality into the Release Notes and Open Source Licenses screens\n- Created a custom searchable Open Source Licenses screen replacing the default system page

### Improvements
- Enhanced flavor profile visualization by forcing the radar chart in detail screens\n- Added integration tests to verify search functionality in info screens
## Version 1.12.3+155 (2026-02-27)

### Improvements
- Maintenance and feature synchronization\n- Refined About screen and branding consistency\n- Synchronized assets for Android and iOS
## Version 1.12.2+154 (2026-02-27)

### Improvements
- Upgraded splash screen to sharp high-quality image\n- Updated app launcher icons to a premium design (adaptive for Android)\n- Refreshed branding in About screen for a more polished aesthetic

## Version 1.12.1+153 (2026-02-27)

### Improvements
- Implemented a dedicated About screen with Design Philosophy and Resources & Legal sections.\n- Added a Release Notes viewer with Markdown support.\n- Integrated flutter_markdown dependency and bundled RELEASE_NOTES.md as an asset.\n- Updated settings navigation to include the new About page.

## Version 1.12.0+152 (2026-02-27)

### New Features
- **Material 3 \"About\" Screen**: A beautiful new information hub with mission statements, AI capabilities, and privacy transparency.\n- **Integrated Release Notes**: Browse the full history of Pipe Cellar Master updates directly within the app, ensuring you're always up to speed with new features.\n- **UI Polish**: Added high-fidelity Hero animations and standardized Material 3 \"Lounge\" design tokens across the settings experience.

## Version 1.11.0+151 (2026-02-27)

### Improvements
- **Finalized Google Play Bundle**: This version prepares the app for its official storefront debut.\n- **Improved Performance**: Internal build refinements for a smoother scanning and inventory management experience.

## Version 1.10.0+150 (2026-02-27)

### Improvements
- **Finalized Stable Release**: This version marks a stable production milestone, consolidating recent major features including the Google Drive cloud backup system and a polished AI scanning experience.\n- **Improved Settings**: Standardized the Cloud Backup and Restore interfaces into `ListTile` entries for better discoverability and consistency.\n- **Technical Refinements**: Implemented `rootNavigator` for all modal progress dialogs to prevent UI deadlocks during complex data operations.\n- **Maintenance**: General performance optimizations and build refinements for Google Play Console deployment.

## Version 1.9.0+148 (2026-02-26)

### Technical
- **App Bundle**: Created a production-ready app bundle for Google Play Console.\n- **Versioning**: Incremented version to 1.9.0 (build 148).

## Version 1.8.0+147 (2026-02-26)

### Improvements
- **Unified Backup Experience**: Aligned the Cloud Backup and Restore interfaces with the local Data Management (Export/Import) features to ensure a consistent look and feel across the app.\n- **ListTile Integration**: Transformed cloud backup actions into standard `ListTile` elements within Settings, making them more discoverable and consistent with other settings categories.\n- **Visual Progress Tracking**: Implemented a unified progress overlay for all data-heavy operations.\n- **Typography Standardization**: Refined the visual weight of secondary information across the entire Settings screen using standard `bodySmall` typography.

### Technical
- **Enhanced Modal Safety**: Refactored progress dialogs to use the `rootNavigator`, ensuring they correctly overlay all UI elements.\n- **Improved Layout Resilience**: Integrated `useSafeArea` into key import and restore screens to ensure content is perfectly positioned.

## Version 1.7.0+146 (2026-02-26)

### New Features
- **Google Drive Cloud Backup**: Securely back up your entire pipe tobacco collection to your personal Google Drive.\n- **Automated Sync**: Choose between Daily or Weekly automatic background backups on app startup.\n- **Cloud Restore Wizard**: A new in-app file browser that lets you easily select from your previous cloud backups.\n- **Backup History**: Track the status of every manual and automated backup attempt directly in Settings.

### Improvements
- **Refined Scanner Overlay**: Fixed the \"white box\" visual glitch in the scanning screen with 80% opacity dark overlay.\n- **Enhanced Scanning Visuals**: Improved the scanning line with a stronger glow and refined the pulsing icon and progress bar.\n- **Robust Clipping**: Added anti-alias clipping to the scanner container to ensure all overlay elements respect the rounded corner design.\n- **Data Fidelity**: 100% field parity for JSON imports/exports, ensuring your reviews, flavor wheels, and notes are perfectly preserved.

### Technical
- **Database Schema v14**: Incremented database version to support local backup logs and persistent sync status.\n- **OAuth 2.0 Resilience**: Centralized authenticated HTTP client to ensure reliable token injection for AI and Drive services.

## Version 1.2.1+138 (2026-02-25)

### Bug Fixes
- **AgeCountingMode Serialization**: Fixed a critical crash that occurred when importing collections.\n- **Data Recovery**: Automatically repairs corrupted records from previous failed imports using a new database migration (v12).

## Version 1.1.0+136 (2026-02-25)

### New Features
- **Enhanced Data Import Validation**: A major update to the import system that provides deep visibility into data validation.\n- **Detailed Error Reporting**: Identifies exactly which fields failed, why they failed, and what value was encountered.\n- **Contextual Format Hints**: Helps you fix your CSV/JSON files by showing expected formats for complex metadata.\n- **Validation Inspection Screen**: A new dedicated view to safely review all warnings and errors before executing an import.

### Technical
- **Defensive JSON Extraction**: Hardened CSV parser to handle malformed or hand-edited JSON strings.\n- **Robust State Management**: Updated `ImportController` with improved navigation state tracking.

## Version 1.0.0+135 (2026-02-25)

### New Features
- **Official Release**: This marks the first official stable release of Pipe Cellar Master.

### Bug Fixes
- **Wishlist Stability**: Resolved a bug where updating wishlist items could cause them to disappear or throw errors.

### Technical
- **Improved Data Integrity**: Enhanced `TinRepository` to ensure all items maintain consistent IDs.

## Version 0.9.2+133 (2026-02-25)

### Improvements
- **Modernized AI Auth**: Updated the authentication layer to support Gemini 2.5 Flash security requirements.\n- **Optimized Performance**: Significant speed improvements when loading large collections.\n- **Proactive AI Readiness**: Session refresh before starting deep AI analysis.

### Bug Fixes
- **Deadlock Fix**: Resolved a critical issue where the app could hang when adding tins.

## Version 0.9.1+132 (2026-02-25)

### New Features
- **Expanded CSV Support**: Added support for importing quantity fields via CSV.

### Improvements
- **Smart CSV Type Coercion**: Improved parsing that intelligently handles user-edited spreadsheets.\n- **Robust Error Reporting**: Enhanced Import Wizard with detailed validation summaries.

### Technical
- **Defensive Validation Engine**: A robust new pre-ingestion validation layer.\n- **JSON Format Hardening**: Improved handling of malformed fields within CSV files.

## Version 0.9.0+131 (2026-02-25)

### New Features
- **High-Performance Data Import**: Migrate collections from other apps using JSON or CSV.\n- **Guided Import Wizard**: A polished 5-stage experience with real-time feedback.\n- **Smart Conflict Resolution**: Automatic detection of existing tins with Skip/Overwrite/Keep options.\n- **OS-Level Backup Support**: Configured Android Backup and Data Extraction rules.

### Technical
- **Data Retention Hardening**: Multi-layered survival strategy for inventory and images.\n- **Robust Migration Testing**: Suite of tests simulating real-world app upgrades.\n- **Transactional Safety**: Atomic inventory operations to prevent data corruption.\n- **Background Isolate Parsing**: Heavy file processing performed off-thread for UI fluidity.

## Version 0.8.1+130 (2026-02-24)

### Improvements
- **Smart Category Matching**: Updated filters to use \"contains\" matching for multi-type blends.\n- **Accurate Filter Counts**: Chips now reflect the total number of tins in each category.\n- **Improved Search Stability**: Enhanced search field targeting in automated tests.

## Version 0.8.0+126 (2026-02-24)

### New Features
- **Instant Feedback**: Preview tobacco flavor wheels immediately during the scanning process.

### Improvements
- **Wishlist Flavor Parity**: Tobacco added from AI search now includes full flavor profile data.\n- **Enhanced Navigation**: Improved tab behavior when viewing wishlist details.\n- **Polished Search Experience**: New Analysis Indicator with pulsing icons and status labels.\n- **Smart Detection**: Recognizes when flavor profiles have been modified for unsaved changes warnings.

### Bug Fixes
- **Flavor Reliability**: Fixed an issue where flavor profile data could be lost during state transitions.

### Technical
- **Nested Routing**: Improved bottom navigation bar focus for wishlist details.\n- **State Synchronization**: Robust sync between AI extraction and local persistence.

## Version 0.5.5+120 (2026-02-24)

### New Features
- **Advanced Diagnostics**: Added \"Enable Debug Logging\" toggle in Settings.\n- **Smart Resource Management**: Debug logging automatically disables after sharing logs.

### Improvements
- **Dynamic Logging**: Switch between standard and verbose modes without restart.

## Version 0.5.2+117 (2026-02-23)

### Improvements
- **Enhanced UX**: Automatic analysis state synchronization when returning to the app.\n- **Convenient Sign-In**: Remembered Google account selection with auto-sign-in.\n- **Improved Flow**: Sign-out clears stored credentials only on explicit user action.

### Bug Fixes
- **Fixed Background Analysis**: Resolved hanging issues in background tin analysis.\n- **Connectivity**: Improved error handling for AI service connectivity.

### Technical
- **Enhanced Logging**: Better debugging for authentication and analysis.\n- **Timeouts**: Improved timeout handling for network operations.

## Version 0.5.1+116 (2026-02-23)

### Improvements
- **State Sync**: Automatic analysis state synchronization.\n- **Stability**: Added timeouts and enhanced logging for background AI tasks.

### Bug Fixes
- **Background Analysis**: Fixed hanging issues during tin analysis.

## Version 0.5.0+115 (2026-02-23)

### New Features
- **Unsaved Changes Warning**: Implemented across all edit screens (Tin, Item, Group).

### Improvements
- **3-button Dialog**: Consistent Save/Discard/Cancel editing experience.\n- **Navigation Safety**: Enhanced PopScope interception for async navigation.

## Version 0.3.1+112 (2026-02-23)

### New Features
- **Streamlined Scanner**: Automatic image analysis when selecting a photo.\n- **Smart Date Memory**: Remembers last used cellar and manufacture dates.\n- **Filter Counts**: Shows tin counts on filter buttons.\n- **Wishlist Search**: Added search and type filters to the wishlist screen.\n- **UI Update**: Changed add tin FAB icon from camera to plus icon.

## Version 0.3.0+110 (2026-02-23)

### New Features
- **Tin Groups**: Automatic grouping of multiple tins of the same blend.\n- **Flexible Quantity Tracking**: Track as individual tins or batch with counts.\n- **Date-based Grouping**: Separate tracking for different cellar/manufacture dates.

### Technical
- **Data Migration**: Existing data automatically migrated with duplicates merged.

## Version 0.2.4+105 (2026-02-23)

### New Features
- **Official Descriptions**: Fetches official G.L. Pease descriptions from manufacturer.\n- **Age Counting Mode**: Choose between Cellar Date or Manufactured Date for age calculation.

### Technical
- **Code Quality**: Fixed deprecated APIs and removed unused imports.

## Version 0.2.3+104 (2026-02-23)

### Bug Fixes
- **Diagnostic Logs**: Fixed log truncation issues with proper file sharing.

## Version 0.2.2+102 (2026-02-23)

### Improvements
- **Persistent Auth**: Fixed Google Sign-In sessions and API key persistence.\n- **Robust Startup**: Enhanced initialization timeout for Google services.\n- **Improved UX**: Background token refreshing without visual flashes.

## Version 0.2.1+101 (2026-02-23)

### New Features
- **Manufacture Tracking**: Added \"Sealed/Manufactured Date\" tracking.

### Improvements
- **Error Feedback**: Improved error message dismissibility.

## Version 0.2.0+100 (2026-02-23)

### New Features
- **Wishlist Integration**: Added persistence and cellar integration.\n- **Notification UI**: Manage aging milestones and history.\n- **Enhanced Scanning**: Improved AI data extraction for tobacco tins.

## Version 0.1.2+95 (2026-02-23)

### Bug Fixes
- **Maintenance**: Minor bug fixes and UI refinements.

## Version 0.1.0+90 (2026-02-23)

### New Features
- **Initial Release**: Project setup with core inventory management capabilities.\n- **Documentation**: Initial Design and Implementation guides.
