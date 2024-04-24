# Source Scramble Patches

This repository is a collection of [Source Scramble](https://github.com/nosoop/SMExt-SourceScramble) patches, intended to replace single-purpose plugins that rarely get updated and are likely to break.

In order to use these, you **need** the `sourcescramble_manager` plugin, which is included in Source Scramble releases.

## Usage

For each patch that you would like to enable, download its relevant `cfg` file  from `addons/sourcemod/configs/sourcescramble/` and place it into your server's `addons/sourcemod/configs/sourcescramble/` directory (create this directory if it does  not exist).

Download the corresponding gamedata file for each patch from `addons/sourcemod/gamedata/` and place it in your server's `addons/sourcemod/gamedata/` directory.

For example, if you want to unlock the maximum movement speed, you'd download `addons/sourcemod/configs/sourcescramble/tf2.movement_speed_unlocker.cfg` and `addons/sourcemod/gamedata/tf2.movement_speed_unlocker.txt`.

To disable a patch, delete the relevant `cfg` file.

## What's In The Box?

* `tf2_movement_speed_unlocker.cfg` and `tf2.movement_speed_unlocker.txt`
    * Replaces [TF2 Move Speed Unlocker](https://forums.alliedmods.net/showthread.php?p=2659562)
* `tf2.no_thriller_taunt.cfg` and `tf2.no_thriller_taunt.txt`
    * Replaces [No Thriller Taunt](https://forums.alliedmods.net/showthread.php?t=171343)
* `tf2.mvm_increased_bot_limit.cfg` and `tf2.mvm_increased_bot_limit.txt`
  * Replaces [Unlimited MvM Bots](https://forums.alliedmods.net/showthread.php?t=343531)
