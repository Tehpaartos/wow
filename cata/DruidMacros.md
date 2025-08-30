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
/cancelaura Nitro Boosts
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
/use [stealth] Pounce; Maim
/startattack [nostealth]
```

Shread/Ravage(Stealth/Incarnation)
```
#showtooltip
/use [known:Ravage!][stealth] Ravage; Shred
/startattack [nostealth]
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
/cancelform [form:5]
/stopcasting
/use !Cat Form
```

Bear Form
```
#showtooltip Bear Form
/cancelform [form:5]
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
#showtooltip
/console autoUnshift 0
/use [@mouseover,help,nodead] [help,nodead,form:1/3] [@playertargettarget,help,nodead,form:1/3] [] Healing Touch
/console autoUnshift 1
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

Prowl
```
#showtooltip Prowl
/cast [nocombat] !Prowl
```

Druid 45
```
#showtooltip
/use [@mouseover,harm,nodead,talent:3/1] [talent:3/1] Faerie Fire
/use [@mouseover,harm,nodead,talent:3/2] [talent:3/2] Mass Entanglement
/use [talent:3/3] Typhoon
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
Wild Charge
```
#showtooltip
/cancelform [@mouseover,nodead,form:5,talent:1/3][nodead,form:5,talent:1/3]
/use [talent:1/2] Displacer Beast
/use [@mouseover,nodead,talent:1/3] [talent:1/3] Wild Charge
```

Feral Charge
```
#showtooltip Wild Charge
/stopmacro [notalent:1/3]
/cancelform [@mouseover,harm,nodead,form:5][nodead,harm,form:5]
/use [@mouseover,harm,nodead,noform:1][nodead,harm,noform:1]Bear Form;[@mouseover,harm,nodead][nodead,harm]Wild Charge
```

Cat Leap
```
#showtooltip Wild Charge
/cancelform [@mouseover,exists,form:5][exists,form:5][@mouseover,help,form:3][help,form:3]
/use [@mouseover,harm,noform:1/3]Cat Form;[@mouseover,exists]Wild Charge;[harm,noform:1/3]Cat Form;Wild Charge
```

```
#showtooltip 
/console autounshift 0
/cast Nature's Swiftness
/use [@mouseover,help,nodead] Healing Touch; [@mouseover,harm,nodead] [harm,nodead] Wrath; Healing Touch
/console autounshift 1
```



Testing

```
#showtooltip
/use [talent:1/2] Displacer Beast
/stopmacro [notalent:1/3]
/cancelform [@mouseover,nodead,form:5][nodead,form:5]
/use [@mouseover,harm,noform:1/3][harm,noform:1/3]Bear Form
/use [@mouseover,nodead][]Wild Charge
```
```
#showtooltip
/use [talent:1/2] Displacer Beast
/stopmacro [notalent:1/3]
/cancelform [@mouseover,nodead,form:5][nodead,form:5]
/use [@mouseover,harm,noform:1/3]Bear Form;[@mouseover,nodead]Wild Charge;[harm,noform:1/3]Bear Form;Wild Charge
/use [harm,noform:1/3]Bear Form;Wild Charge
```

```
#showtooltip Wild Charge
/cancelform [@mouseover,exists,form:5][exists,form:5][@mouseover,help,form:3][help,form:3]
/use [@mouseover,harm,noform:1/3]Cat Form;[@mouseover,exists]Wild Charge;[harm,noform:1/3]Cat Form;Wild Charge
```
```
#showtooltip Wild Charge
/stopmacro [@mouseover,nodead,notalent:1/3][nodead,notalent:1/3]
/cancelform [form:5]
/use [@mouseover,harm,noform:1][harm,noform:1]Bear Form
/use [@mouseover,harm,noform:1]Bear Form;[@mouseover][help]Wild Charge;[harm,noform:1]Bear Form;Wild Charge
```


```
#showtooltip
/use [talent:1/2] Displacer Beast
/stopmacro [notalent:1/3]
/cancelform [@mouseover,nodead,form:5] [nodead,form:5]
/use [@mouseover,nodead] [nodead] Wild Charge
```


```
#showtooltip Wild Charge
/stopmacro [@mouseover,nodead,notalent:1/3][nodead,notalent:1/3]
/cancelform [form:5]
/use [@mouseover,harm,noform:1][harm,noform:1]Bear Form
/use [@mouseover][]Wild Charge
```

```
#showtooltip
/stopmacro [@mouseover,nodead,notalent:1/3][nodead,notalent:1/3]
/cancelform [form:5]
/use [@mouseover,harm,nodead,noform:1]Bear Form;[@mouseover,nodead][help,nodead]Wild Charge;[harm,noform:1]Bear Form;Wild Charge
```

```
[@mouseover,harm,nodead] [harm,nodead] Wrath; Healing Touch
```




 








```  
#showtooltip
/cancelform [@mouseover,nodead,form:5,talent:1/3][nodead,form:5,talent:1/3]
/use [talent:1/2] Displacer Beast
/use [@mouseover,nodead,talent:1/3] [talent:1/3] Wild Charge
```
```
#showtooltip Wild Charge
/stopmacro [notalent:1/3]
/cancelform [@mouseover,harm,nodead,form:5][harm,nodead,form:5]
/use [@mouseover,harm,nodead,noform:1][harm,nodead,noform:1]Bear Form
/castsequence [@mouseover,harm,nodead][]Wild Charge,Growl
```

```
#showtooltip
/stopmacro [noform:1]

/stopmacro [notalent:1/3]
/cancelform [@mouseover,nodead,form:5,talent:1/3][nodead,form:5,talent:1/3]
/use [@mouseover,harm,nodead,noform:1,talent:1/3][harm,nodead,noform:1,talent:1/3]Bear Form
/castsequence [@mouseover,harm,nodead,form:1,talent:1/3][form:1,talent:1/3]Wild Charge,Growl
```

