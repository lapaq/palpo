# palpo

Projektisuunnitelma

Ryhmän jäsenet: Joni Laihonen, 211587

API:n kuvaus: Döölist API tarjoaa REST-rajapinnan kahden asian vertailuun keskenään. Vertailu tapahtuu keräämällä ja yhdistämällä tietoa eri lähteistä ja pisteyttämällä vaihtoehdot eri kriteerien mukaan. Toteutettava ensimmäinen versio tästä epäilemättä maailman maineeseen nousevasta API:sta mahdollistaa vertailun yhdistämällä hakusanaa vastaavaa tietoa Yelpistä, Wikipediasta ja Eventfulista. Lisäksi on mahdollista asettaa vertailuun avainsanoja, joiden avulla voi hieman muokata pisteytyskriteerejä. Pisteytykseen vaikuttavia kriteereitä ovat vertailtavista asioista riippuen mm. Wikipedia-artikkelin olemassaolo/pituus, Yelp-arvostelut, tapahtumien lukumäärä, avainsanan esiintymislukumäärä, ja avainsanaa vastaavan otsikon alla olevan Wikipedia-artikkelin osan pituus.

Esimerkkisovellus: Märriz Seivör on parisuhteiden pelastamiseen tähtäävä sovellus, joka auttaa ratkomaan pahimmat parisuhderiidat eli valitsee voittajan kummankin osapuolen ehdotuksista. Märriz Seivör valitsee voittajan kahdesta annetusta ravintolasta, kahdesta eri häämatkakohteesta ja kahdesta eri poliitikosta (tai muusta julkisuuden henkilöstä), jotta vältyttäisiin ns. Trump vs Clinton -avioeroilta. Märriz Seivörin päätavoitteena on ennen pitkää saattaa kaikki parisuhdeterapeutit työttömiksi.

Toteutustekniikat: Node.js (koska cool), jQuery, HTML5

Aikataulu:

Vko 46: Rajapinnan suunnittelu ja dokumentointi, kehitysympäristö toimimaan
Vko 47: Rajapinnan toteutus ja testaus
Vko 48: Sovelluksen toteutus ja testaus, loppuviilailut
