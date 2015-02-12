Šablóna a príklad na pridanie feature requestu Itemu.
-----------

**Názov:** Padák (Parachute)
- Názov itemu v angličtine a v slovenčine.

**Mapping:** `GOLD_HOE:0;1` 
- Mapovanie tohoto itemu na existujúci item vo formáte `MATERIAL:data;amount`. 
- Konštanty typu materiálu je možné nájšt tu: <https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse/src/main/java/org/bukkit/Material.java> 

**Zriedkavosť:** UNCOMMON
- zriedkavosť (šanca na nájdenie itemu)
- jedna z hodnôt z tabulky:
  - COMMON (Zvyčajné)
  - UNCOMMON (Nezvyčajné)
  - RARE (Zriedkavé)
  - LEGENDARY (Legendárne)

**Kategória:** MISCELLANEOUS 
- kategória itemu podľa tabuľky:
  - CHEMICALS (Chemikálie)
  - FIREARMS (Strelné zbrane)
  - FOOD (Jedlo)
  - DRINKS (Tekutiny - pitné)
  - ELECTRONICS (Elektronické)
  - MISCELLANEOUS (Ostatné, rôzne)

**Popis funkcionality:** Ak hráč klikne pravým tlačidlom myši na blok alebo do vzduchu s padákom v ruke a zároveň sa nachádza
vo vzduchu (padá), tak sa otvorí padák a item sa spotrebuje (item je na jedno použitie). Keď má hráč otvorený padák, padá pomalšie a letí dopredu smerom, 
ktorým sa pozerá. Keď sa dotkne zeme dostane nulový *fall-damage*.
