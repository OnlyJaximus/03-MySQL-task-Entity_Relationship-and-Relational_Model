# 03-MySQL-task-Entity_Relationship-and-Relational_Model


************************************* Entity_Relationship ********************************************** </br>

SLABI ENTITETI (dupli pravougaonik) :   </br>

- CD se identifikuje preko svog ID_BROJA i NAZIVA CD KLUBA (npr CD broj 3 pripada CD klubu koji se zove recimo "Pinky" ) </br>
  Morace se identifikovati preko svog ID_BROJA i naziva CD_KLUBA </br>
  
- Pozajmica se moze identifikovati preko datuma iznajmljivanja i ID broja CD-a

- Imamo CD koji se identifikuje preko CD kluba, imamo pozajmicu koja se identifikuje preko CD.
- Da bi identifikovali pozajmicu, moramo da znamo CD, CD klub


- Kategorija ce imati IS vezu jer ima tacno definisane kategorije koje mogu da budu. </br>
  U tekstu zadatka pise: Moguce kategorije su: film, muzika, igra, kompijuter. </br>

- Kod IS-a se ne definisu kardinaliteti! </br>
- 
ENTITETI: CD klub, CD, kategorija, clan, pozajmica, kategorija clana
