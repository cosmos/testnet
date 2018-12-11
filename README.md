# Cosmos Testnets

This repo collects the genesis and configuration files for the various Cosmos
testnets. It exists so the [Cosmos-SDK](https://github.com/cosmos/cosmos-sdk) 
repo does not get bogged down with large genesis files and status updates.

# Getting Started

To get started with the latest testnet, see the
[docs](https://cosmos.network/docs/gaia/join-testnet.html).

# Testnet Status


## *November 30, 2018 21:00 EST* - Gaia-9002

- `gaia--9002` Launching Gaia-9002 https://forum.cosmos.network/t/gaia-9002-planning-thread/1378



## *November 9, 2018 21:00 EST* - Gaia-9001

- `gaia--9001` Launching Gaia-9001 https://forum.cosmos.network/t/gaia-9001-launch-thread-w-seeds-lets-try-this-again/1301/4


## *August 20, 2018 11:00 EST* - Gaia-8000

- `gaia--8000` Launching Gaia-8000 https://forum.cosmos.network/t/launching-gaia-8000/739

## *August 7, 2018 11:00 EST* - Gaia-7005

- `gaia--7005` Launching Gaia-7005 https://forum.cosmos.network/t/launching-gaia-7005/698

## *August 4, 2018 1:30 EST* - Gaia-7004

- `gaia--7004` Network halted. Stack Trace https://github.com/cosmos/cosmos-sdk/issues/1920


## *July 29, 2018, 12:00 EST* - Gaia-7003 
- `gaia-7003` halted as fortold by the fuzzer. Stack trace here:https://github.com/cosmos/cosmos-sdk/issues/1872
- `gaia-7004` is online now https://forum.cosmos.network/t/gaia-7004-launching/635

## *July 27, 2018, 20:00 EST* - Gaia-7003 

- Testnet halted on a Tendermint [regression](https://github.com/tendermint/tendermint/pull/2076)
- [v0.23.1 of the SDK](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.23.1)
- Details on `gaia-7003` can be found [here](https://forum.cosmos.network/t/launching-gaia-7003/607)



## *July 26, 2018, 0:00 EST* - Gaia-7002 

- [v0.23.0 of the
  SDK](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.23.0)
- [Launch timeline](https://forum.cosmos.network/t/gaia-7002-launch-timeline/581)
- [Details on genesis.json](https://forum.cosmos.network/t/building-gaia-7002-genesis-json/589)

## *July 22, 2018, 17:00 EST* - Gaia-7001 consensus failure

- Bug in the governance module caused a panic

## *July 17, 2018, 4:00 EST* - New Testnet Gaia-7001 

- New testnet with fixes for the genesis file 
- Increased max validators to 128

## *July 17, 2018, 3:00 EST* - Gaia-7000 consensus failure

- Misconfiguration in the genesis file led to a consensus failure
- New genesis file for gaia-7001 will be up soon

## *July 17, 2018, 2:40 EST* - Gaia-7000 is making blocks!

- Gaia-7000 is live and making blocks!

## *July 16, 2018, 17:00 EST* - New Testnet Gaia-7000

- Gaia-7000 is up!
- 108 validators in the genesis.json file.

## *July 2, 2018, 1:00 EST* - Gaia-6002 slashing failure

- Gaia-6002 has been halted due to a slashing issue.
- The team is taking its time to look into this Gaia-7000 will be introduced this week.

## *June 13, 2018, 17:00 EST* - Gaia-6002 is making blocks!

- Gaia-6002 is live and making blocks
- Absent validators have been slashed and revoked 
- Currently live with 17 validators

## *June 13, 2018, 4:30 EST* - New Testnet Gaia-6002

- After fixing bugs from gaia-6001, especially [issue
  #1197](https://github.com/cosmos/cosmos-sdk/issues/1197), we are announcing a
  new testnet, Gaia-6002
- Gaia-6002 has the same genesis file as Gaia-6001, just with the chain-id
  updated
- Update from previous testnet [here](https://github.com/cosmos/cosmos-sdk/tree/master/cmd/gaia/testnets#upgrading-from-previous-testnet)

## *June 13, 2018, 4:30 EST* - New Release

- Released gaia
  [v0.19.0](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.19.0)
- Includes various bug-fixes for staking found on Gaia-6001

## *June 13, 2018, 2:30 EST* - Published Postmortem of Gaia-6001 failure

- A bug in the design of the staking data model caused a sanity check to fail
- Full writeup
  [here](https://github.com/cosmos/cosmos-sdk/issues/1197#issuecomment-396823021)

## *June 10, 2018, 8:30 EST* - Gaia-6001 consensus failure

- Validator unbonding and revocation activity caused a consensus failure
- There is a bug in the staking module that must be fixed
- The team is taking its time to look into this and release a fix following a
  proper protocol for hotfix upgrades to the testnet
- Please stay tuned!

## *June 9, 2018, 14:00 EST* - New Release

- Released gaia
  [v0.18.0](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.18.0) with
  update for Tendermint
  [v0.20.0](https://github.com/tendermint/tendermint/releases/tag/v0.20.0)
- Includes bug fix for declaring candidacy from the command line

## *June 8, 2018, 23:30 EST* - Gaia-6001 is making blocks

- +2/3 of the voting power is finally online for Gaia-6001 and it is making
  blocks!
- This is a momentous achievement - a successful asynchronous decentralized
  testnet launch
- Congrats everyone!

## *June 8, 2018, 12:00 EST* - New Testnet Gaia-6001

- After some confusion around testnet deployment and a contention testnet
  hardfork, a new genesis file and network was released for `gaia-6001`

## *June 7, 2018, 9:00 EST* - New Testnet Gaia-6000

- Released a new `genesis.json` file for `gaia-6000`
- Initial validators include those that were most active in
  the gaia-5001 testnet
- Join the network via gaia `v0.18.0-rc0`

## *June 5, 2018, 21:00 EST* - New Release

- Released gaia
  [v0.17.5](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.17.5) 
  with update for Tendermint
  [v0.19.9](https://github.com/tendermint/tendermint/releases/tag/v0.19.9)
- Fixes many bugs!
    - evidence gossipping 
    - mempool deadlock
    - WAL panic
    - memory leak
- Please update to this to put a stop to the rampant invalid evidence gossiping
  :)

## *May 31, 2018, 14:00 EST* - New Release

- Released gaia
  [v0.17.4](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.17.4) with update for Tendermint v0.19.7
- Fixes a WAL bug and some more
- Please update to this if you have trouble restarting a node

## *May 31, 2018, 2:00 EST* - Testnet Halt

- A validator equivocated last week and Evidence is being rampantly gossipped
- Peers that can't process the evidence (either too far behind or too far ahead) are disconnecting from the peers that
  sent it, causing high peer turn-over
- The high peer turn-over may be causing a memory-leak, resulting in some nodes
  crashing and the testnet halting
- We need to fix some issues in the EvidenceReactor to address this and also
  investigate the possible memory-leak

## *May 29, 2018* - New Release

- Released v0.17.3 with update for Tendermint v0.19.6
- Fixes fast-sync bug
- Please update to this to sync with the testnet
