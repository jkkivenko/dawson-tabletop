#WIP #weapon #plasma

An electromagnetic launcher which fires globs of plasma big enough to entirely encompass smaller vessels.

## Action: Fire Engulfer

**Requirement: You are operating a Tactical Workstation.**

Cost: `??? credits`
Type: Plasma
Slots: 12

| Power Draw | Accuracy | Damage | Effect |
| -----------|----------|--------|--------|
| 4 | `80%` | `16-24` | Glob (`4`) |
| 5 | `80%` | `20-28` | Glob (`5`) |
| 6 | `80%` | `24-32` | Glob (`6`) |
| 7 | `80%` | `29-37` | Glob (`7`) |
| 8 | `80%` | `33-41` | Engulf |
| 9 | `80%` | `37-45` | Engulf |
| 10 | `80%` | `41-49` | Engulf |
| 11 | `80%` | `45-53` | Engulf |
| 12 | `80%` | `49-57` | Engulf |

### Glob

A shot with Glob leaves a sticky glob of plasma when it impacts a Hull. On a successful hit to the Hull, the target becomes Globbed with a value equal to the Glob value. At the end of a Globbed target's turn, it takes Plasma damage equal to its Globbed value and the Globbed value decreases by 1.

### Engulf

A shot with Engulf has a different effect depending on the Class of the targeted ship.

Effects from Engulf can be ended by clever engineering, including but not limited to: washing the plasma off, dispelling it with a shield pulse, repelling it with a tractor beam, and teleporting it away. GMs and Dawsoneers are encouraged to be creative with this effect!

| Target Class | Effect |
|--------------|--------|
| *Orbit*, *Escape* | On a successful hit to the target's Hull or Shields, the target becomes completely engulfed in searing hot plasma causing it to take 10 plasma damage at the end of each of its turns and gaining Weakness (`1.5`), causing it to take 1.5 times as much damage from all sources, including the plasma damage from Engulf. | 
| *Astro* or *Constellation* | On a successful hit to the target's Hull, the ball of plasma melts a hole clean through armour. The target gains Weakness (`1.5`), causing it to take 1.5 times as much damage from all sources. |
| *Nebula* or *Galaxy* | The same effects as Glob (`10`). |