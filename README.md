autopkg-recipes
===============

My recipes for autopkg https://github.com/autopkg


Please keep in mind the recipes Adobe Digital Editions, Box Sync, Exceed onDemand Client, Google Voice and Video, Mendeley, RStudio, Stellarium, Studiocode, and TN3270X are just munki recipes for the download recipes created by @hansen_m.  These recipes MUST have his repo also in order to function.  His recipe repo can be found at https://github.com/autopkg/hansen-m-recipes/

The QnA recipe requires the download recipe created by @rustymyers.  His repo can be found at https://github.com/autopkg/rustymyers-recipes/

Known Issues:

DYMO LabelMaker: The DYMO recipe works fine and imports into Munki fine however some of the PKG receipts written out to the PKGInfo do not install properly thus users are prompted to reinstall.  Remove these PKG receipts before placing into production as a workaround to resolve the issue:

com.dymo.dls.uninstall - com.dymo.dls.npapi.addin.105 - com.dymo.drivers - com.dymo.cups.leopard
