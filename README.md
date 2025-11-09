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

![Náhled](https://i.imgur.com/oWhaZb6.png)
