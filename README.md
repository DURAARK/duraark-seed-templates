# DURAARK Seed Templates

This repository holds a set of seed (enrichment) templates supporting the semantic enrichment capabilities of the of the [DURAARK system](https://github.com/DURAARK/duraark-system).

# Format

Each template is living in its own [YAML](https://en.wikipedia.org/wiki/YAML) file. Each file has the four mandatory items

* label,
* description,
* seeds,
* variables,

where 'seeds' is a list of seed entities. 'label' and 'description' are necessary to display the query in the [WorkbenchUI](https://github.com/DURAARK/workbench-ui).

'variables' is an array of [buildm](https://github.com/DURAARK/Schemas/tree/master/rdf) properties which will be inserted from the respective bduilding metadata.

## Demo

A public demo of the [DURAARK System](http://github.com/duraark/duraark-system) which incorporates the queries in this repository is available [here](http://workbench.duraark.eu).
