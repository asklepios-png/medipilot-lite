---
title: Tietosuojaseloste
---

# MediPilot Lite: tietosuojaseloste

- **Julkaisija:** Asklepios Consulting Oy, Y-tunnus 3245307-1, IoT Campus, Joensuunkatu 7, 24100 Salo,
  asklepiosconsultingoy@gmail.com, +358 44 013 0683
- **Koskee:** Chrome-laajennus "MediPilot Lite" (Chrome Web Store; tunniste lisätään tähän julkaisun jälkeen)
- **Versio:** 1.0, voimassa 23.10.2026 alkaen
- **In English:** [Privacy Policy](privacy)

**Laajennuksen versiot:** laajennuksen versio 1.0.0 sisältää vain anonymisoidun kopioinnin (kohta 3 ja
kohdan 5 leikepöytä). Tämä seloste kuvaa jo myös versiossa 1.1.0 tulevat toiminnot (uusinnan apuri, "ota
seuraava", palkkiolaskenta), jotta seloste ei muutu päivityksessä. Selainoikeudet ovat molemmissa samat.

## 1. Lyhyesti

MediPilot Lite on lääkärin oma apuväline Mehidoc-potilastietojärjestelmään. Se toimii kokonaan käyttäjän
selaimessa osoitteessa mehidoc.mehilainen.fi. Laajennus ei lähetä mitään tietoja julkaisijalle eikä
kenellekään muulle, ei sisällä analytiikkaa eikä mainontaa, eikä julkaisija saa laajennuksen kautta mitään
tietoja sen käyttäjistä tai potilaista. Ainoa verkkokutsu on sama, jonka Mehidocin oma "ota"-nappi tekee, ja
se kulkee Mehidocin omaan palveluun.

## 2. Roolit

- **Mehiläinen Oy** on Mehidocin potilastietojen rekisterinpitäjä. Laajennus ei muuta tätä: se on työkalu,
  jolla terveydenhuollon ammattilainen käsittelee työssään samoja tietoja, joihin hänellä on jo Mehidocissa
  pääsy.
- **Käyttäjä** (Mehidocia työssään käyttävä ammattilainen) asentaa laajennuksen itse ja päättää sen käytöstä.
- **Asklepios Consulting Oy** on laajennuksen julkaisija ja ylläpitäjä. Se ei vastaanota, tallenna eikä
  käsittele laajennuksen käyttäjien tai potilaiden tietoja, koska laajennus ei siirrä niitä minnekään.

## 3. Mitä laajennus lukee (vain muistissa)

Laajennus lukee Mehidoc-sivulta sen avoinna olevan sovellustilan, jotta toiminnot toimivat. Nämä tiedot ovat
olemassa vain sivun ollessa auki, ja ne katoavat, kun sivu suljetaan tai keskustelu vaihtuu. Niitä ei
tallenneta.

| Mitä luetaan | Mihin |
|---|---|
| Keskustelun viestit ja reseptit | anonymisoitu kopiointi (Alt+X) ja reseptinuusinnan apuri |
| Potilaan ja ammattilaisten tunnistetiedot (nimi, henkilötunnus, maksajan tiedot) | anonymisoinnin "tunnetut arvot": laajennus tietää, mitkä sanat poistetaan kopioitavasta tekstistä |
| Käyttäjän oma kirjautumistunniste Mehidociin | vain "ota seuraava" -kutsu (kohta 5); ei tallenneta, ei kirjata lokiin |
| Reseptihistoria (Mehidocin oma vastaus) | reseptinuusinnan apuri; tyhjennetään ajon päättyessä |
| Kirjauksen tallennuspyynnön laskutusrivit | palkkiolaskenta (kohta 4) |

## 4. Mitä laajennus tallentaa

Tallennus tapahtuu vain selaimen laajennuskohtaiseen tallennustilaan käyttäjän omalla laitteella. Potilaan
nimeä, henkilötunnusta tai kertomustekstiä ei tallenneta. Laajennus poistaa vanhentuneet tiedot itse.

| Tieto | Sisältö | Säilytys |
|---|---|---|
| Laskutusrivit | per kirjaus: keskustelun numero, käyttäjän oma ammattilaisnumero, laskutuskoodit, sairausloma kyllä/ei, resepti kyllä/ei, jonotyyppi, oton ja kirjauksen aika | 120 päivää |
| Tavoiteluvut | käyttäjän päivälle asettamat tavoitemäärät | 30 päivää |
| Tavoitelaskurin asetukset | widgetin sijainti ja näkyvyys | kunnes laajennus poistetaan |
| Listatut tunnit | käyttäjän itse tuomat työvuorot kuukausinäkymään | 4 kuukautta |
| Laatubonuksen arvio | käyttäjän valitsema prosentti | kunnes laajennus poistetaan |
| Virheloki | enintään 50 viimeisintä virhettä: aika, moduuli, virhekoodi, lyhyt tekninen selite ilman sivun tekstiä tai potilastietoja | kiertävä |

Laskutusrivit ovat käyttäjän omaa työtä koskevia tietoja, ja niitä käytetään vain käyttäjän oman palkkion
laskemiseen hänen omalla laitteellaan. Rivin keskustelun numero on Mehidocin sisäinen viite: sillä rivin voi
yhdistää potilaaseen vain Mehidocissa ja vain sen käyttöoikeudella. Rivit ovat siten pseudonymisoitua
tietoa, ja laajennus käsittelee niitä terveystietona: ei siirtoa, rajattu säilytys, vain käyttäjän laite.
Tallennus on selaimen profiilissa ilman laajennuksen omaa salausta, joten sen suojaus on sama kuin selaimen
muun paikallisen datan ja nojaa laitteen ja käyttäjätilin suojaukseen.

## 5. Mitä laajennus lähettää tai kirjoittaa

- **Verkkoon:** yksi kutsu. Kun käyttäjä painaa "ota seuraava", laajennus lähettää Mehidocin omaan
  rajapintaan saman pyynnön, jonka Mehidocin oma "ota"-nappi lähettää, käyttäjän omalla
  kirjautumistunnisteella. Pyyntö kulkee vain Mehidocin palveluun. Mitään muuta laajennus ei lähetä mihinkään.
- **Leikepöydälle:** kun käyttäjä painaa Alt+X ja hyväksyy esikatselun, anonymisoitu teksti kopioidaan
  käyttäjän laitteen leikepöydälle. Mihin käyttäjä sen liittää, on käyttäjän oma toimi, jota laajennus ei
  seuraa.
- **Mehidoc-sivulle:** reseptinuusinnan apuri painaa Mehidocin omia painikkeita, rastittaa reseptirivejä ja
  kirjoittaa kertomusmerkinnän tekstin (keskustelun teksti anonymisoituna) vain, kun käyttäjä on virittänyt
  sen ja vain siinä keskustelussa. Apuri pysähtyy tarkistuspisteeseen, ja käyttäjä kuittaa ja allekirjoittaa
  itse. Mitään ei allekirjoiteta eikä tallenneta Mehidociin ilman käyttäjän omaa toimea.

## 6. Mitä laajennus ei koskaan tee

- ei lähetä tietoja julkaisijalle tai kolmansille osapuolille
- ei myy, vuokraa tai luovuta tietoja
- ei sisällä analytiikkaa, telemetriaa, mainontaa tai käytön seurantaa
- ei lataa koodia verkosta
- ei toimi millään muulla sivustolla kuin mehidoc.mehilainen.fi
- ei lue evästeitä, selaushistoriaa, muita välilehtiä tai muita sivustoja
- ei tallenna potilaan nimeä, henkilötunnusta eikä kertomustekstiä
- ei tee kliinisiä päätöksiä eikä allekirjoita mitään käyttäjän puolesta
- ei vaadi tiliä, rekisteröitymistä tai kirjautumista

Tietoja käytetään vain laajennuksen ilmoitettuun tarkoitukseen. Niitä ei myydä, ei käytetä mainontaan eikä
anneta ihmisten luettavaksi.

## 7. Tietoturva

Laajennus pyytää vain yhden selainoikeuden (oma tallennustila) ja toimii vain yhdellä osoitteella. Sen oma
sisältöturvakäytäntö estää ulkopuolisen koodin ja yhteydet popupista ja taustaskriptistä. Jokainen julkaistava
paketti ajetaan automaattitestin läpi, joka tarkistaa, ettei paketissa ole muita verkkokutsuja kuin kohdassa 5
kuvattu. Anonymisoitu teksti näytetään käyttäjälle esikatselussa ennen kopiointia.

## 8. Käyttäjän keinot

- **Tietojen poisto:** laajennuksen poistaminen selaimesta poistaa kaiken sen tallentaman tiedon. Virhelokin
  voi tyhjentää erikseen laajennuksen popupista.
- **Tarkastelu:** laajennuksen popup näyttää tallennetut palkkioluvut, ja virheloki on luettavissa
  popupin diagnostiikkaosiosta.
- **Potilastietoihin liittyvät pyynnöt** (tarkastus, oikaisu, poisto) osoitetaan rekisterinpitäjälle eli
  Mehiläinen Oy:lle, koska laajennus ei tallenna potilastietoja eikä julkaisijalla ole niitä.
- Laajennuksen käyttö on vapaaehtoista, ja sen voi poistaa milloin tahansa.

## 9. Muutokset tähän selosteeseen

Jos laajennukseen lisätään uusi tietovirta, uusi tallennettava tieto tai uusi selainoikeus, seloste päivitetään
ennen muutoksen julkaisua ja versionumero sekä päivämäärä muuttuvat. Ajantasainen seloste on aina tässä
osoitteessa. Laajennuksen muutosloki on luettavissa sivulla [Muutosloki](changelog).

## 10. Yhteystiedot

- Asklepios Consulting Oy, Y-tunnus 3245307-1
- IoT Campus, Joensuunkatu 7, 24100 Salo
- asklepiosconsultingoy@gmail.com
- +358 44 013 0683
