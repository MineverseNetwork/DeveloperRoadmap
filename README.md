# Developer Roadmap [ 20.7.2024 ]
Zde můžete vidět, na čem aktuálně pracuje náš Technický Tým, a co je už hotové.

## Minecraft

### Aktuální Status:

*Právě probíhá přepisování všech pluginů z Javy do Kotlinu. Během tohoto procesu také probíhá velké množství změn v pluginu MV-Lib (přejmenováno na MineCore) pro dosažení vyšší stability, flexibility a udržitelnosti. Dále probíhá přechod z Waterfallu na Velocity.*

**MineCore** (MV-Lib)
- Client pro komunikaci s Rest API [ 100% ]
- Redis systém & komunikační kanály [ 100% ]
- Systém hráčů a ukládání jejich dat [ 100% ]
- Systém serverové ekonomiky [ 40% ]
- Systém pro tvorbu a správu GUI [ 90% ] 
- Systém pro tvorbu a správu příkazů [ 100% ]
- Systém ranků, permisí a prefixů [ 90% ]
- Systém pro status serverů [ 100% ]
- Režim údržby a testování [ 100% ]
- Logger a Verbose systém [ 100% ]

**MV-Velocity**
- Lobby systém [ 100% ]
- Balancování hráčů [ 100% ]
- StaffChat [ 100% ]
- MOTD [ 100% ]

**MV-Lobby**
- Ochrana mapy [ 100% ]
- Výběr serverů [ 100% ]
- Armor standy [ 0% ]
- Parkour (checkpointy, žebříčky) [ 0% ]

**MV-Essentials**
- Počet příkazů: 19

**MV-Survival** - *Brzy rewrite*
- Vlastní itemy [ 20% ]
- Speciální schopnosti [ 15% ]

## Web

**Rest API**
- Veškeré potřebné funkce jsou plně implementovány. Více v případě potřeby.

**Panel**
- Systém přihlašování [ 100% ]
- Správa uživatelů [ 80% ]
- Správa serverů [ 20% ]

**Hlavní Web**
- Úvodní stránka [ 10% ]


## Discord

**Bot**
- Client pro komunikaci s Rest API [ 100% ]
- Redis systém & komunikační kanály [ 100% ]
- Status serveru [ 100% ]
- StaffChat synchronizován s Minecraft servery [ 100% ]
- Ověření a synchronizace účtů [ 15% ]
- Ticket systém [ 5% ]
- Integrace s Loggerem z MineCoru [ 100% ]

# Statistiky

| Plugin | Řádků kódu | Souborů (.java, .kt) | Ke dni |
| ------- | ------- | --------- | ---------------- |
| MV-Lib | 2 850 | 44 | 20.7.2024 |
| MV-Velocity | 600 | 11 | 20.7.2024 |
| MV-Lobby | 300 | 6 | 20.7.2024 |
| MV-Essentials | 1 800 | 28 | 20.7.2024 |
| MV-Survival | 700 | 16 | 20.7.2024 |
| Discord Bot | 450 | 8 | 20.7.2024 |

Celkem: **6 700** řádků kódu a **113** souborů (20.7.2024)

### Ostatní statistiky

Interních Dokumentů: 49 (Mimo vzorové dokumenty)

Grafických Souborů: 14 (Loga, Bannery, Ikony - Mimo ResourcePackovou grafiku)

Hostovaných Služeb: 24

Lidí v týmu: 3
