# Spiral-knights-Autofarm

password is mathews birthday 

# setup
--------------------
extract all
*note rich1.jar , rich2.jar, rich_launcher.jar

*GAMEDIR = C:\Program Files (x86)\Steam\steamapps\common\Spiral Knights

make folder NAMED ->rich_mods     
move rich_mods.folder -> GAMEDIR
move rich_launcer.jar -> GAMEDIR

move rich1.jar -> GAMEDIR\code
move rich_config.yml -> GAMEDIR\code

move rich2.jar -> GAMEDIR\rsrc

configure rich_config.yml to your hearts content

not ocr based
optional =
{ 
  use mods rated for (Knight_launcher by Lucas.l) to strip most graphics & save electricity
  dont put those mods into GAMEDIR\mods
  move them -> GAMEDIR\rich_mods
  create a shortcut for rich_launcher.jar on your desktop for easier access
}

run rich_laucner.jar
type /rich into the console.

if you recive unknown command, thats bad
# usage
/rich start # begins the autofarm
/rich stop # stops autofarming
/rich panic # disables all
Any mods in GAMEDIR\mods can only be used by knight laucner, 
move them into GAMEDIR\rich_mods to see effect

# note
restart = pick gate x at tier y

autofarm will autoattack with whatever is in tool 1. keep a sword there!
restarts on 2nd death

no machine learning was involved. therfore it cannot solve most...all? puzzles
restarts on (pickable_statue, switch, blue ghost block) entering your FOV

will prioritize destroying bushes and rocks after monsters
(basically everything in case theres a button it needs to stand on)

at tier 3: 4kcr per hour.
