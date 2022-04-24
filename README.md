# -ExitLoop
ArrayDisplay_GetSortColStruct(Const ByRef $aArray, $iCol)     ...     Switch $r         Case -1             $hi = $mi - 1         Case 1             $lo = $mi + 1         Case -2         ; &lt;============== added line             ExitLoop 2  ; &lt;============== added line         Case 0             ExitLoop     EndSwitch     ... EndFunc
