<!-- Yay, no errors, warnings, or alerts! -->


# **Minutes DILCIS Board 2023-02-16**


## **Members attending:**



* Karin Bredenberg (Kommunalförbundet Sydarkivera, chair)
* Anders Bo Nielsen (National Archives of Denmark) 
* Audun Lund (Swiss Federal Archives)
* Miguel Ferreira (KEEP Solutions)
* Sven Schlarb (Austrian Institute of Technology)
* Gregor Zavrsnik (Geoarh)
* Janet Anderson (Highbury R&D Ireland)
* David Anderson (Highbury R&D Ireland and DLM Observer)

*=absent 


## **Agenda:**



1. Welcome
2. Secretary of the meeting
3. E-ARK CSP updates (all)
    1. Versioning numbers for the IP’s
4. Status of our specifications (all specification responsible)
    1. CSIP
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/698](https://github.com/DILCISBoard/E-ARK-CSIP/issues/698)
        2. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/699](https://github.com/DILCISBoard/E-ARK-CSIP/issues/699)
        3. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/700](https://github.com/DILCISBoard/E-ARK-CSIP/issues/700)
    2. SIP
        1. METS Pointers and a simple METS document?
    3. AIP
        1. [https://github.com/DILCISBoard/E-ARK-AIP/issues/74](https://github.com/DILCISBoard/E-ARK-AIP/issues/74)
        2. [https://github.com/DILCISBoard/E-ARK-AIP/issues/76](https://github.com/DILCISBoard/E-ARK-AIP/issues/76)
        3. [https://github.com/DILCISBoard/E-ARK-AIP/issues/77](https://github.com/DILCISBoard/E-ARK-AIP/issues/77)
        4. [https://github.com/DILCISBoard/E-ARK-AIP/pull/78](https://github.com/DILCISBoard/E-ARK-AIP/pull/78)
    5. DIP
    6. Preservation
        1. Name of the specification, CITS?
    7. Archival
    8. eHealth1
    9. eHealth2
    10. ERMS
    11. Geodata
    12. CITS SIARD
5. SIARD
    1. [https://github.com/DILCISBoard/SIARD/issues/58](https://github.com/DILCISBoard/SIARD/issues/58)
    2. [https://github.com/DILCISBoard/SIARD/issues/59](https://github.com/DILCISBoard/SIARD/issues/59) 
6. Webpage
7. Next meeting
8. Meeting closes


## **Notes:**


### Welcome

Karin Bredenberg welcomed everyone to the meeting.


### Secretary

SS will make the notes.


### E-ARK CSP



* Versioning numbers for the IP’s: Agreed that versioning numbers should be aligned, but only the first two numbers. The third number is reserved for minor updates, such as spelling corrections. 
* The versioning is explaned in ([https://dilcis.eu/images/procedures/LC-001390244_CEF-TC_2019-3_M23d.pdf](https://dilcis.eu/images/procedures/LC-001390244_CEF-TC_2019-3_M23d.pdf)


### Current status of our specifications



* CSIP: 
    * Make sure that dependencies between requirements are coherent, must clarify if schema/schematron must be adapted ([https://github.com/DILCISBoard/E-ARK-CSIP/issues/698](https://github.com/DILCISBoard/E-ARK-CSIP/issues/698) )
    * Contradictory requirements regarding cardinality and must criteria need to be resolved ([https://github.com/DILCISBoard/E-ARK-CSIP/issues/699](https://github.com/DILCISBoard/E-ARK-CSIP/issues/699) )
    * Regarding illegal characters in folder names, the requirment that exactly the OBJID should be used as folder name may lead to problems. Should be reformulated stating that it needs to correspond but does not need to be exactly the same. ([https://github.com/DILCISBoard/E-ARK-CSIP/issues/700](https://github.com/DILCISBoard/E-ARK-CSIP/issues/700) )
* AIP:
    * Most AIP issues have been closed ([https://github.com/DILCISBoard/E-ARK-AIP/issues/74](https://github.com/DILCISBoard/E-ARK-AIP/issues/74) , [https://github.com/DILCISBoard/E-ARK-AIP/issues/77](https://github.com/DILCISBoard/E-ARK-AIP/issues/77) , [https://github.com/DILCISBoard/E-ARK-AIP/pull/78](https://github.com/DILCISBoard/E-ARK-AIP/pull/78) )
    * Need to address  [https://github.com/DILCISBoard/E-ARK-AIP/issues/76](https://github.com/DILCISBoard/E-ARK-AIP/issues/76)  by documenting the lifecycle of the AIP with examples of SIP updates. This is also related to [https://github.com/DILCISBoard/E-ARK-SIP/issues/6](https://github.com/DILCISBoard/E-ARK-SIP/issues/6) .
    * The field CONTENTIDS is a candidate to map SIPs from generator systems to the corresponding AIPs.
    * SIP requirement for Shallow AIP also is relevant for the AIP ([https://github.com/DILCISBoard/E-ARK-SIP/issues/110](https://github.com/DILCISBoard/E-ARK-SIP/issues/110) ). Object stores, such as S3, are used for preservation. It can be that the packaged AIP is used for serialization only. Need to think about the requirement of information package encapsulation. Karin will create an issue to discuss that in the CSIP repo.


### SIARD



* Using clean links to allow usage of URLs in a semantic web environment. Spaces and dots in Filenames - can't link to homepage from linked open data. This is to address NARA's needs. ([https://github.com/DILCISBoard/SIARD/issues/58](https://github.com/DILCISBoard/SIARD/issues/58) )
* Issue [https://github.com/DILCISBoard/SIARD/issues/59](https://github.com/DILCISBoard/SIARD/issues/59)  is off topic and can be closed. Audun will update the tool section readme on Github.


### Webpage

Karin is working with updates.


### Next meeting

New meeting in May at the DLM Forum in Ljubljana.


### Meeting closes

KB thanked all for participating!


## **Notes by:**

Sven Schlarb, 2023-02-16
