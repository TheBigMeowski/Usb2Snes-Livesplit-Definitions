# NOTES ON NINJA GAIDEN AUTOSPLITTER

## Trigger Conditions
### Autostart

NG1 and NG2: When the level and sublevel values are set to 1
NG3: When the sublevel value is 0 and timer's value is 250

### "Enter Level X-Y"

NG1 and NG2: When the level value is set to X and sub-level value set to Y
NG3: When the sublevel value is changed to the next number

### "Enemy X Down"

When both Enemy HP and Timer reach 0

## Ninja Gaiden I Memory details
- 0x01212C => Level
- 0x012130 => Sublevel
- 0x0066 => Enemy HP Display
- 0x0063 => Timer

## Ninja Gaiden II
- 0x0126AC => Level
- 0x0126B0 => Sublevel
- 0x0081 => Enemy HP Display
- 0x00B1 => Timer

## Ninja Gaiden III
- 0x012EAC => Level
- 0x005F => Sublevel as a count
- 0x00A8 => Enemy HP Display
- 0x00D0 => Timer
