# Frequently Asked Questions

***

### How do I set up a hook?

1. Open `worth.yml` in the Sellwand plugin folder.
2. Change 'Hook' to the name of your hook. (e.g., 'EconomyShopGUI' if you want to use EconomyShopGUI).
3. **RESTART** your server.

If it is still not working after these steps, please open a support ticket on my Discord server, and include a link from `/sellwanddebug`.

### Why do I get the error "Nothing to sell in this chest."?
Make sure to set up a hook.

### How do I set unlimited uses on the wand?

To allow unlimited uses, you have to write `-1`. Here is an example configuration:
```
tier_1:
    name: "&6&lTier 1 sell wand"
    material: STICK
    glowing: true
    permission: null
    multiplier: 1.0
    uses: -1
    lore:
      - "&6Right-Click &eon chest to"
      - "&esell its content!"
      - ""
      - "&eSell wand information:"
      - "&e Multiplier: &6%multiplier%x"
      - "&e Uses: &6%uses%"
      - ""
      - "&eStatistics:"
      - "&e Total items sold: &6%total_item%"
      - "&e Total sold price: &6%total_sold_price%&e$"
```

### What is a permission plugin?
A permission plugin allows you to create groups and assign different rights to different users. An example plugin is [LuckPerms](https://luckperms.net/).  
You can find every available permission for Sellwand here: [Commands and Permissions](https://docs.zachfr.com/plugin/sellwand/command-and-permission).

### How do I add my own items?
This depends on the plugin you use as a hook. In the default settings (without a hook), you can add items in `worth.yml`. Just scroll down to `Worth:` and add it there using the following format: `item: price`.

### Where do I find a list of all available Minecraft items?
You can find every available Minecraft item in the following list: [https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html).

### Sellwand is listed as a virus?!
For more information, see: [https://www.spigotmc.org/threads/windows-defender-false-positives.639507/](https://www.spigotmc.org/threads/windows-defender-false-positives.639507/).

### Where do I get support?
You can contact our support on the [Discord server](https://discord.gg/3UjfQ7sbR8). 
