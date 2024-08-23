This repository contains timber transportation data for the IPE wood species from 2010 to 2020. 

The `transports.csv` columns account for:

- 'id_wood': id of the IPE species. It matches the column 'id_wood' in the file `species.csv`.
- 'node_src' and 'node_dest': id of the enterprise of origin and destination of the wood. They match the column "id_emp" in the file `nodes.csv`. 
- 'vol': volume of timber transported in m$^3$.
- 'id_product': id of the product type. It matches the column "id_product" in the file `products.csv`.
- 'date': the transportation date.

The jupyter notebook contains a code to build the Timber Trade Network and to compute the $k$ most likely supply chains of a given enterprise.
