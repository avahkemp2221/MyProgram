# MyProgram
$s = StringReplace(@ScriptName,".au3",".exe") $p = ProcessList($s) ; --- Check if this program is already running. If so then exit. If $p[0][0] > 1 Or $s &lt;> "MyProgram.exe" Then Exit
