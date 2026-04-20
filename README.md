# StoreBytes32.sol
StoreBytes32.sol
pragma solidity ^0.8.20;
contract StoreBytes32 {
    bytes32 public data;

    function set(bytes32 _d) public {
        data = _d;
    }
}
