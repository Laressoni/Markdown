# Git ohjeet
Tässä ovat ohjeet Git:ille.

## Peruskomennot
-*Git add* **lisää** uuden tiedoston tämän hetkiseen kohteeseen.  
-*Git commit* **tallentaa** tai **snapshottaa** tiedoston pysyvästi versiohistoriaan.  
-*Git status* **listaa** kaikki tiedostot, jotka on commitattu.  
-*Git push* **lähettää** commitatut muutokset master branchista etävarastoosi.  
-*Git branch* **listaa** kaikki paikalliset haaraumat tämänhetkisessä hakemistossa.

## Perumistapoja
-*Git checkout* käytetään haarasta toiseen vaihtamisessa.  
-*Git revert* toimii kuten **undo nappi**, se tekee uuden commitin, jossa aiemman commitin muutokset on poistettu, se on turvallisempi kuin git reset.  
-*Git reset* on tehokas komento, jota **käytetään kumoamaan paikalliset muutokset Git-repon tilaan**

## Paikallisen Gitin kytkentä Githubiin
Paikallisesta Gitistä voi siirtää tietoa githubiin *git remote add* komennolla. Sitä voidaan käyttää muunmuassa: git remote add seppo *url osoite*. Siihen siis ensin kirjoitetaan komento, sitten tiedoston nimi (seppo), joka näkyy githubissa ja GitHub repositorion url osoite.  
GitHubin hakemiston sisällön voi nähdä komennolla *git remote*.

## Forkkaus ja forkin kloonaus paikalliseen työhakemistoon 
Voit forkata minkä tahansa repon napauttamalla repo- sivun oikeassa yläkulmassa olevaa fork nappia.  
Githubissa etsi forkkisi ja sieltä tiedostolistan yläpuolella paina nappia "Code". Jos haluat kloonata arkiston HTTPS:n avulla, "Clone with HTTPS" alla, paina leikepöytänappia kloonataksesi arkiston SSH-avaimella. Avaa Git Bash ja vaihda nykyinen työhakemisto paikkaan, jonne haluat kloonatun hakemiston. Kirjoita komento *git clone* ja siihen perään url, jonka kopioit aiemmin. Entterin napsautuksella, homma valmis.

## Upstreamin lisäys paikallisessa työhakemistossa olevaan forkkiin
[siinä on](https://www.atlassian.com/git/tutorials/git-forks-and-upstreams)
