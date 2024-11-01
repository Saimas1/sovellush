# h2

## X)

- Yksi yleinen haavoittuvuus on rikkinäinen käyttöoikeushallinta. Se mahdollistaa luvattoman pääsyn tietoihin tai toimintoihin sovelluksissa. Rikkinäisen käyttöoikeushallinnan tyyppilliset ongelmat ovat liian laajat oikeudet, roolin ylittäminen tai pääsynhallinnan kiertäminen URL-muokkauksella. Sitä ja sen riskejä voidaan kuitenkin ehkäistä: Käyttämällä oletuksena "kielletty"-politiikkaa, varmistamalla tiedostojen listauksen eston tai testaamalla käyttöoikeuksien hallinan säännöllisesti.
- Verkkopalvelimien piiloltettuja hakemistoja voidaan löytää kokeilemalla manuaalisesti erilaisia polkuja. Fuff-työkalulla tämä prosessi voidaan automatisoida nopeasti. Fuff on tehokas fuzzing-työkalu. Sillä voidaan etsiä erilaisia resursseja, kuten hakemistoja tai POST-parametrejä. Sen turvallisen käytön takaamiseksi työkalua tulee käyttää paikallisesti sekä varmistaa että käytössä on tarvittavat luvat sekä sopimukset.
- Access control-haavoittuvuudet liittyvät käyttäjien pääsyyn resursseihin tai oikeuksiin suorittaa tiettyjä toimintoja. Access control-malleja on kolme: vertikaaliset käyttöoikeudet, horisontaaliset käyttöoikeudet sekä kontekstiriippuvat käyttöoikeudet. Vertikaaliset rajoittavat eri käyttäjäryhmiä eli esim admin-oikeudet. Horisontaaliset antavat käyttäjille pääsyn vain heidän omiin tietoihinsa. Kontekstiriippuvaiset taas estävät toimintoja väärässä järjestyksessä esim, maksun jälkeen ostoskorin muokkaaminen. 



## Lähteet:

- OWASP: OWASP Top 10: A01 Broken Access Control: https://owasp.org/Top10/A01_2021-Broken_Access_Control/
- Karvinen 2023: Find Hidden Web Directories - Fuzz URLs with ffuf: https://terokarvinen.com/2023/fuzz-urls-find-hidden-directories/
- PortSwigger: Access control vulnerabilities and privilege escalation: https://portswigger.net/web-security/access-control
- Karvinen 2006: https://terokarvinen.com/2006/raportin-kirjoittaminen-4/
  
