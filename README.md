# 03-MySQL-task-Entity_Relationship-and-Relational_Model


************************************* Entity_Relationship ********************************************** </br>

SLABI ENTITETI (dupli pravougaonik) :   </br>

-1 CD se identifikuje preko svog ID_BROJA i NAZIVA CD KLUBA (npr CD broj 3 pripada CD klubu koji se zove recimo "Pinky" ) </br>
  Morace se identifikovati preko svog ID_BROJA i naziva CD_KLUBA </br>
  
-2 Pozajmica se moze identifikovati preko datuma iznajmljivanja i ID broja CD-a. </br>

- Imamo CD koji se identifikuje preko CD kluba, imamo pozajmicu koja se identifikuje preko CD. </br>
- Da bi identifikovali pozajmicu, moramo da znamo CD, CD klub. </br>


- Kategorija ce imati IS vezu jer ima tacno definisane kategorije koje mogu da budu. </br>
  U tekstu zadatka pise: Moguce kategorije su: film, muzika, igra, kompijuter. </br>

- Kod IS-a se ne definisu kardinaliteti! </br>
 
ENTITETI: CD klub, CD, kategorija, clan, pozajmica, kategorija clana </br>


![1](https://user-images.githubusercontent.com/56784702/208904324-fd6a330d-1daf-418d-a8a8-d6e4c4cfc4c9.png)
![3 kraj text zad](https://user-images.githubusercontent.com/56784702/208904488-22c60e68-23bb-448d-bc0b-61d10a1fbd02.png)

![zad 1 slika](https://user-images.githubusercontent.com/56784702/208904334-2dc6200a-fac6-4021-ad9d-b6bf4382ffd1.png)
![zad 2 slika](https://user-images.githubusercontent.com/56784702/208904342-d16dca3e-0292-4445-9f8d-2543c8e8f957.png)
--------------------------------------------------------------------------------------------------------------------  </br>
![1 na 1 relacija](https://user-images.githubusercontent.com/56784702/208946671-0335b1ef-0544-4dbc-ae2b-1dc10e22cda8.png)
![1 na vise](https://user-images.githubusercontent.com/56784702/208946694-972ece0e-a02a-43f7-b1b0-a1c919ea19da.png)
![m na n vise na vise](https://user-images.githubusercontent.com/56784702/208946710-aab3d934-1d96-4006-adaf-cbf4621b847a.png)
![asocijativni entitet nije iskrabano](https://user-images.githubusercontent.com/56784702/208946775-3dfc7335-4650-449c-8307-228b3e7baaca.png)
![22](https://user-images.githubusercontent.com/56784702/208946890-18b4247d-ba9b-46c3-af3a-20eeec3a19cb.png)


