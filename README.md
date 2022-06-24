Link na originalni rad je https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2016JD024877

# Zahtev zadatka

## Analiza podataka
#### 1. Pojašnjenje podataka iz baze:
* No: redni broj vrste
* year: godina
* month: mesec
* day: dan u mesecu
* hour: sat u danu
* season: godišnje doba
* PM: koncentracija PM2.5 čestica na nekoliko lokacija (ug/m3)
* DEWP: temperatura rose/kondenzacije (stepeni Celzijusa)
* TEMP: temperatura (stepeni Celzijusa)
* HUMI: vlažnost vazduha (%)
* PRES: vazdušni pritisak (hPa)
* cbwd: pravac vetra (N-sever, S-jug, E-istok, W-zapad, cv-calm/variable)
* Iws: brzina vetra (m/s)
* precipitation: padavine na sat (mm)
* Iprec: ukupne padavine (mm)
#### 2.	Učitati bazu u DataFrame. Proveriti kako izgleda prvih nekoliko vrsta u bazi.
#### 3.	Upoznati se sa bazom. Koliko ima obeležja? Koliko ima uzoraka? Šta predstavlja jedan uzorak baze? Kojim obeležjima raspolažemo? Koja obeležja su kategorička, a koja numerička? Postoje li nedostajući podaci? Gde se javljaju i koliko ih je? Postoje li nelogične/nevalidne vrednosti?
#### 4.	Izbaciti obeležja koja se odnose na sve lokacije merenja koncentracije PM čestica osim US Post.
#### 5.	Ukoliko postoje nedostajući podaci, rešiti taj problem na proizvoljan način (neke od mogućnosti rađene su na vežbama). Objasniti zašto je rešeno na odabrani način.
#### 6.	Analizirati obeležja (vrsta obeležja, osnovne statistike, raspodela, …)
#### 7.	Analizirati detaljno vrednosti obeležja koje će biti postavljeno kao izlaz linearne regresije, a to je PM2.5 (’PM_US Post’).
#### 8.	Vizuelizovati i iskomentarisati zavisnost promene promenljive koja se predviđa linearnom regresijom od preostalih obeležja u bazi.
#### 9.	Analizirati međukorelaciju obeležja.
#### 10.	Po sopstvenom izboru uraditi još neku vrstu analize (takođe obavezna stavka).

## Napraviti model linearne regresije koji predviđa koncentraciju PM2.5 čestica
*	Potrebno je 10% nasumično izabranih uzoraka ostaviti kao test skup, a preostalih 90% koristiti za obuku modela.
*	Isprobati različite hipoteze, primeniti selekciju obeležja, kao i regularizaciju.
* Odabrati konačni model linearne regresije koji po vama predstavlja najbolji model od svih ispitanih modela i objasniti zašto je baš taj model odabran.
