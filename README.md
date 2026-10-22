# Lucent Studio Pro v2.6

Static browser-based visual script editor for Lucent.

## New in 2.6
- Complete Quest steps can select a specific reward by its numeric AQW item ID.
- Default reward behavior remains available.
- Uses `api.environment.setQuestReward` before completing the quest and clears the selection after successful or failed boolean completion.
- Five-language UI and existing steps are preserved.

## Publish
Replace repository root `index.html`, commit, and deploy via GitHub Pages.

Note: Live Lucent behavior is not tested. Enter the reward item ID, not its name or option index.
