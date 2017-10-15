# raujc-hw0
#pitanje 1:
  
  Nakon što sam dodao class library kao referencu, u sadržaju Bin/Debug foldera konzolne aplikacije primjećujem dvije nove datoteke:
  ClassLibrary1.dll te ClassLibrary1.pdb.
  Nakon što sam maknuo .dll datoteku program javlja grešku (Could not load file or assembly 'ClassLibrary1)
  Greška se javlja jer u programu koristimo metodu iz nepostojeće biblioteke (jer smo je izbrisali.
  Kad je ne bi koristili program ne bi javljao grešku.
  Ako moram nekome poslati aplikaciju poslao bih .dll datoteke svih referenci i izvršni program .exe


#pitanje 2:
  
  Nakon izmjene stringa i pokretanje exe datoteke bez buildanja na konzoli vidimo stari string
  tj. konzolna aplikacija je koristila staru verziju class library asemblija
  Razlog tome je sto se dll datoteke obnove nakon buildanja, a ne nakon spremanja


#pitanje 3:
  
  Nakon brisanja NodaTime direktorija, build je svejedno uspio i vratio je NodaTime package nazad u direktorij
  
