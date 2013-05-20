## Commands /rpgitem 

### /rpgitem <span style='color:#000000'>help</span> <span style='color:#006EFF'>Terms</span><span style='color:#0000ff'>[String]</span> 
Shows commands and help for commands that contain the search terms <span style='color:#0000ff'>[Terms]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> 
Prints item <span style='color:#0000ff'>[Item]</span>'s tool-tip to chat

### /rpgitem <span style='color:#006EFF'>Name</span><span style='color:#0000ff'>[String]</span> <span style='color:#000000'>create</span> 
Create an item with the name <span style='color:#0000ff'>[Name]</span>. The <span style='color:#0000ff'>[Name]</span> is what you use to identify the item for later commands e.g: Give. <span style='color:#0000ff'>[Name]</span> is not the name of the item on the tool-tip, that is set with Display instead.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>armour</span> <span style='color:#006EFF'>Armour</span><span style='color:#0000ff'>[Integer(0-100)]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s armour to <span style='color:#0000ff'>[Armour]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>armour</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current armour

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>damage</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current damage

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>damage</span> <span style='color:#006EFF'>Min</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Max</span><span style='color:#0000ff'>[Integer]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s damage to do random damage between <span style='color:#0000ff'>[Min]</span> and <span style='color:#0000ff'>[Max]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>damage</span> <span style='color:#006EFF'>Damage</span><span style='color:#0000ff'>[Integer]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s damage to <span style='color:#0000ff'>[Damage]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>description</span> <span style='color:#000000'>set</span> <span style='color:#006EFF'>LineNo</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>DescriptionLine</span><span style='color:#0000ff'>[String]</span> 
Sets the line <span style='color:#0000ff'>[LineNo]</span> to <span style='color:#0000ff'>[DescriptionLine]</span> on the item <span style='color:#0000ff'>[Item]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>description</span> <span style='color:#000000'>add</span> <span style='color:#006EFF'>DescriptionLine</span><span style='color:#0000ff'>[String]</span> 
Adds the line <span style='color:#0000ff'>[DescriptionLine]</span> to the item <span style='color:#0000ff'>[Item]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>description</span> <span style='color:#000000'>remove</span> <span style='color:#006EFF'>LineNo</span><span style='color:#0000ff'>[Integer]</span> 
Removes the line <span style='color:#0000ff'>[LineNo]</span> on the item <span style='color:#0000ff'>[Item]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>display</span> <span style='color:#006EFF'>Display</span><span style='color:#0000ff'>[String]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s display name to <span style='color:#0000ff'>[Display]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>display</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current display name

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>drop</span> <span style='color:#0000ff'>[EntityType]</span> <span style='color:#006EFF'>Chance</span><span style='color:#0000ff'>[Double]</span> 
Sets the chance that <span style='color:#0000ff'>[Item]</span> will drop from <span style='color:#0000ff'>[EntityType]</span> to <span style='color:#0000ff'>[Chance]</span>%. 0% prevents it from dropping

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>drop</span> <span style='color:#0000ff'>[EntityType]</span> 
Gets the chance that <span style='color:#0000ff'>[Item]</span> will drop from <span style='color:#0000ff'>[EntityType]</span>. 0% means it doesn't drop

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>durability</span> <span style='color:#000000'>infinite</span> 
Sets the durability to infinite. This means the item should never break

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>durability</span> <span style='color:#000000'>togglebar</span> 
Toggles the display of the tooltip based durability bar

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>durability</span> <span style='color:#006EFF'>Durability</span><span style='color:#0000ff'>[Integer]</span> 
Sets the durability for the item. The durability is the number of times the item can be used to attack, block damage(armour) or mine

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>give</span> 
Gives the item <span style='color:#0000ff'>[Item]</span> to the user of the command

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>give</span> <span style='color:#0000ff'>[Player]</span> <span style='color:#006EFF'>Count</span><span style='color:#0000ff'>[Integer]</span> 
Gives <span style='color:#0000ff'>[Count]</span> of the item <span style='color:#0000ff'>[Item]</span> to the player <span style='color:#0000ff'>[Player]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>give</span> <span style='color:#0000ff'>[Player]</span> 
Gives the item <span style='color:#0000ff'>[Item]</span> to the player <span style='color:#0000ff'>[Player]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>hand</span> <span style='color:#006EFF'>Hand</span><span style='color:#0000ff'>[String]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s hand to <span style='color:#0000ff'>[Hand]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>hand</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current hand

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> <span style='color:#0000ff'>[Material]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s item to <span style='color:#0000ff'>[Material]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> <span style='color:#0000ff'>[Material]</span> <span style='color:#000000'>hex</span> <span style='color:#006EFF'>HexColour</span><span style='color:#0000ff'>[String]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s item to <span style='color:#0000ff'>[Material]</span> : <span style='color:#0000ff'>[Data]</span>, where <span style='color:#0000ff'>[Data]</span> is a hex number

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> <span style='color:#006EFF'>ItemID</span><span style='color:#0000ff'>[Integer]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s item to <span style='color:#0000ff'>[ItemID]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> <span style='color:#006EFF'>ItemID</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Data</span><span style='color:#0000ff'>[Integer]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s item to <span style='color:#0000ff'>[ItemID]</span> : <span style='color:#0000ff'>[Data]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> <span style='color:#0000ff'>[Material]</span> <span style='color:#006EFF'>Data</span><span style='color:#0000ff'>[Integer]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s item to <span style='color:#0000ff'>[Material]</span> : <span style='color:#0000ff'>[Data]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>item</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current item

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>lore</span> <span style='color:#006EFF'>Lore</span><span style='color:#0000ff'>[String]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s lore to <span style='color:#0000ff'>[Lore]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>lore</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current lore

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>arrow</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> 
Adds the arrow power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The arrow power will fire an arrow on right click

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>arrow</span> 
Adds the arrow power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second). The arrow power will fire an arrow on right click

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>command</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#0000ff'>[left,right]</span> <span style='color:#006EFF'>Display</span><span style='color:#0000ff'>[String]</span> <span style='color:#006EFF'>Command</span><span style='color:#0000ff'>[String]</span> <span style='color:#006EFF'>Permission</span><span style='color:#0000ff'>[String]</span> 
Adds the command power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The tooltip will display <span style='color:#0000ff'>[Display]</span>. The item will run <span style='color:#0000ff'>[Command]</span> on <span style='color:#0000ff'>[left,right]</span> click giving the permission <span style='color:#0000ff'>[Permission]</span> just for the use of the command. **Note**: If you want spaces in <span style='color:#0000ff'>[Display]</span>, <span style='color:#0000ff'>[Command]</span> or <span style='color:#0000ff'>[Permission]</span> then surround the string with ` e.g: `/say Hello`

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>command</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#0000ff'>[left,right]</span> <span style='color:#006EFF'>Display</span><span style='color:#0000ff'>[String]</span> <span style='color:#006EFF'>Command</span><span style='color:#0000ff'>[String]</span> 
Adds the command power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The tooltip will display <span style='color:#0000ff'>[Display]</span>. The item will run <span style='color:#0000ff'>[Command]</span> on <span style='color:#0000ff'>[left,right]</span> click. **Note**: If you want spaces in <span style='color:#0000ff'>[Display]</span> or <span style='color:#0000ff'>[Command]</span> then surround the string with ` e.g: `/say Hello`

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>command</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#0000ff'>[left,right]</span> <span style='color:#006EFF'>Details</span><span style='color:#0000ff'>[String]</span> 
Runs the command on <span style='color:#0000ff'>[left/right]</span> click. <span style='color:#0000ff'>[Detials]</span> is a | seperated list of <span style='color:#0000ff'>[display Text]</span> | <span style='color:#0000ff'>[command]</span> | <span style='color:#0000ff'>[permission]</span>. The tool-tip displays <span style='color:#0000ff'>[display Text]</span>. display Text and command must be separated a | symbol. If permission is provided the player will be given the permission just for the use of the item and then it will be removed

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>consume</span> 
Adds the consume power to <span style='color:#0000ff'>[Item]</span>. The consume power will remove the item on right click.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>fireball</span> 
Adds the fireball power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second). The fireball power will fire an fireball on right click

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>fireball</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> 
Adds the fireball power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The fireball power will fire an fireball on right click

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>flame</span> <span style='color:#006EFF'>Burntime</span><span style='color:#0000ff'>[Integer]</span> 
Adds the flame power to <span style='color:#0000ff'>[Item]</span> with a burntime of <span style='color:#0000ff'>[Burntime]</span> ticks. The flame power will set the target on fire on hit

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>flame</span> 
Adds the flame power to <span style='color:#0000ff'>[Item]</span> with a default burntime of 20 ticks (1 second). The flame power will set the target on fire on hit

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>ice</span> 
Adds the ice power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second). The ice power will fire an ice block on right click which will then create a box of ice on impact, the ice will slowly remove itself

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>ice</span> <span style='color:#006EFF'>!command.info.COOLDOWN!</span><span style='color:#0000ff'>[Integer]</span> 
Adds the ice power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The ice power will fire an ice block on right click which will then create a box of ice on impact, the ice will slowly remove itself

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>knockup</span> <span style='color:#006EFF'>Chance</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Power</span><span style='color:#0000ff'>[Double]</span> 
Adds the knockup power to <span style='color:#0000ff'>[Item]</span> with a chance of 1/<span style='color:#0000ff'>[Chance]</span> and a power of <span style='color:#0000ff'>[Power]</span>. The knockup power will send the hit target flying

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>knockup</span> 
Adds the knockup power to <span style='color:#0000ff'>[Item]</span> with a default chance of 1/20 and a power of 2. The knockup power will send the hit target flying

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>lightning</span> 
Adds the lightning power to <span style='color:#0000ff'>[Item]</span> with a default chance of 1/20. The lightning power will strike the hit target with lightning

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>lightning</span> <span style='color:#006EFF'>Chance</span><span style='color:#0000ff'>[Integer]</span> 
Adds the lightning power to <span style='color:#0000ff'>[Item]</span> with a chance of 1/<span style='color:#0000ff'>[Chance]</span>. The lightning power will strike the hit target with lightning

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>potionhit</span> <span style='color:#006EFF'>Chance</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Duration</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Amplifier</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Effect</span><span style='color:#0000ff'>[String]</span> 
Adds the potionhit power to <span style='color:#0000ff'>[Item]</span> with a chance of hitting 1/<span style='color:#0000ff'>[Chance]</span>. On hit it will apply <span style='color:#0000ff'>[Effect]</span> for <span style='color:#0000ff'>[Duration]</span> ticks at power <span style='color:#0000ff'>[Amplifier]</span>. Valid potion effects:speed, slow, fast_digging, slow_digging, increase_damage, heal, harm, jump, confusion, regeneration, damage_resistance, fire_resistance, water_breathing, invisibility, blindness, night_vision, hunger, weakness, poison, wither, 

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>potionself</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Duration</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Amplifier</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Effect</span><span style='color:#0000ff'>[String]</span> 
Adds the potionself power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span>. On right click it will apply <span style='color:#0000ff'>[Effect]</span> for <span style='color:#0000ff'>[Duration]</span> ticks at power <span style='color:#0000ff'>[Amplifier]</span>. Valid potion effects:speed, slow, fast_digging, slow_digging, increase_damage, heal, harm, jump, confusion, regeneration, damage_resistance, fire_resistance, water_breathing, invisibility, blindness, night_vision, hunger, weakness, poison, wither, 

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>potiontick</span> <span style='color:#006EFF'>Amplifier</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Effect</span><span style='color:#0000ff'>[String]</span> 
Adds the potiontick power to <span style='color:#0000ff'>[Item]</span>. The potiontick power will give the welder of the <span style='color:#0000ff'>[Item]</span> <span style='color:#0000ff'>[Effect]</span> level <span style='color:#0000ff'>[Amplifier]</span> while held/worn

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>rainbow</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Count</span><span style='color:#0000ff'>[Integer]</span> 
Adds the rainbow power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks and a block count of <span style='color:#0000ff'>[Count]</span>. The rainbow power will fire blocks of coloured wool on right click, the wool will remove itself.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>rainbow</span> 
Adds the rainbow power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second) and a block count of 5. The rainbow power will fire blocks of coloured wool on right click, the wool will remove itself.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>rumble</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Power</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Distance</span><span style='color:#0000ff'>[Integer]</span> 
Adds the runble power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks and a power of <span style='color:#0000ff'>[Power]</span>, the wave will travel <span style='color:#0000ff'>[Distance]</span> blocks. The rumble power sends a shockwave through the ground and sends any hit entities flying

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>skyhook</span> <span style='color:#0000ff'>[Material]</span> <span style='color:#006EFF'>Distance</span><span style='color:#0000ff'>[Integer]</span> 
Adds the skyhook power to <span style='color:#0000ff'>[Item]</span>. The skyhook power will allow the user to hook on to <span style='color:#0000ff'>[Material]</span> up to <span style='color:#0000ff'>[Distance]</span> blocks away

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>teleport</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> <span style='color:#006EFF'>Distance</span><span style='color:#0000ff'>[Integer]</span> 
Adds the teleport power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks (1 second) and teleport distance of <span style='color:#0000ff'>[Distance]</span> blocks. The teleport will teleport you in the direction you're looking in

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>teleport</span> 
Adds the teleport power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second) and teleport distance of 5 blocks. The teleport will teleport you in the direction you're looking in

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>tntcannon</span> <span style='color:#006EFF'>Cooldown</span><span style='color:#0000ff'>[Integer]</span> 
Adds the tntcannon power to <span style='color:#0000ff'>[Item]</span> with a cooldown of <span style='color:#0000ff'>[Cooldown]</span> ticks. The tntcannon power will fire active tnt on right click.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>power</span> <span style='color:#000000'>tntcannon</span> 
Adds the tntcannon power to <span style='color:#0000ff'>[Item]</span> with a default cooldown of 20 ticks (1 second). The tntcannon power will fire active tnt on right click.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>quality</span> <span style='color:#0000ff'>[Quality]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s quality to <span style='color:#0000ff'>[Quality]</span>.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>quality</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current quality

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>recipe</span> 
Sets the <span style='color:#0000ff'>[Item]</span>'s recipe

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>removerecipe</span> 
Removes the <span style='color:#0000ff'>[Item]</span>'s recipe

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>remove</span> 
Remove the item <span style='color:#0000ff'>[Item]</span> from the system. This does not currently remove the item from players' inventories but all powers and damage will stop working on them.

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>removepower</span> <span style='color:#006EFF'>Power</span><span style='color:#0000ff'>[String]</span> 
Removes power <span style='color:#0000ff'>[Power]</span> from item <span style='color:#0000ff'>[Item]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>type</span> 
Shows the item <span style='color:#0000ff'>[Item]</span>'s current type

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>type</span> <span style='color:#006EFF'>Type</span><span style='color:#0000ff'>[String]</span> 
Sets the item <span style='color:#0000ff'>[Item]</span>'s type to <span style='color:#0000ff'>[Type]</span>

### /rpgitem <span style='color:#0000ff'>[Item]</span> <span style='color:#000000'>worldguard</span> 
Toggles worldguard override on the <span style='color:#0000ff'>[Item]</span>

### /rpgitem <span style='color:#000000'>list</span> 
Shows a list of all created items

### /rpgitem <span style='color:#000000'>option</span> <span style='color:#000000'>giveperms</span> 
Toggles give requiring permissions

### /rpgitem <span style='color:#000000'>option</span> <span style='color:#000000'>worldguard</span> 
Toggles worldguard support. Currently if enabled it prevents RPG Items from being used in non-pvp area



Generated at: 20 May 2013 20:23:33 GMT