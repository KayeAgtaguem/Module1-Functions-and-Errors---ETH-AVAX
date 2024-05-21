# ShoeSales Smart Contract

# Overview
The ShoeSales smart contract facilitates the management of a shoe store's inventory and sales operations on the Ethereum blockchain. It allows for restocking inventory, recording shoe sales, and checking the total number of shoes in the store.

# Functions

Constructor:
    Sets the deployer of the contract as the owner of the store.

restock:
    Allows the owner to restock the inventory by a specified quantity, ensuring that the restock quantity is greater than 50.
    Increases the total number of shoes in the inventory.

soldShoe:
    Records the sale of shoes by deducting the sold quantity from the inventory.
    Requires that the quantity of shoes sold is greater than 20 and does not exceed the total number of shoes in the inventory.

TotalShoeInMyStore:
    Allows the contract owner to update the total number of shoes in the store.
    Restricted to the contract owner.
    Enables adjustments to the inventory count.

MyNewTotalShoes:
    A view function that returns the total number of shoes currently in the store without modifying the state of the contract.
    Provides transparency into the current inventory count.

    # Owner
Meta Kaye Agtaguem
