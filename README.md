# Linked-Data-Project
This is my linked data project.
This dataset is taken from the top 50 of Letterboxd's top 500 narrative films list. The data includes the directors, genres, countries, runtimes, studios, and release years associated with each film. 
This project uses the Schema ontology for all triples. 
For the films themselves and the genres, I linked to Wikidata. For the countries, I used Geonames. For the studios, I used Wikidata for most of them, but used VIAF as a substitute if they weren't listed there. Finally, for the directors, I linked to VIAF. 
RDf Examples:
wikidata:Q1130395  rdf:type       schema:Movie;
schema:countryOfOrigin    geonames:8354411;
schema:datePublished      "1985"^^<xsd:gYear>;
schema:director           viaf:24864176;
schema:duration           "PT2H22M"^^<xsd:duration>;
schema:genre              wikidata:Q130232 , wikidata:Q369747;
schema:productionCompany  wikidata:Q141336 , wikidata:Q2621941 .
