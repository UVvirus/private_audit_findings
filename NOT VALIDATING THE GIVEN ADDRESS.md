# [H-01] NOT VALIDATING THE GIVEN ADDRESS

## Description:
The purpose of the function is to add the given crypto credit card address to the wallet.

## Vulnerability:
Accepts any user-supplied address and not validating that whether the user-supplied input is valid or not.

## Impact:
if the attacker knows the card address of any other user then  he can add the card to his wallet and can use it.
