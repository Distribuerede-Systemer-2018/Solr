#Solr

I denne øvelsesgang skal i prøve at lege med et Apache Solr. Solr er en søge- og indekseringsplatform, som er meget populær og meget hurtig. Typisk vil man bruge denne til at indeksere en database, og så lave sine søgninger direkte i Solr, og efterfølgende trække dataen ud af databasen. 

###Øvelse 1 - få Solr op at køre

1. Følg denne guide ned til afsnittet omkring searching: http://lucene.apache.org/solr/guide/7_4/solr-tutorial.html
2. Hvor mange entries er der i databasen? Og hvor mange af disse er bøger?
3. Hvor mange Belkin produkter er der i databasen?
4. Hvilket grafikkort er billigst?
5. (Optional) Hent programmet Postman og opgave 2-4 igen direkte derinde.

###Øvelse 2

1. Hent filen pokemon.json fra dette repository
2. Opret din egen collection i Solr, og importer pokomon.json dokumentet.
3. Inde i Solr bør du nu have alle 151 pokemoner. Leg lidt rundt med søge querries. Kan du fx skrive én enkelt query, som returnere både Squirtle og Bulbasaur?
4. Tilføj din egen pokemon nummer 152 direkte i Solr. Under den nuværende collection i Solr vælges Documents og skriver dataen ind i json korrekt format, og trykker submit document. Check at din pokemon er blevet tilføjet inde i Query
