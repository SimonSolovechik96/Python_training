python --version
[Zaidimas.py](https://github.com/user-attachments/files/23433175/Zaidimas.py)


now = datetime.now()
current_year =  now.year
current_month = now.month
current_day = now.day

Lithuanian_time = datetime.now (ZoneInfo("Europe/Vilnius"))
print(Lithuanian_time.strftime ("%Y-%m-%d %H:%M:%S") ) 

Story = ("%s tu, mano %s tėvyne \n" 
"Šalis, kur %s kapuos %s \n" 
"%s tu savo dangaus mėlyne! \n"  
"%s: tiek vargo, kančių %s \n" 
"Kaip puikūs slėniai sraunios Dubysos, \n"
"Miškais lyg rūta kalnai %s; \n"
"O po tuos kalnus %s visos \n"
"Griaudžiai malonias dainas ringuoja. \n"

"-Maironis ir %s"

) 

Būdvardis = input ( "Įrašyk būdvardį")
Būdvardis2 = input ( "Įrašyk būdvardį")
Veiksmažodis = input ("Įrašyk veiksmažodį" )
Daiktavardis_daugiskaita = input ( "Įrašyk daiktavardį, daugiskaita")
Būdvardis3 = input ( "Įrašyk būdvardį")
Būdvardis4 = input ( "Įrašyk būdvardį")
Veiksmažodis2 = input ("Įrašyk veiksmažodį" )
Veiksmažodis3 = input ("Įrašyk veiksmažodį" )
Daiktavardis_motgim = input ("Įrašyk daiktavardį moteriškos giminės" )
Vardas = input ("Įrašyk vardą")







print (Story % (Būdvardis,Būdvardis2,Veiksmažodis,Daiktavardis_daugiskaita,Būdvardis3,Būdvardis4,Veiksmažodis2,Veiksmažodis3,Daiktavardis_motgim, Vardas))
