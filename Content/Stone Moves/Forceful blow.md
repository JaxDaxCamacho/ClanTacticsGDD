Ability Name > Forceful Blow
Ability Cooldown > 2
Ability Type > Block&Counter
Initiative > 9
Movement Allowance > 0
Movement Requirement > 0
Rotation Allowance > 1
Rotation Requirement > 0
Action? (Attack, Block or etc) >
Forceful Block
	Action Type > Block
	Target Hex > Hex directly in front of user's facing
	Facing > User's Facing
	OnSuccessBlock > Trigger Forceful Strike
	OnFailBlock > Trigger Fumble
Forceful Strike
	Action Type > Attack
	Target Hex > Hex directly in front of user's facing
	Facing > User's Facing
	Damage > 4 + (3 * Ability Level)
	Armor Pen > 2
Fumble 
	Take  50% extra damage from incoming attack.