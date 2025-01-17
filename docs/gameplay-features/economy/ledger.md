---
description: Track your in-game transactions effortlessly!
---

# Ledger

The ledger system helps you keep track of all your in-game Denarii transactions. Here's how to use it and understand the data it provides.

## How to Use the Ledger

1. **Generate a Ledger Session:** Use the command `/ledger` in-game to create a new session.
2. **Access the Ledger Link:** After running the command, click the link that appears in the chat to open your personal ledger.
3. **Link Expiration:** Ledger links have expiration times. If your link expires, simply run `/ledger` again to generate a new one.

## Understanding Transaction Causes

Due to limitations in current economy plugins, transaction causes are simplified into the following categories:

- **API**: Transactions triggered by external plugins (e.g., ChestShop, MobArena, or receiving bags of denarii from MobHunter).
- **Unknown**: Transactions triggered by plugins other than Essentials, often as penalties (e.g., fines in MobHunter for killing a wolf).
- **COMMAND_SELL**: Transactions initiated by using the `/sell hand` command.
- **COMMAND_ECO**: Transactions where money is granted directly by the server.
- **HISTORICAL**: Transactions that occurred before the ledger system was implemented.

## Example Visuals

Below are examples of how your ledger data is presented:

### Player Chart

![Example of a player chart](<../.gitbook/assets/image (2).png>)

### Player Transactions

![Example of player transactions](<../.gitbook/assets/image (8).png>)

---

If you encounter any issues or have questions about the ledger, feel free to ask for help in-game or on our Discord!
