# SellGUI

`/sell` opens a native transparent Minecraft dialog listing the sellable items in your inventory.
Click an item, type how many to sell (or sell all of it). **Sell All** on the main list sells everything. Prices are set in `plugins/SellGUI/prices.yml`.

Requires **Paper 1.21.7+** (dialog API), **Java 21**, **Vault** + an economy (EssentialsX).

Sell message: `+$<amount>` (the `$` is bright green).

## Build
GitHub Actions builds the jar on every push: open the **Actions** tab -> latest run -> download the `SellGUI` artifact.
Locally: `mvn package` -> `target/SellGUI.jar`.
