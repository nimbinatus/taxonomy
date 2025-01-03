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
        id(ref subgraph)
    compositional skills
        id(ref subgraph)
    knowledge
        id(ref subgraph)
```

## Foundational or Core Skills

Note that the InstructLab project is not accepting submissions for foundational skills at this time.

To learn more, reference [the docs on core skills](https://docs.instructlab.ai/taxonomy/skills/skills_guide/#core-skills).

Currently, the only foundational skill tree is reasoning.

```mermaid
---
title: Foundational Skills - Reasoning
config:
    fontSize: 8
    theme: base
    mindmap:
        maxNodeWidth: 110
---
mindmap
    root((reasoning))
        common sense
            id(...)
        linguistics
            id(logical sequence of words)
            id(object identification)
            id(odd one out)
            id(...)
        logical
            id(causal)
            id(general)
            id(tabular)
            id(...)
        mathematical
            id(...)
        temporal
            id(...)
        theory of mind
            id(...)
        unconventional
            id(lower score wins)
            id(...)
        id(...)
```
## Compositional Skills

* [Overall](#overall-skills)
* [Grounded](#grounded)
* [Freeform](#freeform)

### Overall Skills
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
            id(ref subgraph)
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
### Grounded

To learn about what grounded skills are, reference [the docs on grounded compositional skills](https://docs.instructlab.ai/taxonomy/skills/skills_guide/#grounded-compositional-skills).

```mermaid
---
title: Compositional Skills - Grounded
config:
    theme: base
    mindmap:
        maxNodeWidth: 100
    fontSize: 8
---
mindmap
    root((grounded))
        arts and recreation
            id(...)
        engineering
            id(...)
        geography
            id(...)
        history
            id(...)
        linguistics
            id(inclusion)
            id(...)
            id{{writing}}
                id(rewriting)
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

### Freeform

To learn about what freeform or ungrounded compositional skills are, reference [the docs on freeform compositional skills](https://docs.instructlab.ai/taxonomy/skills/skills_guide/#freeform-compositional-skills).

```mermaid
---
title: Compositional Skills - Freeform
config:
    theme: base
    mindmap:
        maxNodeWidth: 100
    fontSize: 8
---
mindmap
    root((freeform or ungrounded compositional skills))
        arts and recreation
            id(...)
        engineering
            id(...)
        geography
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

* [Overall](#overall-knowledge)
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

### Overall Knowledge
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
            id(ref subgraph)
        engineering
            id(ref subgraph)
        geography
            id(ref subgraph)
        history
            id(ref subgraph)
        linguistics
            id(ref subgraph)
        mathematics
            id(ref subgraph)
        philosophy
            id(ref subgraph)
        religion
            id(ref subgraph)
        science
            id(ref subgraph)
        technology
            id(ref subgraph)
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
            id(ref subgraph)
        sports
            id(ref subgraph)
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
        maxNodeWidth: 105
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