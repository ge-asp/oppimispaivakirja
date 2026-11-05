# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

SSH avaimen luominen tilille aiheutti haasteita. Siihen olisin ehkä kaivannut hieman enemän ohjeita. Kävin dokumentaatiota läpi ja pyysin vielä apua ystävältä sen saamiseksi toimimaan.

 Git pull ja push komentoja ennenkin käyttäneenä, olivat ehkä helpoin osio tässä. 
 
 Minulta oli myös jäänyt jokin osio välissä pullaamatta, niin sivustoni jäi digitaaliseksi kelloksi analogisen version sijaan, enkä saanut sitä vaihdettua enää. Kello silti päivittyi ja näytti oikean ajan ja päivämäärän. 
 
 Yhdistämispyynnöt jäi myös hieman epäselviksi. Ymmärrän mihin niiden käyttö perustuu, mutta en oikein muista miten niissä pitää toimia. 

 Kuten edellisessä päiväkirjamerkinnässä, myös näissä sain ystävältä apua käsitteiden selkeyttämiseen, mikäli jokin jäi epäselväksi materiaalista. 

 En myöskään nähnyt päiväkirjaohjeita materiaalissa, kuin vasta tehtyäni tehtävät. Päiväkirjan täyttäminen jälkeenpäin oli hhidasta ja olisi tullut varmasti paremmaksi, jos olisin tajunnut täyttää tätä samaan aikaan kun tein tehtäviä. Ohjauduin siis opettajan sivuille missä oli tehtävänanto ja materiaali, enkä huomannut kuin vasta myöhemmin että moodlessa olisi ollut lisäohjeita.
## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git pull | hakee etärepositoriosta saatavat muutokset ja yhdistää ne nykyiseen haaraan |
| git add . | otetaan seuraavaan talletukseen mukaan kaikki uudet ja muuttuneet tiedot |
| git commit -m <Kommentti> | Tekee varsinaisen talletuksen |
| git push | vie paikallisen haaran oletusarvoiseen etähaaraan |
| git switch  -c <uuden haaran nimi> | luo ja vaihtaa uuteen haaraan |
| git switch <haaran nimi> | vaihtaa haaraa |
| git merge <haaran nimi> | yhdistää nimetyn haaran siihen haaraan missä tällä hetkellä on |
| git remote add actions <linkki> | Lisää uuden etärepositorion nimellä actions |
| git fetch actions main | lataa uusimmat muutokset etärepositoriosta, ei muokkaa nykyistä haaraa tai tiedostoja |
| git merge actions/main --allow-unrelated-histories | yhdistää ladatut haarat nykyiseen vaikkei niillä olisi yhteistä talletushistoriaa | 
| git tag <taginimi> | luodaan viitaus tiettyyn talletukseen
| git push origin --tags | viedään tagit etärepositorioon sillä ne eivät mene sinne automaattisesti | 
