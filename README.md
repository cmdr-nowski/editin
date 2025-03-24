(VERY) Dumb script to extract exploration itinerary from ed journal files

Written when I had a sudden need to retrace my exploration steps, after a certain .. incident.

run as `./itin <journals filespec>`, e.g.

```
     ./itin /path/to/journals/Journal.2025*
```

Sample output:

```
jumped to Blau Eur WX-I c10-4, scanned all 2 bodies (2023-12-20T22:38:51Z)
jumped to Blau Eur WI-S d4-40, scanned all 4 bodies (2023-12-20T22:40:10Z)
jumped to Blau Eur QF-S b20-0 (2023-12-20T22:41:30Z)
jumped to Blau Eur WI-S d4-41, scanned all 2 bodies (2023-12-20T22:42:37Z)
jumped to Blau Eur WI-S d4-42, scanned all 12 bodies (2023-12-20T22:43:39Z)
        mapped
                Blau Eur WI-S d4-42 1: High metal content body
                Blau Eur WI-S d4-42 2: High metal content body
jumped to Blau Eur WI-S d4-43, scanned all 13 bodies (2023-12-20T22:50:40Z)
        mapped
                Blau Eur WI-S d4-43 9: Ammonia world
                Blau Eur WI-S d4-43 4: High metal content body
                Blau Eur WI-S d4-43 5: High metal content body
                Blau Eur WI-S d4-43 6: High metal content body
                Blau Eur WI-S d4-43 7: Water world
jumped to Blau Eur WI-S d4-44, scanned all 10 bodies (2023-12-20T23:08:18Z)
        mapped
                Blau Eur WI-S d4-44 1: Water world
                Blau Eur WI-S d4-44 3: Ammonia world
jumped to Blau Eur WI-S d4-45, scanned all 7 bodies (2023-12-20T23:16:01Z)
jumped to Blau Eur NK-S b20-1 (2023-12-20T23:17:53Z)
jumped to Blau Eur WI-S d4-46, scanned all 20 bodies (2023-12-20T23:19:04Z)
        mapped
                Blau Eur WI-S d4-46 B 1: High metal content body
                Blau Eur WI-S d4-46 B 1 a: Rocky body
                Blau Eur WI-S d4-46 B 5: Icy body
                Blau Eur WI-S d4-46 B 6: Icy body
                Blau Eur WI-S d4-46 B 7: Icy body
                Blau Eur WI-S d4-46 A 3: High metal content body
                Blau Eur WI-S d4-46 A 4: High metal content body
        scanned:
                Blau Eur WI-S d4-46 B 1:
                        Stratum Tectonicas - Green
                        Bacterium Aurasus - Teal
                        Tussock Caputus - Emerald
                        Frutexa Metallicum - Grey 
                Blau Eur WI-S d4-46 B 1 a:
                        Bacterium Aurasus - Teal
                        Tussock Ignis - Emerald
                        Tubus Compagibus - Teal 
                Blau Eur WI-S d4-46 B 5:
                        Bacterium Vesicula - Gold
                        Fonticulua Campestris - Amethyst 
                Blau Eur WI-S d4-46 B 6:
                        Fonticulua Lapida - Amethyst
                        Bacterium Informem - Yellow 
                Blau Eur WI-S d4-46 B 7:
                        Bacterium Informem - Gold
                        Fonticulua Lapida - Amethyst 
                Blau Eur WI-S d4-46 A 3:
                        Bacterium Cerbrus - Emerald 
```

