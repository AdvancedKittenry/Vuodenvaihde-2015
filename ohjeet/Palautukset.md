<h2>Palautusten vaatimukset</h2>

* Jokaisen viikon sunnuntaina on deadline, johon mennessä harjoitustyön tulisi täyttää tällä sivulla määritellyt vaatimukset
* Aikataulun noudattamisesta saa max. 3 pistettä per deadline
* Maksimipisteet aikataulun noudattamisesta siis 15
* Myöhästymisestä pisteet on 0
  * Seuraavaan deadlineen on oltava kyseinen deadline ja myöhästynyt deadline
* Jokaisesta palautuksesta tulee lyhyehkö kirjallinen palaute labtooliin
* Tarkempaa palautetta saat käymällä pajassa
* **Jos et toteuta sovellustasi PHP:lla, mukaile vaatimuksia parhaasi mukaan**
* **Lisäaikaa saa hyvällä syyllä, etukäteen pyytämällä**

<h3>Viikko 1</h3>
<ol>
  <li>
    Valitse harjoitustyösi aihe (katso <a href="http://advancedkittenry.github.io/suunnittelu_ja_tyoymparisto/aiheet/index.html">aihe-ehdotukset</a>, jos aiheen valinta tuottaa vaikeuksia). <strong>(0,5p)</strong>
  </li>
  <li>
    Pystytä versionhallinta. <strong>(0,5p)</strong>
    <ul>
      <li>Luo repositorio <a href="http://github.com">GitHubiin</a>, ja lisää <code>README.md</code>-tiedostoon aiheesi kuvaus tai linkki valmiiseen aiheeseen, linkki sovellukseesi ja linkki dokumentaatioosi (linkki kansiossa <code>doc</code> sijaitsevaan <code>pdf</code>-tiedostoon).
    </ul>
  </li>
  <li>
    Dokumentoi perusasiat <code>doc</code>-kansioon yhteen <code>pdf</code>-tiedostoon. <strong>(1p)</strong></li>
    <ul>
      <li>Lisää <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#johdanto">johdanto</a></li>
      <li>Lisää <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#yleiskuva-j%C3%A4rjestelm%C3%A4st%C3%A4">käyttötapaukset</a></li>
    </ul>
  </li>
  <li>
    Pystytä työympäristö. <strong>(1p)</strong>
    <ul>
      <li>Ota PHP-tuki käyttöön</li>
      <li>Ota PostgreSQL-tietokantapalvelin käyttöön</li>
      <li>Luo SSH-avain</li>
    </ul>
  </li>
  <li>Rekisteröidy <a href="http://tsoha-labtool.herokuapp.com">labtooliin</a>.</li>
</ol>

<h3>Viikko 2</h3>
  <ol>
    <li>
      Suunnittele käyttöliittymäsi ja toteuta niistä staattiset HTML-sivut. Muista lisätä linkit toteuttamiisi sivuihin reposi <code>README.md</code>-tiedostoon. <strong>(1,5p)</strong>
      <ul>
        <li>Suunnittele etusivu</li>
        <li>Suunnittele listaussivut</li>
        <li>Suunnittele muokkaus- ja esittelysivut</li>
      </ul>
    </li>
    <li>
      Ota tietokanta käyttöön ja dokumentoi se. <strong>(1,5p)</strong>
      <ul>
        <li>Lisää dokumentaatioon <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#j%C3%A4rjestelm%C3%A4n-tietosis%C3%A4lt%C3%B6">järjestelmän tietosisältö</a> osio ja <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#relaatiotietokantakaavio">relaatiotietokantakaavio</a></li>
        <li>Lisää tietokantataulujen pystytyslauseet <code>create_tables.sql</code>-tiedostoon</li>
        <li>Lisää tietokantataulujen poistolauseet <code>drop_tables.sql</code>-tiedostoon</li>
        <li>Lisää testidatan lisäyslauseet <code>add_test_data.sql</code>-tiedostoon</li>
      </ul>
    </li>
    <li>
      <strong>Pushaa kaikki tekämäsi muutokset repoosi!</strong>
    </li>
  </ol>
  
  <h3>Viikko 3</h3>
  <ol>
  <li>Toteuta sovellukseesi vähintään yksi malliluokka, jossa on kaikki tietokohteen oliot tietokannasta hakeva metodi (esim. <code>all</code>), tietyllä id:llä varustetun tietokohteen olion tietokannasta hakeva metodi (esim. <code>find</code>) ja tietokohteen olion tietokantaan lisäävä metodi (esim. <code>save</code>). <strong>(1,5p)</strong></li>
  <li>Toteuta malliasi käyttämään kontrolleriin metodit, jotka esittävät tietokohteen listaus-, esittely- ja lisäysnäkymän. Toteuta myös kontrolleriisi metodi, joka mahdollistaa tietokohteen olion lisäämisen tietokantaan käyttäjän lähettämän lomakkeen tiedoilla. <strong>(1,5p)</strong></li>
  <li>Kirjoita <a href="http://advancedkittenry.github.io/aikataulu/koodikatselmointi.html" target="_blank">koodikatselmointi</a> (vapaaehtoinen). <strong>(0-2p)</strong></li>
  <li>
    <strong>Pushaa kaikki tekämäsi muutokset repoosi!</strong>
  </li>
</ol>

<h3>Viikko 4</h3>
<ol>
  <li>Lisää malliluokkaasi metodi tietokohteen olion muokkaamiselle (esim. <code>update</code>)- ja poistolle (esim. <code>destroy</code>). <strong>(1p)</strong></li>
  <li>Lisää käyttäjälle mahdollisuus muokkaukseen ja poistoon lisäämällä kontrolleriin tarvittavat medotit ja toteuttamalla tarvittavat näkymät. Muokkausnäkymä on luultavasti lisäysnäkymää muistuttava lomake ja poisto voi tapahtua painiketta painamalla esimerkiksi tietokohteen esittely- tai listaussivulla. <strong>(0,5p)</strong></li>
  <li>Lisää malliisi tarvittavat validaattorit ja estä kontrollereissa virheellisten syötteiden lisääminen tietokantaan. Muista näyttää lomakkeissa virhetilanteissa virheilmoitukset ja täyttää kentät käyttäjän antamilla syötteillä. <strong>(0,5p)</strong></li>
  <li>Toteuta malliluokka sovelluksen käyttäjälle ja toteuta käyttäjän kirjautuminen. Toteuta <code>get_user_logged_in</code>-metodi ja käytä tarvittaessa kirjautuneen käyttäjän tietoa hyväksi näkymissä ja malleissa. <strong>(0,5p)</strong></li>
  <li>Kirjoita alustava <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#k%C3%A4ynnistys--k%C3%A4ytt%C3%B6ohje" target="_blank">käynnistys- / käyttöohje</a> dokumentaatioosi. Lisää myös reposi <code>README.md</code> tiedostoon käyttäjätunnus ja salasana, jolla ohjaaja voi kirjautua sisään sovellukseesi. <strong>(0.5p)</strong></li>
  <li>
    <strong>Pushaa kaikki tekämäsi muutokset repoosi!</strong>
  </li>
</ol>

<h3>Viikko 5</h3>
<ol>
  <li>Toteuta käyttäjän uloskirjautuminen ja estä kirjautumattoman käyttäjän pääsy sivuille, jotka vaativat kirjautumisen. <strong>(1p)</strong></li>
  <li>Edistä sovellustasi ja pidä koodi siistinä noudattamalla selkeää kansiorakennetta ja järkevää nimeämistä tiedostojen, luokkien ja metodien nimissä. Vaatimuksena on, että ainakin kahdelle tietokohteelle on toteutettu sivuja. <strong>Kaikkia CRUD-nelikon osia ei kuitenkaan tarvitse toteuttaa, listaus- ja esittelysivut uudelle tietokohteelle riittävät hyvin</strong>. Lisäksi kaikkien toimintojen tulee toimia ja virhetilanteissa käyttäjälle täytyy antaa järkeviä virheilmoituksia. <strong>(1p)</strong></li>
  <li>Lisää dokumentaatioosi <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#j%C3%A4rjestelm%C3%A4n-yleisrakenne" target="_blank">järjestelmän-yleisrakenne</a>-osio ja <a href="http://advancedkittenry.github.io/dokumentaatio-ohje.html#kayttoliittymakomponentit" target="_blank">käyttöliittymän ja järjestelmän komponentteja kuvaa kaavio</a>. <strong>(1p)</strong></li>
  <li>Kirjoita <a href="http://advancedkittenry.github.io/aikataulu/koodikatselmointi.html" target="_blank">koodikatselmointi</a> (vapaaehtoinen). <strong>(0-2p)</strong></li>
  <li>
    <strong>Pushaa kaikki tekämäsi muutokset repoosi!</strong>
  </li>
</ol>
<h3>
<a href="http://tsoha.github.io/#/lopullinen-palautus">Lopullinen palautus</a>
</h3>
