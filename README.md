# I Identify as a Rocket
*This is my first time making a github fork, please tell me if there's anything I can add.
![image](https://github.com/Nardeem/I-identify-as-a-rocket/assets/128815377/f75f348c-f3fa-4528-8e48-0f92000a9afd)
## This is a minecraft command kit. Anything using 4 blocks (as a main) will have an EZ Setup that you just right click.

### This command kit is in v1. The first uploaded version includes **3 command barrels**, a rocket barrel (yes this is why it's called that.) that uses a few extra command blocks to make you not fly off and along with the setup command blocks. A moon jump barrel that includes moon boots. And a fire scroll barrel, this can be used as a template. Copy the following text to get the command, place it in a command block and activate it.
```sh
/setblock ~ ~ ~ minecraft:barrel[facing=up,open=true]{Items:[{Count:1b,Slot:0b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:1b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:2b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:3b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:4b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:5b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:6b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:7b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:8b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:9b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:10b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:11b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:12b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:13b,id:"minecraft:light_gray_shulker_box",tag:{BlockEntityTag:{CustomName:'{"bold":true,"italic":false,"extra":[{"color":"#FFBE2C","text":"I"},{"color":"#FEBF2C","text":" "},{"color":"#FCC12C","text":"i"},{"color":"#FBC32C","text":"d"},{"color":"#F9C52C","text":"e"},{"color":"#F8C62D","text":"n"},{"color":"#F6C82D","text":"t"},{"color":"#F5CA2D","text":"i"},{"color":"#F3CC2D","text":"f"},{"color":"#F2CE2D","text":"y"},{"color":"#F0CF2E","text":" "},{"color":"#EFD12E","text":"a"},{"color":"#EDD32E","text":"s"},{"color":"#ECD52E","text":" "},{"color":"#EAD62F","text":"a"},{"color":"#E9D82F","text":" "},{"color":"#E7DA2F","text":"r"},{"color":"#E6DC2F","text":"o"},{"color":"#E4DE2F","text":"c"},{"color":"#E3DF30","text":"k"},{"color":"#E1E130","text":"e"},{"color":"#E0E330","text":"t"},{"color":"#DEE530","text":"."}],"text":""}',Items:[{Count:1b,Slot:0b,id:"minecraft:barrel",tag:{BlockEntityTag:{Items:[{Count:1b,Slot:0b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:"/effect clear @a[tag=Rocket,scores={shift=0}] minecraft:levitation",CustomName:'{"text":"@"}',LastExecution:109100L,LastOutput:'{"extra":[{"color":"red","extra":[{"translate":"commands.effect.clear.specific.failed"}],"text":""}],"text":"[18:17:31] "}',SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Unconditional"}],"text":""}'],Name:'{"italic":false,"color":"#FF38D4","text":"#3"}'}}},{Count:1b,Slot:1b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:"execute as @a[tag=Rocket,scores={shift=1..}] run effect give @s minecraft:levitation 1 6 true",CustomName:'{"text":"@"}',LastExecution:107572L,LastOutput:'{"extra":[{"translate":"commands.effect.give.success.single","with":[{"translate":"effect.minecraft.levitation"},{"insertion":"CkreaM","clickEvent":{"action":"suggest_command","value":"/tell CkreaM "},"hoverEvent":{"action":"show_entity","contents":{"type":"minecraft:player","id":"26a9b6de-63d5-4ce1-8d76-3e96ca43583d","name":{"text":"CkreaM"}}},"text":"CkreaM"},"1"]}],"text":"[18:16:14] "}',SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:0b,id:"minecraft:command_block",powered:1b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Conditional"}],"text":""}'],Name:'{"italic":false,"color":"#FF38D4","text":"#2"}'}}},{Count:1b,Slot:2b,id:"minecraft:repeating_command_block",tag:{BlockEntityTag:{Command:"execute as @a[tag=Rocket,scores={shift=1..1}] at @s run particle minecraft:flame ~ ~ ~ 0.235 0.235 0.235 0.1 50",CustomName:'{"text":"@"}',LastExecution:108822L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:0b,conditionMet:1b,id:"minecraft:command_block",powered:1b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Unconditional"}],"text":""}'],Name:'{"italic":false,"color":"#FF38D4","text":"#1"}'}}},{Count:1b,Slot:3b,id:"minecraft:lever"},{Count:1b,Slot:8b,id:"minecraft:paper",tag:{display:{Name:'{"italic":false,"color":"#3DD1FF","text":"Tag: Rocket"}'}}},{Count:1b,Slot:17b,id:"minecraft:repeating_command_block",tag:{BlockEntityTag:{Command:"/scoreboard players set @a shift 0",CustomName:'{"text":"@"}',LastExecution:111379L,LastOutput:'{"extra":[{"translate":"commands.scoreboard.players.set.success.multiple","with":[{"translate":"chat.square_brackets","with":[{"hoverEvent":{"action":"show_text","contents":{"text":"shift"}},"text":"Shift"}]},"2","0"]}],"text":"[18:19:25] "}',SuccessCount:1,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Name:'{"italic":false,"color":"#CCFF3C","text":"Shift Reset"}'}}},{Count:1b,Slot:26b,id:"minecraft:command_block",tag:{BlockEntityTag:{Command:'execute run scoreboard objectives add shift minecraft.custom:minecraft.sneak_time "Shift"',CustomName:'{"text":"@"}',SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Name:'{"italic":false,"color":"#CCFF3C","text":"Shift Scoreboard"}'}}}],id:"minecraft:barrel"},display:{Name:'{"extra":[{"bold":true,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"yellow","text":"Shift Score & Rocket"}],"text":""}'}}},{Count:1b,Slot:1b,id:"minecraft:barrel",tag:{BlockEntityTag:{Items:[{Count:1b,Slot:0b,id:"minecraft:lever"},{Count:1b,Slot:1b,id:"minecraft:repeating_command_block",tag:{BlockEntityTag:{Command:"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slow_falling 1 5 true",CustomName:'{"text":"@"}',LastExecution:5326927L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:0b,conditionMet:1b,id:"minecraft:command_block",powered:1b},display:{Name:'{"italic":false,"color":"#FF25BC","text":"#1"}'}}},{Count:1b,Slot:2b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:jump_boost 1 3 true",CustomName:'{"text":"@"}',LastExecution:5326945L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:1b},display:{Name:'{"italic":false,"color":"#FF25BC","text":"#2"}'}}},{Count:1b,Slot:3b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slowness 1 1 true",CustomName:'{"text":"@"}',LastExecution:5326962L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Name:'{"italic":false,"color":"#FF25BC","text":"#3"}'}}},{Count:1b,Slot:4b,id:"minecraft:leather_boots",tag:{Damage:0,HideFlags:100,Tags:"moonwalk",Unbreakable:1b,display:{Lore:['["",{"text":"Low Gravity Boots","italic":false,"color":"dark_gray","bold":true}]'],Name:'{"bold":true,"italic":false,"color":"#7FD1CD","text":"Moon Boots"}',color:10327205}}},{Count:1b,Slot:5b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:6b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:7b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:8b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:9b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:10b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:11b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:12b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:13b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:14b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:15b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:16b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:17b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:18b,id:"minecraft:oak_sign",tag:{BlockEntityTag:{Text1:'{"text":"Right Click to","clickEvent":{"action":"run_command","value":"execute run setblock ~1 ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slowness 1 1 true\\"}"},"color":"#FFE26E"}',Text2:'{"text":"get Moon Boots","clickEvent":{"action":"run_command","value":"execute run setblock ~-1 ~ ~ minecraft:repeating_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slow_falling 1 5 true\\"}"},"color":"#FFE26E"}',Text3:'{"text":"=======","clickEvent":{"action":"run_command","value":"execute run setblock ~ ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:jump_boost 1 3 true\\"}"},"color":"#FFCB29"}',Text4:'{"text":"EZ SETUP","clickEvent":{"action":"run_command","value":"execute run setblock ~-2 ~ ~ minecraft:lever[facing=west]"},"bold":true,"color":"#FFD257"}'},display:{Lore:['{"italic":false,"color":"#FFE262","text":"Instantly sets up the command blocks"}'],Name:'{"bold":true,"italic":false,"extra":[{"color":"#FFE85F","text":"E"},{"color":"#FFE966","text":"Z"},{"color":"#FFEA6D","text":" "},{"color":"#FFEB74","text":"S"},{"color":"#FFEC7B","text":"E"},{"color":"#FFED82","text":"T"},{"color":"#FFEE89","text":"U"},{"color":"#FFEF90","text":"P"}],"text":""}'}}},{Count:1b,Slot:19b,id:"minecraft:oak_sign",tag:{BlockEntityTag:{Text1:'{"text":"Right Click to","clickEvent":{"action":"run_command","value":"execute run setblock ~1 ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slowness 1 1 true\\"}"},"color":"#FFE26E"}',Text2:'{"text":"get Moon Boots","clickEvent":{"action":"run_command","value":"execute run setblock ~-1 ~ ~ minecraft:repeating_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slow_falling 1 5 true\\"}"},"color":"#FFE26E"}',Text3:'{"text":"=======","clickEvent":{"action":"run_command","value":"execute run setblock ~ ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:jump_boost 1 3 true\\"}"},"color":"#FFCB29"}',Text4:'{"text":"EZ SETUP","clickEvent":{"action":"run_command","value":"execute run setblock ~-2 ~ ~ minecraft:lever[facing=west]"},"bold":true,"color":"#FFD257"}'},display:{Lore:['{"italic":false,"color":"#FFE262","text":"Instantly sets up the command blocks"}'],Name:'{"bold":true,"italic":false,"extra":[{"color":"#FFE85F","text":"E"},{"color":"#FFE966","text":"Z"},{"color":"#FFEA6D","text":" "},{"color":"#FFEB74","text":"S"},{"color":"#FFEC7B","text":"E"},{"color":"#FFED82","text":"T"},{"color":"#FFEE89","text":"U"},{"color":"#FFEF90","text":"P"}],"text":""}'}}},{Count:1b,Slot:20b,id:"minecraft:oak_sign",tag:{BlockEntityTag:{Text1:'{"text":"Right Click to","clickEvent":{"action":"run_command","value":"execute run setblock ~1 ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slowness 1 1 true\\"}"},"color":"#FFE26E"}',Text2:'{"text":"get Moon Boots","clickEvent":{"action":"run_command","value":"execute run setblock ~-1 ~ ~ minecraft:repeating_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slow_falling 1 5 true\\"}"},"color":"#FFE26E"}',Text3:'{"text":"=======","clickEvent":{"action":"run_command","value":"execute run setblock ~ ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:jump_boost 1 3 true\\"}"},"color":"#FFCB29"}',Text4:'{"text":"EZ SETUP","clickEvent":{"action":"run_command","value":"execute run setblock ~-2 ~ ~ minecraft:lever[facing=west]"},"bold":true,"color":"#FFD257"}'},display:{Lore:['{"italic":false,"color":"#FFE262","text":"Instantly sets up the command blocks"}'],Name:'{"bold":true,"italic":false,"extra":[{"color":"#FFE85F","text":"E"},{"color":"#FFE966","text":"Z"},{"color":"#FFEA6D","text":" "},{"color":"#FFEB74","text":"S"},{"color":"#FFEC7B","text":"E"},{"color":"#FFED82","text":"T"},{"color":"#FFEE89","text":"U"},{"color":"#FFEF90","text":"P"}],"text":""}'}}},{Count:1b,Slot:21b,id:"minecraft:oak_sign",tag:{BlockEntityTag:{Text1:'{"text":"Right Click to","clickEvent":{"action":"run_command","value":"execute run setblock ~1 ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slowness 1 1 true\\"}"},"color":"#FFE26E"}',Text2:'{"text":"get Moon Boots","clickEvent":{"action":"run_command","value":"execute run setblock ~-1 ~ ~ minecraft:repeating_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:slow_falling 1 5 true\\"}"},"color":"#FFE26E"}',Text3:'{"text":"=======","clickEvent":{"action":"run_command","value":"execute run setblock ~ ~ ~ minecraft:chain_command_block[conditional=false,facing=east]{Command:\\"execute as @a[nbt={Inventory:[{Slot:100b,tag:{Tags:moonwalk}}]}] run effect give @s minecraft:jump_boost 1 3 true\\"}"},"color":"#FFCB29"}',Text4:'{"text":"EZ SETUP","clickEvent":{"action":"run_command","value":"execute run setblock ~-2 ~ ~ minecraft:lever[facing=west]"},"bold":true,"color":"#FFD257"}'},display:{Lore:['{"italic":false,"color":"#FFE262","text":"Instantly sets up the command blocks"}'],Name:'{"bold":true,"italic":false,"extra":[{"color":"#FFE85F","text":"E"},{"color":"#FFE966","text":"Z"},{"color":"#FFEA6D","text":" "},{"color":"#FFEB74","text":"S"},{"color":"#FFEC7B","text":"E"},{"color":"#FFED82","text":"T"},{"color":"#FFEE89","text":"U"},{"color":"#FFEF90","text":"P"}],"text":""}'}}},{Count:1b,Slot:22b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:23b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:24b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:25b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:26b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}}],id:"minecraft:barrel"},display:{Name:'{"extra":[{"bold":true,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"yellow","text":"Moon Boots"}],"text":""}'}}},{Count:1b,Slot:2b,id:"minecraft:barrel",tag:{BlockEntityTag:{Items:[{Count:1b,Slot:0b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:'execute as @a[nbt={Inventory:[{Slot:-106b,tag:{Tags:["firespell"]}}]}] run item replace entity @s weapon.offhand with air',CustomName:'{"text":"@"}',LastExecution:5481539L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Unconditional"}],"text":""}'],Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FF38D4","text":"#4"}],"text":""}'}}},{Count:1b,Slot:1b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:'execute as @a[nbt={Inventory:[{Slot:-106b,tag:{Tags:["firespell"]}}]}] run item replace entity @s weapon.mainhand from entity @s weapon.offhand',CustomName:'{"text":"@"}',LastExecution:5481520L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:1b,id:"minecraft:command_block",powered:0b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Unconditional"}],"text":""}'],Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FF38D4","text":"#3"}],"text":""}'}}},{Count:1b,Slot:2b,id:"minecraft:chain_command_block",tag:{BlockEntityTag:{Command:'execute as @a[nbt={Inventory:[{Slot:-106b,tag:{Tags:["firespell"]}}]}] at @s run execute at @e[type=!#c:boats,type=!#c:minecarts,type=!#minecraft:arrows,type=!minecraft:glow_item_frame,type=!item,type=!minecraft:item_frame,type=!#minecraft:beehive_inhabitors,type=!minecraft:allay,type=!sheep,type=!chicken,type=!pig,type=!horse,type=!cow,type=!minecraft:axolotl,type=!minecraft:cat,type=!wolf,name=!,distance=..6.7] run setblock ~ ~ ~ fire',CustomName:'{"text":"@"}',LastExecution:5480531L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:1b,conditionMet:0b,id:"minecraft:command_block",powered:1b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Conditional"}],"text":""}'],Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FF38D4","text":"#2"}],"text":""}'}}},{Count:1b,Slot:3b,id:"minecraft:repeating_command_block",tag:{BlockEntityTag:{Command:'execute as @a[nbt={Inventory:[{Slot:-106b,tag:{Tags:["firespell"]}}]}] at @s run effect give @s minecraft:fire_resistance 30 255 true',CustomName:'{"text":"@"}',LastExecution:5481474L,SuccessCount:0,TrackOutput:1b,UpdateLastExecution:1b,auto:0b,conditionMet:1b,id:"minecraft:command_block",powered:1b},display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#F2FF3E","text":"Unconditional"}],"text":""}'],Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FF38D4","text":"#1"}],"text":""}'}}},{Count:1b,Slot:4b,id:"minecraft:lever"},{Count:1b,Slot:5b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:6b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:7b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:8b,id:"minecraft:paper",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#3DD1FF","text":"Item Tag: firespell"}],"text":""}'}}},{Count:1b,Slot:9b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:10b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:11b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:12b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:13b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:14b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:15b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:16b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:17b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:18b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:19b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:20b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:21b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:22b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:23b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:24b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:25b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"white","text":""}],"text":""}'}}},{Count:1b,Slot:26b,id:"minecraft:creeper_banner_pattern",tag:{HideFlags:32,Tags:["firespell"],display:{Lore:['{"bold":true,"italic":false,"color":"#F6D689","text":"==========="}','{"italic":false,"color":"#767676","text":"[F] To use."}','{"italic":false,"color":"#F5FFA7","text":"Sets your enemies onfire!"}','{"italic":false,"color":"#F5FFA7","text":""}','{"italic":false,"color":"#E5671D","text":"WARNING: THIS WILL DELETE ANY OFFHAND ITEM."}'],Name:'{"italic":false,"extra":[{"color":"#FFEE8F","extra":[{"text":"🔥"},{"bold":true,"extra":[{"color":"#FF4606","extra":[{"text":"F"}],"text":""},{"color":"#FF4E0C","extra":[{"text":"i"}],"text":""},{"color":"#FF5612","extra":[{"text":"r"}],"text":""},{"color":"#FF5E18","extra":[{"text":"e"}],"text":""},{"color":"#FF651F","extra":[{"text":" "}],"text":""},{"color":"#FF6D25","extra":[{"text":"S"}],"text":""},{"color":"#FF752B","extra":[{"text":"c"}],"text":""},{"color":"#FF7D31","extra":[{"text":"r"}],"text":""},{"color":"#FF8438","extra":[{"text":"o"}],"text":""},{"color":"#FF8C3E","extra":[{"text":"l"}],"text":""},{"color":"#FF9444","extra":[{"text":"l"}],"text":""}],"text":""}],"text":""},{"color":"#FFEE8F","extra":[{"text":"🔥"}],"text":""}],"text":""}'}}}],id:"minecraft:barrel"},display:{Name:'{"extra":[{"bold":true,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"yellow","text":"Fire Spell"}],"text":""}'}}}],id:"minecraft:shulker_box"},HideFlags:32,display:{Lore:['{"extra":[{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFC52C","text":"C"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFC730","text":"o"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFC934","text":"m"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFCC38","text":"m"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFCE3C","text":"a"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFD140","text":"n"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFD345","text":"d"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFD649","text":" "},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFD84D","text":"K"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFDB51","text":"i"},{"bold":false,"italic":false,"underlined":false,"strikethrough":false,"obfuscated":false,"color":"#FFDD55","text":"t"}],"text":""}'],Name:'{"bold":true,"italic":false,"extra":[{"color":"#FFBE2C","text":"I"},{"color":"#FEBF2C","text":" "},{"color":"#FCC12C","text":"i"},{"color":"#FBC32C","text":"d"},{"color":"#F9C52C","text":"e"},{"color":"#F8C62D","text":"n"},{"color":"#F6C82D","text":"t"},{"color":"#F5CA2D","text":"i"},{"color":"#F3CC2D","text":"f"},{"color":"#F2CE2D","text":"y"},{"color":"#F0CF2E","text":" "},{"color":"#EFD12E","text":"a"},{"color":"#EDD32E","text":"s"},{"color":"#ECD52E","text":" "},{"color":"#EAD62F","text":"a"},{"color":"#E9D82F","text":" "},{"color":"#E7DA2F","text":"r"},{"color":"#E6DC2F","text":"o"},{"color":"#E4DE2F","text":"c"},{"color":"#E3DF30","text":"k"},{"color":"#E1E130","text":"e"},{"color":"#E0E330","text":"t"},{"color":"#DEE530","text":"."}],"text":""}'}}},{Count:1b,Slot:14b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:15b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:16b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:17b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:18b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:19b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:20b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:21b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:22b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:23b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:24b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:25b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}},{Count:1b,Slot:26b,id:"minecraft:gray_stained_glass_pane",tag:{display:{Name:'{"italic":false,"color":"#FFFFFF","text":""}'}}}]}`
```
