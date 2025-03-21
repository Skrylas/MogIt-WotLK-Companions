# MogIt-WotLK-Companions
MogIt is an in-game catalogue of items with the aim of helping players build their own sets for transmogrification purposes.

- Database and preview of Mounts, Companions (non-combat pets), and Hunter Pets

## Functions:
![companions](https://github.com/user-attachments/assets/50785b39-3ad2-4555-9820-42fd0b518ff9)
![pets](https://github.com/user-attachments/assets/700fad14-011d-43cf-bb9c-bda65cb48dde)

## Help
Type /mog or /mogit to open the main panel.

## FAQ

**All I see are question marks?**  
WotLK unfortunately has very limited caching functionality for mobs.  Items can be force-cached if unseen, NPCs cannot.  The only Mounts, Pets and Companions that'll show up are usually the ones you own, or potentially have seen (mounts don't really work when seen).

**How does this install?**  
Just drop it into the addon folder, as long as you have [MogIt-WotLK](https://github.com/Skrylas/MogIt-WotLK/) installed, this will appear as an Extra Module ![image](https://github.com/user-attachments/assets/d9110087-e570-498e-b82e-aa1174faa4d3)

**My server has custom items, how do I add them?**  
Many servers have custom mounts and pets, they can be added to the end of the list using the same format listed at the top of the Mount/Pet/Companion.lua file.  Or you can create a new module for them that will load separately from the Blizzlike ones.
