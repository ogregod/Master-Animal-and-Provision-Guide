# CERVINE OF WESTERN FAERÛN - IMPLEMENTATION PLAN
## Comprehensive Design Document for Fifth Edition Guide

**PLAN STATUS:** Draft for User Approval
**CREATED:** 2026-01-09
**SCOPE:** Complete deer/venison processing guide with 12 breeds

---

## I. PROJECT OVERVIEW

### Guide Specifications

**Title:** Cervine of Western Faerûn
**Subtitle:** A Comprehensive Professional Guide to Deer Processing
**Edition:** Fifth Edition (following: Provisional 6th, Bovine 6th, Porcine 4th, Ursine 3rd, Butcher 1st)
**Authors:** Thadius Del Irontet (132 years), Helena Fairstock (32 years)
**Published:** 1492 DR, Waterdeep

### Breed Count

**Total Breeds:** 12 (up from original 8-10 proposal)
- **Common Deer:** 5 breeds (CR 0, accessible, 40-400 lbs)
- **Large Game:** 4 breeds (CR 1/4-1/2, elk/moose, 280-1,400 lbs)
- **Exotic:** 2 breeds (CR 0-1/4, rare/magical, 50-150 lbs)
- **Dangerous Trophy:** 1 breed (CR 2, megafauna, 1,800-2,200 lbs)

### File Structure

**Total Files:** 19 files
- 3 Foundation files
- 12 Breed files
- 4 Appendices

**Estimated Total Lines:** ~14,000-16,000 lines (larger than Ursine due to 12 breeds vs 8)

---

## II. THE 12 DEER BREEDS (Detailed Profiles)

### COMMON DEER (5 Breeds) - Part 2

#### 1. SWORD COAST WHITETAIL DEER [BASELINE]

**File:** `02_SWORD_COAST_WHITETAIL.md`

**Role:** Baseline standard for all cervine processing

**Physical Specs:**
- **Live Weight:** 120-180 lbs (male), 90-140 lbs (female)
- **CR:** 0 (25 XP, non-threatening)
- **Antlers:** 6-10 points (male only), 12-18 inch spread
- **Coat:** Reddish-brown summer, grayish-brown winter, white tail underside

**Yield Data (180 lb male, fall condition):**
- **Dressing %:** 65% (117 lbs dressed - DIFFERENT from bear 75%)
- **Retail %:** 45% of dressed (52 lbs retail cuts)
- **Total Yield:** 29% live to retail (52 lbs from 180 lbs)
- **Fat Yield:** Minimal (2-3% body weight = 4-5 lbs) - NOT rendered like bear
- **Hide:** 8-12 lbs, tanned value 8-15 sp
- **Antlers:** 6-point rack = 5-10 sp, 8-point = 12-20 sp, 10-point = 25-40 sp

**Processing Time:** 6-8 hours (smaller/faster than bear)

**Geographic Distribution:**
- Neverwinter Wood (very common)
- Ardeep Forest (common)
- Cloakwood (common)
- Misty Forest (common)
- Everywhere in temperate Sword Coast

**Market Position:**
- **Most common venison** (like black bear for ursine)
- Affordable (15-25 gp total value)
- Reliable availability Sept-Nov

**Unique Features:**
- White tail flag (identification)
- Rutting season Oct-Nov (testosterone = gamey flavor)
- Velvet antler harvest (July-Aug, medicinal value 8-15 sp)

**Baseline Status:** ALL other deer described as variations from this

---

#### 2. HIGH FOREST MULE DEER

**File:** `02_HIGH_FOREST_MULE_DEER.md`

**Role:** Western mountain specialist, larger antlers

**Physical Specs:**
- **Live Weight:** 150-250 lbs (male), 110-170 lbs (female)
- **CR:** 0 (25 XP)
- **Antlers:** Bifurcated (fork into two main beams), 8-12 points, 18-24 inch spread
- **Coat:** Grayish-brown, large mule-like ears (distinctive)

**Yield Data (200 lb male):**
- **Dressed:** 130 lbs (65%)
- **Retail:** 58 lbs (45% of dressed)
- **Total:** 29% live to retail
- **Antlers:** Larger than whitetail (+30% value) = 8-point mule deer = 15-26 sp

**Geographic Distribution:**
- Sword Mountains (common, 4,000-8,000 ft elevation)
- Spine of the World foothills (uncommon)
- High Moor edges (rare)

**Market Position:**
- Premium over whitetail (+15-20%) due to larger size
- Total value: 22-32 gp

**Unique Features:**
- Larger ears (better hearing, mountain predator adaptation)
- Bifurcated antlers (different from whitetail's main beam + tines)
- "Pronking" behavior (bounding jump, distinctive)
- Higher elevation specialist (prefers 3,000-9,000 ft)

---

#### 3. ARDEEP ROE DEER

**File:** `02_ARDEEP_ROE_DEER.md`

**Role:** Smallest common deer, settled forest specialist

**Physical Specs:**
- **Live Weight:** 40-80 lbs (male), 35-65 lbs (female)
- **CR:** 0 (10 XP, timid, flees always)
- **Antlers:** Small, 3-6 points, 8-12 inch spread (spikehorn common)
- **Coat:** Reddish-brown summer, gray winter, white rump patch

**Yield Data (60 lb male):**
- **Dressed:** 39 lbs (65%)
- **Retail:** 17-18 lbs (45% of dressed)
- **Total:** 28-30% live to retail
- **Antlers:** Small value (3-point = 2-5 sp, 6-point = 8-12 sp)

**Geographic Distribution:**
- Ardeep Forest (very common, close to settlements)
- Neverwinter parks (semi-domestic)
- Settled forests near farms (Daggerford, Amphail, Goldenfields edges)

**Market Position:**
- Lowest cost venison (8-15 gp total)
- Individual/family size (whole deer for one household)
- Beginner hunter friendly (timid, easy to track)

**Unique Features:**
- **Smallest natural deer** (vs fawn which is juvenile)
- Gentle, non-aggressive (never attacks)
- Short antlers (shed annually like all deer)
- Barking alarm call (sounds like dog)

---

#### 4. NEVERWINTER FALLOW DEER

**File:** `02_NEVERWINTER_FALLOW_DEER.md`

**Role:** Semi-domestic park deer, spotted coat novelty

**Physical Specs:**
- **Live Weight:** 120-200 lbs (male), 80-130 lbs (female)
- **CR:** 0 (25 XP)
- **Antlers:** Palmate (flattened, shovel-like), 6-10 points, 20-26 inch spread
- **Coat:** **Spotted** (white dots on brown, persists year-round unlike fawn spots)

**Yield Data (160 lb male):**
- **Dressed:** 104 lbs (65%)
- **Retail:** 47 lbs (45%)
- **Total:** 29%
- **Hide:** **Premium spotted pattern** (+40-60% value over standard) = 15-25 sp
- **Antlers:** Palmate racks are decorative = 12-20 sp (6-point), 25-40 sp (10-point)

**Geographic Distribution:**
- Neverwinter noble parks (common, semi-domestic)
- Waterdeep Castle Ward estates (rare, imported)
- Cormyr royal hunting preserves (uncommon)

**Market Position:**
- **Prestige venison** (noble table, distinctive spotted hide)
- Total value: 25-40 gp
- **Hide is primary value** (spotted pattern = decorative rugs, noble cloaks)

**Unique Features:**
- **Only deer with permanent spots** (adults keep fawn-like pattern)
- Semi-domestic (tolerates humans, park animals)
- Palmate antlers (flat, shovel-shaped, unique)
- **Color morphs:** Common (spotted brown), Black (melanistic, rare +50% value), White (leucistic, very rare +100%)

**Cultural Notes:**
- Neverwinter nobles keep herds (status symbol)
- Hunting requires permit/invitation (50-200 gp fee)
- Similar to Cormyrean forest bear (prestige > profit)

---

#### 5. TRIELTA HILLS RED DEER

**File:** `02_TRIELTA_HILLS_RED_DEER.md`

**Role:** Bridge between common deer and elk, medium-large

**Physical Specs:**
- **Live Weight:** 250-400 lbs (male), 180-280 lbs (female)
- **CR:** 0 (50 XP - larger, can be dangerous if cornered)
- **Antlers:** 8-14 points, 28-36 inch spread, heavy mass
- **Coat:** Reddish-brown (summer), gray-brown (winter), cream rump patch

**Yield Data (350 lb male):**
- **Dressed:** 228 lbs (65%)
- **Retail:** 102 lbs (45%)
- **Total:** 29%
- **Antlers:** Large, valuable (8-point = 20-35 sp, 12-point = 50-80 sp, 14-point trophy = 100-150 sp)

**Geographic Distribution:**
- Trielta Hills (very common, 500+ individuals)
- High Forest edges (common)
- Reaching Wood (uncommon)

**Market Position:**
- **Largest "common" deer** (overlaps with small elk)
- Premium venison (35-60 gp total)
- Trophy potential (mature stags compete with elk racks)

**Unique Features:**
- **Bugling call during rut** (sounds like elk, loud echoing)
- Aggressive during rut (will charge hunters, CR 0 but dangerous)
- Large herds (20-40 individuals, social)
- **Stag vs Hind terminology** (males = stags, females = hinds, not buck/doe)

**Processing Notes:**
- Larger size = elk-like processing time (8-12 hours)
- **Stag in rut = poor meat quality** (testosterone, stress, -20-30% value)
- **Post-rut stag = excellent** (fat reserves, tender)

---

### LARGE GAME (4 Breeds) - Part 3

#### 6. HIGH MOOR WAPITI (ELK)

**File:** `03_HIGH_MOOR_WAPITI.md`

**Role:** Classic elk, massive herds, premium venison

**Physical Specs:**
- **Live Weight:** 600-900 lbs (male), 450-600 lbs (female)
- **CR:** 1/4 (50 XP - large, can defend itself)
- **Antlers:** 10-14 points (mature), 40-60 inch spread, **massive weight** (30-40 lbs)
- **Coat:** Dark brown neck/head, tan body, large cream rump patch

**Yield Data (750 lb male):**
- **Dressed:** 488 lbs (65%)
- **Retail:** 220 lbs (45%)
- **Total:** 29%
- **Antlers:** **PREMIUM TROPHIES** (6-point = 40-70 sp, 10-point = 100-180 sp, 12-point trophy = 250-450 sp)
- **Elk Hide:** Large (40-60 lbs), thick, valuable for armor = 35-60 sp

**Processing Time:** 12-16 hours (large animal, like brown bear)

**Geographic Distribution:**
- High Moor (very common, 2,000+ individuals, massive herds)
- Evermoors (common, 500-800 individuals)
- Delimbiyr Vale (uncommon)
- High Forest (rare, southern range limit)

**Market Position:**
- **Premium wild game venison** (60-120 gp total value)
- Trophy antler market (10-point+ racks = major value)
- Herd hunting (can harvest 3-5 elk per expedition)

**Unique Features:**
- **Bugling call** (loud, echoing, 1-2 mile range, rut communication)
- **Massive herds** (50-200 individuals, bulls/cows/calves)
- **Harem behavior** (1 bull controls 15-30 cows during rut)
- **Aggressive rut** (bulls spar, dangerous to approach)

**Hunting Strategy:**
- **Herd culling** (harvest multiple animals to justify expedition cost)
- **Cow elk** (no antlers, but better meat quality year-round = practical choice)
- **Trophy bulls** (rut season, antlers = 50-70% of value, accept lower meat quality)

**Economics:**
- Expedition costs: 40-60 gp (High Moor = remote, 5-7 day trek from Waterdeep)
- Harvest 3 elk minimum to break even
- Trophy bull alone = 100-120 gp (if 12-point rack)

---

#### 7. EVERMOOR MOOSE

**File:** `03_EVERMOOR_MOOSE.md`

**Role:** Largest deer, solitary, dangerous if provoked

**Physical Specs:**
- **Live Weight:** 900-1,400 lbs (male), 700-900 lbs (female)
- **CR:** 1/2 (100 XP - **DANGEROUS**, will charge if threatened)
- **Antlers:** **Palmate** (massive flat paddles), 10-16 points, **50-70 inch spread**, 50-70 lbs weight
- **Coat:** Dark brown to black, long legs, shoulder hump, dewlap (throat flap)

**Yield Data (1,200 lb male):**
- **Dressed:** 780 lbs (65%)
- **Retail:** 351 lbs (45%)
- **Total:** 29%
- **Antlers:** **MASSIVE TROPHIES** (10-point = 150-250 sp, 14-point = 400-600 sp, 16-point record = 800-1,200 sp)
- **Moose Hide:** Extremely thick (60-90 lbs), **armor-grade** (AC bonus like cave bear) = 80-120 sp

**Processing Time:** 16-22 hours (massive size, like grizzly bear)

**Geographic Distribution:**
- Evermoors (common, solitary, 300-500 individuals)
- Lurkwood (common)
- Northern High Forest (uncommon)
- Cold Wood (rare)

**Market Position:**
- **Largest venison source** (100-180 gp total value)
- **Dangerous game** (requires party, CR 1/2 can kill solo hunter)
- **Trophy focus** (antlers alone = 80-140 gp for mature bull)

**Unique Features:**
- **Solitary** (not herds, lone bulls, cows + calves only)
- **Aggressive when provoked** (will charge, can kill horses/people)
- **Rut season danger** (Sept-Oct, bulls are EXTREMELY aggressive, CR effectively 1)
- **Massive size** (shoulder height 6-7 feet, towering over hunters)
- **Aquatic feeder** (swims, eats water plants, different habitat from other deer)

**Combat Stats:**
- **Charge:** +6 to hit, 3d8+4 bludgeoning damage (can one-shot level 1-2 characters)
- **Antler gore:** +6 to hit, 2d10+4 piercing damage
- **Trampling:** Knocks prone, can stomp prone targets

**Hunting Warnings:**
- **DO NOT hunt bulls during rut alone** (CR 1 effective, deadly)
- **Cows are safer** (CR 1/4, less aggressive, no trophy but better meat)
- **Requires party of 3+ level 3 characters** (dangerous game)
- **Wounded moose = rampage** (will chase and trample)

**Professional Quote:**
*"Moose hunting is not deer hunting. It's dangerous game hunting. A bull moose in rut will charge a grizzly bear. Respect it or die."*
**— Thadius Del Irontet**

---

#### 8. ICEWIND DALE CARIBOU

**File:** `03_ICEWIND_DALE_CARIBOU.md`

**Role:** Northern migratory herds, survival staple

**Physical Specs:**
- **Live Weight:** 280-450 lbs (male), 180-300 lbs (female)
- **CR:** 0 (25 XP, herd animals, flee)
- **Antlers:** **Both sexes have antlers** (unique among deer), 8-12 points, 30-45 inch spread
- **Coat:** Thick double coat, gray-brown, white neck/rump, **hollow hair** (insulation)

**Yield Data (350 lb male):**
- **Dressed:** 228 lbs (65%)
- **Retail:** 102 lbs (45%)
- **Total:** 29%
- **Antlers:** Moderate (8-point = 15-25 sp, 12-point = 35-50 sp)
- **Hide:** **Premium cold-resistant** (hollow hair = exceptional insulation) = 25-40 sp
- **Caribou Hide Use:** Winter cloaks, cold-weather gear (Icewind Dale staple)

**Processing Time:** 8-12 hours

**Geographic Distribution:**
- **Icewind Dale** (very common, 5,000-10,000 individuals, massive migratory herds)
- Spine of the World (migration route)
- Icewind Pass (migration corridor)

**Market Position:**
- **Icewind Dale survival staple** (primary meat source for Ten-Towns)
- Total value: 40-70 gp
- **Hide is critical** (cold resistance, high demand in arctic)

**Unique Features:**
- **Migration herds** (thousands of individuals, seasonal movement)
- **Both sexes antlered** (cows use antlers to dig through snow for food)
- **Hollow hair coat** (flotation, insulation, unique to caribou)
- **Clicking tendons** (audible clicking when walking, herd location sound)
- **Lichen diet** (tundra specialist, slow-growing food source)

**Cultural Significance:**
- **Reghed Barbarian tribes:** Caribou = primary food source (sacred animal)
- **Ten-Towns economy:** Caribou meat = winter survival
- **Migration timing:** Critical for fall harvest (Eleint-Marpenoth, herds pass through)

**Hunting Strategy:**
- **Herd culling** (can harvest 5-10 caribou in single migration day)
- **Reghed quotas:** Respect tribal hunting grounds (avoid conflict)
- **Fresh vs preserved:** Most meat smoked/dried (winter storage essential)

**Economics:**
- Migration harvest = zero expedition cost (caribou come to you)
- Hides shipped to Luskan = 30-50 sp each (cold-weather gear market)
- Smoked caribou = winter staple (25-40% price premium Dec-Feb)

---

#### 9. MOONSHAE ISLAND ELK

**File:** `03_MOONSHAE_ISLAND_ELK.md`

**Role:** Island-adapted elk, Northlander culture

**Physical Specs:**
- **Live Weight:** 500-700 lbs (male), 400-550 lbs (female)
- **CR:** 1/4 (50 XP)
- **Antlers:** 8-12 points, 35-50 inch spread (smaller than High Moor wapiti)
- **Coat:** Dark brown, stockier build (island dwarfism)

**Yield Data (600 lb male):**
- **Dressed:** 390 lbs (65%)
- **Retail:** 175 lbs (45%)
- **Total:** 29%
- **Antlers:** 8-point = 35-60 sp, 12-point = 90-140 sp

**Processing Time:** 10-14 hours

**Geographic Distribution:**
- **Gwynneth** (common, 400-600 individuals)
- **Alaron** (uncommon)
- Moray (rare)

**Market Position:**
- Island specialty (45-80 gp total)
- **Northlander cultural hunt** (tribal permissions required)
- Export to Waterdeep (+30-50% premium for "island elk")

**Unique Features:**
- **Island dwarfism** (20-25% smaller than mainland wapiti)
- **Stockier build** (adapted to coastal weather, wind resistance)
- **Northlander sacred animal** (tribal hunting rites, permissions required)
- **Maritime climate adaptation** (wetter habitat, different diet)

**Cultural Notes:**
- Fffolk and Northlander tribes regulate hunting
- Outsider hunting requires tribal guide (20-40 gp fee)
- **Harvest limits:** 1-2 elk per outsider (population management)
- Tribal quotas enforce sustainability

**Economics:**
- **Expedition cost:** 30-50 gp (ship passage to Moonshae, 3-5 days)
- **Processing on-island:** Fresh sale to Caer Callidyrr market (low prices, oversupply)
- **Shipping to Waterdeep:** Smoked/preserved only (20-30 sp freight), premium pricing

---

### EXOTIC (2 Breeds) - Part 4

#### 10. FEYWILD MOONLIT DEER

**File:** `04_FEYWILD_MOONLIT_DEER.md`

**Role:** Fey-touched magical, glowing antlers, rare

**Physical Specs:**
- **Live Weight:** 100-150 lbs (ethereal, lighter than material deer)
- **CR:** 1/4 (50 XP - magical defenses, fey nature)
- **Antlers:** **Bioluminescent** (soft blue-white glow at night), 6-10 points, 14-20 inch spread
- **Coat:** Silvery-white to pale blue, **shimmers in moonlight**, faint ethereal glow

**Yield Data (120 lb deer):**
- **Dressed:** 78 lbs (65%)
- **Retail:** 35 lbs (45%)
- **Total:** 29%
- **Antlers (MAGICAL):** **30-80 gp EACH** (alchemical reagent, fey magic, enchantment component)
  - **Velvet antlers (harvested in Feywild):** 50-120 gp (fey potion ingredient)
- **Hide:** Shimmering pelt = 40-80 gp (magical properties, decorative, fey charm)
- **Meat:** **Fey-touched flavor** (+50-100% premium over standard venison)

**Processing Time:** 6-8 hours

**Geographic Distribution:**
- **Feywild crossings** (rare, ephemeral, unpredictable)
- **Misty Forest** (fey portals, uncommon sightings)
- **Ardeep Forest** (occasional, moonlit glades)
- **Myth Drannor ruins** (rare, ancient fey magic)

**Market Position:**
- **Extremely rare** (1-10 harvested per year across all Western Faerûn)
- **Total value:** 80-200 gp (antlers alone = majority of value)
- **Alchemical premium:** Wizards/alchemists pay 2-3x retail for antlers

**Unique Features:**
- **Fey Nature:** Immune to charm, fey magic resistance
- **Moonlight glow:** Antlers glow at night (trackable, beautiful, cursed)
- **Ethereal step:** Can briefly phase into Ethereal Plane (escape hunters)
- **Timeless meat:** Venison doesn't spoil for 30 days (fey preservation)
- **Dream visions:** Consuming meat may grant prophetic dreams (DM option)

**Hunting Difficulty:**
- **Requires magic weapons or silvered weapons** to harm reliably
- **Fey cunning:** Intelligence 10 (vs normal deer Int 2), can outwit hunters
- **Portal escape:** If near fey crossing, may flee into Feywild
- **Curse risk:** Killing fey deer near sacred glade may anger fey lords (GM discretion)

**Alchemical Uses (Antlers):**
- **Enchantment potions** (charm, illusion magic)
- **Fey crossing reagent** (plane shift rituals)
- **Dream magic** (divination, sleep spells)
- **Moonlight elixirs** (darkvision, night magic)

**Cultural Notes:**
- **Elven taboo:** Many elves refuse to hunt fey deer (sacred to Corellon)
- **Human hunters:** Prize trophies, no cultural restriction
- **Fey courts:** May send agents to recover slain fey deer (avoid angering Feywild)

**Professional Warning:**
*"Beautiful, valuable, and potentially cursed. Know which fey court claims the glade before you shoot. A 200 gold deer isn't worth a pixie curse or satyr vendetta."*
**— Helena Fairstock**

---

#### 11. CHULTAN PYGMY ANTELOPE

**File:** `04_CHULTAN_PYGMY_ANTELOPE.md`

**Role:** Tropical exotic import, smallest, curiosity

**Physical Specs:**
- **Live Weight:** 50-90 lbs (male), 40-70 lbs (female)
- **CR:** 0 (10 XP, timid, no threat)
- **Horns:** **NOT antlers** (permanent, never shed, 4-8 inch straight spikes)
- **Coat:** Reddish-brown with white stripes (distinctive tropical pattern)

**Yield Data (70 lb male):**
- **Dressed:** 45 lbs (65%)
- **Retail:** 20 lbs (45%)
- **Total:** 29%
- **Horns:** Exotic curiosity = 5-12 sp (decorative only, no antler market comparison)
- **Hide:** Striped pattern = 8-15 sp (decorative, novelty)

**Processing Time:** 4-6 hours (smallest, like Chultan sun bear)

**Geographic Distribution:**
- **Chult jungles** (common in native habitat)
- **Western Faerûn:** **EXTREMELY RARE** (imported, escaped exotics only)
- **Wizard estates:** Occasionally kept as exotic pets (rare escapes)

**Market Position:**
- **DO NOT IMPORT** (like Chultan sun bear - economics don't work)
- **Import cost:** 180-280 gp (ship passage, containment, risk)
- **Revenue:** 15-30 gp (total animal value)
- **Net:** -150 to -265 gp LOSS
- **Only process if:** Found in Western Faerûn already (escaped exotic, wizard estate)

**Unique Features:**
- **Horns, not antlers** (permanent, like cattle, different from deer)
- **Tropical specialist** (heat-adapted, suffers in temperate/cold climates)
- **Striped coat** (camouflage in jungle, distinctive in Faerûn)
- **Smallest cervid** (technically not in Cervidae family, but grouped with deer for guide purposes)

**Exotic Meat Premium:**
- **Waterdeep novelty buyers:** +80-120% premium (exotic cuisine, rare)
- **Chultan expat community:** Nostalgia premium (pay 2-3x for homeland flavors)
- **Wizard cuisine:** Exotic component dinners (prestige, not profit)

**Cultural Notes:**
- Chultan natives don't export these (too common in Chult, no value)
- **Western Faerûn imports:** Failed experiment (economics terrible)
- **Surviving populations:** Wizard estates only (contained, not wild)

**Professional Quote:**
*"If you find a Chultan antelope in Western Faerûn, it's either escaped from a wizard's menagerie or someone's very expensive failed import. Process it, sell the exotic meat for novelty pricing, and move on. Never import one yourself."*
**— Thadius Del Irontet**

---

### DANGEROUS TROPHY (1 Breed) - Part 5

#### 12. GIANT ELK OF THE FAR NORTH

**File:** `05_GIANT_ELK.md`

**Role:** Megafauna, CR 2, legendary trophies, apex deer

**Physical Specs:**
- **Live Weight:** 1,800-2,200 lbs (male), 1,200-1,600 lbs (female)
- **CR:** 2 (450 XP - **DEADLY**, requires experienced party)
- **Antlers:** **LEGENDARY** (14-18 points, 70-90 inch spread, 80-120 lbs weight)
- **Coat:** Dark brown to black, massive shoulder hump, cream rump patch

**Yield Data (2,000 lb male):**
- **Dressed:** 1,300 lbs (65%)
- **Retail:** 585 lbs (45%)
- **Total:** 29%
- **Antlers:** **EXTREME VALUE** (14-point = 600-900 sp, 16-point = 1,000-1,500 sp, 18-point record = 1,800-2,500 sp / **180-250 gp**)
- **Hide:** Massive (80-120 lbs), thick, armor-grade = 100-180 sp

**Processing Time:** 18-24 hours (largest deer, longer than grizzly)

**Geographic Distribution:**
- **Spine of the World** (rare, alpine meadows, 8,000-12,000 ft)
- **Icewind Dale tundra** (very rare, isolated individuals)
- **Lurkwood (northern reaches)** (extremely rare)

**Total Population:** ~50-100 individuals across all Western Faerûn (endangered, legendary)

**Market Position:**
- **Legendary trophy hunt** (150-300 gp total value)
- **Antlers = 60-80% of value** (trophy focus, not meat focus)
- **Prestige > Profit** (hunt for glory, not economics)

**Unique Features:**
- **Megafauna size** (rivals horses, can carry riders - though never domesticated)
- **Aggressive territorial bulls** (will charge threats, not flight animals)
- **Massive antlers** (largest of any deer, world-record trophy potential)
- **Rare sightings** (1-2 per year reported across Western Faerûn)
- **Legendary status** (hunters tell stories, exaggerate size)

**Combat Stats (D&D 5e):**
- **AC:** 14 (thick hide, size)
- **HP:** 42 (5d12+15)
- **Speed:** 60 ft. (fast despite size)
- **STR:** 19 (+4), **CON:** 16 (+3)

**Actions:**
- **Charge:** If moves 20 ft+ then hits with ram, target DC 14 STR save or knocked prone. If prone, trampling attack as bonus action.
- **Ram:** +6 to hit, 2d8+4 bludgeoning damage
- **Antler Gore:** +6 to hit, 3d10+4 piercing damage (deadly)
- **Trampling Hooves:** +6 to hit, 2d10+4 bludgeoning (vs prone targets)

**Hunting Difficulty:**
- **Party of 4-6, level 4+ required** (CR 2 can kill level 3 characters easily)
- **Bull in rut = CR 3 effective** (aggressive, territorial, will seek combat)
- **Wounded giant elk = rampage** (will chase party, deadly)

**Expedition Economics:**
- **Expedition cost:** 100-180 gp (Spine of the World, 10-14 days, guides, supplies, danger)
- **Trophy bull revenue:** 250-350 gp (if record antlers)
- **Net profit:** 70-170 gp (marginal after expedition)
- **Prestige value:** Priceless (social capital, bragging rights, legendary status)

**Trophy Mount:**
- **Shoulder mount:** 400-700 gp (commissioned)
- **Full body mount:** 800-1,200 gp (commissioned, centerpiece)
- **Antler rack only:** 150-300 gp (European mount, skull + antlers)

**Cultural Significance:**
- **Northern Barbarian rite of passage:** Kill giant elk = become chieftain candidate
- **Noble hunting:** Prestige hunt (Cormyrean/Waterdhavian nobles commission expeditions)
- **Bardic tales:** Legendary hunts become songs (social immortality)

**Professional Quote:**
*"Giant elk are the grizzly bears of the deer world. Deadly, rare, legendary. Hunt with a full party, expect a week-long expedition, and understand you're hunting for glory, not gold. The 18-point rack on your wall is worth more than the 200 gold you spent getting it - but only to you and the bards who sing about it."*
**— Thadius Del Irontet, 132 years experience**

---

## III. FILE STRUCTURE & ORGANIZATION

### Foundation Files (3 files)

1. **`00_FRONT_MATTER.md`**
   - Title, authors, edition (Fifth Edition)
   - About this guide (what makes cervine unique)
   - What's NOT covered (brief warnings: dire stags, were-creatures, peryton - DO NOT PROCESS)
   - How to use (for DMs, players, skill references)
   - Integration with foundation guides
   - Estimated lines: 400-500

2. **`01_REGIONAL_OVERVIEW.md`**
   - Regional deer distribution (where each breed is found)
   - Market hubs (Waterdeep, Neverwinter, Baldur's Gate venison markets)
   - Seasonal availability (rut season, migration timing)
   - Transport logistics (fresh venison = perishable, preserved = flexible)
   - Estimated lines: 500-600

3. **`01_UNIVERSAL_CERVINE_CUTS.md`**
   - Deer anatomy (different from bear/cattle)
   - **7 cervine primals** (vs 8 ursine, 9 bovine - deer have less fat/variety)
   - Yield formula: 65% dressing, 45% retail (29% total - LEAN vs 37% bear)
   - Backstrap, ham, shoulder, ribs, neck, shank, trim
   - **No fat rendering** (2-3% body fat, not economical like bear's 8-10%)
   - Butcher's choice options (steaks vs roasts)
   - Field dressing procedure (wilderness processing)
   - Estimated lines: 700-800

### Breed Files (12 files)

**Part 2: Common Deer (5 files, numbered 02_)**
- `02_SWORD_COAST_WHITETAIL.md` [BASELINE] - 1,000-1,200 lines (like black bear baseline)
- `02_HIGH_FOREST_MULE_DEER.md` - 700-800 lines
- `02_ARDEEP_ROE_DEER.md` - 650-750 lines
- `02_NEVERWINTER_FALLOW_DEER.md` - 700-800 lines (spotted hide premium)
- `02_TRIELTA_HILLS_RED_DEER.md` - 750-850 lines (bridge to elk)

**Part 3: Large Game (4 files, numbered 03_)**
- `03_HIGH_MOOR_WAPITI.md` - 800-900 lines (classic elk)
- `03_EVERMOOR_MOOSE.md` - 850-950 lines (dangerous game emphasis)
- `03_ICEWIND_DALE_CARIBOU.md` - 750-850 lines (cultural significance)
- `03_MOONSHAE_ISLAND_ELK.md` - 700-800 lines (island specialty)

**Part 4: Exotic (2 files, numbered 04_)**
- `04_FEYWILD_MOONLIT_DEER.md` - 750-850 lines (magical, expensive)
- `04_CHULTAN_PYGMY_ANTELOPE.md` - 700-800 lines (DO NOT IMPORT warning)

**Part 5: Dangerous Trophy (1 file, numbered 05_)**
- `05_GIANT_ELK.md` - 700-800 lines (apex, legendary)

**Total Breed Lines:** ~9,500-11,000 lines

### Appendix Files (4 files)

1. **`APPENDIX_A_BREED_COMPARISON.md`**
   - Quick reference tables (all 12 breeds)
   - Size/weight comparison
   - Combat/danger comparison (CR ratings)
   - Retail yield comparison
   - Total value comparison
   - Antler trophy comparison (point system)
   - Risk vs reward analysis
   - Estimated lines: 400-500

2. **`APPENDIX_B_CUTS_AND_PRICES.md`**
   - Complete Foundry VTT item list (all 12 breeds)
   - Exact item counts, weights, pricing
   - Seasonal pricing modifiers (rut impact, winter scarcity)
   - Market-specific pricing (Waterdeep, Icewind Dale, Moonshae, etc.)
   - Venison preservation pricing (smoked, jerky, summer sausage)
   - Estimated lines: 1,400-1,600

3. **`APPENDIX_C_ANTLER_TROPHY_MASTERY.md`** ← **DEEP DIVE (30+ pages)**
   - **Complete antler trophy system** (like bear fat rendering got 30 pages)
   - **Antler growth cycle:** Velvet → hardened → shed (timing, biology)
   - **Point scoring system:** Boone & Crockett adapted for Faerûn
   - **Velvet antler harvest:** Timing (July-Aug), medicinal/alchemical value, cutting technique
   - **Hardened antler processing:** Skull cap removal, European mount, pedestal mount
   - **Trophy mounting techniques:** DIY vs professional taxidermist
   - **Antler shed collection:** Spring foraging (no hunting required), value
   - **Market pricing by rack quality:** Symmetry, spread, mass, points
   - **Age estimation:** Antler size vs deer age (yearling spike vs mature 10-point)
   - **Velvet alchemical uses:** Healing potions, virility elixirs, traditional medicine
   - **Regional trophy standards:** What's trophy-class in Waterdeep vs Icewind Dale
   - **Trophy mount costs:** Shoulder mount, European mount, full body (commissioned pricing)
   - Estimated lines: 1,600-1,800

4. **`APPENDIX_D_FOUNDATION_CROSS_REFERENCE.md`**
   - Integration index (Master Butcher's, Master Provisioner's, Bovine, Porcine, Ursine)
   - 60+ § references to foundation sections
   - Topic-based lookup (venison preservation, trophy prep, lean meat processing)
   - Reverse index (by cervine file)
   - Estimated lines: 700-800

**Total Appendix Lines:** ~4,100-4,700 lines

---

**TOTAL FILE COUNT:** 19 files (3 foundation + 12 breeds + 4 appendices)
**TOTAL ESTIMATED LINES:** ~14,500-16,800 lines

---

## IV. UNIQUE CERVINE MECHANICS

### 1. Antler System (THE signature cervine feature)

**Antler Growth Cycle (Annual):**
- **Spring (March-May):** Antlers shed, new growth begins
- **Summer (June-Aug):** Velvet growth (soft, blood-filled, medicinal value)
- **Late Summer (Aug-Sept):** Velvet shedding, antlers harden
- **Fall-Winter (Sept-Feb):** Hardened antlers (rut, fighting, display)
- **Spring (March):** Shedding cycle repeats

**Velvet Antler Harvest:**
- **Timing:** July-August (peak velvet, before hardening)
- **Method:** Requires live deer (farmed fallow deer) OR freshly killed (within 12 hours)
- **Yield:** 2-6 lbs velvet per deer (depending on size)
- **Alchemical Value:**
  - Whitetail velvet: 8-15 sp per lb
  - Elk velvet: 20-35 sp per lb
  - Fey deer velvet: 50-120 gp per lb (magical)
- **Uses:** Healing potions, virility elixirs, athletic enhancement, traditional medicine

**Hardened Antler Trophy System:**
- **Point Scoring:** Faerûn Boone & Crockett adaptation
  - Count all points 1 inch or longer
  - Measure inside spread (tip to tip)
  - Measure main beam length
  - Measure circumference at 4 points
  - **Symmetry bonus:** Matched points = +20% value
- **Trophy Classes:**
  - **Whitetail:** 6-point (common), 8-point (good), 10-point (trophy), 12+ point (record)
  - **Elk:** 8-point (common), 10-point (good), 12-point (trophy), 14+ point (record)
  - **Moose:** 10-point (common), 14-point (trophy), 16+ point (record)
  - **Giant Elk:** 14-point (minimum), 16-point (trophy), 18+ point (legendary)

**Antler Shedding Collection:**
- **Timing:** Ches-Tarsakh (antlers naturally fall off)
- **Foraging:** Search forest floors, no hunting required
- **Value:** 40-60% of attached antler value (no skull, standalone)
- **Decoration:** Chandelier antlers, knife handles, buttons, dog chews

### 2. Rut Season Variation (Different from bear hibernation)

**Rut Timing:**
- **Whitetail/Mule/Roe:** Marpenoth-Uktar (peak breeding)
- **Red Deer/Elk:** Eleint-Marpenoth (earlier, bugling season)
- **Moose:** Eleint-Marpenoth (DANGEROUS, aggressive bulls)
- **Caribou:** Marpenoth (brief, synchronized)

**Rut Impact on Meat Quality:**
- **Bulls/Bucks in rut:** -20-30% meat value (testosterone, stress, gamey flavor, tough)
- **Cows/Does:** No rut impact (stable quality year-round)
- **Post-rut bulls:** Best quality (fattened, relaxed, tender)

**Rut Impact on Behavior:**
- **Aggressive:** Bulls challenge hunters, dangerous
- **Distracted:** Bulls focus on cows, easier to approach (calling/rattling)
- **Vocal:** Bugling (elk), grunting (whitetail), bellowing (moose) = location cues

**Optimal Hunting Windows:**
- **Trophy antlers:** Peak rut (Marpenoth-Uktar), accept poor meat quality
- **Meat quality:** Post-rut (Nightal-Hammer) OR pre-rut (Eleasis-Eleint), smaller antlers
- **Balance:** Early rut (Eleint-early Marpenoth), moderate antlers + decent meat

### 3. Age Class System (Different from bear seasonal variation)

**Fawn (0-1 year):**
- **Weight:** 40-80 lbs (species dependent)
- **Antlers:** None (males grow first spikes at 1 year)
- **Meat:** Tender, mild, but low yield (not economical to hunt)
- **Legal:** Often protected (harvest limits, ethical concerns)

**Yearling (1-2 years):**
- **Weight:** 60-70% of adult
- **Antlers:** Spikes or small 4-6 point racks
- **Meat:** Good quality, tender
- **Trophy Value:** Low (immature antlers)
- **Hunting Strategy:** Meat hunters target these (no trophy, but tender)

**Mature (3-7 years):**
- **Weight:** Full adult size
- **Antlers:** Peak size (8-14 points depending on species)
- **Meat:** Excellent (well-marbled, flavorful, not tough)
- **Trophy Value:** High (mature racks)
- **Hunting Strategy:** Trophy hunters target these (prime age)

**Old (8+ years):**
- **Weight:** Full size, possibly declining
- **Antlers:** Large but often asymmetrical (broken points, disease)
- **Meat:** Tough, gamey, poor quality
- **Trophy Value:** Variable (large but flawed racks)
- **Hunting Strategy:** Cull these (population management, poor genetics)

**Age Estimation in Field:**
- **Tooth wear:** Check premolars (worn = old)
- **Body size:** Mature deer have thick necks, deep chests
- **Antler mass:** Heavy, thick beams = mature
- **Behavior:** Dominant, confident = mature

### 4. Lean Meat Processing (Different from fatty bear/pork)

**Fat Content Comparison:**
- **Bear:** 8-10% body fat (fall), renders to valuable grease
- **Pork:** 15-25% fat (domestic), fat cap on cuts
- **Cattle:** 5-15% marbling (domestic, breeds vary)
- **Deer:** **2-3% body fat** (wild herbivore, minimal fat)

**Processing Implications:**
- **No fat rendering:** Not economical (2-3 lbs fat from 180 lb deer = 4-6 sp vs 12 hours labor)
- **Dry aging required:** Lean meat needs enzymatic tenderizing (7-14 days hanging)
- **Moisture loss:** Lean meat dries out if overcooked (rare-medium rare optimal)
- **Preservation challenge:** Low fat = dries well for jerky, but smoked meat can be dry

**Venison-Specific Techniques:**
- **Backstrap/tenderloin:** NEVER overcook (medium-rare only, 135-145°F)
- **Roasts:** Low/slow braising (moisture retention)
- **Ground venison:** Add pork/beef fat (15-20%) for burgers/sausages
- **Jerky:** Ideal (lean = perfect drying, no rancid fat)
- **Smoking:** Brine required (moisture retention), shorter smoke times

### 5. Field Dressing (Wilderness Processing)

**Deer vs Bear Field Dressing:**
- **Deer:** Faster (smaller), less dangerous (dead animal), lighter (easier transport)
- **Bear:** Slower (larger), dangerous (large claws, teeth), heavier (requires multiple people)

**Cervine Field Dressing Procedure:**
1. **Bleed immediately:** Throat cut (jugular) for blood drainage (improves meat quality)
2. **Gut within 1-2 hours:** Prevent bacterial contamination, remove organs
3. **Cool carcass:** Hang in shade (50-60°F ideal, prevent spoilage)
4. **Age 3-7 days:** Enzymatic tenderizing (lean meat requirement)
5. **Skin before aging** (unlike cattle which age with hide on - deer hide = thin, doesn't protect)

**Field Dressing Survival DCs (D&D 5e):**
- **DC 8:** Basic field dressing (favorable conditions, common deer, daytime)
- **DC 10:** Standard field dressing (whitetail in forest, moderate temp)
- **DC 12:** Difficult conditions (rain, heat >70°F, night)
- **DC 15:** Large game (elk, moose, heavy animal, poor conditions)
- **DC 18:** Emergency field dressing (combat aftermath, wounded hunters, hostile environment)

### 6. Antler Velvet Alchemical Properties

**Velvet Antler Components:**
- **Growth factors:** Healing, tissue regeneration
- **Minerals:** Calcium, phosphorus (bone health)
- **Blood-rich:** Iron, vitality

**Alchemical Uses:**
- **Healing Potions:** Minor/moderate healing (velvet = ingredient)
- **Virility Elixirs:** Traditional use (potency, stamina)
- **Athletic Enhancement:** Strength, endurance (short duration buff)
- **Anti-Aging:** Longevity potions (expensive, rare)

**Velvet Harvest Pricing:**
- **Whitetail velvet:** 8-15 sp/lb (common)
- **Elk velvet:** 20-35 sp/lb (larger, more potent)
- **Moose velvet:** 30-50 sp/lb (rare, massive yield)
- **Fey deer velvet:** 50-120 gp/lb (magical properties)

**Velvet Farming:**
- **Fallow deer farming:** Neverwinter nobles farm fallow deer for velvet (live harvest, annual cycle)
- **Harvest technique:** Sedate deer, saw antlers in velvet (July-Aug), deer survives, regrows next year
- **Economics:** 1 fallow deer = 3-5 lbs velvet/year × 15 sp/lb = 45-75 sp annual yield

---

## V. INTEGRATION WITH FOUNDATION GUIDES

### Master Butcher's Guide Cross-References

**§ Animal Classification & Anatomy, Cervine Family:**
- Deer anatomy, ruminant digestive system, antler growth biology
- Seasonal behavior (rut vs hibernation)
- Field dressing wild herbivores

**§ Processing Techniques, Cervine Processing:**
- 7 cervine primals breakdown
- Lean meat handling (different from fatty meat)
- Dry aging procedures (7-14 days hanging)
- Field dressing in wilderness conditions

**§ Preservation Methods, Lean Meat Preservation:**
- Venison smoking (brine required for moisture)
- Summer sausage (venison specialty, fat added)
- Jerky production (ideal for lean meat)

**§ Processing Techniques, Trophy Preparation:**
- Antler cape removal (hide + skull cap)
- European mounts (skull cleaning, whitening)
- Skull cap removal (antler removal from skull)

**§ Economic Mathematics, Yield Formulas:**
- 65% dressing percentage (vs 75% bear, 60% cattle)
- 45% retail from dressed (lean meat = less trim waste)
- 29% live to retail total

**§ Professional Standards, Wild Game Processing:**
- Ethical hunting (age class selection, population management)
- Rut season meat quality (when to avoid bulls)
- Field safety (wounded deer escape, tracking)

### Master Provisioner's Guide Cross-References

**§ Herbs & Spices, Game Meat Seasonings:**
- Juniper berries (traditional venison pairing)
- Rosemary, thyme (aromatic herbs for venison)
- Black pepper, garlic (venison rubs)

**§ Wood & Fuel, Smoking Woods for Venison:**
- Cherry (sweet, mild, complements lean venison)
- Apple (fruity, traditional deer pairing)
- Hickory (strong, for elk/moose)
- Oak (neutral, long burn for large game)

**§ Storage & Containers, Lean Meat Storage:**
- Venison aging requirements (cool, dry, 40-50°F, 7-14 days)
- Smoked venison packaging (waxed paper, prevents drying)
- Jerky storage (dry, cool, 6-12 months)

**§ Salt Varieties, Curing Salts:**
- Prague Powder #1 (venison smoking, summer sausage)
- Kosher salt (dry brining lean meat)

**§ Wild Herbs & Foraging, Medicinal Plants:**
- Velvet antler harvesting (timing, technique)
- Traditional medicinal uses (healing, vitality)

**§ Seasonal Preservation Timing, Fall Hunting Season:**
- Sept-Nov venison harvest (rut season timing)
- Winter preserved venison sales (Dec-Feb scarcity premium)

### Bovine Guide Cross-References

**Comparison: Domestic Herbivore vs Wild Herbivore:**
- Cattle = farm-raised, consistent quality, fat marbling, year-round
- Deer = wild game, seasonal availability, lean meat, trophy focus

**Shared Techniques:**
- Dry aging (both beef and venison benefit)
- Large herbivore processing (elk/moose = similar to cattle size)

### Porcine Guide Cross-References

**Fat Processing Contrast:**
- Pork = high fat (lard rendering, fat cap preservation)
- Venison = low fat (no rendering, lean specialization)

**Summer Sausage:**
- Pork fat added to venison (15-20% blend for moisture/flavor)

### Ursine Guide Cross-References

**Wild Game Comparison:**
- Bear = omnivore, fatty, dangerous, trophy pelts
- Deer = herbivore, lean, mostly safe (except moose/giant elk), trophy antlers

**Shared Techniques:**
- Field dressing in wilderness
- Trophy preparation (pelts vs antlers)
- Seasonal hunting economics
- Fresh vs preserved value analysis

---

## VI. ECONOMIC SYSTEM DESIGN

### Baseline Economics (180 lb Sword Coast Whitetail)

**Live Weight:** 180 lbs
**Dressed Weight:** 117 lbs (65%)
**Retail Weight:** 52 lbs (29% of live)

**Retail Cut Values:**
- Backstrap (8 lbs): 40-55 sp (5-7 sp/lb, premium)
- Ham (12 lbs): 24-36 sp (2-3 sp/lb)
- Shoulder (10 lbs): 15-20 sp (1.5-2 sp/lb)
- Ribs (6 lbs): 12-18 sp (2-3 sp/lb)
- Ground/Stew (16 lbs): 16-24 sp (1-1.5 sp/lb)

**Byproduct Values:**
- Hide: 8-15 sp (tanned)
- Antlers (8-point): 12-20 sp
- Organ meat: 3-5 sp (heart, liver)

**Total Fresh Value:** 130-193 sp (13-19.3 gp)

**Processing Costs:**
- Labor: 6-8 hours × 4 sp/hour = 24-32 sp
- **Net Profit:** 106-161 sp (10.6-16.1 gp)

**Profit per Hour:** 1.3-2.0 gp/hour (lower than bear 1.8-2.6 gp/hour due to smaller size)

### Trophy Bull Economics (750 lb Elk, 12-point rack)

**Live Weight:** 750 lbs
**Dressed Weight:** 488 lbs (65%)
**Retail Weight:** 220 lbs (29% of live)

**Retail Cut Values:**
- Backstrap (28 lbs): 140-196 sp (5-7 sp/lb)
- Ham (40 lbs): 80-120 sp (2-3 sp/lb)
- Shoulder (35 lbs): 52-70 sp (1.5-2 sp/lb)
- Ribs (25 lbs): 50-75 sp (2-3 sp/lb)
- Ground/Stew (92 lbs): 92-138 sp (1-1.5 sp/lb)

**Byproduct Values:**
- Hide: 35-60 sp (large, thick)
- **Antlers (12-point trophy): 250-450 sp (25-45 gp)** ← MAJOR VALUE
- Organs: 10-15 sp

**Total Fresh Value:** 709-1,124 sp (70.9-112.4 gp)

**Processing Costs:**
- Labor: 12-16 hours × 4 sp/hour = 48-64 sp
- **Net Profit:** 661-1,076 sp (66.1-107.6 gp)

**Trophy Focus:** Antlers = 35-40% of total value (hunt for racks, sell meat as bonus)

### Preservation Economics (Whitetail)

**Scenario A: Sell Fresh**
- Revenue: 130-193 sp
- Labor: 24-32 sp (6-8 hours)
- **Net: 106-161 sp (10.6-16.1 gp)**

**Scenario B: Preserve (Smoked Venison + Jerky)**
- Smoked backstrap/ham (20 lbs): 100-140 sp (5-7 sp/lb smoked)
- Jerky (10 lbs fresh → 3 lbs jerky): 18-24 sp (6-8 sp/lb)
- Fresh ground (22 lbs): 22-33 sp
- Hide (tanned): 12-18 sp
- Antlers: 12-20 sp
- **Total Revenue: 164-235 sp**
- **Labor:** 24 sp (processing) + 64 sp (smoking 16 hours) + 32 sp (jerky 8 hours) = 120 sp
- **Supplies:** 15 sp (salt, Prague Powder, wood)
- **Total Costs:** 135 sp
- **Net: 29-100 sp (2.9-10 gp)**

**Preservation Verdict:** Fresh sale is MORE profitable (10.6-16.1 gp vs 2.9-10 gp) UNLESS you have zero labor cost (player characters doing it themselves).

### Market Pricing Modifiers

**Waterdeep (Best Market):**
- Premium cuts: +20-30% (wealthy buyers)
- Antlers: +25-40% (decorators, nobles)
- Exotic species: +40-60% (fey deer, island elk)

**Icewind Dale:**
- Fresh meat: +30-50% (scarcity, winter necessity)
- Antlers: -20-30% (local product, no rarity)
- Caribou: Baseline (local species, oversupply during migration)

**Moonshae Isles:**
- Island elk: -10-20% (local, must export to Waterdeep for premium)
- Shipping cost: 20-30 sp (boat to Waterdeep)

**Seasonal Modifiers:**
- **Fall (Eleint-Uktar):** Baseline (hunting season, moderate supply)
- **Winter (Nightal-Alturiak):** +30-50% (scarcity, no fresh meat, preserved only)
- **Spring (Ches-Mirtul):** -20-30% (low demand, poor quality if hunted)
- **Summer (Kythorn-Eleasis):** -10-15% (off-season, moderate demand)

---

## VII. APPENDIX C: ANTLER TROPHY MASTERY (Deep Dive Plan)

### Section I: Antler Biology & Growth Cycle

**Antler Growth Timeline:**
- **Ches-Tarsakh:** Shedding (old antlers fall off, triggered by dropping testosterone)
- **Tarsakh-Mirtul:** Pedicle healing (skull cap wound closes, new growth begins)
- **Mirtul-Kythorn:** Velvet bud (blood-rich tissue, rapid growth, 1-2 inches/week)
- **Flamerule-Eleasis:** Peak velvet (full size achieved, soft, medicinal harvest window)
- **Eleasis-Eleint:** Hardening (velvet dries, peels off, antlers mineralize)
- **Eleint-Alturiak:** Hardened (fighting, rut, display, trophy harvest window)
- **Ches:** Cycle repeats

**Velvet Antler Harvest (Alchemical/Medicinal):**

**Why Velvet is Valuable:**
- Blood-rich tissue (growth factors, minerals)
- Rapid cell growth (fastest-growing tissue in mammals)
- Traditional medicine (healing, vitality, longevity)
- Modern alchemy (potion ingredients, enhancement elixirs)

**Harvest Methods:**
- **Live harvest (farm deer):** Sedate deer, saw antlers in velvet (Flamerule-Eleasis), deer survives and regrows next year
- **Fresh kill harvest:** Kill deer in velvet season (Flamerule-Eleasis), process antlers within 12 hours (blood spoils)
- **Dried velvet:** Hang/dry velvet antlers (2-4 weeks), shelf-stable for years

**Velvet Processing:**
1. Remove antlers from skull (saw at pedicle)
2. Slice into thin strips (1/4 inch) OR dry whole
3. Hang in cool, dry, dark location
4. Dry 2-4 weeks (brittle, shelf-stable)
5. Powder OR sell whole to alchemists

**Velvet Alchemical Uses:**
- Healing potions (minor/moderate healing ingredient)
- Potion of Vitality (exhaustion removal, temp HP)
- Potion of Heroism (temp HP, bless effect)
- Virility elixirs (traditional use)
- Athletic enhancement (temporary STR/CON bonus)

**Velvet Market Pricing:**
- Whitetail: 8-15 sp/lb fresh, 12-20 sp/lb dried
- Elk: 20-35 sp/lb fresh, 30-50 sp/lb dried
- Moose: 30-50 sp/lb fresh, 45-70 sp/lb dried
- Fey deer: 50-120 gp/lb (magical properties)

**Velvet Farming Economics:**
- 1 fallow deer = 3-5 lbs velvet/year (harvested Flamerule-Eleasis)
- Annual revenue: 36-100 sp per deer
- Farm of 10 deer = 360-1,000 sp/year
- Upkeep cost: 200-400 sp/year (feed, care, sedation)
- Net profit: 160-600 sp/year per 10 deer

---

### Section II: Point Scoring System (Trophy Antler Valuation)

**Faerûn Boone & Crockett System (Adapted):**

**What to Measure:**
1. **Point count:** Count all points 1 inch or longer on BOTH sides
2. **Inside spread:** Tip-to-tip measurement (widest point)
3. **Main beam length:** Base to tip, both sides
4. **Circumference:** Measure at 4 locations on each beam
5. **Symmetry:** Deduct points for asymmetry (broken tines, unmatched points)

**Point Count Examples:**
- **6-point whitetail:** 3 points per side (+ brow tines + main beam tip)
- **8-point whitetail:** 4 points per side (good trophy)
- **10-point whitetail:** 5 points per side (excellent trophy)
- **12-point elk:** 6 points per side (trophy class)
- **16-point moose:** 8 points per side (record class)

**Spread Measurement:**
- **Whitetail:** 12-18 inches (common), 20-24 inches (good), 26+ inches (trophy)
- **Elk:** 35-45 inches (common), 50-60 inches (good), 65+ inches (record)
- **Moose:** 45-60 inches (common), 65-75 inches (trophy), 80+ inches (legendary)

**Trophy Class Thresholds:**

**WHITETAIL:**
- **Common (6-8 point):** 5-20 sp value
- **Good (8-10 point, 20+ spread):** 25-40 sp
- **Trophy (10-12 point, 24+ spread, symmetrical):** 50-80 sp
- **Record (12+ point, 26+ spread, perfect symmetry):** 100-150 sp

**ELK:**
- **Common (8-10 point):** 40-80 sp
- **Good (10-12 point, 50+ spread):** 100-180 sp
- **Trophy (12-14 point, 60+ spread):** 250-450 sp
- **Record (14+ point, 65+ spread):** 500-800 sp

**MOOSE:**
- **Common (10-12 point):** 100-180 sp
- **Trophy (14-16 point, 70+ spread):** 400-600 sp
- **Record (16+ point, 80+ spread):** 800-1,200 sp

**GIANT ELK:**
- **Minimum (14 point):** 600-900 sp
- **Trophy (16 point, 80+ spread):** 1,000-1,500 sp
- **Legendary (18+ point, 90+ spread):** 1,800-2,500 sp

**Symmetry Bonus/Penalty:**
- **Perfect symmetry:** +20% value (matched points, even beams)
- **Minor asymmetry:** No modifier (1-2 broken tines, minor differences)
- **Major asymmetry:** -30% value (one side much smaller, multiple breaks)

---

### Section III: Antler Removal & Skull Cap Processing

**Skull Cap Removal (For Antler Mounting):**

**Equipment:**
- Bone saw or hacksaw
- Markers (chalk, pen)
- Pot for boiling (if cleaning skull)
- Sandpaper (smoothing cut edges)

**Procedure:**
1. **Mark cut line:** 2-3 inches below antler base, create oval around both pedicles
2. **Saw carefully:** Follow marked line, keep skull cap intact
3. **Clean skull cap:** Scrape meat, boil 30 minutes, scrape again
4. **Smooth edges:** Sandpaper rough edges from saw
5. **Whiten (optional):** Soak in hydrogen peroxide 24-48 hours

**Result:** Skull cap with both antlers attached, ready for mounting

---

### Section IV: Trophy Mounting Options

**EUROPEAN MOUNT (Most Common):**

**What It Is:** Cleaned skull + antlers, mounted on wall plaque

**Process:**
1. Remove skull cap (as above)
2. Boil skull 2-4 hours (remove all tissue)
3. Whiten skull (hydrogen peroxide soak)
4. Mount skull cap on wood plaque
5. Hang on wall

**Cost:**
- DIY: 5-10 sp (supplies, plaque)
- Professional: 30-60 sp (commissioned)

**Value:**
- Whitetail 8-point: 15-25 sp (mounted)
- Elk 12-point: 80-120 sp (mounted)

**Best For:** Budget option, rustic aesthetic, hunter DIY

---

**PEDESTAL MOUNT (Premium):**

**What It Is:** Skull + antlers on decorative pedestal/stand (freestanding)

**Process:**
1. Clean skull completely (full skull, not just cap)
2. Whiten and polish
3. Mount on carved wooden pedestal
4. Display on shelf/table

**Cost:**
- Professional: 80-150 sp (commissioned, carved pedestal)

**Value:**
- Trophy elk: 150-250 sp
- Giant elk: 400-700 sp

**Best For:** Centerpiece display, formal settings, noble estates

---

**SHOULDER MOUNT (Full Taxidermy):**

**What It Is:** Antlers + head + neck/shoulders, lifelike pose

**Process:**
1. Cape deer (skin head/neck, keep attached to antlers)
2. Ship to taxidermist
3. Taxidermist creates mannequin, mounts cape, positions antlers
4. 4-8 months production time

**Cost:**
- Whitetail: 200-350 sp
- Elk: 400-700 sp
- Moose: 600-1,000 sp
- Giant Elk: 800-1,200 sp

**Best For:** Lifelike display, prestige, formal trophy room

---

**FULL BODY MOUNT (Ultimate Trophy):**

**What It Is:** Entire deer, standing/posed, lifelike

**Process:**
1. Skin entire deer (casing method, like bear pelts)
2. Ship to master taxidermist
3. Create full-body mannequin, pose, mount
4. 6-12 months production time

**Cost:**
- Whitetail: 500-900 sp
- Elk: 1,000-1,800 sp
- Moose: 1,500-2,500 sp
- Giant Elk: 2,500-4,000 sp

**Best For:** Legendary trophies, estate centerpiece, museum quality

---

### Section V: Antler Shed Collection (No Hunting Required)

**What Are Sheds?**
- Naturally fallen antlers (March-April)
- Bucks/bulls shed annually, leave antlers on ground
- Can be collected without hunting/killing

**Where to Find Sheds:**
- Deer trails (movement corridors)
- Feeding areas (winter browse zones)
- Bedding areas (resting spots)
- Water sources (creek crossings)

**Shed Hunting Season:**
- **Peak:** Ches-Tarsakh (fresh sheds, just dropped)
- **Late:** Mirtul-Kythorn (weathered sheds, gnawed by rodents)

**Shed Value:**
- **Fresh sheds:** 40-60% of attached antler value (no skull, standalone)
- **Matched pair:** 80-90% of attached antler value (+50% bonus for both sides)
- **Weathered sheds:** 20-30% of value (gnawed, sun-bleached)

**Shed Uses:**
- Decorative display (antler chandelier, matched pairs on wall)
- Knife/tool handles (carving material)
- Dog chews (mineral-rich, entertainment)
- Buttons, jewelry (craft material)

**Shed Hunting Economics:**
- Zero cost (foraging, no hunting license)
- 4-8 hours foraging = 1-5 sheds found (depending on deer population)
- Elk sheds = 20-80 sp each (larger, more valuable)
- Can earn 40-200 sp per day (skilled forager, good location)

---

### Section VI: Velvet Alchemical Recipes (Detailed)

**POTION OF MINOR HEALING (Enhanced):**
- Velvet antler (2 oz, powdered): +5 HP healing boost
- Standard recipe: 1d4+1 HP → With velvet: 1d4+6 HP

**POTION OF VITALITY:**
- Velvet antler (4 oz, fresh or dried): Primary ingredient
- Removes exhaustion, grants 2d4+2 temp HP
- Market price: 80-120 gp
- Craft cost with velvet: 40-60 gp (50% savings)

**ATHLETIC ENHANCEMENT ELIXIR (Custom):**
- Velvet antler (6 oz, fresh recommended): Strength component
- Effect: +2 STR for 1 hour, advantage on STR checks
- Market price: 50-80 gp
- Craft cost: 25-40 gp

**VIRILITY TONIC (Traditional):**
- Velvet antler (8 oz, dried and powdered): Potency
- Effect: Advantage on CHA (Persuasion) checks for social/romantic encounters, 4 hours
- Market price: 30-50 gp (novelty demand)
- Craft cost: 15-25 gp

---

**ESTIMATED APPENDIX C LENGTH:** 1,600-1,800 lines (30+ pages, deep dive mastery)

---

## VIII. QUALITY ASSURANCE CHECKLIST

**Before writing files, verify:**

✅ **Edition Consistency:** Fifth Edition throughout
✅ **Author Credits:** Thadius 132 years, Helena 32 years (every file with author notes)
✅ **Labor Rates:** 4 sp/hour journeyman (all economic analyses)
✅ **Yield Formula:** 65% dressing, 45% retail (29% total) - applied to all 12 breeds
✅ **Cross-References:** 60+ § references to foundation guides mapped
✅ **Geographic Names:** Western Faerûn only (no "American" or "European")
✅ **Steaks Included:** Backstrap steaks, ham steaks, rib chops (user feedback from Ursine)
✅ **Mathematical Accuracy:** All yield calculations, profit analyses verified
✅ **CR Ratings:** D&D 5e accurate (CR 0, 1/4, 1/2, 2 appropriate for species)
✅ **Antler System:** Point scoring, velvet harvest, mounting options consistent across breeds
✅ **Rut Season:** Oct-Nov timing, meat quality impact (-20-30%) applied consistently
✅ **Unique Mechanics:** Antlers, rut, age classes, lean meat differentiated from bear/cattle/pork

---

## IX. IMPLEMENTATION TIMELINE ESTIMATE

**Phase 1: Foundation Files (3 files, 1 session)**
- 00_FRONT_MATTER.md
- 01_REGIONAL_OVERVIEW.md
- 01_UNIVERSAL_CERVINE_CUTS.md

**Phase 2: Common Deer (5 files, 1-2 sessions)**
- 02_SWORD_COAST_WHITETAIL.md [BASELINE, longest file]
- 02_HIGH_FOREST_MULE_DEER.md
- 02_ARDEEP_ROE_DEER.md
- 02_NEVERWINTER_FALLOW_DEER.md
- 02_TRIELTA_HILLS_RED_DEER.md

**Phase 3: Large Game (4 files, 1-2 sessions)**
- 03_HIGH_MOOR_WAPITI.md
- 03_EVERMOOR_MOOSE.md
- 03_ICEWIND_DALE_CARIBOU.md
- 03_MOONSHAE_ISLAND_ELK.md

**Phase 4: Exotic & Dangerous (3 files, 1 session)**
- 04_FEYWILD_MOONLIT_DEER.md
- 04_CHULTAN_PYGMY_ANTELOPE.md
- 05_GIANT_ELK.md

**Phase 5: Appendices (4 files, 1 session)**
- APPENDIX_A_BREED_COMPARISON.md
- APPENDIX_B_CUTS_AND_PRICES.md
- APPENDIX_C_ANTLER_TROPHY_MASTERY.md [Deep dive, longest appendix]
- APPENDIX_D_FOUNDATION_CROSS_REFERENCE.md

**Phase 6: Quality Review (1 session)**
- Comprehensive consistency check
- Mathematical verification
- Cross-reference validation

**TOTAL ESTIMATED TIME:** 5-7 work sessions

---

## X. NEXT STEPS

**User Approval Required:**

1. **Breed Count & Distribution:** 12 total (5 common, 4 large, 2 exotic, 1 dangerous) - APPROVED?
2. **Edition Number:** Fifth Edition - APPROVED?
3. **Breed Names & Geography:** All use Western Faerûn locations (no real-world references) - APPROVED?
4. **Unique Mechanics:** Antlers (deep dive), Rut season, Age classes, Lean meat - APPROVED?
5. **File Structure:** 19 files (3 foundation + 12 breeds + 4 appendices) - APPROVED?
6. **Deep Dive Topic:** Antler Trophy Mastery (30+ pages in Appendix C) - APPROVED?

**If approved, implementation begins immediately.**

---

**END OF PLAN**
