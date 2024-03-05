# Oefenproject Git Deployment
Dit is de oefenopdracht:
 
1. Clone dit project naar je locale developer machine (Windows of Mac)
   
2. Open het project met VSCode of andere IDE

3. verwijder de .git directory en check of hij ook weg is (2e commando)

Powershell (PS):

```
rm .git -r -force
dir -force
```

CMD: 
    
```
rmdir /s .git
dir /a
```

unix: 
    
```
rm -rf .git
ls -la
```

4. maak een nieuwe lokale repository
    
5. Pas het project aan en maak een aantal commits:
    - Zet er een ander plaatje in!
    - Maak van index.html index.php
    - Zorg dat de actuele datum en tijd op de pagina komt te staan
    - Zet je naam op de pagina
    
6. Zorg dat dit project via een private github repository naar je linux machine wordt gedeployed.
    
7. Laat de docent de website zien draaien vanaf je lokale unix machine.
