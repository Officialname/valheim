[ValheimPlus]

; Change false to true to enable this section. https://valheim.plus/documentation/list#ValheimPlus
enabled = true

; Display the Valheim Plus logo in the main menu
mainMenuLogo = true

; Display the advertisement of our server hosting partner on the server browser menu
serverBrowserAdvertisement = true

[AdvancedBuildingMode]

; https://docs.unity3d.com/ScriptReference/KeyCode.html <- a list of keycodes
; Change false to true to enable this section, if you set this to false the mode will not be accessible. https://valheim.plus/documentation/list#AdvancedBuildingMode
enabled = true

; Enter the advanced building mode with this key when building
enterAdvancedBuildingMode = F1

; Exit the advanced building mode with this key when building
exitAdvancedBuildingMode = F3

; Copy the object rotation of the currently selected object in ABM
copyObjectRotation = Keypad7

; Apply the copied object rotation to the currently selected object in ABM
pasteObjectRotation = Keypad8

; Increases the amount an object rotates and moves. Holding Shift will increase in increments of 10 instead of 1.
increaseScrollSpeed = KeypadPlus

; Decreases the amount an object rotates and moves. Holding Shift will decrease in increments of 10 instead of 1.
decreaseScrollSpeed = KeypadMinus

[AdvancedEditingMode]

; https://docs.unity3d.com/ScriptReference/KeyCode.html <- a list of keycodes
; Change false to true to enable this section, if you set this to false the mode will not be accessible. https://valheim.plus/documentation/list#AdvancedEditingMode
enabled = true

; Enter the advanced editing mode with this key
enterAdvancedEditingMode = Keypad0

; Reset the object to its original position and rotation
resetAdvancedEditingMode = F7

; Exit the advanced editing mode with this key and reset the object
abortAndExitAdvancedEditingMode = F8

; Confirm the placement of the object and place it
confirmPlacementOfAdvancedEditingMode = KeypadEnter

; Copy the object rotation of the currently selected object in AEM
copyObjectRotation = Keypad7

; Apply the copied object rotation to the currently selected object in AEM
pasteObjectRotation = Keypad8

; Increases the amount an object rotates and moves. Holding Shift will increase in increments of 10 instead of 1.
increaseScrollSpeed = KeypadPlus

; Decreases the amount an object rotates and moves. Holding Shift will decrease in increments of 10 instead of 1.
decreaseScrollSpeed = KeypadMinus

[Bed]

; Change false to true to enable this section
enabled = true

; Change false to true to enable sleeping without setting bed as spawn.
; When hovering over a bed you will be presented with a Hot-Key 'LShift+E'. This Hot-Key will allow for you to sleep on any bed without having to set a spawn-point.
sleepWithoutSpawn = true

; Change false to true to enable sleeping on only unclaimed beds without setting bed as spawn.
; With this option enabled only beds that are not claimed by other players can be slept on without setting spawn-point using 'Shift+E'
unclaimedBedsOnly = true

[Beehive]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Beehive
enabled = true

; Configure the speed at which the bees produce honey in seconds, 1200 seconds are 24 ingame hours.
honeyProductionSpeed = 1200

; Configure the maximum amount of honey in beehives.
maximumHoneyPerBeehive = 4

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = false

; The range of the chest detection for the auto deposit feature.
; Maximum is 50
autoDepositRange = 10

; Display the minutes and seconds until the beehive produces honey on crosshair hover.
showDuration = true

[Building]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Building
enabled = true

; Remove some of the Invalid placement messages, most notably provides the ability to place objects into other objects
noInvalidPlacementRestriction = true

; Removes the "Mystical forces" building prevention and allows destruction of build objects in those areas with the hammer.
noMysticalForcesPreventPlacementRestriction = true

; Removes the weather damage from rain and water erosion.
noWeatherDamage = true

; The maximum range in meters that you can place build objects at inside the hammer build mode.
maximumPlacementDistance = 8

; The radius, in meters, in which a piece must be to contribute to the comfort level.
pieceComfortRadius = 10

; When destroying a building piece, setting this to true will ensure it always drops full resources.
; We recommend to enable this if you use this section.
alwaysDropResources = true

; When destroying a building piece, setting this to true will ensure it always drops pieces that the devs have marked as "do not drop".
; We recommend to enable this if you use this section.
alwaysDropExcludedResources = false

; Setting this to true will cause repairing with the hammer to repair in a radius instead of a single piece.
enableAreaRepair = true

; Sets the area repair radius of enableAreaRepair. A value of 7.5 would mean your repair radius is 7.5 meters.
; Requires enableAreaRepair=true
areaRepairRadius = 7.5

[Camera]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Camera
enabled = true

; The maximum zoom distance to your character in-game.
; Default is 6
cameraMaximumZoomDistance = 6

; The maximum zoom distance to your character when in a boat.
; Default is 6
cameraBoatMaximumZoomDistance = 6

; The in-game camera FOV.
; Default is 65
cameraFOV = 65

[Experience]

; Change false to true to enable this section. This section contains modifiers. https://valheim.plus/documentation/list#Experience
; Modifiers are increases and reduction in percent declared by 50, or -50. The value 50 will increase experience gained by 50%, -50 will reduce experience gained by 50%.
enabled = true

; The modifier value for the experience gained of swords.
swords = 0

; The modifier value for the experience gained of knives.
knives = 0

; The modifier value for the experience gained of clubs.
clubs = 0

; The modifier value for the experience gained of polearms.
polearms = 0

; The modifier value for the experience gained of spears.
spears = 0

; The modifier value for the experience gained of blocking.
blocking = 0

; The modifier value for the experience gained of axes.
axes = 0

; The modifier value for the experience gained of bows.
bows = 0

; The modifier value for the experience gained of fire magic.
fireMagic = 0

; The modifier value for the experience gained of frost magic.
frostMagic = 0

; The modifier value for the experience gained of unarmed.
unarmed = 0

; The modifier value for the experience gained of mining.
pickaxes = 0

; The modifier value for the experience gained of wood cutting.
woodCutting = 0

; The modifier value for the experience gained of jumping.
jump = 0

; The modifier value for the experience gained of sneaking.
sneak = 0

; The modifier value for the experience gained of running.
run = 0

; The modifier value for the experience gained of swimming.
swim = 0

[Fermenter]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Fermenter
enabled = true

; Configure the time that the fermenter takes to produce its product, 2400 seconds are 48 ingame hours.
fermenterDuration = 2400

; Configure the total amount of produced items from a fermenter.
fermenterItemsProduced = 6

; Display the minutes and seconds until the fermenter is done on crosshair hover.
showDuration = true

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; Automatically pull meads from nearby chests to be placed inside the Fermenter as soon as its empty.
autoFuel = true

; This option prevents the fermenter to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and auto fuel features
; Maximum is 50
autoRange = 10

[FireSource]

; Change false to true to enable this section. https://valheim.plus/documentation/list#FireSource
enabled = true

; If set to true, torch-type fire sources will stay at max fuel level once filled.
; Applies to: wood torches, iron torches, green torches, sconces and brazier.
torches = true

; If set to true, non torch-type fire sources will stay at max fuel level once filled.
fires = true

; Automatically pull wood from nearby chests to be placed inside the Fire as soon as its empty.
autoFuel = true

; This option prevents the Fire to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto fuel features.
; Maximum is 50
autoRange = 10

[Food]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Food
enabled = true

; Increase or reduce the time that food lasts by %.
; The value 50 would cause food to run out 50% slower, -50% would cause the food to run out 50% faster.
foodDurationMultiplier = 0

; This option prevents food degrading over time - in other words, it retains its maximum benefit until it runs out instead of reducing its effect over time.
disableFoodDegradation = true

[Smelter]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Smelter
enabled = true

; Maximum amount of ore in a Smelter.
maximumOre = 10

; Maximum amount of coal in a Smelter.
maximumCoal = 20

; The total amount of coal used to produce a single smelted ingot.
coalUsedPerProduct = 2

; The time it takes for the Smelter to produce a single ingot in seconds.
productionSpeed = 30

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; The Smelter will pull coal and raw materials from nearby chests to be automatically added to it when its empty.
autoFuel = true

; This option prevents the Smelter to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and auto fuel features.
; Maximum is 50
autoRange = 10

[Furnace]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Furnace
enabled = true

; Maximum amount of ore in a Furnace.
maximumOre = 10

; Maximum amount of coal in a Furnace.
maximumCoal = 20

; The total amount of coal used to produce a single smelted ingot.
coalUsedPerProduct = 2

; The time it takes for the Furnace to produce a single ingot in seconds.
productionSpeed = 30

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; The Furnace will pull coal and raw materials from nearby chests to be automatically added to it when its empty.
autoFuel = true

; This option prevents the Furnace to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and auto fuel features.
; Maximum is 50
autoRange = 10

; This option allows all ores inside the Furnace.
allowAllOres = true

[Game]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Game
enabled = true

; The games damage multiplier per person nearby in difficultyScaleRange(m) radius.
; Default is 4% monster damage increase per player in radius.
gameDifficultyDamageScale = 4

; The games health multiplier per person nearby in difficultyScaleRange(m) radius.
; Default is 40% monster health increase per player in radius.
gameDifficultyHealthScale = 40

; Adds additional players to the difficulty calculation in multiplayer unrelated to the actual amount.
; This option is disabled if its set to 0.
extraPlayerCountNearby = 0

; Sets the nearby player count always to this value + extraPlayerCountNearby.
; This option is disabled if its set to 0.
setFixedPlayerCountTo = 0

; The range in meters at which other players count towards nearby players for the difficulty scale.
difficultyScaleRange = 200

; If you set this to true, all portals will be disabled.
disablePortals = false

; If you set this to true the console will be force enabled in-game, false will force disable it.
forceConsole = true

;If you set this to true, portal names will be displayed in big text in center of screen.
bigPortalNames = true

;Remove dense fog from the game.
disableFog = false

[Hotkeys]

; https://docs.unity3d.com/ScriptReference/KeyCode.html <- a list of keycodes
; Change false to true to enable this section. https://valheim.plus/documentation/list#Hotkeys
enabled = true

; Roll forwards on hot key pressed.
rollForwards = F9

; Roll backwards on hot key pressed.
rollBackwards = F10

[Items]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Items
enabled = true

; Enables you to teleport with ores and other usually teleport restricted objects.
noTeleportPrevention = true

; Increase or reduce item weight by a modifier in percent.
; The value -50 will reduce item weight of every object by 50%, 50 will increase the weight of every item by 50%.
baseItemWeightReduction = 0

; Increase or reduce the size of all maximum item stacks by a modifier in percent.
; The value 50 would set a usual item stack of 100 to be 150.
; The value -50 would set a usual item stack of 100 to be 50.
itemStackMultiplier = 0

; Set duration that dropped items stay on the ground before they are despawning. Game default is 3600 seconds.
droppedItemOnGroundDurationInSeconds = 3600

[Hud]

; Change false to true to enable this section. https://valheim.plus/documentation/list#HUD
enabled = true

; Shows the required amount of items AND the amount of items in your inventory in build mode and while crafting.
; This is enabled when the CraftFromChest section is enabled.
showRequiredItems = true

; Shows small notifications about all skill experienced gained in the top left corner.
experienceGainedNotifications = true

; Set to true to remove the red screen flash overlay when the player takes damage.
removeDamageFlash = false

; If bow is in hotbar, display current ammo & total ammo under hotbar icon - never (0), when equipped (1), or always (2).
displayBowAmmoCounts = 0

[Gathering]

; Change false to true to enable this section. This section contains modifiers. Modifiers are increases and reduction in percent declared by 50, or -50. https://valheim.plus/documentation/list#Gathering
enabled = true

; Modify the chance to drop resources from resource nodes affected by this category. This only works on resource nodes that do not have guaranteed drops.
; As example by default scrap piles in dungeons have a 20% chance to drop a item, if you set this option to 200, you will then have a 60% chance to drop iron.
dropChance = 0

; Each of these values increase or reduce the dropped items from destroyed objects with tools (Stones, Trees, Resource nodes, etc.) by %.
; The value 50 will increase the dropped wood from trees from 10 to 15. The value -50 will reduce the amount of dropped wood from 10 to 5.
wood = 0
stone = 0
fineWood = 0
coreWood = 0
elderBark = 0
ironScrap = 0
tinOre = 0
copperOre = 0
silverOre = 0
chitin = 0

[Pickable]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Pickable
; Each value below (in percent) will modify the yield when "picking" items (default key E) such as berries and flowers.
; A value of 100 will double drops, 200 will triple and so on.
enabled = true

; All berries, all mushrooms, and carrots
edibles = 0

; Barley, Flax, Dandelion, Thistle, Carrot Seeds, Turnip Seeds, Turnip
flowersAndIngredients = 0

; Bone Fragments, Flint, Stone, Wood (branches on the ground)
materials = 0

; Amber, Amber Pearl, Coins, Ruby
valuables = 0

; Surtling Core only
surtlingCores = 0

[Durability]

; Change false to true to enable this section. This section contains modifiers. https://valheim.plus/documentation/list#Durability
; Modifiers are increases and reduction in percent declared by 50, or -50.
enabled = true

; Each of these values increase or reduce the durability of the specific item type by %.
; The value 50 will increase the durability from 100 to 150. The value -50 will reduce the durability from 100 to 50.
axes = 0
pickaxes = 0
hammer = 0
cultivator = 0
hoe = 0
weapons = 0
armor = 0
bows = 0
shields = 0
torch = 0

[Armor]

; Change false to true to enable this section. This section contains modifiers. https://valheim.plus/documentation/list#Armor
; Modifiers are increases and reduction in percent declared by 50, or -50.
enabled = true

; Each of these values increase or reduce the armor of the specific item type by %.
; The value 50 will increase the armor from 14 to 21. The value -50 will reduce the armor from 14 to 7.
helmets = 0
chests = 0
legs = 0
capes = 0

[Kiln]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Kiln
enabled = true

; Maximum amount of wood in a Kiln.
maximumWood = 25

; Change false to true to disable Fine Wood processing.
dontProcessFineWood = false

; Change false to true to disabled Round Log processing.
dontProcessRoundLog = false

; The time it takes for the Kiln to produce a single piece of coal in seconds.
productionSpeed = 15

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; The Kiln will pull wood from nearby chests to be automatically added to it when its empty.
; This option respects the dontProcessFineWood and dontProcessRoundLog settings.
autoFuel = true

; Stops autoFuel (looking for fuel) when there is at leasts this quantity of Coal in nearby chests
; (ignored if set to 0)
stopAutoFuelThreshold = 0

; This option prevents the Kiln to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and fuel features.
; Maximum is 50
autoRange = 10

[Map]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Map
enabled = true

; With this enabled you will receive the same exploration progression as other players on the server.
; This will also enable the option for the server to sync everyones exploration progression on connecting to the server.
shareMapProgression = true

; The radius of the map that you explore when moving.
exploreRadius = 100

; Prevents you and other people on the server to turn off their map sharing option.
preventPlayerFromTurningOffPublicPosition = false

; Allow pins to be shared
shareablePins = true

; Shares all pins always
shareAllPins = true

; Display carts and boats on the map
displayCartsAndBoats = true

[Player]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Player
enabled = true

; The base amount of carry weight of your character.
baseMaximumWeight = 300

; Increase the buff you receive to your carry weight from Megingjord's girdle.
baseMegingjordBuff = 150

; Increase auto pickup range of all items.
baseAutoPickUpRange = 2

; Disable all types of camera shake.
disableCameraShake = true

; The base unarmed damage multiplied by your skill level. 120 will result in a maximum of up to 12 damage when you have a skill level of 10.
baseUnarmedDamage = 70

; When changed to true, you will not be permitted to place a crop within the grow radius of another crop.
cropNotifier = true

; How many seconds each comfort level contributes to the rested bonus.
restSecondsPerComfortLevel = 60

; Change the death penalty in percentage, where higher will increase the death penalty and lower will reduce it.
; This is a modifier value. 50 will increase it by 50%, -50 will reduce it by 50%.
deathPenaltyMultiplier = 0

; If set to true, this option will automatically repair your equipment when you interact with the appropriate workbench.
autoRepair = true

; Boss buff duration (seconds)
guardianBuffDuration = 300

; Boss buff cooldown (seconds)
guardianBuffCooldown = 1200

; Disable the Guardian Buff animation
disableGuardianBuffAnimation = false

; If set to true, when equipping a one-handed weapon, the best shield from your inventory is automatically equipped.
; (Best is determined by highest block power)
autoEquipShield = false

; If set to true, weapon switches requested mid-attack will be carried out when the current attack is finished instead of being ignored.
queueWeaponChanges = false

; If set to true, you will always skip the intro of the game.
skipIntro = true

; If set to false, disables the "I have arrived!" message on player spawn.
iHaveArrivedOnSpawn = true

; If set to true, items will be re-equipped when you exit water after swimming (if they were hidden automatically)
reequipItemsAfterSwimming = true

; This value represents how much the fall damage should be scaled in +/- %. This is a modifier value.
; The value 50 would result in 50% increased fall damage. The value -50 would result in 50% reduced fall damage.
fallDamageScalePercent = 0

; Max fall damage. Game default is 100 (so with enough health, falls can't kill).
maxFallDamage = 100

; If set to true, all tutorials will skip from now on. You can turn this config off and reset the tutorial (in the settings) at any time.
skipTutorials = true

; Disable encumbered
disableEncumbered = false

[Server]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Server
enabled = true

; Modify the maximum amount of players on your Server.
maxPlayers = 10

; Removes the requirement to have a server password.
disableServerPassword = false

; This settings add a version control check to make sure that people that try to join your game or the server you try to join has V+ installed
; WE HEAVILY RECOMMEND TO NEVER DISABLE THIS!
enforceMod = true

; Changes whether the server will force it's config on clients that connect. Only affects servers.
; WE HEAVILY RECOMMEND TO NEVER DISABLE THIS!
serverSyncsConfig = true

; If false allows you to keep your own defined hotkeys instead of synchronising the ones declared for the server.
; Sections need to be enabled in your local configuration to load hotkeys.
; This is a client side setting and not affected by server settings.
serverSyncHotkeys = false

[Stamina]

; Change false to true to enable this section. This section contains modifiers. https://valheim.plus/documentation/list#Stamina
; Modifiers are increases and reduction in percent declared by 50, or -50.
enabled = true

; Changes the amount of stamina cost of using the dodge roll by %
dodgeStaminaUsage = 0

; Changes the stamina drain of being overweight by %
encumberedStaminaDrain = 0

; Changes the stamina cost of jumping by %
jumpStaminaDrain = 0

; Changes the stamina cost of running by %
runStaminaDrain = 0

; Changes the stamina drain by sneaking by %
sneakStaminaDrain = 0

; Changes the total amount of stamina recovered per second by %
staminaRegen = 0

; Changes the delay until stamina regeneration sets in by %
staminaRegenDelay = 0

; Changes the stamina drain of swimming by %
swimStaminaDrain = 0

[StaminaUsage]

; Change false to true to enable this section. This section contains modifiers. https://valheim.plus/documentation/list#StaminaUsage
; Modifiers are increases and reduction in percent declared by 50, or -50.
enabled = true

; Each of these values change the respective tool in stamina usage by increases and reduction in percent declared by 50, or -50.
axes = 0
blocking = 0
bows = 0
clubs = 0
knives = 0
pickaxes = 0
polearms = 0
spears = 0
swords = 0
unarmed = 0
hammer = 0
hoe = 0
cultivator = 0

[StructuralIntegrity]

; Change false to true to enable this section. https://valheim.plus/documentation/list#StructuralIntegrity
enabled = true

; Disables the entire structural integrity system and allows for placement in free air, does not prevent building damage.
disableStructuralIntegrity = true

; Disables any damage from anything to all player built structures. Does not prevent damage from structural integrity.
disableDamageToPlayerStructures = true

; Disables any damage from anything to all player built boats.
disableDamageToPlayerBoats = true

; Disables water force damage to all player built boats.
disableWaterDamageToPlayerBoats = true

; Each of these values reduce the loss of structural integrity by distance by % less.
; The value 100 would result in disabled structural integrity over distance, does not allow for placement in free air without disableStructuralIntegrity.
wood = 0
stone = 0
iron = 0
hardWood = 0

[Ward]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Ward
enabled = true

; The range of wards by meters.
wardRange = 20

; Set the enemy spawn radius around wards in meters
; This value equals wardRange if its set to 0.
wardEnemySpawnRange = 0

[Workbench]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Workbench
enabled = true

; Set the workbench radius in meters.
workbenchRange = 20

; Set the enemy spawn radius around workbenches in meters
; This value equals workbenchRange if its set to 0.
workbenchEnemySpawnRange = 0

; Sets the workbench attachment (e.g. anvil) radius.
workbenchAttachmentRange = 5

; Disables the roof and exposure requirement to use a workbench.
disableRoofCheck = true

[Wagon]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Wagon
enabled = true

; Change the base wagon physical mass of the wagon object.
; This is essentially the base weight of a cart.
wagonBaseMass = 20

; This value changes the physical weight of wagons by +/- more/less from item weight inside.
; The value 50 would increase the weight by 50% more. The value -100 would remove the entire extra weight.
wagonExtraMassFromItems = 0

[Inventory]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Inventory
enabled = true

; Player inventory number of rows (inventory is resized up to 6 rows, higher values will add a scrollbar). default 4, min 4, max 20
playerInventoryRows = 4

; Wood chest number of columns
; (default 5, 5 min, 8 max)
woodChestColumns = 5

; Wood chest number of rows (more than 4 rows will add a scrollbar).
; (default 2, min 2, 10 max)
woodChestRows = 2

; Personal chest number of columns.
; (default 3, 3 min, 8 max)
personalChestColumns = 3

; Personal chest number of rows
; (default 2, 2 min, 20 max)
personalChestRows = 2

; Iron chests already have 8 columns by default but now you can lower it
; (default 8, min 6, max 8)
ironChestColumns = 8

; Iron chest number of rows (more than 4 rows will add a scrollbar)
; (default 4, min 3, max 20)
ironChestRows = 4

; Cart (Wagon) inventory number of columns
; (default 8, min 6, max 8)
cartInventoryColumns = 8

; Cart (Wagon) inventory number of rows (more than 4 rows will add a scrollbar)
; (default 3, min 3, max 30)
cartInventoryRows = 3

; Karve (small boat) inventory number of columns
; (default 2, min 2, max 8)
karveInventoryColumns = 2

; Karve (small boat) inventory number of rows (more than 4 rows will add a scrollbar)
; (default 2, min 2, max 30)
karveInventoryRows = 2

; Longboat (large boat) inventory number of columns
; (default 8, min 6, max 8)
longboatInventoryColumns = 8

; Longboat (large boat) inventory number of rows (more than 4 rows will add a scrollbar)
; (default 3, min 3, max 30)
longboatInventoryRows = 3

; By default tools and weapons go into inventories top to bottom and other materials bottom to top.
; Set to true to make all items go into the inventory top to bottom.
inventoryFillTopToBottom = false

; By default items go to their original position when picking up your tombstone.
; Set to true to make all stacks try to merge with an existing stack first.
mergeWithExistingStacks = true

[FreePlacementRotation]

; Change false to true to enable this section, if you set this to false the mode will not be accessible. https://valheim.plus/documentation/list#FreePlacementRotation
enabled = true

; Rotates placement marker by 1 degree with keep ability to attach to nearly pieces.
rotateY = LeftAlt
rotateX = C
rotateZ = V

; Copy rotation of placement marker from target piece in front of you.
copyRotationParallel = F

; Set rotation to be perpendicular to piece in front of you.
copyRotationPerpendicular = G

[Shields]

; Change false to true to enable this section, if you set this to false the mode will not be accessible. https://valheim.plus/documentation/list#Shields
enabled = true

; Increase or decrease the block value on all shields in %. -50 would be 50% less block rating, 50 would be 50% more block rating.
blockRating = 0

[FirstPerson]

; Change false to true to enable this section. https://valheim.plus/documentation/list#FirstPerson
enabled = true

; Hotkey to enable First Person.
hotkey = F10

; Default Field Of View to use.
defaultFOV = 65.0

; Hotkey to raise Field Of View.
raiseFOVHotkey = PageUp

; Hotkey to lower Field Of View.
lowerFOVHotkey = PageDown

[GridAlignment]

; Change false to true to enable this section. https://valheim.plus/documentation/list#GridAlignment
; This offers a global fixed grid system to make precise placements.
enabled = false

; Key to enable grid alignment.
align = LeftAlt

; Key to toggle grid alignment.
alignToggle = F7

; Key to change the default alignment.
changeDefaultAlignment = F6

[CraftFromChest]

; Change false to true to enable this section. https://valheim.plus/documentation/list#CraftFromChest
; This feature allows you to craft from nearby chests when in range.
enabled = false

; Change false to true to disable this feature when using a Cooking Station.
disableCookingStation = false

; If in a workbench area, uses it as reference point when scanning for chests.
checkFromWorkbench = true

; This option prevents crafting to pull items from warded areas if the player doesnt have access to it.
ignorePrivateAreaCheck = false

; The range of the chest detection in meters.
range = 20

; The interval in seconds that the feature scans your nearby chests.
; We recommend not going below 3 seconds.
lookupInterval = 3

[Windmill]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Windmill
enabled = true

; Maximum amount of barley in a windmill.
maximumBarley = 50

; The time it takes for the windmill to produce a single ingot in seconds.
productionSpeed = 10

; Ignore wind intensity so it always takes the production speed value to process one barley.
ignoreWindIntensity = true

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; The Windmill will pull barley from nearby chests to be automatically added to it when its empty.
autoFuel = true

; This option prevents the Windmill to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and auto fuel features.
; Maximum is 50
autoRange = 10

[SpinningWheel]

; Change false to true to enable this section. https://valheim.plus/documentation/list#SpinningWheel
enabled = true

; Maximum amount of flax in a spinning wheel.
maximumFlax = 50

; The time it takes for the spinning wheel to produce linen thread.
productionSpeed = 30

; Instead of dropping the items, they will be placed inside the nearest nearby chests.
autoDeposit = true

; The Spinning Wheel will pull flax from nearby chests to be automatically added to it when its empty.
autoFuel = true

; This option prevents the Spinning Wheel to pull items from warded areas if it isn't placed inside of it.
; For convenience, we recommend this to be set to true.
ignorePrivateAreaCheck = true

; The range of the chest detection for the auto deposit and auto fuel features
; Maximum is 50
autoRange = 10

[PlayerProjectile]

; Change false to true to enable this section. https://valheim.plus/documentation/list#PlayerProjectile
enabled = true

; Value of 50 would increase the minimum charge velocity from 2 to 3.
playerMinChargeVelocityMultiplier = 0

; Value of 50 would increase the maximum charge velocity (of Finwood bow) from 50 to 75.
playerMaxChargeVelocityMultiplier = 0

; Value of (+)50 increase in accuracy will change the variance of arrows 20 degree to 10 degree at the point of minimum charge release.
playerMinChargeAccuracyMultiplier = 0

; Value of (+)50 increase in accuracy will change the variance of arrows 1 degree to 0.5 degree at the point of maximum charge release.
playerMaxChargeAccuracyMultiplier = 0

; Enabling this option will linearly scale by skill level from the base values of the weapon to the modified values (according to multipliers above).
enableScaleWithSkillLevel = false

[MonsterProjectile]

; Change false to true to enable this section. https://valheim.plus/documentation/list#MonsterProjectile
enabled = true

; Value of 10 would increase the projectile velocity from 50 to 55.
monsterMaxChargeVelocityMultiplier = 0

; Value of (+)10 increase in accuracy will change the variance of projectile 1 degree to 0.9 degree at the point of projectile release.
monsterMaxChargeAccuracyMultiplier = 0

[Tameable]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Tameable
enabled = true

; Modify what happens when a tamed creature is attacked.
; 0 = normal, 1 = essential(deadly attacks stun instead of kill), 2 = immortal.
mortality = 0

; Change to true so only the owner of a tamed creature can hurt it. This will circumvent the mortality setting, so even if tamed creatures are immortal, the owner can still kill them.
ownerDamageOverride = true

; How long it takes for a tamed creature to recover if mortality is set to 1(essential) and they are stunned.
stunRecoveryTime = 10

[GameClock]

; Change false to true to enable this section. https://valheim.plus/documentation/list#GameClock
enabled = true

; Change time formatting from 24hr to AM-PM.
useAMPM = true

; Change font size of time text.
textFontSize = 34

; Change how red the time text is (51/255).
textRedChannel = 248

; Change how green the time text is (51/255).
textGreenChannel = 105

; Change how blue the time text is (51/255).
textBlueChannel = 0

; Change how transparent the time text is (255 is solid with no transparency).
textTransparencyChannel = 255

[Brightness]

; Change false to true to enable this section. https://valheim.plus/documentation/list#Brightness
enabled = true

; Changes how bright it looks at night. A value between 5 and 10 will result in nearly double in brightness at night.
nightBrightnessMultiplier = 0
