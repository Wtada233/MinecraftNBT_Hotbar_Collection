# Minecraft快捷栏 NBT 集合 (Minecraft Hotbar NBT Collection)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/Wtada233/MinecraftNBT_Hotbar_Collection)

这是一个用于存储和管理我的世界（Minecraft）快捷栏布局的集合。

## 文件说明

*   `hotbar.nbt`: 这是 Minecraft 直接使用的标准 NBT（Named Binary Tag）格式文件。你可以将此文件放入你的 Minecraft 存档中来加载其中保存的快捷栏设置。
*   `hotbar.json`: 这是 `hotbar.nbt` 文件的 JSON 表示形式。JSON 格式更易于人类阅读、编辑和进行版本控制。

## 如何使用

1.  **定位你的存档文件夹**:
    *   在 Minecraft 游戏中，进入“选项” > “资源包” > “打开资源包文件夹”。
    *   返回上一级目录（`.minecraft` 文件夹）。
    *   进入 `saves` 文件夹，然后选择你想要应用此快捷栏的存档。

2.  **替换文件**:
    *   **（重要）备份** 你存档文件夹中现有的 `hotbar.nbt` 文件。
    *   将本仓库中的 `hotbar.nbt` 文件复制并替换到你的存档文件夹中。

3.  **加载游戏**:
    *   启动 Minecraft 并加载对应的存档，快捷栏布局将会更新。
