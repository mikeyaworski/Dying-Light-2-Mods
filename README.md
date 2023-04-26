# Dying Light 2 Mods

## Installation

1. Put the `dataX.pak` file into your `Steam\steamapps\common\Dying Light 2\ph\source` folder. Increment the number if there are conflicting data files. data2, data3, ..., data7

## Development

1. Make a copy of `data0.pak` named `dataX.pak`.
1. Extract `dataX.pak` archive using 7Zip or whatever.
1. Remove everything except for the files you intend to modify. For now, that is everything except for the `dataX/scripts/player/player_variables...` files.
1. Modify the files by changing whichever variables.
1. Zip the folder and rename it from `dataX.zip` to `dataX.pak`. Make sure the zip does not contain the `dataX` folder as a wrapper. The structure inside the `dataX.pak` archive should be `scripts/player/...`, NOT `dataX/scripts/player/...`.