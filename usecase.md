# Käyttötapaukset

* **Rekisteröityminen:**
  * Käyttäjät: Kaikki
  * Jälkiehto: Käyttäjätiedot tallennettu
  * Käyttötapauksen kulku: Käyttäjätunnus ja salasana valittu, tiedot tallennettu muistiin

* **Kirjautuminen:**
  * Käyttäjät: Kaikki
  * Laukaisija: Kirjautumispainikkeen valinta
  * Esiehto: Onnistunut rekisteröityminen
  * Jälkiehto: Kirjautunut sisään onnistuneesti
  * Käyttötapauksen kulku: Käyttäjä syöttää käyttäjätietonsa, tiedot tarkistetaan muistista
  * Poikkeuksellinen toiminta: Virheilmoitus jos käyttäjätiedot ovat virheelliset

* **Äänestysten selaaminen:**
  * Käyttäjät: Kaikki
  * Laukaisija: Etusivu
  * Esiehto: Sivu on ladattu ja auki
  * Jälkiehto: Käyttäjä näkee avoinna olevat äänestykset ja voi selata niitä
  * Käyttötapauksen kulku: Verkkosivu latautuu, käyttäjälle tarjotaan äänestyksiä selattavaksi
  * Poikkeuksellinen toiminta:

* **Äänestystilanteiden tarkastelu:**
  * Käyttäjät: Kaikki
  * Laukaisija: Käyttäjä valitsee äänestyksen
  * Esiehto: Äänestyksiä on valittavana
  * Jälkiehto: Käyttäjä näkee äänestystilanteen
  * Käyttötapauksen kulku: Käyttäjä selaa äänestyksiä ja valitsee yhden, äänestystilanne avautuu
  * Poikkeuksellinen toiminta:
 
* **Äänestäminen:**
  * Käyttäjät: Käyttäjä
  * Laukaisija: Käyttäjä äänestää
  * Esiehto: Äänestys auki
  * Jälkiehto: Käyttäjä on äänestänyt onnistuneesti
  * Käyttötapauksen kulku: Käyttäjä valitsee äänestyksen, valitsee haluamansa vaihtoehdon, äänestystilanne päivittyy
  * Poikkeuksellinen toiminta: Käyttäjä on jo äänestänyt

* **Äänestyksen luominen:**
  * Käyttäjät: Ylläpitäjä
  * Laukaisija: Ylläpitäjä aloittaa äänestyksen
  * Esiehto: Ylläpitäjä on kirjautunut sisään
  * Jälkiehto: Äänestys on luotu onnistuneesti
  * Käyttötapauksen kulku: Ylläpitäjä luo uuden äänestyksen, lisää tarvittavat tiedot, äänestys julkaistaan, äänestys näkyy kaikille käyttäjille
  * Poikkeuksellinen toiminta:

* **Äänestyksen poisto:**
  * Käyttäjät: Ylläpitäjä
  * Laukaisija: Ylläpitäjä haluaa poistaa äänestyksen
  * Esiehto: Poistettavia äänestyksiä on käynnissä, ylläpitäjä on kirjautunut sisään
  * Jälkiehto: Äänestys on poistettu onnistuneesti
  * Käyttötapauksen kulku: Ylläpitäjä valitsee haluamansa äänestyksen, valitsee sen poistettavaksi, ylläpitäjä vahvistaa poiston, äänestys poistuu ja ei ole enää näkyvissä käyttäjille
  * Poikkeuksellinen toiminta: 
