# Task1
# Ownership logic

When this smart contract is created, the person who deploys it automatically becomes the owner. You can think of the owner as the person who opened the savings account.

This happens inside a  function called the constructor, which runs only once when the contract is deployed. The contract saves the deployer’s wallet address as the owner.

Only the owner is allowed to take money out of the contract. Before allowing a withdrawal, the contract checks whether the person trying to withdraw is the owner. 

If someone else tries to withdraw money, the transaction is stopped.

This simple ownership rule helps keep the funds safe and makes sure only the right person can access them.
