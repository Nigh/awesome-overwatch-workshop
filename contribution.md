
# How to contribute

Please use the PR submission code, Simplified Chinese in [script_zh](script_zh) , English in [script](script), other languages ​​should be placed in the `script_[language]` path.

If you have an entry that needs to be translated, please submit an `issue`

If you want to help with the translation, first check if there are untranslated entries in the `issue`, and then check the `list of script` for untranslated entries (the untranslated entries will appear in the `list of script` of all languages in the language of original submitted)

## Submit format
Please use the `markdown` language in the following format:

```markdown
# Name
Brief
## Description
Detailed description
## script
`Share code`
```
Among them, the items you need to fill in are `Name`, `Brief`, `Detailed description`, `Share code`.

- **Name** - Name for this mode, it is best to let others have an intuitive understanding of this mode
- **Brief** - Try to briefly describe the core gameplay of this mode
- **Detailed description** - Detailed description of the gameplay, victory conditions, etc.
- **Share code** - Script code generated using the share function

Here's a simple example:

```markdown
# Lava Death Fight
Anyone who touched ground will get suffer continuous damage
## description
All players, when in contact with the ground, deal 30 damage per second, and when they jump or fly, the continuous damage stops immediately.
Using the standard dead bucket mode, a total of 8 players competed, and the top 4 players in the killing number won.
## script
`skfdui58fgjh3j210dlvmgj5830xks`
```
