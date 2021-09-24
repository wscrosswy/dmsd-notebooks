### Overview
This repo contains notebooks with queries, examples and code snippets as part of my research on data model-driven systems integration.

**fhir-profiles-sparql**: FHIR profiles mapped into the ontology domain are analyzed using generic SPARQL queries to produce compatibility reports

### Setup
Stardog Setup
- Stardog docs: https://docs.stardog.com/
(TODO)

Jupyter Notebook Setup
- Install jupyter: https://harshityadav95.medium.com/jupyter-notebook-in-windows-subsystem-for-linux-wsl-8b46fdf0a536
- Set up SPARQL in jupyter:
	- User's blog post: http://www.bobdc.com/blog/jupytersparql/
	- User's example notebook: https://github.com/bobdc/misc/blob/master/JupyterSPARQL/Jupyter%20and%20SPARQL%20and%20Dort%20or%20Dordrecht.ipynb
	- sparql-kernel documentation: https://github.com/paulovn/sparql-kernel

	
### Running
Stardog
- Run stardog server: "<stardog bin dir>/stardog-admin.bat server start &"
- (not necessary) stardog studio: access https://stardog.studio/#/ in browser and connect to local stardog server
- NOTE ENDPOINT IS localhost:<PORT>/<db>/{query|update}

Jupyter
- Start jupyter notebook: "jupyter-notebook" in WSL
