# diveplusdata
repository for datasets for the DIVE Plus demonstrator

See http://diveproject.beeldengeluid.nl

Currently we have partial data from four collections and three thesauri:

Collections
# Openbeelden
* Originally from openbeelden.nl (3000 videos)
Creative Commons – Attribution-Share Alike license (CC-by-SA)
Subset in DIVE triple store is 510 videos that were enriched with entities, events, persons, places through crowdsourcing

# Radio bulletins from KB
Originally from http://www.delpher.nl/nl/radiobulletins. Size is 1.5 millions of items
ANP has made the objects (JPGs, OCRs, ALTOs) in this set available under a CC-BY-NC-ND 3.0 license (link is external).
Subset in DIVE triple store is 2210 digitized typoscripts (radio news scripts, to be read during news broadcasts) from the period 1937-1984.These were chosen to match the Openbeelden subset by re-using terms found there for the search request. 

# Amsterdam museum
Originally from https://bitbucket.org/biktorrr/amlod (thousands)
Which was derived from public collection website (www.amsterdammuseum.nl/collectie/)
Data published under Creative Commons Attribution license (CC-by)
Subset in DIVE triple store: this one has all items from the 1950s-1980s which corresponds to the OI dataset. In total there are now 3576 objects with 140K triples

# Tropenmuseum
 Originally from the old 2004 data we converted for the eculture project (eculture.multimedian.nl). This consists of some 70.000 objects. 
This is most likely the same as http://www.opencultuurdata.nl/wiki/tropenmuseum/. That dataset has CC-by-SA 3.0. We will discuss and check this on 30-3-2016
Subset in DIVE triple store: a selection, based on a 'series' (something like a collection). The randomly selected Series 0003 has around 1000 objects.

Furthermore, the triplestore contains the following thesauri: 
# GTAA (Gemeenschappelijke Thesaurus Audiovisuele Archieven). 
Entities from Openbeelden and KB are matched to this thesaurus.

# Amsterdam Museum Thesaurus: 
the thesaurus used to annotate AM objects. This is (partially) aligned with GTAA.

# SVCN:
the thesaurus used to annotate Tropenmuseum objects. This is (partially) aligned with GTAA.

