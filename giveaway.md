# Sinvite: Help with giveaway commands

## `role_requirement_type`

### All roles required (`all`)

**All** the roles specified in the `role_requirements` parameter are required in order to be eligible to enter the giveaway.

### One or more required (`one_of`)
Having **one or more** roles specified in the `role_requirements` parameter makes one eligible to enter the giveaway.

## `additional_entry_type`

### Additional entries are cumulative (stack them) (`cumulative`)

For each role listed in `additional_entry_roles`, the additional entries will be added to the user, thereby increasing their chance of winning in the raffle.

### Use role with highest additions only (`highest`)
  - For whichever roles listed in `additional_entry_roles` that a user has, only the one with the highest additional entry amount is added to their total entries.
