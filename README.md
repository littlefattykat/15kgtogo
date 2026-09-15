# CalTrack final GitHub Pages package

## Publish or update

Upload the **contents of this folder** to the root of the `caltrack-web` repository and replace the old files. Keep only `.github/workflows/pages.yml` in the workflows folder. Delete any root-level `pages.yml` and unused Azure workflow. In **Settings > Pages**, set Source to **GitHub Actions**.

## Included

- Activity-ring-inspired mobile interface
- Summary and remaining calories first
- Automatic calorie and macro targets from profile and weight goal
- Editable goal weight and target date
- 50 ml water button
- Personal Food List
- Manual nutrient facts
- Camera/photo nutrition-label OCR
- Personal Food List meal search and quantity scaling
- Google/manufacturer lookup inside Food List
- Full export/import including entries, water, profile, goal, and Food List
- No Category field
- Equal Import and Export controls

## Label scanning

Tesseract.js is loaded from jsDelivr. Images are processed in the browser and are not intentionally retained. OCR can misread kcal versus kJ, decimals, and serving bases. Review all values against the package before saving. English OCR is used.

## Apple Health

A GitHub Pages website cannot directly read Apple Health/HealthKit. Apple Health integration requires a native iOS application or a native wrapper such as Capacitor with a HealthKit plugin, user permission, and App Store/device signing. You can manually enter Apple Health active calories or weight now, or import a future converted export.

## Formula and assumptions

Mifflin-St Jeor BMR × activity minus the deficit implied by current weight, goal weight, and days remaining, constrained by the minimum calorie floor. Protein is 1.4 g/kg, fat is 28% of target calories, fiber is 25 g, and carbohydrate receives remaining calories. These are general estimates, not medical advice.
