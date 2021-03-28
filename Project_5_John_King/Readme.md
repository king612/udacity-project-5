
Submission Instructions:

Upload to GitHub and submit link:
=================================

https://github.com/king612/udacity-project-5.git



Specify the Truffle version and OpenZeppelin version used in the project.
=========================================================================

➜  ~ truffle -version
Truffle v5.2.4 - a development framework for Ethereum

openzeppelin-solidity@2.1.2


Your ERC-721 Token Name
=======================
Star Token



Your ERC-721 Token Symbol
=========================
STR



Your “Token Address” on the Rinkeby Network
===========================================

2_deploy_contracts.js


   Deploying 'StarNotary'
   ----------------------
   > transaction hash:    0x80707d3940ea164975eb22b9b25f0b3ad595d5c024d375c18caa258e1d53ab08
   > Blocks: 0            Seconds: 12
   > contract address:    0xa88813B621c56191E0e4332a9779EFf7082b484d
   > block number:        8314364
   > block timestamp:     1616948921
   > account:             0xEede6Ae3D910fd9fCAc3A0456ed5008F252689a4
   > balance:             4.97762242
   > gas used:            1965458 (0x1dfd92)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.01965458 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.01965458 ETH



-----------------------------------------------------------------------------------------

All tests pass:

Compiling your contracts...
===========================
> Compiling ./contracts/StarNotary.sol
> Artifacts written to /var/folders/y0/tvy7fkzn0b732ztr5lmb40rw0000gn/T/test--36065-nt4Af8ajhhW6
> Compiled successfully using:
   - solc: 0.5.16+commit.9c3226ce.Emscripten.clang



  ✓ can Create a Star (74ms)
  ✓ lets user1 put up their star for sale (91ms)
  ✓ lets user1 get the funds after the sale (123ms)
  ✓ lets user2 buy a star, if it is put up for sale (166ms)
  ✓ lets user2 buy a star and decreases its balance in ether (121ms)
  ✓ can add the star name and star symbol properly (44ms)
  ✓ lets 2 users exchange stars (149ms)
  ✓ lets a user transfer a star (101ms)
  ✓ lookUptokenIdToStarInfo test (66ms)

  9 passing (939ms)
