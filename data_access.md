---
layout: page
title: Data access
date: 20180620
slug: data_access
permalink: /data_access/
---

The most appropriate way to access HELP data will depend on your science interest and the tools you are comfortable with using. Here we will provide some links to the data in various formats including large tables of millions objects in addition to web queries to return a small number of objects of interest to you. HELP is targeted towards generating all sky samples of objects that have Herschel measurements. However many people have found the collation and homogenisation of optical survey data to be useful to them. If you are just getting started a good introduction is to look at one specific field to understand the data that is available there. The [ELAIS-N1 field](http://hedam.lam.fr/HELP/dataproducts/dmu31/dmu31_Field_overviews/ELAIS-N1.html) is a good example or you can get links to overviews for all fields [here](http://hedam.lam.fr/HELP/dataproducts/dmu31/dmu31_Field_overviews/). You might also want to think about writing a query across the whole sky using the Virtual Observatory at susseX (VOX). Here is an [example query](https://herschel-vos.phys.sussex.ac.uk/__system__/adql/query/form?__nevow_form__=genForm&query=SELECT%20TOP%2010%20*%20from%20help_a_list.main%20WHERE%20redshift%20%3E%204&_TIMEOUT=5&_FORMAT=HTML&submit=Go) for objects at high redshift.

If you are familiar with the structure of the database you can access all data on the Herschel Database in Marseille:

- [http://hedam.lam.fr/HELP/](http://hedam.lam.fr/HELP/)

The raw files can be extremely large. For some of the final data products it is also possible to query the data from the Virtual Observatory database:

- [https://herschel-vos.phys.sussex.ac.uk/](https://herschel-vos.phys.sussex.ac.uk/)

The structure of the database server and the code used to perform the reduction is all stored on [GitHub](https://github.com/H-E-L-P/dmu_products) which contains extensive documentation including in the Jupyter notebooks used to execute the code. The GitHub pages are probably the best place to find details about the data used and how the final database is structured. We also encourage reuse of all the code there. Please contact us with any queries by creating a GitHub issue.
