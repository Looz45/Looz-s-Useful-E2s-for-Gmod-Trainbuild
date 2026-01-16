# Hello this chip was made to be a close representation of the 060 diesel shunter in derail valley. This chip has working gears, damage throttle and rpm.
# There is also a repair feature for those that are still learning the chip, its not overly complex but its more advanced than standard olc.
# Damage features include > Harsh downshifting, Gear crunches, Gearbox Failure, Engine overheating, Engine failure, Clutch wear, Clutch failure.
# Other features include Stalling, so RPMs matter in certain gears. Note Gear 1 you cannot stall in.
# This chip is designed to work with my startup, clag and control e2s. Which will be inside my Github
# 
#
# This is Version 2.5 (Early access, some bugs may be present)
# Created by #Looz45 (discord) and with the help of chatgpt, feel free to contact me if you have any questions.
# 
#
# Known issues; 
# When repairing the clutch and restarting the engine it will still say the clutch is broken when it isn't.
# When braking with chat commands it will say the brake is released when it isnt. 
#
#
# CHAT COMMANDS: (.throttle [-10 - + 10]) e.g .throttle 5 or .throttle -5. (.gear 1-6) (.brake 1[1 = indepentant, 2 = trainbrake, 3=handbrake] 1-0 = on or off) E.g .brake 1 1 = indepenant brake on >
# > .brake 1 0 = indepentant brake off, .brake 2 1 = trainbrake on and so forth.
# (.repair) repairs all damage
# (.currenttemps) reads current engine temperature (engine explodes at 200 degrees celcius)
# (.restart) restarts the engine, youll need to be in gear 1 for this.
#
# Think thats about it for now > Youtube tutorial here <url>
# Github <https://github.com/Looz45/Looz-s-Useful-E2s-for-Gmod-Trainbuild>
