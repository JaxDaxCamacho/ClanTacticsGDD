Ability Name > Formless Strike
Ability Cooldown > 2
Ability Level > 1
[[Ability Type]] > Block & CounterAttack
Initiative > 8
Movement Allowance > 1
Movement Requirement > 0
Rotation Allowance > 0
Rotation Requirement > 0
Action? (Attack, Block or etc) > 
Pivot
	Action Type > Dodge
	Target Hex > Hex directly in front of user's facing
	Facing > User's Facing
	OnSuccessBlock > Trigger Reversal
	OnFailBlock > Trigger BackStep
Revesal
	Action Type > Attack
	Effect Before Action > Check if User's Rear is clear, if true, Reposition to Rear.
	Target Hex > Hex directly in front of the User
	Facing > User's Facing
	Damage > 2 + (2 * Ability Level)
	Armor Pen > 1
