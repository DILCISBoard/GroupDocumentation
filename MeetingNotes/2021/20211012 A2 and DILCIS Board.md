# Meeting Minutes of E-ARK3 A2 and DILCIS Board 2021-10-12

## Members attending:

* Karin Bredenberg DLM (Kommunalförbundet Sydarkivera, chair)
* Anders Bo Nielsen (Danish National Archives)
* Anja Paulič (Archives of the Republic of Slovenia) 
* Audun Lund (Swiss Federal Archives)
* Carl Wilson (OPF)
* David Anderson (Highbury R&D and DLM Observer)
* Gregor Završnik (Geoarch)
* Jamie Kaminski (Highbury R&D)
* Janet Anderson (Highbury R&D)
* Jože Škofljanec (Archives of the Republic of Slovenia)
* Karin Oolu DLM (EasyLean OÜ)
* Kuldar Aas (National Archives of Estonia)
* Lauri Rätsep (National Archives of Estonia)
* Markus Merenmies DLM (National Archives of Finland)
* Miguel Ferreira (KEEP Solutions)
* Stephen Mackey (PIQL)
* Sven Schlarb (Austrian Institute of Technology)
* Kuldar Aas (National Archives of Estonia)
* Krystyna Ohnesorge (Swiss Federal Archives)


## Secretary:
Karin Oolu will make the notes


## Text:

The focus of the meeting is on status reports of documents that will be published on month M24, the deadline is on coming Friday, Oct 15th: 

#### *CSIP* 
Mostly textual updates and clarity of language (not changing anything but making wording more precise as not native speakers may understand words differently). CW demonstrates the examples on the big screen, explaining misleading words. The third opinion by Martin Dew is expected in the afternoon. No Q-s in the room. 

- *Action point: CW informs about the final version.* 

#### *SIP* 
MF has been looking at the examples of specs and few mistakes need to be fixed, mostly fixing the cardinality. This is handed over to KB who will do it ASAP after the conference. SIP has not changed a lot during the last year.

#### *AIP* 
A White Paper of AIP has been distributed lately explaining the principles of the new AIP design. SS introduces the document where AIP is fully compliant with SIP, the scope is limited to what concerns storage and lifecycle, how are IP-s are managed over time. Redundancies were removed, also things that are already covered by CSIP or by concrete CITS, so we don’t have to keep them in line and consistent. The doc is much shorter and easier to implement now, also the reference implementation is in line with AIP spec. Now sorting out minor issues like automatic markdown, done by CW. 

The spec has to be ready by Friday as being part of deliverables, but as few things need clarifications for colleagues outside this group (writing GL-s and examples), ABN proposes to have more meetings in Oct regarding AIP. SS explains that with the new structure we have dependencies, details of OCFL implementation, also the naming scheme examples how to name physical containers to avoid overwriting, examples for the METS, etc. The reference implementation and the AIP allow more examples now, also others could provide examples. E.g. if they are compliant they can share examples that show more complex migration scenarios with metadata, splitting, advanced use cases. 

KA was lacking info about how AIP does relate to real-life solutions? Some examples, like where to put json files, would help to explain. MF asked if examples should be in the document or somewhere else. Short typical examples are included to spec, but bigger examples should be in a separate folder in GH. Examples need to grow, and we need use cases to be able to create examples. 

KB asks to add some text to GL for CSIP, but first, finish the spec by Oct 15th and we will cover that afterwards. 

ABN has got a Q from colleagues and it's a little bit difficult to sell the spec right now, but still, DNA is very keen to implement most of it next year. SS reports we can highlight the collaboration with OCFL, they are very interested. It works like E-ARK opens the issue in OCFL GH to address the issue we want an inventory of packages, containers. It helps us to define the additional structure, take all OCFL files and keep them in separate disks easily accessible. IP-s themselves are still autonomous, we do not depend on OCFL json files. 

- *Action point: KA and ABN will look into migration scenarios or real-life use-cases.*

#### *DIP* 
We haven’t described in detail how going from AIP to DIP and it is difficult to do as we are not fully settled on AIP. KB adds it has to take into account all the new CITS and therefore it's not OK to update it now.  JA Q if it is a new potential project.

#### *e-Health2 GL*/ 
It will be ready by Friday, only some changes and suggestions have yet to be done.

- *Action point: KA will get documents by Friday.* 

### DILCIS board role  
E-ARK project ends with Oct 2021, but we need to maintain the specs also in a time when we are not in the project. As a member of DILCIS Board you have duties as a member and you need to check that in GH. We can't count on getting paid for the work in DILCIS Board. KB will keep e-mail addresses.

In regards to website dilcis.eu it’s time to review the texts and provide updates by specs leads to KA. Preferably by the last week of Oct. Not only IP-s but all CITS as well.                                                                                                                                      
KA Q about zoom after finishing E-ARK and regular A2 meetings. Yes, KB will handle that. 
DILCIS Board meetings will take place once a month when there are working groups meetings. We'll have one meeting before the end of the new year, but further on as we do it with METS Board, every 6 weeks. 

ABN Q about handling issues of current specs and what’s the time frame is to respond to due time. 
We have said in Bylaws that one member is appointed to one spec. To bring issues for board's advice we need board meetings in fixed series. It’s now time to set up the procedure and figure that out. 

- Important to remember:  If you are a member of DILCIS Board you have obligations. All the leads can assemble teams around specs to get more implementers, which also means more issues. It's good to show out that we are working voluntarily!

## Notes by: 

Karin Oolu
