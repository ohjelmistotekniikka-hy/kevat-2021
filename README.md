# Ohjelmistotekniikka, kevät 2021

_Kurssin nimi on muuttunut syksyllä 2018, tätä aiemmin kurssi tunnettiin nimellä Ohjelmistotekniikan menetelmät_

## Yleistä

Kurssilla tutustutaan ohjelmistokehityksen periaatteisiin sekä menetelmiin ja sovelletaan niitä toteuttamalla pienehkö harjoitustyö.

Kurssin kolmella ensimmäisellä viikolla on muutama ohjauksessa tai omatoimisesti tehtävä harjoitustehtävä. Kurssin pääpainon muodostaa viikolla 2 aloitettava, itsenäisesti tehtävä harjoitustyö. Työtä on tarkoitus edistää pala palalta [viikoittaisten](#aikataulu) tavoitteiden ohjaamana.

Kurssin arvostelu perustuu pääasiassa harjoitustyöstä saataviin pisteisiin. Osa pisteistä kertyy [aikatauluun](#aikataulu) määriteltyjen viikoittaisten välitavoitteiden kautta, osa taas perustuu työn lopulliseen palautukseen.

Kurssilla ei ole koetta. Harjoitustyö tulee tehdä kurssin aikataulujen puitteissa. Kesken jäänyttä harjoitustyötä ei voi jatkaa seuraavalla kurssilla (syksyllä 2021), joten **muista varata riittävästi aikaa (10-15h viikossa) koko periodin ajaksi!**

Tarkemmat arvosteluperusteet [täällä](./web/arvosteluperusteet.md).

## Kirjoitusvirheitä

Jos huomaat tehtävissä tai muussa materiaalissa kirjoitusvirheitä, kirjaudu GitHubiin ja toimi [täällä](./web/typokorjaukset.md) olevan ohjeen mukaan.

## Kieli

Voit tehdä kurssin Javalla tai Pythonilla. Tämä on Java-version kurssisivu. Python-version kurssisivu löytyy [täältä](https://github.com/ohjelmistotekniikka-hy/python-kevat-2021/blob/master/README.md).

## Ajankohtaista

- Kurssin ainoa luento ti 16.3. klo 12-14 etänä [zoomissa](https://helsinki.zoom.us/j/67356041626)
  - luento tallennetaan, linkki tulee tänne myöhemmn
- Sovellus tehdään käyttämällä Javan versiota 11. [Asennusohjeet](https://www.mooc.fi/fi/installation/netbeans)
- Kurssista on nyt myös olemassa [Python-versio](https://github.com/ohjelmistotekniikka-hy/python-kevat-2021/blob/master/README.md)
- Kurssin Telegram-kanava: [https://t.me/tktlotm](https://t.me/tktlotm)
  - **Huom:** kaikki epäasialliset, halventavat ja jotain ihmisryhmää syrjivät kommentit kanavalla ovat kiellettyjä ja tälläisten kommenttien esittäjät poistetaan kanavalta
- Jos tarvitset kurssiin liittyvää ohjausta, tule zoom-pajaan:
    - xx nn-nn  [zoom]()
    - xx nn-nn  [zoom]()
    - xx nn-nn  [zoom]()
  - Myös Telegramissa voi kysellä erityisesti arkisin klo 9-16
  - **Jos kysymys koskee koodia tai siinä esiintyviä virhetilanteita, kannattaa laittaa kysymyksen yhteyteen linkki omaan repositorioosi.** Ilman koodin näkemistä ongelman selvittäminen on hankalaa tai jopa mahdotonta.
  - Jos et halua kysyä kysymystä suoraan kurssin kanavalla, voit ottaa yhteyttä suoraan "telegram-vastaavaan" Kalle Ilvekseen. Pääasiassa kysymykset kannattaa kuitenkin esittää kanavalla, sillä samat ongelmat koskevat usein useampaakin opiskelijaa
- Jos olet jo toteuttaunut isohkoja ohjelmistoja, on kurssi tietyissä tapauksissa mahdollista [hyväksilukea](./web/hyvaksiluku.md)

## Harjoitustyön toimivuus

- Harjoitustyö on tehtävä Javan versiolla 11

- Koneiden konfiguraatioissa on eroja, ja tällä kurssilla ei riitä että hajoitustyössä tekemäsi sovellus toimii vain omalla koneellasi

- Harjoitustyösi pitää pystyä joka viikko suorittamaan, kääntämään ja testaamaan komentoriviltä käsin laitoksen Linux-koneilla (tai uusimmat päivitykset sisältävällä cubbli-linuxilla), muussa tapauksessa työtä ei tarkasteta ja menetät viikon/loppupalautuksen pisteet.

- Pääset testaamaan ohjelmaasi laitoksen koneella myös kotoa käsin käyttämällä etätyöpöytää https://helpdesk.it.helsinki.fi/ohjeet/tietokone-ja-tulostaminen/tyoasemapalvelu/etakaytettavat-tyopoydat-vdi-ja-vmware tai kirjautumalla ssh:lla palvelimelle melkki.cs.helsinki.fi

## Linkkejä

- [Kurssimateriaali](./web/materiaali.md)
- Viikoittaiset palautukset

  - viikko 1 [laskarit](./tehtavat/viikko1.md)
  - viikko 2 [laskarit](./tehtavat/viikko2.md) ja [harjoitustyö](./tehtavat/harjoitustyo_viikko2.md)
  - viikko 3 [laskarit](./tehtavat/viikko3.md) ja [harjoitustyö](./tehtavat/harjoitustyo_viikko3.md)
  - viikko 4 [harjoitustyö](./tehtavat/harjoitustyo_viikko4.md)
  - viikko 5 [harjoitustyö](./tehtavat/harjoitustyo_viikko5.md)
  - viikko 6 [harjoitustyö](./tehtavat/harjoitustyo_viikko6.md)
  - viikko 7 [harjoitustyö](./tehtavat/harjoitustyo_viikko7.md)

- Kurssin referenssisovellus [OtmTodoApp](https://github.com/mluukkai/OtmTodoApp)
  - Sovelluksen tarkoituksena on demonstroida erästä tapaa tehdä suurin piirtein täysiin pisteisiin riittävä dokumentaatio ja testaus projektillesi. Itse ohjelma on sen verran suppea, että saadaksesi kurssilta arvosanan 5 joudut tekemään hieman laajemman sovelluksen.
- [Labtool](https://study.cs.helsinki.fi/labtool/courses/TKT20002.2021.K.K.1)
- Ohjeita
  - Kaikki ohjeista eivät ole kurssin alussa vielä ajankohtaisia. Kaikkeen tärkeään tulee aikanaan linkki laskareihin tai harjoitustöiden viikkotavoitteisiin
  - [Aiheideoita ja ohjeita työn harjoitustyön aloittamiseen](./web/tyon_aloitus.md)
  - [JUnit-ohje](./web/junit.md)
  - [Käyttöliittymän ja tietojen tallettamisen toteuttamiseen sekä sovelluksen konfigurointiin liittyviä vihjeitä](./web/java.md)
  - [Maven](./web/maven.md)
  - [Checkstyle](./web/checkstyle.md)
  - [JavaDoc](./web/javadoc.md)
  - [koodin laatu](./web/koodin_laatuvaatimukset.md)
- Työkaluja kaavioiden piirtoon
  - <http://yuml.me/> luokkakaaviot
  - <https://www.websequencediagrams.com/> sekvenssikaavioihin
  - <https://app.diagrams.net/> kaikki kaaviot

## Aikataulu

### viikko 1

Palautuksen deadline ti 23.03. klo 23:59

- Tiistaina 16.03. klo 12-14 aloitustilaisuus [zoomissa](https://helsinki.zoom.us/j/67356041626)
- Komentorivi- ja Git-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset [tehtävät](/tehtavat/viikko1.md)
- Tehtävien palautus tapahtuu tekemällä repositorio githubiin ja rekisteröitymällä labtooliin

### viikko 2

Palautuksen deadline ti 30.03. klo 23:59

- Harjoitustyön aiheen alustava määrittelydokumentti (1p)
  - katso tarkemmin [täältä](/tehtavat/harjoitustyo_viikko2.md)
- JUnit-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset [tehtävät](/tehtavat/viikko2.md)
- Oman projektin koodaus alkaa

### viikko 3

Palautuksen deadline ti 06.04. klo 23:59

- Harjoitustyön koodin runko valmiina (2p)
  - katso tarkemmin [täältä](/tehtavat/harjoitustyo_viikko3.md)
- Pajassa tehtävät tai omatoimiset [tehtävät](/tehtavat/viikko3.md) Luokka- ja sekvenssikaaviosta (1p)

### viikko 4

Palautuksen deadline ti 13.04. klo 23:59

- Harjoitustyö (3p)
  - Ohjelman perustoiminnallisuus
  - Testien aloitus
  - Alustava rakenne luokkakaaviona
  - Checkstyle otettu käyttöön
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko4.md)

### viikko 5

Palautuksen deadline ti 20.04. klo 23:59

- Harjoitustyö (3p)
  - Release 1
  - Testikattavuus nousee
  - Jotain päätoiminnallisuutta kuvaava sekvenssikaavio
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko5.md)
- Koodikatselmointi (2p)
  - [Koodikatselmointi](/web/koodikatselmointi.md)

### viikko 6

Palautuksen deadline ti 27.04. klo 23:59

- Harjoitustyö (3p)
  - Release 2
  - Testikattavuus nousee
  - JavaDoc aloitettu
  - Alustava versio arkkitehtuuridokumentista
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko6.md)

### viikko 7

Lopullisen palautuksen deadline su 09.05. klo 23:59

- [loppupalautuksen ohjeet](/tehtavat/harjoitustyo_viikko7.md)
