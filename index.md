## A Personal Ethereum Token
Cap was created for demonstration purposes for Avon High School's Capstone projects.

Based on the ERC20 standard interface, CAP is a fully functional cryptocurrency with transfer ability.

### Smart Contracts

By implementing the functions (shown below) defined by the ERC20 interface, CAP can be called an 'ERC20 Token'. This means that CAP follows the rules that are required to interact with other tokens on the Ethereum network. 

```markdown
    function totalSupply() constant returns (uint256 supply);
    function balanceOf(address _owner) constant returns (uint256 balance);
    function transfer(address _to, uint256 _value) returns (bool success);
    function transferFrom(address _from, address _to, uint256 _value) returns (bool success);
    function approve(address _spender, uint256 _value) returns (bool success);
    function allowance(address _owner, address _spender) constant returns (uint256 remaining);
    event Transfer(address indexed _from, address indexed _to, uint256 _value);
    event Approval(address indexed _owner, address indexed _spender, uint256 _value);
```

### CAP Token Attributes

In the smart contract 'CapToken.sol', I defined CAP to have a total supply 1,000,000 Caps with 0 decimal places.

```markdown
    uint public constant _totalSupply = 1000000;
    string public constant symbol = "CAP";
    string public constant name = "Cap Token";
    uint8 public constant decimals = 0;
```
