# Keyword

**Purpose**: At least one [keyword](#keyword) must be given to describe the subject.

**Prerequisites**

**Test method**

The test checks if at least one [keyword](#keyword) element is provided and it is not an [empty CharacterString](http://inspire.ec.europa.eu/id/ats/metadata/1.3/iso-19115-19119/README#emptychar)

**Reference(s)**	 

* [TG MD](http://inspire.ec.europa.eu/id/ats/metadata/1.3/iso-19115-19119/README#ref_TG_MD), 2.4, Req 13

**Test type**: Automated

**Notes**

##Contextual XPath references

The namespace prefixes used as described in [README.md](http://inspire.ec.europa.eu/id/ats/metadata/1.3/iso-19115-19119/README#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
<a name="keyword"></a> keyword  | gmd:identificationInfo[1]/\*/gmd:descriptiveKeywords/\*/gmd:keyword
