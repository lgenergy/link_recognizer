# Link recognizer

### Bevezetés az adattudományba - Önálló kutatási feladat *2018H2*




## Ötlet:

A probléma forrása:

- Ha valaki olyan gépen böngészik, amin nem akar bejelentkezni semmilyen személyes profiljába,
  de talál egy linket amit szeretne elmenteni, vagy megosztani bármilyen sociális felületen azonnal.
- Erre egy lehetőség ha "bepötyögi" telefonjába az url-t, vagy kulcsszavakat megjegyez, ez azonban az url-ek hossza miatt
  meglehetősen időigényes, a kulcsszavak megjegyzése pedig nem garantálna 100%-os megbizhatóságot, hogy újra megtalálja az
  oldalt.

Megoldás, algoritmus célja:

- Önálló kutatási feladat keretében egy ilyen telefonos applikáció alap algoritmusát szeretnénk megírni,
  mely inputként egy képet kap, felismeri a képen az url-sáv pozicióját. Majd ezt a sávot (tartományt)
  elforgatja, átalakítja, úgy hogy a link betűi, minél inkább szabályosak legyenek és így egy betűfelismerő
  ORC algoritmus segítségével felismeri a linket, és outputként ezt adja vissza. 


## Projekt fázisai (előzetesen) 

- Témához megfelelő ismeretek elsajátítása, felmerülő problémák előzetes felmérése (**planning**) 
- Adat gyűjtés (**data collection**)
- A link cellájának felismerése képről (**target**)
- A cella elforgatása, hogy egy téglalap alapú alakzatot kapjunk (**transform**)
- Link felismerése (**recognize**)
- Eremény egyéb felhasználása, végterméke a projektnek, algoritmus kiértékelése (**result**)

---
> Kiss Botond

> Lakos Gergő
