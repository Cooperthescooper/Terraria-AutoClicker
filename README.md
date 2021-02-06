# Terraria-AutoClicker
holed down Left click and it repeats the click really fast 

LMouse::
Loop {
    Getkeystate, State, LMouse, P
    If State=U
    Break
    Sendinput {Click}
    Sleep 10
}
Return
