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

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jzhr/cap.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
