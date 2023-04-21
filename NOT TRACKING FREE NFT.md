# [M-01] NOT TRACKING FREE NFT

## Description:
The protocol has 4 tiers of NFT. If a user buys any 1 NFT from any of the tiers, then they will be eligible for a free mint. 

## Vulnerability:
The minted Nft's are tracked in a mapping, but there is no logic written to mint the free NFT's.

## Impact:
Since there is no logic was implemented for a free mint, Users can't redeem their free NFT, thus the functionality of the protcol is broken.
