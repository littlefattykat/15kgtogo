# 15kgtogo

Single GitHub Pages package.

## Publish

Upload the contents of this folder to the repository root and replace the old files. Keep `.github/workflows/pages.yml`. In repository **Settings > Pages**, choose **GitHub Actions**. The workflow is named **Deploy 15kgtogo to GitHub Pages**.

If an old version remains, export a backup first, then clear site storage/cache or uninstall and reinstall the PWA.

## Included changes

- Date selector inside Summary, with previous, next, and Today controls
- Import and Export grouped in the top navigation beside Food List and Profile & Goal
- Context-sensitive Food, Exercise, and Weight forms
- Food meal selector: Breakfast, Lunch, Dinner, Snack
- Common Apple Health-style workout/activity selector and active-calorie input
- Separate water section with +250 ml, +500 ml, and +1 L
- Delete button on every selected-date log row
- Separate Dashboard tab with 7-day and monthly analysis
- Full backup including profile, goal, foods, entries, and water
- Personal Food List and in-browser English nutrition-label OCR

## Apple Health note

The activity selector uses common activity names found in health/workout tracking ecosystems, but this static website does not connect to Apple Health. Use Apple Health active-calorie values when available. Direct HealthKit data requires a signed native iOS app or native wrapper and user permission.
