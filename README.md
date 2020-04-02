# Vmesno poročilo projektne naloge

## 1. Uvod
V tej projektni nalogi bomo poskušali odkriti zanimive vzorce iz podatkov o kakovosti zraka v Sloveniji. Preverili bomo onesnaženost zraka (koncentracija ozona O3, delci PM10, PM2.5, SO2, CO, O3, NO2, ...) v različnih krajih v Sloveniji in poskušali ugotoviti kateri so najbolj in najmanj onesnaženi. Preverili bomo kako meritve kot so količina padavin, hitrost vetrov, vlaga, temperatura in letni časi vplivajo na stopnjo onesnaženosti. Na voljo imamo urne, dnevne in letne meritve za več let v preteklost. Nekateri podatki so v formatu PDF in XML, kar je vredu saj jih po potrebi lahko pretvorimo v CSV.

Poskušali bomo odgovoriti na vprašanja:
* Kateri so najbolj in najmanj onesnaženi kraji v Sloveniji?
* Ali letni časi vplivajo na onesnaženost?
* Za kakšno vrsto onesnaženosti gre (O3, PM10, PM2.5)?
* Kako temperatura zraka, vlaga, vetrovi, ..., vplivajo na vse težke kovine v PM10?
* Ali ogrevanje domov med zimskim časom vpliva na onesnaženost?

## 2. Iskanje in priprava podatkov

Na voljo imamo kopico podatkov, vendar se je treba malo potruditi priti do le teh oz. jih dobiti/spremeniti v takšno obliko, ki bo uporabna. Večino podatkov, ki jih bomo uporabili so v pdf obliki, zato smo tabele morali pretvoriti v csv.

Mnogo meritvenih postaj zajema podatke izpred desetletij, ampak za začetek se bomo omejili na novejše meritve iz zadnjih dveh let. Po potrebi oz. če dobimo kakšno dobro idejo bomo primerjali novejše z meritvami izpred 10-ih let. 

Podatke trenutno pridobivamo iz naslednjih spletnih strani:
* https://www.arso.gov.si/zrak/kakovost%20zraka/podatki/
* https://meteo.arso.gov.si/

Na spletni strani arso je na voljo še analiza delcev PM10, koncentracija vsake težke kovine, ki spada v to kategorijo (aluminij, svinec, baker, ...). To nam bo omogočilo natančno analizo onesnaženosti na vsaki meritveni postaji.

Nekatere meritve postaje imajo na voljo tudi podatke o nevihtah, toči, megli, snežni plohi, viharnih vetrih, ipd. So diskretne spremenljivke z vrednostimi "da" ali "ne". Preverili bomo, če vplivajo na vse možne vremenske spremembe, kot so onesnaženje, temperature in povezave med njimi.

## 3. Iskanje vzorcev, zanimivosti
### 3.1 Prikaz
Iz podatkov o koncentraciji delcev PM10 za leto 2019 smo ustvarili dva grafa.

Prvi graf prikazuje povprečno koncentracijo na različnih meritvenih postajah po Sloveniji.
![Graf 1: Povprečne koncentracije PM10 po krajih](https://github.com/TilenBerlak/PR19TBANLRMIUS/blob/master/graf.PNG)

<center>Graf 1 :  Povprečne količine PM10 po krajih</center>

Še en graf, ki prikazuje povprečno koncentracijo delcev PM10 v Sloveniji po posameznih mesecih v letu 2019.
![Graf 2: Povprečne koncentracije PM10 po mesecih](https://github.com/TilenBerlak/PR19TBANLRMIUS/blob/master/graf_pm10_slovenija.PNG)

<center>Graf 2: Povprečne koncentracije PM10 po mesecih</center>

### 3.2 Analiza
Za enkrat smo ostali pri pripravi podatkov, analize nam še ni uspelo narediti, saj nam je veliko časa vzelo pretvarjanje iz pdf oblike v uporabno csv obliko. Med podatki je tudi nekoliko neskladij, kar nam je dodatno otežilo delo. Ko bomo ilemi vse podatke pripravljene, se bomo lotili združevanja.

## 4. Kam naprej?

## 5. Zaključek


## 6. Viri
