# Land System /lands

- `/land edit` - Edit land. Usually, you only need to use it when you have a lot of land.

- `/land claim` - Expand or claim (for the first time) the land in your area.The amount of money spent depends on the number of blocks.

- `/land create` - Create land (requires $4000 (first time)).

- `/land unclaim` - Unclaim the land in your area.

- `/land info` - Displays the land information for your current area.

- `/land trust [player name]` - Grant a specific player trust on your land.

- `/land untrust [player name]` - Revoke a specific player's trust on your land.

- `/land menu` - Main interface of the lands system (includes functions: create "areas" Note 1, manage permissions for others and yourself, view statistics, change the name and introduction of the lands upon entry, level up Note 2, etc.).

- `/land taxes` - Confirm or pay land taxes.

- `/land top` - View the current lands ranking.

- `/land chat` - Enter lands chat (only members inside can receive messages).Usage: Option 1: `/land chat [lands name] [message]`, Option 2: `/land chat` (directly activates this mode, re-execute the command to restore).

- `/land ban` - Ban someone (prohibit entry) (`/land unban` to restore).

- `/land map` - Display the mini-map (lands).

- `/land setrole` - Set the player's permissions in the lands (default permissions: member|ally|admin).Usage: `/land setrole [player name] [region name]` (input represents all) members.

- `/land view` - Directly displays the lands range in the game (since the marking method uses particle effects, you need to enable the options related to particle effects in the display settings).

- `/land confirmtp` - Confirm teleporting to a dangerous place (this might happen if you were in flying mode while creating the land, executing this command will ignore the warning and teleport you).

- `/land setspawn` - Set the spawn point (referring to resetting the spawn point of `/land spawn`, currently no fee (Milk Tea Coins) is required to change it).

- `/land setowner` - Transfer ownership (`/land setowner [player name]` followed by executing `/land setowner [player name] confirm` to confirm).

- `/land list` - View all lands.

- `/land leave` - Leave the lands (it is recommended to stand in the lands first and then execute `/land edit` before executing this command, otherwise you might leave another lands).

- `/land invites` - View the received lands invitations.

- `/land merge` - Merge land (First, stand on the place to be merged `/land edit`, then `/land merge [name of the land to be merged]`, and finally type `/land merge [name of the land to be merged] confirm`).

- `/land help` - View tutorial.

- `/lands selection` - A selection tool similar to /lands claim (can be replaced with a selection tool (golden shovel)) Note 4 Note 5 Note 6

!!! Comment

Note 1: An "area" is like a small piece of land within a lands, which can also manage the permissions of others and yourself. For example, if you place an enchanting table in your home, you can directly set that block to be usable by everyone, allowing people to use that block without needing trust.

Note 2: The rank can change when entering the lands, as explained in the rank title of the land.

Note 3: The basic unit of lands is calculated using chunks.