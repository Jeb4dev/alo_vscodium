# VSCodium

![VSCodium logo](https://vscodium.com/img/codium_cnl.svg)



### Ohjelmointiin suunnattu tekstieditori

VSCodium on käytännössä versio Microsoftin Visual Studio Codesta, josta on mahdollisuuksien mukaan poistettu käyttäjän yksityisyyttä rikkovia ominaisuuksia kuten telemetriaa. 

Käytännössä VSCodium on olemassa, jotta ihmisten ei tarvitse itse ladata ja kääntää telemetriatonta versiota Visual Studio Codesta.


### Toimintaperiaate

VSCodium on hyvin samanlainen kuin VSCode. Kummatkin ovat koodin editointia varten ja VSCodium sisältää ne osat jotka ovat täysin avoimia 


### Käyttökohteet

VSCodiumia voidaan käyttää samalla tavalla kuin VSCodea, eli koodieditorina ja kehitysympäristönä eri ohjelmointikielille ja alustoille. 

VSCodiumin vahvuus on sen monipuolisuus ohjelmistotuotannossa.

Siihen voi asentaa lisäosilla esimerkiksi syntaksinväritys- ja debuggaustuen ohjelmointikielille, jota se ei ennestään tue.



## Lisenssi


- Visual Studio Coden lähdekoodilla [MIT-lisenssi](https://github.com/VSCodium/vscodium/blob/master/LICENSE)
- Microsoftin jakaman ohjelmatiedoston (.exe, .app jne.) [lisenssi](https://code.visualstudio.com/License/) ei ole avoin
    - Microsoftin Visual Studio Marketplacesta hankittujen lisäosien käyttö VSCodiumissa rikkoo periaatteessa lisenssiä
    - Jotkin Microsoftin kehittämistä laajennuksista (esim. C#- ja C++\-lisäosien debuggeri) eivät toimi kuin Visual Studio Codessa.
- VSCodiumin skripteillä tuotettu ohjelmatiedosto sen sijaan on lisensoitu MIT-lisenssillä

Note: This will only appear in the speaker notes window.



## Aktiivisuus ja ylläpito


### Historia

- Visual Studio Coden ensimmäinen versio julkaistiin 29.4.2015 
- Lähdekoodi saataville GitHubiin 18.11.2015
- VSCodiumin ensimmäinen julkaisu 15.8.2018


### Aktiivisuus

- Päivityksiä tulee suunnilleen viikoittain. Viimeisin julkaistu versio 1.83.0.23283 julkaistiin 10.11.2023.
- Microsoftin julkaistessa päivityksen Visual Studio Codeen VSCodiumin GitHub-repossa oleva skripti kloonaa VSCoden repon, kääntää ohjelman ja lataa tuotetut ohjelmatiedostot GitHubiin


### Ylläpito

VSCodiumia ylläpitää yhteisö vapaaehtoisia kehittäjiä, jotka ovat listattuina projektin GitHub-sivulla.



## Osallistuminen projektiin

### Contribution Model

VSCodium-projekti noudattaa avointa ja yhteisöllistä osallistumismallia, jossa kuka tahansa voi ehdottaa muutoksia tai parannuksia projektin lähdekoodiin tai dokumentaatioon.


### Osallistumisen Menettelytavat

Jos haluat osallistua projektiin sinun täytyy kloonata ensin VSCodium-repositorio omalle tietokoneellesi. Sitten voit tehdä haluamasi muutokset projektin lähdekoodiin.

Kun muutokset ovat valmiit, voit lähettää pull-requestin jossa kuvailet tekemäsi muutokset ja pyydät niiden hyväksymistä master branchiin. 

Jos muutoksesi hyväksytään, ne lisätään osaksi VSCodium projektia.



## Tekninen toteutus


### Kielet

- TypeScript, JavaScript, HTML, CSS
- Joitakin Rust-tiedostoja
- VSCodiumin repossa shell-skriptejä ja yksi XSLT-tiedosto


### Protokollat

Language Server Protocol, [Microsoftin](https://microsoft.github.io/language-server-protocol/) alunperin VS Codea varten kehittämä protokolla, jonka on tarkoitus helpottaa esim. syntaksivärityksen kaltaisten ominaisuuksien kehittämistä eri kielille


### Välineet

- Electron, ohjelmistokehys työpöytäsovellusten tekoon käyttäen HTML:a, CSS:ä ja JavaScriptiä
- Chromium, verkkoselain
- Node.js, JavaScript-palvelin



## Asennus ja käyttöönotto

[Kuinka valittu projekti saadaan toimimaan ja kuinka se käännetään lähdekoodista? Tarvittaessa lisää vaiheittaiset ohjeet.]
- Jos haluat saddgtsd (jatkan  tätä lausetta kohta xd)


### Linux:

(tarviiks tähä alaselitykse tai jtn)


**Asentaminen snapilla:**

VSCodium löytyy Snap Storesta Codium nimellä. Jos GNU/Linux jakelusi tukee snap:iä:

```snap install codium --classic```


**Asentaminen Parrot OSlla:**

VSCodium on valmiiksi asennettuna Parrot OSssa. Jos sitä ei jostain syystä ole valmiina, niin voit löytää sen virallisesta reposta:

```sudo apt update && sudo apt install codium```

**miau**


### Mac:

**Asentaminen Brewillä:**

```brew install --cask vscodium```

Jos käytät Mac OS C Mojativeä ja näet tekstin *App can't be opened because Apple cannot check it for malicous software*, kun avaat VSCodiumin ensimmäistä kertaa, niin klikkaa hiiren oikeaa näppäintä ja valitse *Open*. Tämän pitäisi olla välttämätöntä vain Mojave käyttäjillä!


### Windows: 

(tarviiks jonku ala otsakkeee hä???)


**Asentaminen Windows Package Managerilla:**

```winget install vscodium```

**Asentaminen Chocolateylla:**

```choco install vscodium```

**Asentaminen Scoopilla:**

```scoop bucket add extras```

```scoop install vscodium```



## RevealJS käyttöohjeet

Rivinvaihtojen määrällä on väliä: alaotsikoita vai uusia slideoita


## External 3.3 (Image)

![External Image](https://s3.amazonaws.com/static.slid.es/logo/v2/slides-symbol-512x512.png)


## External 3.4 (Math)

`\[ J(\theta_0,\theta_1) = \sum_{i=0} \]`
