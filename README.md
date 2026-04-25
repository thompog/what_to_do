# what to do
1. C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\DBBS\ make into exe
2. C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\bob fix bob.py
3. C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing fix getdata.ps1 what to fix:
   ''''At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:160 char:68
+ ...  = "Disk"; value = "$($d.Model) â€” $sizeGb$iface"; inline = $true })
+                                         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Unexpected token '$sizeGb$iface"; inline = $true })
            }
        }
        if ($storage.LogicalDisks) {
            $ldArr     = if ($storage.LogicalDisks -is [array]) { $storage.LogicalDisks } else { @($storage.LogicalDisks) }
            $ldSummary = ($ldArr | Where-Object { $_.Size -and $_.Size -gt 0 } | ForEach-Object {
                "$($_.DeviceID)' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:160 char:67
+ ...            $e2.Add(@{ name = "Disk"; value = "$($d.Model) â€” $sizeGb ...
+                                                                  ~
The hash literal was incomplete.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:160 char:67
+ ...            $e2.Add(@{ name = "Disk"; value = "$($d.Model) â€” $sizeGb ...
+                                                                  ~
Missing ')' in method call.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:160 char:75
+ ...  = "Disk"; value = "$($d.Model) â€” $sizeGb$iface"; inline = $true })
+                                                ~~~~~~~~~~~~~~~~~~~~~~~~~~
Unexpected token '$iface"; inline = $true })
            }
        }
        if ($storage.LogicalDisks) {
            $ldArr     = if ($storage.LogicalDisks -is [array]) { $storage.LogicalDisks } else { @($storage.LogicalDisks) }
            $ldSummary = ($ldArr | Where-Object { $_.Size -and $_.Size -gt 0 } | ForEach-Object {
                "$($_.DeviceID)' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:160 char:81
+ ...  = "Disk"; value = "$($d.Model) â€” $sizeGb$iface"; inline = $true })
+                                                      ~~~~~~~~~~~~~~~~~~~~
Unexpected token '"; inline = $true })
            }
        }
        if ($storage.LogicalDisks) {
            $ldArr     = if ($storage.LogicalDisks -is [array]) { $storage.LogicalDisks } else { @($storage.LogicalDisks) }
            $ldSummary = ($ldArr | Where-Object { $_.Size -and $_.Size -gt 0 } | ForEach-Object {
                "' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:166 char:18
+                 "$($_.DeviceID) $([math]::Round($_.FreeSpace / 1GB, 0 ...
+                  ~~
Unexpected token '$(' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:166 char:33
+                 "$($_.DeviceID) $([math]::Round($_.FreeSpace / 1GB, 0 ...
+                                 ~~
Unexpected token '$(' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:166 char:108
+ ... d($_.FreeSpace / 1GB, 0))/$([math]::Round($_.Size / 1GB, 0)) GB free"
+                                                                  ~~
Unexpected token 'GB' in expression or statement.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:167 char:28
+             }) -join "  |  "
+                            ~
Expressions are only allowed as the first element of a pipeline.
At C:\Users\thoma\OneDrive\Skrivebord\mooooooooooooooooooooook\dd\check_thing\getdata.ps1:168 char:50
+             if ($ldSummary) { $e2.Add(@{ name = "Logical Drives"; val ...
+                                                  ~~~~~~~
Unexpected token 'Logical' in expression or statement.
Not all parse errors were reported.  Correct the reported errors and try again.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : UnexpectedToken''''




# file ideas
1. batch file get public adr Troll say sorry after Trolling
2. try to learn how a worm works then make one test with laptops
3. python file witch uses getpass.getpass() to try to get password (kinda like gaslight) then get some data then send it over
4. try to make a backdoor with python/exe (no installer)



# what can do if bord
1. try use troll virus on friend (couse funny)
2. use batch file to make menu make license&TOS so no one can sue then send it over to friend (you know witch one)
3. fuck around with chatgpt with one of meny projects XD
