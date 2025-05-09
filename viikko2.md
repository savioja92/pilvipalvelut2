Tekstiä siitä, miten GitHub-Actionsia voisi käyttää projektissa.

## Viikon 2 tehtävä

Github Actionsia voisi käyttää hyvin automatisoimaan omaa ohjelmointi ja rakennusprosessia. Esimerkiksi aina kun kirjoittaa uutta koodia ja tekee jotain muutoksia, voisi Actionsin avulla saada tehtyä automaattisen testauksen halutussa ympäristössä mikäli siihen olisi tarvetta. Ajoitetun deploymentin avulla ei tarvitse itse tehdä mitään, kun se tehdään automaattisesti. Testauksen suhteen myös GitHubin puolella voisi rakentaa oman uuden juuren, jossa ensin rakennetaan ja testataan, jonka jälkeen ne voitaisiin vasta siirtää pääjuureen, kun toiminnallisuudesta olisi varmistuttu. 
Jos tarkoitus olisi pyörittää julkisena toimivaa sivustoa, voisi siihen laittaa automatisoidut integroimiset päälle ja sen jälkeen vain huolehtia itse ohjelmoinnista.
Olen aikaisemmalla kurssilla tehnyt reaaliaikaista API-dataa näyttävän sivun, jota haluaisin parannella vielä tulevaisuudessa. Kyseiselle sivulle voisin asettaa automaattisen integroinnin esim. joka 50 päivän välein, sillä päivitysten nopea päivittyminen ei ole oleellista sivuston toiminnan kannalta. 
Turhan työn välttämiseksi hyvä toimintamalli uutta sivustoa rakentaessa olisi aloittaa YAML-tiedostosta ja rakentaa pohja juurikansiolle oleellisimmista tiedostoista, readme-tiedostosta sekä strateginen suunnitelma. Kyseinen prosessi nopeuttaisi ja helpottaisi kehittämistyötä, ja sivuston julkaisu tapahtuisi kuin itsestään alussa asetettujen asetusten ansiosta. 

[Takaisin etusivulle](index.md)
