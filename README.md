# truffle-metacoin-example
Truffle 4 MetaCoin example reborn!
```shell
npm install -g truffle
truffle develop
```
## In console...
```shell
truffle(develop)> test
Using network 'develop'.

Compiling ./contracts/ConvertLib.sol...
Compiling ./contracts/MetaCoin.sol...
Compiling ./test/TestMetacoin.sol...
Compiling truffle/Assert.sol...
Compiling truffle/DeployedAddresses.sol...


  TestMetacoin
    ✓ testInitialBalanceUsingDeployedContract (42ms)
    ✓ testInitialBalanceWithNewMetaCoin

  Contract: MetaCoin
    ✓ should put 10000 MetaCoin in the first account
    ✓ should call a function that depends on a linked library (50ms)
    ✓ should send coin correctly (144ms)


  5 passing (617ms)
```