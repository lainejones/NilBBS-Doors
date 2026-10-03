# NilBBS Doors

Door games for **[NilBBS](https://github.com/lainejones/NilBBS)**, the telnet BBS for AmigaOS. They also run
on **CNet** for the Amiga. Each one comes as an `.lha` with a `FILE_ID.DIZ`, ready for a BBS file area, and
with an installer.

| Door | Version | Kind | What it is |
|---|---|---|---|
| **Dwarfhold Depths** | 1.1 | C program | A dwarf hold under the mountain: the Proving Pits, the Deep Mines, forging, runes, duels, clans, the tavern and a lake under the mountain. |
| **Blades of Grimhold** | 1.1 | C program | A frontier town: the Blood Arena, the Old Keep's ten floors, jousting, gangs, the Mage Tower, homes and burglary. |
| **Sunken Isles** | 1.4 | C program | A pirate captain among eight island ports: trade, chase sails, broadsides and boarding, the law, fleets, treasure maps and the Kraken. |
| **Shadowguild** | 1.0 | C program | Run a thieves' guild: recruit, steal, and raid other guilds. The first King of Thieves wins the season and goes into the Hall of Fame. |
| **Legend of the Ember Wyrm** | 1.0 | C program | The classic forest-and-dragon door: fight in the Ashwood, train with the masters, court at the inn, duel rivals and face the Ember Wyrm. Other Places are ARexx add-ons. |
| **Realm of the Overworld** | 3.5.3 | ARexx script | Fantasy RPG on an 80x50 overworld that reveals as you explore: towns, dungeons, trade, castles to build and raid. Comes with RealmEdit, a map and player editor. |
| **Space Bounty** | 1.0 | ARexx script | TradeWars-style trading across a warp map: star ports, pirates, alien empires, corporations, planets and bounties. |

Download them from the **[Releases](../../releases)** page - one release per door.

## Installing

Unpack the `.lha` and double-click **Install_&lt;Door&gt;**. It asks which BBS the door is for:

- **NilBBS** - point it at your BBS drawer. The door goes into `PFiles/<Door>` and is added to
  `Config/Doors.cfg` (level 10; change its name or level in BBSConfig's Doors page). Doors with a nightly
  maintenance script have it in that entry too, so NilBBS runs it with its own nightly maintenance.
- **CNet** - point it at your `PFILES:` drawer. It copies the door there and tells you what to enter in
  CNet's PFile editor.
- **Somewhere else** - it only copies the drawer; each package's ReadMe explains setting it up by hand.

Run the installer again over an existing door to **update** it: the program, scripts and screens are
replaced, players and saves are kept.

## Requirements

- NilBBS 1.3 or later, or CNet for the Amiga.
- The C doors run on any 68000 or better Amiga. The ARexx doors need ARexx (RexxMast) running, as CNet
  and NilBBS ARexx doors always do.
- Every door is made for several callers at once.

## Also for NilBBS

- **[NilTerm](https://github.com/lainejones/NilTerm)** - an ANSI BBS terminal for the Amiga (telnet, rlogin, modem).

The doors are free to use on your BBS.