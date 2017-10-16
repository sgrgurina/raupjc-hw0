# Pitanje 1:
U folderu se pojave .dll i .pdb datoteke za class library. Ako se makne .dll program se ne pokrene
jer nemože učitati class library. Treba poslati ClassLibrary.dll i ConsoleApplication.exe.

# Pitanje 2:
Pri pokretanju konzolne aplikacije preko .exe datoteke ispisuje se stari string jer je ClassLibrary.dll ostao isti. 
Kako bi dobili novi string treba prevesti class library.

# Pitanje 3:
Build proces downloada NuGet pakete koji nedostaju te se u packages direktoriju opet pojavi NodaTime.