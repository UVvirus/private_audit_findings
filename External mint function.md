# [High] External mint function

## Description:
Mint() function was made external leads to unlimited amount of tokens were minted to attackers address.

## Vulnerable code:
```
function mint(address receipient, uint amount) external {
  _mint(receipient, amount);
}
```
