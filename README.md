# Talented - Kader Edition

This is the same old **Talented** addon but instead of having its modules as separate addons, they are included (_Talented\_GlyphFrame & Talented\_SpecTabs_).

Also, all those separated core files were put into single files depending on the context.

Other than that, nothing was modified except for the glyphs frame that was buggy, now it's working fine and also the code was optimized and cleaned.

## Extra:

Instead of those non-working official sites (_wowhead, wowdb, mmo-champion .. etc_), you can now export/import your templates to/from:

1. EvoWoW.com
2. WoTLKDB.com
3. Altervisa.org
4. TrueWoW.org

## Install:

1. [Download the package.](https://github.com/bkader/Talented_WoTLK/archive/refs/heads/main.zip)
2. Open the archive, then open folder Talented_WoTLK-main, extract the single folder to `Interface\AddOns`.
3. Enjoy!

## Project Epoch Regeneration

This fork can regenerate [Talented/Data.lua](Talented/Data.lua) from two inputs:

1. `EpochTalentScan.lua` saved variables from the in-game scanner addon.
2. `.talents.json`, which provides observed per-rank tooltip text.

Run it with:

```bash
python3 generate_from_scan.py
```

If the scanner saved variables are not in the default location, pass them explicitly:

```bash
python3 generate_from_scan.py --scan-path /path/to/WTF/Account/<Account>/SavedVariables/EpochTalentScan.lua
```

The generator keeps spell IDs as the primary source of truth and uses `.talents.json` to match the correct rank spell IDs from the scanner's candidate pool instead of relying only on sequential spell IDs.

## Show Love & Support

Though it's not required and I have never asked for it but people keep asking for it, if you want to show love and support, your PayPal donations are most welcome to **bkader[at]email.com**.
