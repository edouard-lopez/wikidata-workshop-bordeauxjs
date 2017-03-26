# wikidata-workshop-bordeauxjs
Atelier découverte Wikidata avec Maxime Lathuilière


## 5 item in chinese and french wiki

  SELECT ?s WHERE {
  	?chineseItem schema:about ?s .
  	?chinese schema:isPartOf <https://zh.wikipedia.org/> .
  	?french schema:about ?s .
  	?french schema:isPartOf <https://fr.wikipedia.org/> .
  }
  LIMIT 5
