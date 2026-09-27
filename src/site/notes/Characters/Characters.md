---
{"dg-publish":true,"permalink":"/characters/characters/","dg-note-properties":{"tags":null,"attitude":""}}
---

# PCs
 - [[Characters/PC/Vespa Littleflight\|Vespa Littleflight]]
 - [[Characters/PC/Coriander Hope\|Coriander Hope]]
 - [[Characters/PC/Orrath, The Withered One\|Orrath, The Withered One]]

# NPCs
- [[Characters/NPC/Cozmioko\|Cozmioko]]
- [[Characters/NPC/Eldemere\|Eldemere]]

## Chapter 1
Redwood Watch
 - [[Characters/NPC/Selenar Woodwise\|Selenar Woodwise]]
 - [[Characters/NPC/Gwenhumara Goldmoss\|Gwenhumara Goldmoss]]
 - [[Fergus Deerborn\|Fergus Deerborn]]
 - [[Sunny Lightpurse\|Sunny Lightpurse]]
 
Redwood Grove
 - [[Characters/NPC/Kaynen\|Kaynen]]
 - [[Armin Whisperwind\|Armin Whisperwind]]

# Enemies
- [[Anthradusk\|Anthradusk]]
- 
### Chapter 1
- [[Sunset-is-Nigh\|Sunset-is-Nigh]]
- [[Marilissa\|Marilissa]]


# Everyone
```base
views:
  - type: cards
    name: Characters
    filters:
      and:
        - file.inFolder("Characters")
        - '!file.inFolder("Characters/PC - Private")'
        - '!file.ext.contains("base")'
        - file.hasTag("character")
        - "!attitude.isEmpty()"
    groupBy:
      property: attitude
      direction: ASC
    order:
      - file.name
      - aliases
    image: note.player-image
    imageAspectRatio: 1.15
    imageFit: contain

```