---
author: herschellegacyproject
date: 2021-03-16 12:44:35+00:00
layout: page
slug: faq
title: Frequently Asked Questions (FAQ)
---

## How do I get the main results table for a given field?

The final tables are stored on HeDaM. All fields are available [here](http://hedam.lam.fr/HELP/dataproducts/dmu32/). 
You need to click on the directory for a given field, then go in the data folder and download the fits file with name of the field. 
For example the final table for ELAIS-N1 is here:

- [http://hedam.lam.fr/HELP/dataproducts/dmu32/dmu32_ELAIS-N1/data/ELAIS-N1_20171016.fits](http://hedam.lam.fr/HELP/dataproducts/dmu32/dmu32_ELAIS-N1/data/ELAIS-N1_20171016.fits)

## Can I get a table of all the Herschel fluxes?

Yes this is available [here](http://hedam.lam.fr/HELP/dataproducts/dmu32/dmu32_AllSky/data/HELP_all_sky_A-list_20201111.fits). 
That is a link to what we call the 'A-list' that includes objects with two far infrared detections, a photometric redshift and SED fitting. 
You might also be interested in other samples. 
Perhaps you would rather query the virtual observatory to find everything detected in [250 micron SPIRE imaging](https://herschel-vos.phys.sussex.ac.uk/__system__/adql/query/form?__nevow_form__=genForm&query=SELECT%20TOP%2010%20*%20from%20help_a_list.main%20WHERE%20f_spire_250%2Fferr_spire_250%20%3E2&_TIMEOUT=5&_FORMAT=HTML&submit=Go).

## What is the difference betwee 'blind' photometry and the main HELP far infrared fluxes?

Blind catalogues are found directly from the far infrared images without using any other information. 
Because the Herschel maps are 'confused' these are not as deep as the main photometry whcih uses high resolution optical surveys to 'deblend' the far infrared maps and can effectively be deeper than the blind photometry.
You could compare the numbers on the ELAIS-N1 field for instance. You would see that there are fewer objects and mainly brighter obejcts in the blind list [here](http://hedam.lam.fr/HELP/dataproducts/dmu22/dmu22_ELAIS-N1/data/dmu22_XID+SPIRE_ELAIS-N1_BLIND_Matched_MF.fits). 
While you would find many more in the main HELP catalogue [here](ELAIS-N1_20171016.fits).
This deblending is done with the [XID+](https://github.com/H-E-L-P/XID_plus) code developed for HELP.

## HELP is too complicated. I just want 'the' data.

If you are just getting started you probably want to look at the final merged catalogues in what we call [DMU32](http://hedam.lam.fr/HELP/dataproducts/dmu32/). 
Once you have found the main list you are interested in you might want to look at the larger data sets associated with your objects such as the full photometric redshift posterior distributions of individual SED fits.
Please feel free to open a GitHub issue or email us and we will try to help you get the data that you want. 
The [field overviews](http://hedam.lam.fr/HELP/dataproducts/dmu31/dmu31_Field_overviews/) also provide a good entry point to begin to understand all the HELP data products.

