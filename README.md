Work in Progress

# Alalmazások Fejlesztése 3. beadandó

Készítette: Zsiga Bence Krisztián


## Követelményanalízis

###Feladat:

####Funkcionális elvárások:

+ Work in Progress
+ Work in Progress

####Nem funkcionális követelmények
+ Work in Progress
+ Work in Progress

###Használatieset-modell

####Szerepkörök:

Felhasználó
+ TODO-k listázása
+ TODO-k feltöltése, törlése, szerkesztése
+ további felhasználók/feladatvégzők hozzáadása


####Használati eset diagram:
![modell](/docs/imgs/usecase.png "Használatieset-modell")

Egy TODO feltöltésének menete:
![folyamatábra](/docs/imgs/process.png "Folyamatábra")

## Tervezés

1. Architektúra terv
  +  Oldaltérkép
    + Főoldal
      + Todo Lista
        + Új feladat hozzáadása
      + Felhasználó lista
        + Új felhasználó hozzáadása

  + Végpontok
    + Rest.api-n
      + GET
      + POST
      + PATCH
      + DELETE


2. Felhasználóifelület-modell
  + Oldalvázlat
    ![list](/docs/imgs/page_plan.jpg "list")

3. Osztálymodell
  + Adatmodell és Adatbázisterv
  + ![datamodel](/docs/imgs/data_structure.png "datamodel")

4. Dinamikus működés
  + Szekvenciadiagram
  + ![szekvenciadiagram](/docs/imgs/seqdiag.png "szekvenciadiagram")

##Implementáció

+ Fejlesztői környezet
  + Cloud9 IDE (c9.io)
+ Könyvtárstruktúra
  + app: ember.js alkalmazás
    + pods: ember.js podok
      + components: logika
      + index: kezdőlap 
      + todo: todo modellje
      + todos: todos oldal szerkezete
        + ...
      + user: user modellje
      + users: users oldal szerkezete
        + ...
    + styles: stíluslapok
  + bower_components: bower elemei
  + config: ember.js konfiguráció 
  + dist: publikus elemek


##Tesztelés
+ Tesztelési környezet bemutatása
  + Work in progress

##Felhasználói Dokumentáció
+ Követelmények
  + 2GB memória
  + 1GB HDD
+ Ember.js letöltés a 'git clone https://github.com/i3ence/familytodo.git' paracssal
+ Rest.api letöltés a 'git clone https://github.com/i3ence/afbead2-rest.git' paracssal