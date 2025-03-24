#Cosmos 50.X upgrade

##removed Dependencies
* github.com/cosmos/cosmos-sdk/x/crisis
- Deprecated https://github.com/cosmos/cosmos-sdk/tree/main/x#deprecated-modules
* github.com/cosmos/cosmos-sdk/x/upgrade/client
- Removed from the base repo. No clue where this goes? look into auto client gens.
* github.com/cosmos/cosmos-sdk/x/slashing/client/cli
- Removed from the base repo. No clue where this goes? look into auto client gens.
* github.com/cosmos/ibc-go/v8/modules/core/02-client/client
- Removed from the base repo. No clue where this goes? look into auto client gens.
* github.com/cosmos/cosmos-sdk/snapshots
* Removed from the base repo. No clue where this goes? Think it's deprecated?
* cosmossdk.io/api
- Reverted from v0.8 to v0.7. Because they wanted to deprecate cosmos-sdk/module/crisis but it is still used by wasmd.