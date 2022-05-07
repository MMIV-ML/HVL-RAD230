# HVL-RAD230
## RAD230 - Medisinsk bildebehandling, kunstig intelligens og innovasjon i radiografi (HVL)

> Dette repositoriet dekker deler av Modul 1 og Modul 2 i emnet RAD230. Modul 2 (Kunstig intelligens) er sterkt beslektet med det elektive emnet [ELMED219](https://www.uib.no/emne/ELMED219) (**Kunstig intelligens og beregningsorienter medisin**) som gis av Det medisinske fakultet, UiB i samarbeid med Institutt for datateknologi, elektroteknologi og
realfag ved HVL. Alt dette materialet er også tilgjengelig for RAD230 studenter og finnes på https://github.com/MMIV-ML/ELMED219-2022. En kort karakterisering og visjon for ELMED219 er oppsummert [her](https://docs.google.com/presentation/d/e/2PACX-1vQ2goLSZsIjeCQrjUnA4lfnXe2wgsgDpUXWe8be4K_pTqo4OD9qELxDlJyKknYVdCjJ34-Q4gcu-yYx/pub?start=false&loop=false&delayms=3000).


# Plan for Modul 2

Forelesninger og hands-on øvelser går dagene 12. 13. og 16. mai kl. 10:15 - 15:00 på auditorium C121 / HVL Kronstad. Hver av disse dager vil første del vil være en motiverende forelesning, så en lunchpause (ca. 45 min) og deretter praktiske hands-on øvelser ved bruk av Jupyter Notebooks og Google Colab.<br>
Vi er tre lærere / hjelpere som deltar: Arvid Lundervold (A.L.), Sathieash Kaliyugarasan (S.K.), Marek Kocinski (M.K.)


## Gjør deg klar

Se gjennom kursmaterialet for denne modulen og gjør deg litt kjent med verktøyene GitHub, Python, Jupyter Notebooks, og Google Colab.

### Lokal installasjon via Anaconda
Det er også mulig å installere alle øvelser lokalt på egen laptop for de som ønsker det (se informasjon i [setup-img.md](./setup-img.md) og [environment-img.yml](./environment-img.yml)).
Dette er litt mer krevende enn å kjøre alle Notebooks i skyen (Colab), men læringsutbyttet kan være større gjennom å beherske Python-baserte verktøy på egen laptop, også for senere bruk i studiet og i arbeidet som radiograf.

- [**0-test-installation.ipynb**](https://nbviewer.org/github/MMIV-ML/HVL-RAD230/blob/main/0-test-installation.ipynb) (relevant for lokal installasjon, kfr. `environment-img.yml` aog `setup-img.md`) <a href="https://colab.research.google.com/github/MMIV-ML/HVL-RAD230/blob/master/0-test-installation.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>


## Tidsplan (mindre justeringer kan opptre, alle forelesninger og øvelser i Rom C121)

| Dag og tidsrom |  Innhold
|----------------|------------
|**Torsdag 12/5**|                                                  
|10:15-12:00     | Hva er kunstig intelligens og beregningsorientert medisin? motivasjon og målsetting med modulen. [Link til presentasjonen](https://docs.google.com/presentation/d/e/2PACX-1vTnq7vD7ppuRE9Wrc1mj_JJmkDat9aBLW_P4Gm65K9BDYBXFv6ZOae1b-blhQadBYJ1LYbrP6DDG_L3/pub?start=false&loop=false&delayms=3000). Link to [notebook](https://...). (A.L.)
|12.45-15.00 | Arbeid med notebooken [Introduksjon til maskinlæring](https://...) (m/ M.K.)
|**Fredag 13/5** |                                                
|10:15-11:15     | Hva er dyplæring (deep learning)? [Link til presentasjonen](https://...) (S.K.)
|12:00-15:00     | Gjennomgang av hands-on eksempel med automatisk deteksjon av fraktur i skjelettrøntgenbilder. Link til [notebok](https://...)
|**Mandag 16/5** |                                             
|10:15-12:00     | Introduksjon til multiparametrisk MRI av hjernen og vevsklassifikasjon i multispektrale MR-bilder ved bruk av maskinlæring. [Link til presentasjon](https://...) (A.L.)
|12.45-15.00     | Arbeid med notebbooks  [1-MRI-intro](https://nbviewer.org/github/MMIV-ML/HVL-RAD230/blob/master/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/1-MRI-intro.ipynb) <a href="https://colab.research.google.com/github/MMIV-ML/HVL-RAD230/blob/main/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/1-MRI-intro.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>  [2-sMRI-KNN-tissue-classification](https://nbviewer.org/github/MMIV-ML/HVL-RAD230/blob/master/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/2-sMRI-KNN-tissue-classification.ipynb) <a href="https://colab.research.google.com/github/MMIV-ML/HVL-RAD230/blob/main/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/2-sMRI-KNN-tissue-classification.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/> </a> [3-sMRI-Kmeans-tissue-classification](https://nbviewer.org/github/MMIV-ML/HVL-RAD230/blob/master/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/3-sMRI-Kmeans-tissue-classification.ipynb) <a href="https://colab.research.google.com/github/MMIV-ML/HVL-RAD230/blob/main/3-Multispektrale-MR-bilder-og-vevsklassifikasjon/3-sMRI-Kmeans-tissue-classification.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/> </a>   (m/ M.K.)

_______________________________



**Emnebeskrivelse for RAD230:** https://www.hvl.no/studier/studieprogram/emne/rad230 <br>
**Canvas:** https://hvl.instructure.com/courses/18689/pages/dataovelser-og-demonstrasjoner (krever innlogging)


<img src="cc_by_sa.png" width="75"> Innholdet i disse deler av kurset (Modul 2) gis under en <b><a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a></b> lisens hvis ikke annet er angitt.

<!--
## Innhold og oppbygning
Utdanningen har medisinsk bildebehandling som faglig profil der kunnskap om biologiske basalfag, bildebehandlingsmetoder, bildeanalyser og visualisering av medisinske bilder står sentralt. Sentralt i emnet er tema knyttet til hvordan avansert bildebehandling og kunstig intelligens kan komme pasienten til nytte.  Kunstig intelligens og innovasjon innen medisinsk bildebehandling står også sentralt.

## Læringsutbytte

En student med fullført emne skal ha følgende totale læringsutbytte definert i kunnskap, ferdigheter og generell kompetanse:

### Kunnskap:
Studenten…    

- har bred kunnskap om hvordan normale og patofysiologiske prosesser kan visualiseres ved hjelp av ulike metoder for bildebehandling
- har kunnskap om grunnleggende prinsipper for bildebaserte biomarkører
- har bred kunnskap om prinsipper og metoder for bildebehandling og dens betydning for bildekvalitet og diagnostisk bruk
- har kunnskap om prinsipper for kunstig intelligens (KI) anvendt innen medisinsk bildefremstilling og bildebehandling

### Ferdigheter:
Studenten…

- kan beherske ulike bildebehandlingsmetoder for å visualisere vanlig forekommende patologi
- *vise til nytteverdi og utfordringer ved bruk av kunstig intelligens innen bildediagnostikk og behandling
- kan beherske ulike bildebehandlingsteknikker og vurdere sammenhengen mellom disse og bildekvalitet


### Generell kompetanse
Studenten…

- kan vurdere bildebehandlingsmetoder innen radiografi som grunnlag for sikker diagnostikk
- har innsikt i og kan bidra til kunnskapsutvikling innen fagområdet medisinsk avbildning og bildebehandling
- *kjenner til nytenkning og innovasjonsprosesser for å bidra til en bærekraftig og ansvarlig utvikling innen radiografi


## Anbefalte forkunnskaper
RAD200, RAD210, RADP2, RAD220 og RADP3


## Undervisnings- og læringsformer
I dette emnet vil studentaktive læringsformer benyttes for å involvere studentene i teoretisk læring, muliggjøre praktisk utprøving av teoretiske prinsipper og ferdigheter, og for å legge til rette for diskusjoner, samarbeidslæring og øvelse i å presentere relevant stoff. Arbeid i grupper vil stå i fokus i emnet. Ulike arbeidsformer er gruppearbeid, forelesninger og selvstudier, teambased learning, seminar, laboratorieøvelser på SimArena. Digitale læringsressurser vil benyttes, blant annet som forberedelser til undervisning og laboratorieøvelser.

## Arbeidskrav
Følgende obligatoriske læringsaktiviteter må være godkjent for at studenten kan framstille seg til eksamen:

1. Tilstedeværelse 80% i studentaktiv- og erfaringsbasert undervisning

2. Fremlegg på seminar i grupper, 15 minutters varighet. Digital presentasjonsform, 2 forsøk

 Læringsaktiviteten er gyldig i 4 semestre.  

## Vurderingsform

### Hjemmeeksamen over 4 dager
Digital presentasjon med bilde, tekst og tale av selvvalgt tema (videoformat), 10 minutter presentasjon.

### Vurderingsuttrykk
Gradert karakterskala A til F, der A til E er beståtte karakterer og F er ikke bestått.

-->
