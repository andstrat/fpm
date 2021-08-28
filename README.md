# Favorite MIDI Presets
## ABOUT



## FEATURES
- Switch Bank (=Sub-Bank) and Program.
- Switch between automatically or manually sending MIDI data to your MIDI device if Bank/Program is changed
- MIDI preset may have optionally a user definable name
- MIDI preset can be rated
- Choose to let MIDI data through
- Store and recall of a preset in preset slot
- Presets can be organized on row level. Each row has user-definable label that you can adapt to your own liking, eg. sound styles or status of a presets
- Last preset selection is save per category and can be recalled
- Recalled presets are automatically send to your MIDI device
- Clearing of all data or per row
- MIDI preset section can be hidden in case you just recalling your presets.
- Presets can be rated from 1-3
- MIDI send indicators
- Continious program counter
- Select next/previous slot in slot storage
- Give your bank a meningfull name
- The preset slot, bank and programm are MIDI mappable,

## ROADMAP


## CONTRIBUTING

## RELEASES

### v1.1
- Presets are now stored with your Ableton project or you can save it as a normal Abletone device preset (.adv files). Preset slots are automatically restored.
The code is based on https://maxforlive.com/library/device/4286/mikado-base-save-patch-preset-with-live-projet. SPECIAL THANKS to spiralune for this really useful hack.

### v1.2
- NEW: Presents can be rated from 1-3
- NEW: AUTO turned on will automatically send MIDI data to your MIDI device if Bank/Program is changed
- NEW: MIDI send indicators
- NEW: MIDI CC/PGM can be filtered via switch
- NEW: Linear Program Counter
- NEW: Select next/previous slot in slot storage
- NEW: Save last selected slot per category with name for quick recall
- NEW: Clear data in a row
- NEW: MIDI IN data will now change Bank and Program
- CHANGE: Slot storage size changed to 15x9
- CHANGE: Some visual tweaks here and there
- CHANGE: Some devices required Sub-Bank instead of Bank. Both are now set to equal value. 
- BUGFIX: Bank selection now working

### v1.3
- Added a selectable bank size that is used to calculate the Linear Program Counter (bank size * program number).
- Banks can now have a user definable name
- Added a mappable number field for the currently selected slot.
- Added a field showing the current selected preset name that of the select preset slot.
- Some UI tweaks

### v1.4
- Added a section to take notes. 
- Renamed 'Auto' to 'Send'
