# 03-MySQL-task-Entity_Relationship-and-Relational_Model


************************************* Entity_Relationship ********************************************** </br>

SLABI ENTITETI (dupli pravougaonik) :   </br>

- CD se identifikuje preko svog ID_BROJA i NAZIVA CD KLUBA (npr CD broj 3 pripada CD klubu koji se zove recimo "Pinky" ) </br>
  Morace se identifikovati preko svog ID_BROJA i naziva CD_KLUBA </br>
  
- Pozajmica se moze identifikovati preko datuma iznajmljivanja i ID broja CD-a. </br>

- Imamo CD koji se identifikuje preko CD kluba, imamo pozajmicu koja se identifikuje preko CD. </br>
- Da bi identifikovali pozajmicu, moramo da znamo CD, CD klub. </br>


- Kategorija ce imati IS vezu jer ima tacno definisane kategorije koje mogu da budu. </br>
  U tekstu zadatka pise: Moguce kategorije su: film, muzika, igra, kompijuter. </br>

- Kod IS-a se ne definisu kardinaliteti! </br>
 
ENTITETI: CD klub, CD, kategorija, clan, pozajmica, kategorija clana </br>


![1](https://user-images.githubusercontent.com/56784702/208904324-fd6a330d-1daf-418d-a8a8-d6e4c4cfc4c9.png)
![zad 1 slika](https://user-images.githubusercontent.com/56784702/208904334-2dc6200a-fac6-4021-ad9d-b6bf4382ffd1.png)
![zad 2 slika](https://user-images.githubusercontent.com/56784702/208904342-d16dca3e-0292-4445-9f8d-2543c8e8f957.png)

