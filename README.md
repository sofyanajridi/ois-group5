# OIS-Group5

1) Copy the contents of the travelagency-docs file to the htdocs folder in the XAMPP install directory. 
2) Add the following to the host file of your machine:
  127.0.0.1 ontology.travelagency.org
  127.0.0.1 data.travelagency.org
3) Start the XAMPP Apache server
4) Run the linked data front-end using the following command in the jetty-distribution folder:\\ java -jar start.jar

You now have the following things running:
- Apache Jena Fuseki web server running on port 80.
- Pubby which acts our linked data front-end at http://data.travelagency.org/
- SPARQL endpoint running at http://data.travelagency.org/fuseki/cinema/sparql
- Ontology documentation created with WIDOCO running at http://ontology.travelagency.org/
