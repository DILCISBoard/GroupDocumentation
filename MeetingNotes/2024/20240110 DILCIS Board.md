# **Minutes DILCIS Board 2024-01-10**

## **Members attending:**



* Karin Bredenberg (Kommunalförbundet Sydarkivera, chair)
* Anders Bo Nielsen (National Archives of Denmark)
* Anja Paulič (National Archives of Slovenia)
* Arne-Kristian Groven (National Archives of Norway)
* Gregor Zavrsnik (Geoarh)*
* Maya Bangerter (Swiss Federal Archives)
* Janet Anderson (Highbury Research & Development Ltd.)
* Miguel Ferreira (KEEP Solutions)
* Stephen Mackey (Penwern Limited)
* Sven Schlarb (Austrian Institute of Technology)
* David Anderson (Highbury Research & Development Ltd., DLM Forum observer)

*=absent

## **Agenda**

1. Welcome
2. Secretary of the meeting
3. E-ARK CSP updates (all)
    1. Continuation of discussion regarding finances for updates of the publication process
        1. Information Packages
        2. Content Information Type Specifications
4. Common questions
   1. **DECISIONS NEEDED:** \
    Request for a new CITS, 3D Product Model (3D PM), Request form sent out separately
   2. **DECISIONS NEEDED**:
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/703](https://github.com/DILCISBoard/E-ARK-CSIP/issues/703)
        2. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/707](https://github.com/DILCISBoard/E-ARK-CSIP/issues/707)
        3. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/708](https://github.com/DILCISBoard/E-ARK-CSIP/issues/708)
        4. [ https://github.com/DILCISBoard/E-ARK-CSIP/issues/709](https://github.com/DILCISBoard/E-ARK-CSIP/issues/709)
    3. **DECISION NEEDED**
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/4](https://github.com/DILCISBoard/E-ARK-CSIP/issues/4)
            1. Suggestion:[ https://github.com/DILCISBoard/E-ARK-CSIP/compare/master...rel/2.2.0](https://github.com/DILCISBoard/E-ARK-CSIP/compare/master...rel/2.2.0)
    4. **DECISION NEEDED**
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/713](https://github.com/DILCISBoard/E-ARK-CSIP/issues/713)
            1. How to handle – versus –
            2. Addition of missing LoC values
            3. Planning?
            4. Responsible
    5. **DECISION NEEDED**
        1.   What will be part of publication on the 17th of May 2024?
            1. Handling of issues
            2. Inclusion of acknowledgement page
        2. Decision already made upon version numbers
            1. [https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230216%20DILCIS%20Board.md](https://github.com/DILCISBoard/GroupDocumentation/blob/master/MeetingNotes/2023/20230216%20DILCIS%20Board.md)
            2. For IP’s the number is 2.2/2.2.0
                1. Gather all updates for the next version in a branch rel/vN.N or rel/vN.N.N \
 (CSIP already have this branch and its named rel/v2.2)
                2. Make your PR’s towards this version branch
                    1.    Make sure to state which issue the PR is handling
                3. Publication is a PR from rel/vN.N or rel/vN.N.N to Master
5. Status of our specifications (all specification responsible)
    1. CSIP
        1.    Report from Sven
            1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/712](https://github.com/DILCISBoard/E-ARK-CSIP/issues/712)
        2. PR’s[ https://github.com/DILCISBoard/E-ARK-CSIP/pulls](https://github.com/DILCISBoard/E-ARK-CSIP/pulls)
    8. SIP
    9. AIP
    10. DIP
    11.  Preservation
    12. Archival
    13. eHealth1
        1. **DECISION NEEDED**
            1. Review of version 2
    14. eHealth2
    15. ERMS
        1. PR’s[ https://github.com/DILCISBoard/CITS-ERMS/pulls](https://github.com/DILCISBoard/CITS-ERMS/pulls)
    16. Geodata
        1. [https://github.com/DILCISBoard/CITS-Geospatial/issues](https://github.com/DILCISBoard/CITS-Geospatial/issues)
    17. CITS SIARD
        1. [https://github.com/DILCISBoard/CITS-SIARD/issues/8](https://github.com/DILCISBoard/CITS-SIARD/issues/8)
6. SIARD
    1. PR’s[ https://github.com/DILCISBoard/SIARD/pulls](https://github.com/DILCISBoard/SIARD/pulls)<span style="text-decoration:underline;"> </span>
    2. [https://github.com/DILCISBoard/SIARD/issues/61](https://github.com/DILCISBoard/SIARD/issues/61)
7. Webpage
8. Next meeting
9. Meeting closes

# **Notes**

## **Welcome**
Karin welcomed everyone to the meeting 
## **Secretary of the meeting**
Janet Anderson
## **E-ARK CSP updates (all)**
Publication process is ongoing – we need final decisions on updating the IPs so that they can be finalised by March. Some of the CITS have METS profiles already, some will not be done. \
 \
We need to think about what is enforceable– using a METS profile helps here. We should think about which specifications need to be enforceable in the future – we already have “MUST, SHOULD and MAY” but there are also looser recommendations to consider. E.g. the Archival CITS has looser recommendations regarding which standards to use. The CITS need to be structured properly with one of the three explicit levels (you can use should with lower case for recommendations). It should be possible to achieve consensus for most cases: Archival and Preservation will be more difficult. Will these levels it is easier to create the XPATH tests for the XPATH or Schematron tests (Carl Wilson has done this work). The change in the specifications is just a change in form, not in essence, so they can be used the same as ever with the normal outputs. The “agent” is the element with the most dependencies (a topic that people find hard to understand). \
 \
Work is going on with the Geo CITS, John is working on the CSIP, Sven is working on the AIP with one versioning requirement for the METS profile.
## **Common questions**
   1. The DILCIS Board approved the new 3D PM CITS. People encouraged to submit requests for any new CITS – 3D DCH and Digital Signature.
   2. METS profiles should have the version number in the filename from now on, and the same for the vocabularies. Do we use the latest METS profile version number from the link for the SIP (this is how it is done in W3C)? This does not work for the AIP which would have been created some time earlier with a different version number. The default METS profile is the latest version. However, even with SIPs, people can be using 2 or 3 versions back. Also do we use the whole path with the patch version 2.0.4? _Recommendation – point to the specific version used, or the default is the current version. Then an implementer could use a later version of the METS profile, but it must be compatible with the one used and be possible to validate this correctly._ This may lead to V3.0 as the CSIP would not be backwards compatible, also the vocabularies issues. Different validators would need to be used. 
 \
### Note
* it is hard to vote on Github issues
* we need a brief summary, with expected consequences so it is easier and quicker to vote in this Board.
* This could be done, and the link sent out before the board. We could use the Github board and label the issues to help with this process – Karin and Sven to set this up. We have byelaws that cover our voting – we need a majority in favour for change, especially for anything that materially changes the specifications themselves. \
  \
People are suggesting updates on Github.  \
 \
Each team leader needs to regularly check their issues.
## Status of our specifications (all specification responsible) 
Most of the agenda points were postponed to next time to instead be presented with the new suggested kanban view with summaries and voting.

1. CSIP
2. SIP
3. AIP
4. DIP
5.  Preservation
6. Archival
7. eHealth1, There has been a major update on eHealth1, so we need a review. We will need to set up the review EU Survey form – ask Jaime for the old one.
8. eHealth2
9. ERMS
10. Geodata, Gregor is summarising the Geo issues. 
11. CITS SIARD, A-KG is assigned to the issue in the agenda.
## SIARD
There is a new issue for SIARD – for ABN, A-KG, and MB on LOB-folder handling. KEEPS need to be kept in the loop.
## Webpage
Karin have published a welcome and a goodbye for our changes in memberships
## Next meeting
Tentatively Wednesday 14<sup>th</sup> February 10.00 CET.
