---
{"dg-publish":true,"permalink":"/dungeons-and-dragons/realm-of-aldr/index/locations/aldr/outer-bailey/outer-bailey/"}
---

The **Outer Bailey** is an expansive region of varying geography, from wide, dry plains to dense, spidery [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Outer Bailey/Bleakweald\|forests]]; deep valleys that scrape the underworld to jagged mountains that peak beyond the clouds. Nameless [[Dungeons & Dragons/Realm of Aldr/Index/Species/Tiragardian\|Tiragardian]] ruins dot portions of the landscape—castles, cities, towns, and farms that fell to the [[Dungeons & Dragons/Realm of Aldr/Index/Cosmology/Curse of Night\|Curse of Night]]—few repopulated, but most abandoned due to insufficient defenses and barren farmland. During the day, robbers, traders, and indiscriminate mercenaries alike travel the roads. At night, what ruins suffice are turned into bastions, where travelers desperate for light and shelter become as unpredictable as the monsters they flee from. 

The Outer Bailey is a region with no formal government after the fall of Tiragard. [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Outer Bailey/Guild/Guild\|Guild]], the largest city in the area, exerts little control outside its walls in the form of travelling [[Dungeons & Dragons/Realm of Aldr/Index/Factions/Merchwardens\|Merchwardens]] who seek only to protect their own traders. Bandit factions, delusional nobles, and heinous monsters pose equal threat to travelers as they claw at the scraps of a dead land—or dead men.

To the north, the [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Tiragard/Warded Walls\|Warded Walls]] block entrance into [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Tiragard/Tiragard\|Fallen Tiragard]]—though there exists a [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Outer Bailey/Breach\|breach]] in the stone that allow access into the ancient kingdom. A northwestern valley leads into [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Sarnica\|Sarnican]] lands, contested by soldiers and monsters alike. To the south is the Akridan Desert, and to the east are the [[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Wanderwoods\|Wanderwoods]].
# Notable Locations
---
- **Bleakweald.** Once the grove of a powerful druid, this expansive forest harbors myriad creatures and curses alike; it is afflicted with perpetual night.
- **The Breach.** A section of the Warded Walls that have been sundered—one of the few passages into the old empire. A shanty town has developed at the entrance, funding expeditions and providing trade for those on either side of the wall.
- **[[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Outer Bailey/Earthend\|Earthend]].** A lonely warded settlement that lies in the center of the region. Mutual interest makes this a sanctuary for all factions, though tensions are always high. The inn here is a popular meeting place for travelers, mercenaries, and warlocks.
- **Guild.** A massive, independent city-state that once served as a hub for trade all across the realm. Now fallen to greed, chaos, and plague, it is as dangerous as the lands that surround it.
- **[[Dungeons & Dragons/Realm of Aldr/Index/Locations/Aldr/Outer Bailey/Longkeep/Longkeep\|Longkeep]].** A haunted hovel, and much-needed place of resupply on the path out of Guild. The ruins of an old noble's estate.
- **Westharbor.** A port town that precipitates the march into Sarnican territory. The hometown of [[Dungeons & Dragons/Realm of Aldr/Index/Characters/Player Characters/Edgar, the Wandering Rat\|Edgar, the Wandering Rat]].
# Map
---
```leaflet
### Tutorial: https://youtu.be/54EyMzJP5DU
### id must be unique
id: Outer_Bailey
### Lock pins so they can't be moved
lock: true
### If true, view of map will recenter as you zoom out. 
recenter: true
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work. 
noScrollZoom: true
image: [[Outer_Bailey.png]]
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100) 
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit. 
bounds: [[0,0], [1815.07, 2805.48]]
height: 900px
width: 95%
### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
lat: 907.53
long: 1402.74
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: -1.5
### Max zoom is 18. 
maxZoom: 1.5
### Hover mouse over the Reset Zoom icon to see your current zoom level. 
defaultZoom: -1
### How far it zooms in or out with each step. Can be in decimals. 
zoomDelta: 0.5
### This is a string so can be any text. Change it to match your maps measurement scale. 
unit: miles
scale: 1
darkMode: false
```