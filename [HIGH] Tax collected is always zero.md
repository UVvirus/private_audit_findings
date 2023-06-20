# [HIGH] Tax collected is always zero

## Description:
A function was implemented to collect fees for the Staking protocol, but the admin didn't receive any fees 

## vulnerability:
 Variable taxCollectedFromUnstake was set to zero, before transferring it to the owner or admin.

## Impact:
taxCollectedFromUnstake is always zero, which means the contract owner is not getting anything(fees).
