---
hidden: true
---

# 🪄 Builders Wand

## Builders Wand — Player Guide

The Builders Wand helps you create large shapes from blocks in your inventory. Choose a build mode, preview the shape in the world, adjust its size, and print it one block at a time.

### Getting a Builders Wand

Purchase your wand from `/warp titan`.

A new wand starts with **5,000 Uses**. Its lore shows its remaining Uses, first wielder, and lifetime Uses.

### Quick start

1. Hold one **Builders Wand in your main hand**.
2. Hold the block you want to build with, or a water bucket, in your **off hand**.
3. Choose a mode with **Shift + left-click**, or use `/wand form <mode>`.
4. Aim at a surface and **left-click** to anchor the shape.
5. Move your aim to resize the purple preview, then left-click to lock each stage.
6. When the preview is ready, left-click once more to print it.

The action bar tells you what the next click will do. Purple preview blocks are affordable; red preview blocks are not affordable with your current materials or Uses.

### Controls

| Control                 | Action                                                  |
| ----------------------- | ------------------------------------------------------- |
| **Left-click**          | Anchor, lock the current size, or print                 |
| **Shift + left-click**  | Cycle the build mode                                    |
| **Right-click**         | Cancel the current preview                              |
| **Shift + right-click** | Rotate supported blocks such as stairs, logs, and slabs |

Changing modes cancels your current preview. Switching away from the wand, dying, changing worlds, or leaving the server also cancels the preview. Rotation and mode changes are confirmed on the action bar.

### Build modes

* **Box** — hollow boxes, rooms, walls, floors, and ceilings.
* **Diagonal** — diagonal runs useful for stairs, roofs, and slopes.
* **Cylinder** — hollow columns, towers, rings, and tubes.
* **Sphere** — hollow spheres and domes; stretching it creates a capsule.

Large shapes are hollow to keep them practical. The ghost preview shows the exact cells the wand will attempt to build.

### Materials and Uses

| Material              |                      Inventory cost |                   Wand cost |
| --------------------- | ----------------------------------: | --------------------------: |
| Placeable solid block | 1 matching block per completed cell |    1 Use per completed cell |
| Water bucket          |                  Bucket is retained | 3 Uses per completed source |

Keep the selected material in your off hand while creating the preview. The wand draws matching solid blocks from your inventory as it builds. A water bucket acts as a reusable water source and is not emptied or consumed, but it must remain in your off hand until the water print finishes. The wand announces the extra water Use cost when a water print begins.

Cells that are already built are marked as **kept** and do not consume material or Uses. If you run out partway through a print, the completed portion remains and the wand stops before spending anything on the next unaffordable cell.

Doors, beds, shulker boxes, lava buckets, and other unsuitable materials cannot be printed. Water cannot be printed in dimensions where it would immediately evaporate. The wand also respects protected claims and regions.

There is no automatic undo. Mine printed blocks normally if you want to remove or reclaim them.

### Refilling with Denarii

Hold one Builders Wand in your main hand, then request a Use-restoration quote:

* `/wand restore` — quote a refill to the wand's maximum.
* `/wand restore <uses>` — quote a partial refill, such as `/wand restore 500`.
* `/wand restore cancel` — cancel your pending quote.

The standard refill rate is **50 Denarii per Use**, with a **100-Use minimum**. An empty 5,000-Use wand therefore costs 250,000 Denarii to refill completely. Server pricing may change, so the price shown in your refill quote is always authoritative.

Requesting a quote does **not** take money. Review the Uses and price, then click **CONFIRM** in chat or run `/wand restore confirm` within 30 seconds. Changing wands, beginning a print, changing the wand's Uses, or waiting too long invalidates the quote and requires a new one. You cannot request a refill while one of your prints is running.

### Checking your wand

Run `/wand` while holding the wand to see its current mode, Uses, history, selected material, and your building and refill totals.
