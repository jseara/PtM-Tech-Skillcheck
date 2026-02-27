Main files used in this mod:

Story/Scripts
  - PTM_Guard_Fight_Event
  - PTM_Guard_Key_Event
  - PTM_Button_Unlock

New Items
  - PTM_VerySmallButton
  - PTM_Dwarf_Guard
  - PTM_Key

Modified Existing Items
  - INTERACT_DOOR_Single_Dungeon_Abbey_B_000_545ec410-a068-404d-86f1-3566223c76d5

Interactions

  Door is now locked on level load, needs to be unlocked through one of three means.
  Dialogue tree w/ dwarven guard, pass intimidation check and he will unlock (PTM_Guard_Key_Event)
  If fail check, combat begins (PTM_Guard_Fight_Event)
  By Killing guard, you can pick up key (PTM_Key)
  Alternatively, there is a hidden button found with a trivial perception check. Press this button to unlock door. (PTM_Button_Unlock)

  (Or use the existing side door)

Bugs

  - Door does not open or close correctly, must just click through to enter the building.
  - On level reload, occassionally dialogue with dwarf can crash. Unsure as to why, need to fix.
  - Door currently ... glows after being assigned a door constellation. 
