# SEMO AUCTION🔺

This is a precompiled scrypt we are using for running our auction.
Based on [this auction article](https://xiaohuiliu.medium.com/auction-on-bitcoin-4ba2b6c18ba7), we made a slight modification to track the highest bidder by `Ripemd160` of the original bidder. Once a higher bid comes in, the refund will be automatically made to the original funder of the previous bid.

To see this auction working, please come check out auctions at [SEMO](https://www.semo3d.com)

## HOW TO CREATE DESCRIPTION FILE

1. `npm install scryptlib`
2. `npx scryptlib download`
3. `npx scryptlib semoAuction.scrypt`

## TODO
 
 * starting time control
 * minimum, maximum, and buyout setting
 * fee calculation

## SPECIAL THANKS

@sCrypt-Inc [sCrypt Team](https://scrypt.io/)



