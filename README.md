## week3 - Assignment4 in Metana

Made the base code from openzeppelin wizard

### How to test

1. Deploy `MyERC20` contract (the deployer will get 100 tokens initially) and check the **balance** of the deployer

2. Deploy `MyERC721` contract with `MyERC20` contract's address

3. Approve the address as a spender of the MyERC20 tokens.

4. **mint** token from `MyERC721`

5. Check that the deployer's balance decreased in `MyERC721`
