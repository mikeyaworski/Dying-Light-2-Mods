# Dying Light 2 Mods

## Corrupted Saves Warning

**Important**: Read the [wiki page](https://github.com/mikeyaworski/Dying-Light-2-Mods/wiki/Corrupted-Saves) on the possibility of corrupted saves due to mod usage, and then consider how you want to use the mod or whether you want to use it at all.

## Installation

1. Put the `dataX.pak` file into your `Steam\steamapps\common\Dying Light 2\ph\source` folder. Increment the number if there are conflicting data files. data2, data3, ..., data7

## Development

1. Make a copy of `data0.pak` named `dataX.pak`.
1. Extract `dataX.pak` archive using 7Zip or whatever.
1. Remove everything except for the files you intend to modify. For now, that is everything except for the `dataX/scripts/player/player_variables...` files.
1. Modify the files by changing whichever variables.
1. Zip the folder and rename it from `dataX.zip` to `dataX.pak`. Make sure the zip does not contain the `dataX` folder as a wrapper. The structure inside the `dataX.pak` archive should be `scripts/player/...`, NOT `dataX/scripts/player/...`.

## Push a new release

Releases are created when new tags are pushed (if the tag name starts with "v"). Below is an example of creating and pushing a tag:
```
git tag -a v1.0 -m "Version 1.0 of mod for game version 1.10.2"
git push --follow-tags
```
