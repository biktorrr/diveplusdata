# diveplusdata
repository for datasets for the DIVE Plus demonstrator See http://diveproject.beeldengeluid.nl.  Currently we have partial data from four collections and three vocabularies. These are in RDF Turtle. 

# Open Images
Consisting of the video collection itself as well as the GTAA thesaurus
**Open Images collection**
Originally from openbeelden.nl (3000 videos)
Creative Commons – Attribution-Share Alike license (CC-by-SA)
Subset in DIVE triple store is all videos from OpenImages, as found in an existing RDF conversion. For 510 videos crowd enrichments are added with relations entities, events, persons, places through crowdsourcing.

**GTAA** (Gemeenschappelijke Thesaurus Audiovisuele Archieven). 
From http://gtaa.beeldengeluid.nl . Entities from KB are also matched to this thesaurus.

All Open images content can be found in the oi_dive folder:
* al_oipers_to_gtaapers.ttl	alignments from crowdsourced persons to GTAA 
* al_oiplace_to_gtaageo.ttl	alignments from crowdsourced locations to GTAA 
* al_oirest_to_gtaaall.ttl	alignments from crowdsourced concepts to GTAA 
* gtaa_clean.ttl.gz	GTAA dump 
* oi_collectiontriples.ttl	triples registering media objects to a collection
* oi_enrichments.ttl	crowdsourced enrichments 
* oi_schema_mappings.ttl	OI to Dive schema mappings
* oi_sources.ttl	for sources and placeholders (thumbnails and video locations)
* openbeelden.ttl	Openimages collection, earlier dump by Michiel Hildebrand 
* void.ttl VOID file, includes library statements for ClioPatria


# Radio bulletins from KB
Originally from http://www.delpher.nl/nl/radiobulletins. Size is 1.5 millions of items ANP has made the objects (JPGs, OCRs, ALTOs) in this set available under a CC-BY-NC-ND 3.0 license (link is external).
Subset in DIVE triple store is 2210 digitized typoscripts (radio news scripts, to be read during news broadcasts) from the period 1937-1984.These were chosen to match the Openbeelden subset by re-using terms found there for the search request. 

# Amsterdam museum
Originally from https://bitbucket.org/biktorrr/amlod (thousands of objects) Which was derived from public collection website (www.amsterdammuseum.nl/collectie/) Data published under Creative Commons Attribution license (CC-by)

The collection and vocabularies are found in the am_dive folder.

**Collection Subset**
Subset in DIVE triple store: this one has all items from the 1950s-1980s which corresponds to the OI dataset. In total there are now 3576 objects with 140K triples

**Amsterdam Museum Thesaurus**
the thesaurus used to annotate AM objects. This is (partially) aligned with GTAA.

# Tropenmuseum
Originally from the old 2004 data we converted for the eculture project (eculture.multimedian.nl). This consists of some 70.000 objects. This is most likely the same as http://www.opencultuurdata.nl/wiki/tropenmuseum/. That dataset has CC-by-SA 3.0. 

The collection and vocabularies are found in the kit_dive folder.

**Collection subset**
Subset in DIVE triple store: a selection, based on a 'series' (something like a collection). The randomly selected Series 0003 has around 1000 objects.

**SVCN**
the thesaurus used to annotate Tropenmuseum objects. This is (partially) aligned with GTAA.


