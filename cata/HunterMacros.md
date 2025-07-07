
# Shots
Arcane Shot
```
#showtooltip Arcane Shot
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Arcane Shot
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Cobra Shot
```
#showtooltip Cobra Shot
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Cobra Shot
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

A Murder of Crows
```
#showtooltip A Murder of Crows
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]A Murder of Crows
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Black Arrow
```
#showtooltip Black Arrow
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Black Arrow
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Explosive Shot
```
#showtooltip Explosive Shot
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Explosive Shot
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Kill Shot
```
#showtooltip Kill Shot
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Kill Shot
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Multi-Shot
```
#showtooltip Multi-Shot
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Multi-Shot
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Serpent Sting
```
#showtooltip Serpent Sting
/use [noform] Aspect of the Hawk
/use [@mouseover,harm,nodead][]Serpent Sting
/startattack
/stopmacro [@pettarget,noexists]
/use [@pettarget]Bite
/use Rabid
/use Furious Howl
```

Binding Shot
```
#showtooltip
/use [@cursor]Binding Shot
```

Distracting Shot
```
#showtooltip
/use [@mouseover,harm,nodead][]Distracting Shot
```

Concussive Shot
```
#showtooltip
/use [@mouseover,harm,nodead][]Concussive Shot
```

Counter Shot
```
#showtooltip
/use [@mouseover,harm,nodead][]Counter Shot
```

Scatter Shot
```
#showtooltip
/use [@mouseover,harm,nodead][]Scatter Shot
```

Tranqulizing Shot
```
#showtooltip
/use [@mouseover,harm,nodead][]Tranquilizing Shot
```

Widow Venom
```
#showtooltip
/use [@mouseover,harm,nodead][]Widow Venom
```

# Traps

Explosive Trap
```
#show Explosive Trap
/use !Trap Launcher
/castsequence [@cursor] reset=10 Explosive Trap, Snake Trap, Ice Trap
```

Snake Trap
```
#show Snake Trap
/use !Trap Launcher
/use [@cursor] Snake Trap
```

Ice Trap
```
#show Ice Trap
/use !Trap Launcher
/use [@cursor] Ice Trap
```

Freezing Trap
```
#show Freezing Trap
/use !Trap Launcher
/use [@cursor] Freezing Trap
```

# Pet
Pet Micro
```
#showtooltip
/petfollow [nocombat]
/petattack [@pettarget,noexists]
/petfollow [@pettarget,exists]
/petattack [@mouseover,harm,nodead]
/stopmacro [@pettarget,noexists]
/use Charge
/use Dash
/use Dive
```

Pet Move To
```
/petmoveto
```

Pet
```
#showtooltip
/use [@pet,dead]Revive Pet
/use [nopet] Call Pet 1
/use [@pet,nodead] Mend Pet
/petautocaston Furious Howl
/petautocaston Roar of Courage
/petautocaston Dash
/petautocaston Bite
/petautocaston Claw
/petautocastoff Cower
```

# Other

Rapid Fire
```
#showtooltip Rapid Fire
/use [noform:1]Aspect of the Hawk
/stopmacro [nocombat]
/cancelaura Deterrence
/use Bestial Wrath
/use Berserking
/use Blood Fury
/use Rapid Fire
/use Stampede
/use 13
/use 14
/use 10
/use Rabid
```

Hunter's Mark
```
#showtooltip 
/use [@mouseover,harm,nodead][]Hunter's Mark
```

Master's Call
```
#showtooltip
/use [@mouseover,help,nodead][]Master's Call
```

Aspect of the Hawk
```
#showtooltip
/use !Aspect of the Hawk
```

Deterrence
```
#showtooltip
/stopcasting
/use Deterrence
```

Feign Death
```
#showtooltip
/stopcasting 
/use Feign Death
```

Eagle Eye
```
#showtooltip
/use [@cursor]Eagle Eye
```

Flare
```
#showtooltip
/use [@cursor]Flare
```

Misdirection
```
#showtooltip
/use [@mouseover,help,nodead][@focus,help,nodead][@pet,nodead][]Misdirection
```

Fervor
```
#showtooltip Fervor
/use 10
/use Fervor
```

