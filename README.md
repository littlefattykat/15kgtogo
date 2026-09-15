# 15kgtogo GitHub Pages v2

## Publish
Upload the contents of this folder to the repository root and replace the old files. Keep `.github/workflows/pages.yml`. In **Settings > Pages**, use **GitHub Actions**.

## New in this package
- Summary date control has no “Viewing date” text and is aligned with previous/next buttons.
- Monthly Dashboard renders every calendar day, including zero-entry days. On phones the chart scrolls horizontally so all day labels remain visible.
- Food List opens with the current list first. Select **Add food** to open the editor/scanner.
- Manufacturer search removed. Google search remains in Add Food.
- Mobile Close button is aligned in a sticky dialog header.
- Meal Suggestion accepts a comma-separated natural-language ingredient list from Food List and proposes portions against remaining calories, protein, carbs, and fat.
- Suggested portions can be added together to the selected date.

## Meal suggestion limitations
The suggestion engine is a browser-side mathematical heuristic, not a dietitian or AI model. It only uses foods and nutrition values already saved in Food List. It searches ingredient names, changes serving multipliers between 0.25 and 4 servings, and minimizes the difference from remaining calorie and macro targets. Review practicality, appetite, allergies, sodium, micronutrients, cooking ingredients, and food safety yourself. The app does not construct separate breakfast/lunch/dinner menus automatically; it proposes one combined set of quantities and logs them as suggested foods.

## Label OCR
Tesseract.js is loaded from jsDelivr. Review OCR carefully for kcal versus kJ, decimals, and per-serving versus per-100 values.
