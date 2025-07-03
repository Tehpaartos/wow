Skull Bash
```
#showtooltip Skull Bash
/stopcasting [@mouseover,harm,nodead] [harm,nodead]
/use [@mouseover,harm,nodead,noform:1/3] [harm,nodead,noform:1/3] Bear Form
/use [@mouseover,harm,nodead] [] Skull Bash
```

Growl
```
#showtooltip Growl
/stopcasting [@mouseover,harm,nodead] [harm,nodead]
/use [@mouseover,harm,nodead,noform:1] [harm,nodead,noform:1] Bear Form
/use [@mouseover,harm,nodead] [] Growl
```

Bear Hug
```
#showtooltip Bear Hug
/stopcasting [@mouseover,harm,nodead] [harm,nodead]
/use [@mouseover,harm,nodead,noform:1] [harm,nodead,noform:1] Bear Form
/use [@mouseover,harm,nodead] [] Bear Hug
```

Savage Roar
```
#showtooltip Savage Roar
/stopcasting
/use [noform:3] Cat Form
/use Savage Roar
```

Stampeding Roar
```
#showtooltip Stampeding Roar
/cancelaura Dash
/use Stampeding Roar
```

Hurricane
```
#showtooltip Hurricane
/use [@cursor,noform:1] Hurricane
```

Tranquility
```
#showtooltip Tranquility
/use [@cursor,noform:1] Tranquility
```

Entangling Roots
```
#showtooltip Entangling Roots
/use [@mouseover,harm,nodead] [] Entangling Roots
```

Hibernate
```
#showtooltip Hibernate
/use [@mouseover,harm,nodead] [] Hibernate
```

Cyclone
```
#showtooltip Cyclone
/use [@mouseover,harm,nodead] [] Cyclone
```

Lacerate
```
#showtooltip Lacerate
/startattack 
/use [@mouseover,harm,nodead] [] Lacerate
```

Mangle
```
#showtooltip Mangle
/startattack 
/use [@mouseover,harm,nodead,form:1] [] Mangle
```

Pounce/Maim
```
#showtooltip
/startattack [nostealth]
/use [stealth] Pounce; [nostealth] Maim
```

Shread/Ravage
```
#showtooltip
/startattack [nostealth]
/use [stealth] Ravage; [nostealth] Shred
```

Maul
```
#showtooltip Maul
/startattack 
/use [@mouseover,harm,nodead] [] Maul
```

Cat Form
```
#showtooltip Cat Form
/cancelform [noform:1/3]
/stopcasting
/use !Cat Form
```

Bear Form
```
#showtooltip Bear Form
/cancelform [noform:1/3]
/stopcasting
/use !Bear Form
```

Faerie Fire
```
#showtooltip Faerie Fire
/use [@mouseover,harm,nodead] [] Faerie Fire
```

Inervate
```
#showtooltip Innervate
/stopcasting
/use [@mouseover,help,nodead] [] Innervate
```

Rebirth/Mark
```
#showtooltip
/use [@mouseover,help,dead] [help,dead] Rebirth; [@mouseover,help,nodead] [] Mark of the Wild
```

Healing Touch (Feral)
```
#showtooltip Healing Touch
/use [@mouseover,help,nodead] [@playertarget,help,nodead,form:1/3] [@playertargettarget,help,nodead,form:1/3] [] Healing Touch
```

Rejuv/Moonfire
```
#showtooltip 
/use [@mouseover,help,nodead] Rejuvenation; [@mouseover,harm,nodead] [harm,nodead] Moonfire; Rejuvenation
```

Healing T/Wrath
```
#showtooltip 
/use [@mouseover,help,nodead] Healing Touch; [@mouseover,harm,nodead] [harm,nodead] Wrath; Healing Touch
```

Druid 45
```
#showtooltip
/use [@mouseover,harm,nodead,talent:3/1] [talent:3/1] Faerie Fire
/use [@mouseover,harm,nodead,talent:3/2] [talent:3/2] Mass Entanglement
/use [@mouseover,harm,nodead,talent:3/3] [talent:3/3] Typhoon
```

Druid 75
```
#showtooltip
/use [talent:5/1] Disorienting Roar
/use [@cursor,talent:5/2] Ursol's Vortex
/use [@mouseover,harm,nodead,talent:5/3] [talent:5/3] Mighty Bash 
```

Druid 15
```
#showtooltip
/use [talent:1/2] Displacer Beast
/use [@mouseover,help,nodead,noform,talent:1/3][@mouseover,harm,nodead,form:1/3,talent:1/3] [] Wild Charge
```

Feral Charge
```
#showtooltip Wile Charge(form:1)
/stopcasting [@mouseover,harm,nodead] [harm,nodead]
/use [@mouseover,harm,nodead,noform:1] [harm,nodead,noform:1] Bear Form
/use [@mouseover,harm,nodead,form:1] [form:1] WIld Charge
```

