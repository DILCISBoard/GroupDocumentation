# **Minutes DILCIS Board 2023-09-13**


## **Members attending:**



* Karin Bredenberg (Kommunalförbundet Sydarkivera, chair)
* Anders Bo Nielsen (National Archives of Denmark)*
* Audun Lund (Swiss Federal Archives)
* Miguel Ferreira (KEEP Solutions)
* Sven Schlarb (Austrian Institute of Technology)
* Gregor Zavrsnik (Geoarh)
* Stephen Mackey (Penwern Limited)
* Janet Anderson (Highbury R&D Ireland)
* David Anderson (Highbury R&D Ireland and DLM Observer)

*=absent


## **Agenda**



1. Welcome 
2. Secretary of the meeting  
3. E-ARK CSP updates (all) 
4. Common questions 
        1. E-ARK Specifications Illustration (Sven)  
        2. Continuation of versioning numbers for the IP’s (Karin) 
5. Status of our specifications (all specification responsible) 
    1. CSIP 
    2. SIP 
    3. AIP 
    4. DIP 
    5. Preservation 
    6. Archival 
    7. eHealth1 
    8. eHealth2 
    9. ERMS 
    10. Geodata 
    11. CITS SIARD 
6. SIARD 
7. Webpage 
8. Next meeting 
9. Meeting closes 

## **Notes**


### Welcome

Karin welcomed everyone to the meeting 


### Secretary of the meeting
Janet Anderson  


### E-ARK CSP updates
All going well. No DILCIS Board meeting at Salamanca, but have it the week afterward, Wednesday 1<sup>st</sup> November 10.00 CET. 


## Common questions 
### E-ARK Specifications Illustration  
Two members did not vote, so we had 7/9 votes. The original diagram was just voted as the best for non-experts. 

![Image 1](https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230815%20Images/Image1.png)

The validation group last suggested diagram was voted as the best for those with some expertise (and could be used for the ETSI discussions). 

![Image 6](https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230815%20Images/Image6.png)

Suggested to dash the lines for Archvial and Preservation since the use of these specifications is optional.

We could add another folder for signature evidence (Docbyte). This could be a subfolder of the Preservation metadata folder showing evidence of authenticity (signatures are covered in PREMIS)? Root or representation level? This needs to be a Github issue…


### Continuation of versioning numbers for the IPs

[https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230216%20DILCIS%20Board.md](https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230216%20DILCIS%20Board.md)

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/703](https://github.com/DILCISBoard/E-ARK-CSIP/issues/703) 

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/707](https://github.com/DILCISBoard/E-ARK-CSIP/issues/707) 

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/708](https://github.com/DILCISBoard/E-ARK-CSIP/issues/708) 

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/709](https://github.com/DILCISBoard/E-ARK-CSIP/issues/709) 

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/710](https://github.com/DILCISBoard/E-ARK-CSIP/issues/710) 

[https://github.com/DILCISBoard/E-ARK-CSIP/issues/711](https://github.com/DILCISBoard/E-ARK-CSIP/issues/711) 

This needs a lot of thought from the DILCIS Board as it affects many things. The versioning is described in the procedures. Luís commented that we need to know the version used in validation. CW has suggested a solution of using the METS Profile ID to denote the version ( we cannot alter the METS version). So, we need to introduce this path in all the IPs: CSP, SIP, DIP (the AIP has no METS profile yet). This should work (and we need to ensure backward compatibility between versions.)

We need to follow up on METS XPATH and cardinality. CW is suggesting that we have an element in the METS profile that describes tests as well (a test element), thus mimicking what follows in the Schematron rules. This is in addition to the cardinality information already kept in a separate, concise table. The test element would be more discursive, like Agent etc.

XSLT transformation of the XML document for the other things coming from the METS profile suggested by CW.

How to relate requirements? We should have agents and requirements, with elements and sub elements etc. The validation team needs these relationships and dependencies to be clearer. CW has suggested that we make the connections to the agent as well, but this seems to be a duplication of effort.

The SIP METS profile adds to the CSIP profile. For eHealth1 there were some extensions, and these should be described and added to the CSIP and SIP etc. (note that CSIP and SIP might be updated at a different time to eHealth1.)


### Status of our specifications (all specification responsible) 
* CSIP 
    * [https://github.com/DILCISBoard/E-ARK-CSIP/issues/704](https://github.com/DILCISBoard/E-ARK-CSIP/issues/704)  \
Rewording to preferable use the IANA-list.
    * [https://github.com/DILCISBoard/E-ARK-CSIP/issues/706](https://github.com/DILCISBoard/E-ARK-CSIP/issues/706)  \
Some grammar issues – wording about crucial metadata. We would like to see all metadata in the metadata folder. Also, it is possible to recognize _standardised_ metadata. It would be useful to have the manifest in the metadata folder. This can be difficult as not all “standards” are recognised (cf eHealth). We could say there should be a _well-defined/standardised_ system (preferably with a schema, but this doesn’t always happen). KB will create a pull request for this which we can then review.
    * **Postponed to next meeting**
        * SIP 
        * AIP
        * DIP
        * Preservation
        * Archival
        * eHealth1 
            * Prepare for review.
        * eHealth2 
        * ERMS 
        * Geodata 
        * CITS SIARD

 


### SIARD 
Postponed to next meeting


### Webpage 
Postponed to next meeting


### Next meeting 
Wednesday 1<sup>st</sup> November 10.00 CET


## **Notes by:**

Janet Anderson, 2023-09-13
