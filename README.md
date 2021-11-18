# NBTreasureChest
*Create reward in treasure chest for your player during Event, Dungeon and more... Pure Forge Minecraft 1.12.2 Mod*

Customize the chest as you want by placing items and turn it into a treasure chest. Your players will then be able to retrieve a copy of the original contents of the chest and store items in it as a personal chest. Simply change the contents of the treasure chest by right-clicking and holding down "Shift". You can change permissions, Treasure Chest display name and all string of the mod. 

**Enhance your events, treasure hunts, exploration and even dungeons with NBTreasureChest**!

# Video demonstration
*Soon*

# Create a treasure chest
## 1. Place a chest with content you want
![image](https://user-images.githubusercontent.com/30299182/142489687-af2434b9-7f14-4093-af51-57eaf794650a.png)

## 2. Enter in edit mod
Just use the command **/nbtreasurechest Toggle**

## 3. Register it
Just right click on it with Shift.

## 4. Done
Congratulation you have now setup a TreasureChest! 

### You want change Treasure Chest permission ?
- Use **/nbtreasurechest Select**
- Right click on the tresure chest (A confirmation will appear)
- Then use **nbtreasurechest DisplayName \<NewName\>** (And it's done, you can also use color code, change permission, delete it, or just reset player progress)

# Commands
## /nbtreasurechest Toggle
Enables / Disables the editing of the treasures chest.

## /nbtreasurechest Select
Enables / Disables the selection of treasures chest. The following commands will **only** be available if you have selected a treasure chest.

## /nbtreasurechest List
Displays a list of all treasure chests, if you click on one of the items in the list you will be teleported to the treasure chest location.

## /nbtreasurechest DisplayName \<NewDisplayName\>
**Only if a treasure chest is selected.** 
Changes the display name of the chest. You can use color aliases (&).

## /nbtreasurechest Permission \<NewPermission\>
**Only if a treasure chest is selected.** 
Changes permission of a treasure chest. Default is **nbtreasurechest.default**

## /nbtreasurechest Remove
Deletes the interaction of the selected treasure chest, as well as the saved data content modified by players.

## /nbtreasurechest Reset_Player_Data
Deletes only the saved data from the contents of the treasure chests modified by the players. Players will then be able to retrieve the content of treasure chest again.

# Permissions
To configure treasures chest you must have the permission "**nbtreasure.admin**". Your players will only need to have access to "**nbtreasure.base**" to open chests that you have not assigned a specific permission to.
*If you set a special permission for a chest, it will be required for a player to open it.*

# Additional details
- If you break a treasure chest, its data as well as the players' data will be deleted and you will be alerted with a message in the chat.
- A player who opens a treasure chest for the first time receives a configurable message, he can retrieve the contents of the chest at the time of generation.
- If you change the contents of a chest, the next players to open it will get the contents of the chest if they haven't already retrieved it before. If you want them to have the rewards again, select only the treasure chest and reset the players progress. 

# More questions ? 
Feel free to ask me directly on my discord server.
