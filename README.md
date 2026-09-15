# CalTrack Rings update

Mobile-first dark activity-ring interface with the summary first, automatically calculated calorie and macro targets, remaining macros, structured online nutrition lookup, and Google/manufacturer fallback.

## Update GitHub Pages

Upload the contents of this folder to the repository root and replace the existing files. Keep `.github/workflows/pages.yml`. In **Settings > Pages**, use **GitHub Actions**. Delete any accidental root-level `pages.yml` and any unused Azure workflow.

## Nutrition behavior

Open Food Facts provides standardized calories and available protein, carbohydrate, fat, and fiber values. Selecting a result fills the meal form automatically. Product records may be incomplete, so verify the package label. Google and manufacturer buttons open manual searches and do not scrape snippets.

## Macro assumptions

- Protein: 1.4 g per kg of current body weight
- Fat: 28% of target calories
- Fiber: 25 g/day
- Carbohydrate: remaining target calories after protein and fat

These are general planning estimates, not individualized clinical advice.
