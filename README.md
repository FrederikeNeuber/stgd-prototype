# Data of a prototype edition focusing on microtypography in Stefan George’s works

## Description

This repository collects data from the prototype edition ‘Stefan George Digital’ (short StGD) which is dedicated to the typographical dimension of Stefan George’s (1868–1933) literary work and available at http://gams.uni-graz.at/context:stgd. The prototype edition was published as part of a dissertation which is available at http://kups.ub.uni-koeln.de/id/eprint/12202 (2020). For information in English see https://doi.org/10.5281/zenodo.3700455.

## Content of the repository

* stgd.prints-tei: 25 XML/TEI files of printed volumes of George's works, including metadata (all) and full text (only stgd.teppich.*)
* stgd.schema: relaxNG-schema of the XML/TEI files
* stgd.ontology: Description system for microtypography in RDF/OWL

## Background information on the prototype edition

### Edition of printed books

The focus of StGD is the editorial enrichment of information on typography in general and on microtypography in particular, i.e. of the design and use of typefaces and fonts. StGD includes 25 printed editions of George’s poetical works published between 1897 and 1922. The single works are represented in the corpus variable numbers of times according to their typographical variation. All sources are enriched by bibliographical metadata and digital facsimiles. Four typographical versions of ‘Der Teppich des Lebens und die Lieder von Traum und Tod mit einem Vorspiel’ (1899–1932) are available as edited full texts and with regard to their typographical variance at line level.

### The microtypographical inventory

All edited sources are enhanced by descriptions of the applied fonts based on a description ontology that has been developed for this purpose. This ontology also lays the foundation for the microtypographical inventory, which is part of the edition and a research tool itself. It offers three exploration modes: the type repertoire (Typenrepertoire), e.g. to retrace the genesis of the St-G-typeface, the form repertoire (Formenrepertoire), e.g. to observe the transmission of design features between typefaces, and the typeset repertoire (Satzrepertoire), e.g. to explore the application of fonts in certain text contexts. 

### Concept

![Concept of edition](https://github.com/FrederikeNeuber/stgd-prototype-edition/blob/master/media/concept-edition.png)


### Technical framework

The technical ecosystem of StGD is the FEDORA-based asset management system GAMS (Geisteswissenschaftliches Asset Management System) that guarantees long time archiving. Bibliographical metadata and texts are encoded in XML/TEI. The type descriptions are based on an ontology in RDF/OWL. 

## Creation and Usage

**Author:** Frederike Neuber (neuber.frederike@gmail.com)

**Context of Creation:** StGD emerged within the author’s PhD at the Centre for Information Modelling at the University of Graz and the University of Cologne (finished 2019, published 2020). It was supported by the *Digital Scholarly Editions Initial Training Network* DiXiT (funded 2013–2017 under Marie Curie Actions within the European Commission’s 7th Framework). 

**License:** CC-BY-SA 4.0

**Citation Recommendation:** Neuber, Frederike. ‘stgd-prototype-edition: A prototype edition with focus on microtypography in Stefan George's works’ Date Published 28.4.2020. Date Accessed: #### , https://github.com/FrederikeNeuber/stgd-prototype-edition.
