# Source Scramble Patches

This repo is a collection of [Source Scramble](https://github.com/nosoop/SMExt-SourceScramble) patches,
intended to replace single-purpose plugins that rarely get updated and are likely to break.

In order to use these, you **need** the `sourcescramble_manager` plugin, which is included in Source Scramble releases.

## Usage

Get the `addons/configs/sourcescramble_manager.cfg` from the repository and comment out the patches you'd like to use.

For example, if you want to unlock the maximum movement speed, you'd uncomment the following line:

```diff
"tf2.movement_speed_unlocker"		"CTFGameMovement::ProcessMovement::UnlimitedMovementSpeed"
```

Uncomment every patch associated with the same gamedata file, or you'll be missing out on functionality.

Make sure you also install the gamedata file associated with it into `addons/sourcemod/gamedata`, in this
case `tf2.movement_speed_unlocker.txt`.

## What's In The Box?

* `tf2.movement_speed_unlocker.txt`
    * Replaces [TF2 Move Speed unlocker](https://forums.alliedmods.net/showthread.php?p=2659562)
* `tf2.no_thriller_taunt.txt`
    * Replaces [No Thriller Taunt](https://forums.alliedmods.net/showthread.php?t=171343)