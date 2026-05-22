# :construction: This repository is a work in progress.

# Alloy-EVM

## Announcement

The `alloy-op-evm` crate is being moved to [ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism). As part of this change, the `op-evm` crate will be removed from this repository. GitHub contribution history will be preserved.

## Overview

`alloy-evm` is an abstraction layer on top of [revm](https://github.com/bluealloy/revm) providing common implementations of EVMs. Currently, alloy-evm is only used in Reth but is designed to be consumed by any project that needs to execute/trace transactions or blocks on EVM compatible chains.

`alloy-evm` is compatible with no_std and riscv targets.
