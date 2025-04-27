---
{"dg-publish":true,"permalink":"/2-world/np-cs/port-nyanzaru/azaka-stormfang/"}
---


# Azaka Stormfang

## Profil

### Beschreibung

- Azaka Stormfang ist eine große, athletische Frau von etwa 1,83 m (6 Fuß) mit dunkler Haut und stechend grünen Augen, die ihre wilden Ursprünge widerspiegeln.
- Sie trägt einfache, praktische Kleidung, die sie für ihre Reisen durch den Dschungel benötigt, und ihr Haar ist in einem lockeren Zopf gebunden. Ihre Erscheinung vermittelt eine beeindruckende Mischung aus Stärke und Wildheit.
- Azaka verbirgt ihre Lykanthropie vor den Abenteurern so lange wie möglich. Sie hat die Fähigkeit, sich in einen Weretiger zu verwandeln, eine Form, die ihr große Beweglichkeit und Wildheit verleiht.
- Sie ist eine erfahrene Führerin durch den Dschungel und kennt jedes Geheimnis des wilden Landes, das sie in ihrer Tigerform durchstreift hat.
- Azaka hat eine tiefe Verbindung zur Natur und ist mit Saja N'baza, der mächtigen und weisen Naga von Orolunga, bekannt. Sie führt diejenigen, die nach Führung suchen, zu dieser mystischen Kreatur.

### Background
- Mutter Amelia
- Aufgewachsen im Valley of  Dread am Fuße der Sanrach Mountains
- kennt Saja N'Baza [[compendium/bestiary/monstrosity/guardian-naga\|Guardian Naga]] in Orolunga
- war in Kir Sibal und kennt:
	- [[3-Mechanics/CLI/bestiary/npc/asharra-toa\|Asharra]] Anfüherin
	- Princess [[3-Mechanics/CLI/bestiary/npc/mwaxanare-toa\|Mwaxanaré]] und ihren Bruder [[3-Mechanics/CLI/bestiary/npc/na-toa\|Na]] Nachkommen und Erben der Königlichen Linie von Omu 

### Kosten

- Azaka fordert 5 Goldmünzen pro Tag für ihre Dienste als Führerin, verlangt jedoch eine Vorauszahlung für 30 Tage. 
- Wenn Abenteurer ihr bei der Rückeroberung eines gestohlenen Familienerbstücks helfen, wird sie ihren Preis erlassen und sie zu Orten führen, die kaum jemand kennt.

### Persönlichkeit

- „Ich wurde im Dschungel geboren. Ich kenne seine Gefahren und wie man ihnen aus dem Weg geht. Dein Leben ist bei mir in sicheren Händen.“
- Azaka ist stolz auf ihre Fähigkeiten und hat ein starkes Vertrauen in ihre Fähigkeit, die Gruppe sicher durch den Dschungel zu führen.
- Sie ist ruhig und besonnen, aber ihre Augen verraten eine gewisse Wildheit und Geheimnistuerei, besonders wenn es um das gestohlene Erbstück geht.
- Sie hilft anderen gerne, aber sie hat auch ihren eigenen Stolz und wird ihre Lykanthropie nicht leicht offenbaren.

### Ideal

- „Die Natur ist mein Zuhause. Wer die Geheimnisse des Dschungels sucht, sollte seine wahre Bestimmung kennen und bereit sein, alles zu riskieren.“

### Bindung

- „Ich will meine Familienmaske zurück, die von diesen elenden Pterafolken gestohlen wurde. Aber wenn du mir hilfst, wirst du Zugang zu den tiefsten Geheimnissen des Dschungels erhalten.“

### Makel

- „Ich fürchte mich vor Höhen und werde niemals in eine Situation geraten, in der ich höher als 60 Fuß falle. Meine Lykanthropie sollte niemandem auferlegt werden.“

### Plot Hook

Azaka Stormfang bietet ihre Dienste als Führerin durch den Dschungel an, verlangt aber, dass Abenteurer ihr helfen, ein gestohlenes Erbstück – eine Holzmaske, die das Gesicht eines Tigers darstellt – von den Pterafolk des Firefinger zurückzuholen. Während sie die Gruppe zu gefährlichen Orten führt, wird ihre wahre Natur langsam enthüllt, und sie könnte sich irgendwann zu einem mächtigen Verbündeten oder einer unerforschten Gefahr entwickeln, je nachdem, wie das Abenteuer verläuft.


```

```

```statblock
"name": "Azaka Stormfang (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "17"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "11"
"speed": "30 ft. (40 ft. in tiger form)"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common (can't speak in tiger form)"
"cr": "4"
"traits":
- "desc": "The Azaka can use its action to polymorph into a tiger-humanoid hybrid\
    \ or into a tiger, or back into its true form, which is humanoid. Its statistics,\
    \ other than its size, are the same in each form. Any equipment it is wearing\
    \ or carrying isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The Azaka has advantage on Wisdom ([Perception](/3-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "If the Azaka moves at least 15 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 14 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/rules/conditions.md#Prone).\
    \ If the target is [prone](/3-Mechanics/CLI/rules/conditions.md#Prone), the Azaka\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce (Tiger or Hybrid Form Only)"
"actions":
- "desc": "In humanoid form, the Azaka makes two scimitar attacks or two longbow attacks.\
    \ In hybrid form, it can attack like a humanoid or make two claw attacks."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage. If the target is a humanoid, it must succeed on a DC\
    \ 13 Constitution saving throw or be cursed with Azaka lycanthropy."
  "name": "Bite (Tiger or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw (Tiger or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Humanoid or Hybrid Form Only)"
- "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow (Humanoid or Hybrid Form Only)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Azaka%20Stormfang.webp"
```{ #statblock}

