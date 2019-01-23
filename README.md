# Data integration

## Environment

### Database
![db_structure](https://pp.userapi.com/c849228/v849228250/10f8f7/bLXUXdEnrDQ.jpg)

Full [script](create_insert.txt) for db creation

### Ontology

#### Entities:

![entities](https://pp.userapi.com/c849228/v849228250/10f8fe/gJLE3BC02x4.jpg)

#### Object properties:

![properties](https://pp.userapi.com/c849228/v849228250/10f905/Lpr0lHuuVG8.jpg)

#### Data properties:

![properties](https://pp.userapi.com/c849228/v849228250/10f915/307LDr-WVsg.jpg)

#### Ontop mappings:

![mappings](https://pp.userapi.com/c849228/v849228250/10f91d/Ghb2Qpc8D4A.jpg)


## Deploying SPARQL endpoint 

### Setting up Tomcat Server

1. Download and unzip the archive with Tomcat [tomcat-ontop-bundle.zip](https://github.com/ontop/ontop-examples/raw/master/ekaw-tutorial-2016/tomcat-ontop-bundle.zip)
2. Start tomcat from the *bin folder* using the commands: 
	* On Mac/Linux: using the terminal run `sh startup.sh` or  `sh catalina.sh start`.
	* On Windows: click on the executable `startup.bat`.
3. Connect to Sesame Workbench at http://localhost:8080/rdf4j-workbench/ .
4. You will be automatically redirected to the repositories view .

### Setting up rdf4j workbench:

1. Download [OWL ontology file](cyberr_sport.owl) .
2. Download [OBDA mapping file](cyberr_sport.obda) .

3. Click on *New repository*
  * Select *Ontop Virtual RDF Store* from the list.
  * Give an ID to your new repository (ex: Project).
  * Click on *Next*.

On the next page:
  * Specify path to downloaded files
  * Keep the default options.
  * Click on *Create*.
  
## SPARQL Queries examples:

