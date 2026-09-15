# 15kgtogo Version 3.1, zero-meets-goal revision

This is a complete static GitHub Pages package.

## Corrected calorie convention

`difference from target = food calories - active calories - calculated target`

- Negative: net intake is below the target, shown in Apple lime.
- Zero: net intake exactly meets the target, also shown in Apple lime.
- Positive: net intake is above the target, shown in pink/red.

The Summary uses **Calorie Difference from Target** to make the sign convention clear.

## Publish

1. Export the current 15kgtogo backup first.
2. Upload all contents of this folder to the GitHub repository root, replacing the prior files.
3. Keep `.github/workflows/pages.yml`.
4. In **Settings > Pages**, select **GitHub Actions**.
5. After deployment, refresh Safari. If the installed Home Screen app remains cached, remove and add it again after preserving the backup.
