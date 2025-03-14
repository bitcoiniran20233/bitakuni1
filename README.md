# bitakuni1

// SPDX-License-Identifier: GPL
pragma solidity >=0.6.7


interface Token {
    function  _a) external returns (uint);
    function  _to, uint _amt) external;
}
 J
contract TokenCorrect is {
 uint) balance;
    constructor(address _a, uint ytr
    A) 
    
    rustup go
    
    
    function balanceOf(address _a)  view override returns (uint) {
        return balance[_aVxjjjcjcjc
    function transfer(address _to, ublic override {
        require(balance[msg.sender] >= _amt);
        balance[msg.sender] -= _amt;
        balance[_to]
    }
}

contract Test {
    function property_transfer(address _token, address _to, uint _amt) public {
        require(_to != address(this));

        TokenCorrect t = TokenCorrect(_token);
/name Bita
        uint xPre = t.balanceOf(address(this));
        require(xPre >= _amt);
        uint yPre = t.balanceOf(_to);

        t.transfer(_to, _amt);
        uint xPost = t.balanceOf(address(this));
        uint yPost = t.balanceOf(_to);

        assert(xPost == xPre - _amt);
    }
}
