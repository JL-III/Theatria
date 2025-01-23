---
description: Learn how to claim land in Theatria using the chunk claiming system.
---

# Land Claiming

Claiming land is an important feature on Theatria, allowing you to secure your builds and resources. Claims are made on a per-chunk basis (16x16 blocks), and you'll need in-game currency to claim land. Here's how to get started:

---

## How to Claim Land

1. Stand in the area you want to claim.
2. Use the command: `/claim`.

**Tip:** Try the command `/claim auto` to automatically claim chunks as you walk around! This is perfect for creating larger claims quickly and easily.

**Important Notes:**
- Claims are limited by [ranks](./ranks/README.md). To increase your claim limit, you can rank up!
- The initial cost per chunk is **$5000**.
- You can earn money through various activities detailed in the [Economy](../economy/README.md) section of the wiki.

---

## Commands

Here’s a list of useful land-related commands:

- **General Commands**
  - `/lands help` – Displays a list of available commands.
  - `/lands map` – Shows a map of your current area.
  - `/lands menu` – Opens the land management menu.

- **Land Management**
  - `/lands create [land name]` – Create a new land.
  - `/lands delete [land name]` – Delete an existing land.
  - `/lands list` – List all lands you own or are a member of.
  - `/lands leave [land name]` – Leave a specific land.

- **Invitations**
  - `/lands invites` – View all your pending invites.
  - `/lands accept [land name]` – Accept an invitation to join a land.
  - `/lands deny [land name]` – Decline an invitation to join a land.

---

## Managing Access with the Lands Menu

The Lands menu is a powerful tool for managing access and permissions within your claimed land. Here’s how to use it:

1. Use `/lands menu` to open the land management menu.
2. Left-click on one of your lands to manage its settings.
3. Left-click on **Roles** (the bell icon) to manage player permissions.

### Default Roles
- **Visitor**: General players on the server who stop by to visit. By default, visitors can enter your land but will be prevented from interacting with items, opening chests, and breaking blocks.
- **Member**: Players who have joined your land. By default, members can place and break blocks, open doors, and more.
- **Admin**: Players you grant extra permissions to.
- **Owner**: By default, this is you, and you have full permissions.

To invite a player to join your land, use the `/trust [player name]` command. You can tailor the roles in each land you create. If you need help, ask in chat or on our Discord!

### Adjusting Role Permissions
1. Click on a role (e.g., Visitor or Member) to open its permissions.
2. You’ll see options to review **Action Flags** and **Management Flags**.

#### Example: Allowing Members to Open Chests
- Click on the **Member** role.
- Select **Action Flags**.
- Look for the **Open Containers** flag.
- Click it to toggle between enabled and disabled.

Other action flags control various permissions, such as:
- Mob spawning
- Water flow
- Block breaking and placing
- Many other actions

Customize these settings to ensure your land is secure while giving trusted players the right level of access.

---

## Special Features for Higher Ranks

Some ranks allow you to create multiple land claims! If your rank supports this, you can create a second land by using the following command:

`/lands create [name]`

For more information about ranks and their benefits, check out the [Ranks](../ranks/README.md) page.

---

[Gameplay Features](./README.md)

