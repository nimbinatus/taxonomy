## Root

This is the basic structure of our taxonomy.

```mermaid
---
title: Root Taxonomy
config:
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
  root((taxonomy))
    foundational skills
        id(...)
    compositional skills
        id(...)
    knowledge
        id(...)
```

## Foundational Skills

Note that the InstructLab project is not accepting submissions for foundational skills at this time.

```mermaid
---
title: Foundational Skills
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 110
---
mindmap
    root((foundational skills))
        reasoning
            id1(common sense)
            id{{linguistics}}
                id1(logical sequence of words)
                id1(object identification)
                id1(odd one out)
            id2{{logical}}
                id1(causal)
                id1(general)
                id1(tabular)
            id1(mathematical)
            id1(temporal)
            id1(theory of mind)
            id2{{unconventional}}
                id(lower score wins)
```
## Compositional Skills

```mermaid
---
title: Compositional Skills
config:
    theme: base
    mindmap:
        maxNodeWidth: 100
    fontSize: 8
---
mindmap
    root((compositional skills))
        arts and recreation
            id(...)
        engineering
            id(...)
        geography
            id(...)
        grounded
            id{{arts and recreation}}
                id(...)
            id{{engineering}}
                id(...)
            id{{geography}}
                id(...)
            id{{history}}
                id(...)
            id{{linguistics}}
                id(inclusion)
                id(...)
                id{{writing}}
                    id(rewriting)
                    id(...)
            id{{philosophy}}
                id(...)
            id{{religion}}
                id(...)
            id{{science}}
                id(...)
            id{{technology}}
                id(...)
        history
            id(...)
        linguistics
            id(synonyms)
            id(...)
        philosophy
            id(...)
        religion
            id(...)
        science
            id(...)
        technology
            id(...)
```

## Knowledge

* [Overall](#overall)
* [Arts and Recreation](#arts-and-recreation)
* [Engineering](#engineering)
* [Geography](#geography)
* [History](#history)
* [Linguistics](#linguistics)
* [Mathematics](#mathematics)
* [Philosophy](#philosophy)
* [Religion](#religion)
* [Science](#science)
* [Technology](#technology)

### Overall
```mermaid
---
title: Knowledge
config:
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((knowledge))
        arts and recreation
            id(...)
        engineering
            id(...)
        geography
            id(...)
        history
            id(...)
        linguistics
            id(...)
        mathematics
            id(...)
        philosophy
            id(...)
        religion
            id(...)
        science
            id(...)
        technology
            id(...)
```
### Arts and Recreation
```mermaid
---
title: Arts and Recreation
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((arts and recreation))
        cinema and film
            genres
            techniques
        culinary
            cooking
            cuisines
            food preparation
            presentation
        fiber arts
            crocheting
            knitting
            sewing
            weaving
            id(...)
        fine arts
            id(...)
        hobbies
        literature
        music
            fandom
                id(...)
            genre
                id(...)
            instruments
            id(...)
        sports
            acrobatics
            air
            aquatics
            athletics
            ball-and-bat
            billiards
            boules
            bowling
            cycling
            disc
            equestrian
            golf
            gymnastics
            goal-based
            martial arts and combat
            motorsports
            outdoor
            racket/net
            snow
            target
            watersports
            weightlifting and strength
        id(...)
```
#### Music
```mermaid
---
title: Arts and Recreation - Music
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((music))
        fandom
            id(swifties)
            id(...)
        genre
            blues
            classical
            country
            easy listening
            electronic
            folk
            hip hop
            jazz
            pop
            R&B and soul
            regional and cultural
            religious
            rock
            traditional
        instruments
        id(...)
```
#### Sports
```mermaid
---
title: Arts and Recreation - Sports
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((sports))
        acrobatics
            cheerleading and color guard
            dancing
            figure skating
            parkour
        air
            aerobatics
            ballooning
            gliding
            parachuting and wingsuit flying
        aquatics
            diving
            swimming
            water polo
        athletics
            running and walking
                endurance
                hurdles
                sprint
            throwing
            vaulting and jumping
        ball-and-bat
            baseball
            cricket
            softball
        billiards
            croquet
            foosball
            pool
        boules
            bocce
            curling
            shuffleboard
        bowling
        cycling
        disc
            disc dog
            disc golf
            ultimate
        equestrian
            dressage
            eventing
            jumping
            rodeo
            western
        golf
        gymnastics
        goal-based
            American football
            basketball
            field hockey
            flag football
            football <US: soccer>
            hockey
            lacrosse
            polo
            rugby
        martial arts and combat
            boxing
            fencing
            Jujitsu
            Judo
            Sumo
            wrestling
        motorsports
        outdoor
            camping
            climbing
            hiking
            orienteering
        racket/net
            badminton
            pickleball
            racquetball
            squash
            table tennis
            tennis
            volleyball
        snow
            skiing
            snowboarding
        target
            archery
            shooting
        watersports
            canoeing
            rowing
            sailing
        weightlifting and strength
```
### Engineering
```mermaid
---
title: Engineering
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((engineering))
        agricultural
            aquaculture
                id(...)
            biomechanical
                id(...)
            food
                id(...)
            forest
                id(...)
            id(...)
        applied
            id(...)
        biological
            id(...)
        biomedical
            clinical
            medical imaging
            pharmaceutical
        chemical
            biomolecular
                genetic
                molecular
            process
        civil
            environmental
                ecological
                fire protection
                sanitary
            structural
                architectural
                earthquake
                ocean
                wind
            transport
                highway
                railway
                traffic
            urban
                municipal
            water resources
                coastal
                groundwater
                hydraulic
                river
        electrical
            computer
                data
                hardware
                network
                robotics
                software
            electronic
                control
                telecommunications
            optical
            power
                high voltage
                operations, protection, and control
                power system planning and design
            renewable energy
        energy
            solar
            wind
        geological
            geophysical
            geoenvironmental
            geotechnical
                mining
            hydrogeological
            mineral and energy resource exploration
        geomatics
            geodesy
            geospatial
            survey
        industrial
        information
            bioinformatics
            cheminformatics
            computer vision
            control theory
            information theory
            machine learning and statistics
            natural language processing
            robotics perception and algorithms
            signal processing
        materials
            biomaterial
            ceramic
            composites
            computational materials
            corrosion
            nanotechnology and nanoengineering
            material characterization
            metallurgical
            polymer
            semiconductors
            surfaces
        mechanical
            acoustics
            energy
            industrial plant
            manufacturing
            power plant
            optomechanical
                cameras
                fiber optics
                laser systems
                telescopes
            sports
            thermal
                air conditioning
                refrigeration
            vehicle
                aerospace
                automotive
        petroleum
        id(...)
```
### Geography
```mermaid
---
title: Geography
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((Geography))
        Northern Hemisphere
            Asia
            Europe
            North America
        Southern Hemisphere
            Antartica
            Australia
            South America
        Oceans and seas
        id(...)
```
### History
```mermaid
---
title: History
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((History))
        historiography
        human history
            prehistory
            
        methods and tools
        philosophy of history
        schools of thought
        id(...)
```
### Linguistics
```mermaid
---
title: Linguistics
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((Linguistics))
        id(...)
```
### Mathematics
```mermaid
---
title: Mathematics
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((Mathematics))
        id(...)
```
### Philosophy
```mermaid
---
title: Philosophy
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((Philosophy))
        id(...)
```
### Religion
```mermaid
---
title: Religion
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((Religion))
        id(...)
```
### Science
```mermaid
---
title: Science
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((science))
        animals and zoology
            arthropods
                id(...)
            birds
                id(black-capped chicadee)
                id(...)
            chordates
                id(...)
            cold-blooded invertebrates and fishes
                id(...)
            invertebrates
                id(...)
            mammals
                id(...)
            id(...)
        astronomy
            id(...)
        biology
            ecology
                id(...)
            genetics and evolution
                id(...)
            physiology
                id(...)
            id(...)
        chemistry
            physical
                id(...)
            inorganic
                id(...)
            organic
                id(...)
            crystallography
                id(...)
            mineralogy
                id(...)
            id(...)
        earth sciences
            atmospheric science
                id(...)
            biogeochemistry
                id(...)
            geology
                id(...)
            hydrology
                id(...)
            oceanography
                id(...)
            petrology
                id(...)
            id(...)
        physics
            classical mechanics, solid mechanics
                id(...)
            electricity and electronics
                id(...)
            fluid mechanics
                id(...)
            gas mechanics
                id(...)
            heat
                id(...)
            light and infrared and ultraviolet phenomena
                id(...)
            magnetism
                id(...)
            modern physics
                id(...)
            sound
                id(...)
            id(...)
        plants and botany
        id(...)
```
### Technology
```mermaid
---
title: Technology
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 100
---
mindmap
    root((technology))
        agriculture
            agricultrual chemistry
            agricultural education
            agronomy
            aquaculture
            animal husbandry
            communication, economics, and policy
            crops
            equipment and material
            farming
                organic
            fishery
            forestry
            horticulture
            industry
                food safety and processing
            ranching
            techniques and practices
                aeroponics
                aquaponics
                grazing
                harvesting
                hydroponics
                irrigation
                pasteurization
                permaculture
                pest control
                sustainable agriculture
            viticulture
        inventions and patents
        medicine and health
            pharmacology and therapeutics
            surgery
        id(...)
```