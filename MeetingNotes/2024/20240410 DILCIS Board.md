# **Minutes DILCIS Board 2024-04-10**

## **Members attending:**
* Karin Bredenberg (Kommunalförbundet Sydarkivera, chair)
* Anders Bo Nielsen (National Archives of Denmark)
* Anja Paulič (National Archives of Slovenia)*
* Arne-Kristian Groven (National Archives of Norway)
* Gregor Zavrsnik (Geoarh)
* Maya Bangerter (Swiss Federal Archives)*
* Janet Anderson (Highbury Research & Development Ltd.)
* Miguel Ferreira (KEEP Solutions)
* Stephen Mackey (Penwern Limited)
* Sven Schlarb (Austrian Institute of Technology)
* David Anderson (Highbury Research & Development Ltd., DLM Forum observer)

*=absent

Invited guest to agenda point 4b:
* Carl Wilson (OPF and E-ARK CSP)

## **Agenda**



1. Welcome
2. Secretary of the meeting
3. E-ARK CSP updates (all)
4. Common questions
    1. **DECISIONS CONFIRMATION**:
        1. [https://github.com/orgs/DILCISBoard/projects/2/views/7](https://github.com/orgs/DILCISBoard/projects/2/views/7)<span style="text-decoration:underline;"> </span>
    2. Publication process
        1. Updated automated publication process
            1. CSIP,
            2. SIP,
            3. AIP,
            4. DIP,
            5. CITS GEO
        2. Manual publication process (Where this will be made: update of version number and date will be made on the first page, addition of the acknowledgment sheet, the Word-version of the document will be transformed into PDF, First page + acknowledgment sheet + text will be combined into one PDF)
            1. CITS Archival,
            2. CITS Preservation,
            3. CITS ERMS,
            4. CITS SIARD,
            5. CITS eHealth1,
            6. CITS eHealth2,
            7. Guideline (Primer) for the Common Specification for Information Packages (CSIP), SIP, AIP, DIP, Preservation Metadata and Archival Information,
            8. Guideline (Primer) for GitHub,
            9. Guideline for CITS SIARD,
            10. Guideline for CITS eHealth2,
            11. Guideline for CITS eHealth1,
            12. Guideline for CITS Geo GIS,
            13. Appendix 1 to Guideline for CITS Geo,
            14. Appendix 2 to Guideline for CITS Geo,
            15. Appendix 3 to Guideline for CITS Geo
        3. Other updates need for the publication
            1. New folder structure and files names and needed changes inside files following earlier decision (Observe this will be made on a large number of files and repositories)
            2. Publication update to GitHub repositories
            3. Update to vocabulary for content types
            4. Update of list with specification names
            5. Update of DILCIS Board webpage
            6. News item to be sent out by E-ARK CSP
            7. List of updates
            8. List of handled issues in the repositories
5. Status of our specifications (all specification responsible)
    1. CSIP
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/733](https://github.com/DILCISBoard/E-ARK-CSIP/issues/733)<span style="text-decoration:underline;"> </span>
    2. SIP
    3. AIP
    4. DIP
    5.  Preservation
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

 ##   **Notes**

1. **Welcome**
* Karin welcomed everyone to the meeting 
2. **Secretary of the meeting**
  * Janet Anderson
3. **E-ARK CSP updates (all)**
  * None. 
4. **Common questions**
    1. Decisions confirmations \
CITS ERMS will likely make V3.0. Karin is working on this
    2. Publication process \
Only CSIP, SIP, AIP, DIP and Geo. \
Questions from MF. MF made all the changes voted on, and then tried to do the publication process, but it failed. CW is ready to start work on this. There is an AMD section (but it is different for Geo) and CW is currently working on CSIP and a YAML file now used. There was a demo of the Geo structure, and CW will create the same for the SIP. The profile will have a version number (apart from the latest version). This is a bit tricky as we are now doing V2.02, so we will have a forwarding link. CW will do a first pass at reviewing. Everything should be much more straightforward, but it would be much better if everyone follows the same structure. Stephen M still has the eHealth1 specification in Word but has mostly got the 3D PM CITS into markdown. We will be able to point to the files in the repository. \
 Review response for eHealth1? No email responses, but some via the spreadsheet. \
 Automated publications? There will be those 5 specifications, plus 15 other documents, all info in 1 PDF. **All the changes need to be in the Word document, and everything must be ready for 1<sup>st</sup> May 2024. **The Github repositories must be updated. The CITS will have the agreed updates. **All the updates made must be listed.** **Everyone must do their part**, so this is like a release note to say what has been changed.[ https://github.com/DILCISBoard/E-ARK-CSIP/releases](https://github.com/DILCISBoard/E-ARK-CSIP/releases) is an example of the changes to the CSIP. **Everyone must do their part.**  
5. Status of our specifications (all specification responsible)
    1. CSIP
        1. [https://github.com/DILCISBoard/E-ARK-CSIP/issues/733](https://github.com/DILCISBoard/E-ARK-CSIP/issues/733)  - Preservation profile question related to eIDAS issues (the Qualified Electronic Archiving services part). ABN reported that the CEN committee has been discussing this, and that it is a tricky issue. It should maybe be in the AIP (but this changes with time)? It should be in the preservation system, or it could be part of the submission agreement. It should be in the guideline (not a CS like PREMIS) and this is the response we will give on Github – it is a bigger question than just adding an element in the CSIP and it should be part of the preservation planning. For CEN, it will probably be in the SIP and outside as well, but it might not be coherent.
    2. SIP  \
MF has got everything ready for publication and has made the examples more readable. Will check the final version. SM asked does the process take the examples from the METS profile and CW confirmed that it does. There are two branches – PDF and CITE and MF has been helpful with typesetting issues.
    5. AIP  \
streamlining the splitting and dividing. We will be having a meeting. We will make a Github issue about Bagit (this came up in the context of the Reference Implementation), also OCFL. Bagit is useful for the splitting, and OCFL for the versioning but we need a common approach on this.
    6. DIP   \
Do we want to have only one representation for the DIP? 
    7.  Preservation  (Nothing to discuss at this meeting)
    8. Archival   \
minor update since RiC was published.
    9. eHealth1 \
SM making changes to the V2.0 – METS profiles – dictionary pairs. For validation, all requirements are now there. 
    10. eHealth2   \
going to work with the guideline by the end of the year.
    11. ERMS  \
will be V3.0
    12. Geodata \
21 smaller issues that will come into the new release. 11 more complex issues, these will be worked on a few at a time. The guideline needs to be in an automated format, and the appendices need to be ready.
    13. CITS SIARD \
there are a few issues open, and we should be able to close them as they are mostly internal and shouldn’t make any changes. It is MG working on this. 
7. **SIARD** 
* the standard is not part of this release. Working on this with MB, ABN and A-K G and MG. 
8. **Webpage**
  * Q. what does “common mean”. A. Genreal for all information packages
  * Not going to make changes for better searches as being offered in numerous spam emails to our info email.
9. **Next meeting**
* 23rd April 12.30 CEST

