# 🔧 Rozebírání značek

Jednoduchý script pro **rozebírání dopravních značek**.  
Script umožňuje hráčům rozebírat dopravní značky na komponenty pomocí jednoduché interakce s kladivem.

---

## 🧩 Požadavky

Pro správné fungování scriptu potřebujete:

- [ox_lib](https://github.com/overextended/ox_lib)
- Notifikační systém:
  - buď **ESX notify**  
  - nebo **okokNotify**
- Položky zapsané v **ox_inventory**

---

## 📦 Příklad položek v `ox_inventory/data/items.lua`

```lua
["weapon_hammer"] = { 
    label = "Kladivo",
    weight = 500,
    stack = false,
    consume = 0,
},

["komponenty"] = { 
    label = "Komponenty", 
    weight = 4, 
    stack = true,
    close = true,
},

![https://media.discordapp.net/attachments/1399047055829372992/1437056362210267136/Snimek_obrazovky_2025-11-09_130959.png?ex=6911da87&is=69108907&hm=faca15882a68a8dc74527907d2f7ef306351ef3b8d8982fd463ec76003913ef3&=&format=webp&quality=lossless](https://media.discordapp.net/attachments/1399047055829372992/1437056362210267136/Snimek_obrazovky_2025-11-09_130959.png?ex=6911da87&is=69108907&hm=faca15882a68a8dc74527907d2f7ef306351ef3b8d8982fd463ec76003913ef3&=&format=webp&quality=lossless)
