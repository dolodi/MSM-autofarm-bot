# MySingingMonstersAutoBot
Get tired of collecting your gold and shards from your monsters? Run this bot to collect your gold while you're AFK. This cant be virtualized because we are using bluestack already, at least its not reccomended.

BEWARE ! if you dont know anything about python or programming and expect this to work out of the box.

## Version
### - 1.6
Fine tuned everything the only problem right now is finding images or confidence that works on different devices ? (pc) Maybe i should make it always open the game on fullscreen so the resolution should be equal on all?
After that everything should work for ever, the only obstacle is the game updates that changes the font used on text and the images changing or map changing.
## TODO
- [ ] Ask something.

## Features
1. Auto collect coins.
2. Auto collect diamons (mines monsters whatever)
3. Auto collect food.
4. Auto collect daily rewards
5. Auto collect conundrum.
6. Auto reconnect if you play on phone so you dont have to manually re run it.
7. Auto close popups like events and whatever.
8. Auto collects relics or what their called.
9. Auto breed and auto hatch but need to be improved logically, its hard to use if you dont understand it.
10. Auto collect shards.
11. Auto collect tribal rewards.
12. Auto collect nexus (useless now because the rewards are so low)

## How To
1. Download Python (latest version recommended).
2. Open terminal and install the required dependencies.
3. Open the directory where the files are downloaded.
4. Run main.py.


Alt + Tab into MySingingMonsters and let it run 😀

### Initial Setup
1. Download and install Python from the official website.
2. Open your terminal and install the required packages by running the appropriate commands.
3. Install inside the bluestack instance you use my singing monster.

### Configuration Steps
1. **Photos of Buttons etc**: Update the photos of individual buttons as needed for your specific setup.
2. **Shutdown Timing**: Adjust the values for when the system should turn off to match your preferences.
3. **BIOS Settings**: Enable the hours you want the system to turn on in your BIOS settings. For example, set it to turn on at 7 AM and turn off at 2 AM (in the main.py), allowing 5 hours of cooldown.
4. **Autorun on Startup**:
   - Press the Windows key + R to open the Run dialog.
   - Type `shell:startup` and press Enter to open the Startup folder.
   - Place the batch (msm.bat) file in this folder so the script runs automatically on startup.
5. **Bluestacks Configuration**: 
   - Ensure you have Bluestacks installed and configured.
   - If you have multiple instances of Bluestacks, make sure to update the script to use the correct instance.

### Notes
- The script will automatically open Bluestacks first and then run the script. If you're unsure about any of these steps, please refer to the official documentation or seek help from someone familiar with the process.
- If you encounter any issues, please ensure you've followed all the setup steps correctly before opening an issue. Thank you for your understanding!
