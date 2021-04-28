
<h1>Minutes DILCIS Board 2021-04-28</h1>


<h2>Members attending:</h2>




*   Karin Bredenberg (Kommunalförbundet Sydarkivera, chair)
*   Anders Bo Nielsen (National Archives of Denmark) 
*   Audun Lund (Swiss Federal Archives)
*   Miguel Ferreira (KEEP Solutions)
*   Kuldar Aas (National Archives of Estonia)*
*   Sven Schlarb (Austrian Institute of Technology)*
*   Gregor Zavrsnik (Geoarh)
*   Janet Anderson (Highbury R&D)
*   David Anderson (Highbury R&D and DLM Observer)

*=absent 

<h2>Agenda:</h2>




1. Welcome. Secretary of the meeting
2. Change request regarding value list

<h2>Notes:</h2>


<h3>Secretary</h3>


Karin Bredenberg will make the notes.

<h3>Change request value list</h3>


The board has received the change request proposal. 

<h4>The following proposal have been made:</h4>


**Change detail**: Deciding a procedure for the Content Information Type Specification value list.

**Change impact in relation to DILCIS and E-ARK3**:

_Timeline_: This needs to be implemented by August 2021 (at the latest) in preparation for the release of the new and updated specifications.

_Criticality_: High.

_Risk_: Not implementing a procedure will make maintenance of the list of CITS more difficult in the long term. The different ways of doing this described below, have differing implications for the number of entries in the value list.

_Cost_: Update of current value list is 1 hour — implementation of the new ones will be 10 minutes per CITS.

**Approval**:

We have two requirements giving the type of content being sent: 


<table>
  <tr>
   <td><strong>CSIP2</strong>
   </td>
   <td><strong>Content Category</strong>
<p>
<code>mets/@TYPE</code>
<p>
The <code>mets/@TYPE</code> attribute MUST be used to declare the category of the content held in the package, e.g. book, journal, stereograph, video, etc. Legal values are defined in a fixed vocabulary. When the content category used falls outside of the defined vocabulary, the <code>mets/@TYPE</code> value must be set to “OTHER”, and the specific value declared in <code>mets/@csip:OTHERTYPE</code>. The vocabulary will develop under the curation of the DILCIS Board as additional content information type specifications are produced.
<p>
<strong>See also:</strong><a href="https://earkcsip.dilcis.eu/#VocabularyContentCategory"> Content Category</a> (<a href="http://earkcsip.dilcis.eu/schema/CSIPVocabularyContentCategory.xml">http://earkcsip.dilcis.eu/schema/CSIPVocabularyContentCategory.xml</a> )
   </td>
   <td><strong>1..1</strong>
<p>
MUST
   </td>
  </tr>
</table>


 

CSIP2 is stable and should not change its values. (CSIP3 can be used if the type is not in the list and the value OTHER has been chosen.) 

And 


<table>
  <tr>
   <td><strong>CSIP4</strong>
   </td>
   <td><strong>Content Information Type Specification</strong>
<p>
<code>mets/@csip:CONTENTINFORMATIONTYPE</code>
<p>
Used to declare the Content Information Type Specification used when creating the package. Legal values are defined in a fixed vocabulary. The attribute is mandatory for representation level METS documents. The vocabulary will evolve under the care of the DILCIS Board as additional Content Information Type Specifications are developed.
<p>
<strong>See also:</strong><a href="https://earkcsip.dilcis.eu/#VocabularyContentInformationTypeSpecification"> Content information type specification</a> (<a href="http://earkcsip.dilcis.eu/schema/CSIPVocabularyContentInformationType.xml">http://earkcsip.dilcis.eu/schema/CSIPVocabularyContentInformationType.xml</a> )
   </td>
   <td><strong>0..1</strong>
<p>
SHOULD
   </td>
  </tr>
</table>


 

CSIP4 is the one where there is a more open value list with currently these values: ERMS, SIARD1, SIARD2, SIARDDK, GeoData, MIXED and OTHER. (CSIP5 can be used if the CITS is not in the list and value OTHER has been chosen.) Note that we cannot easily delete values in the list since we have no registrations of the use of the values. 

We have no way of saying which version of a CITS is being used. 

We can now handle the values in CSIP4 in 3 ways: 

<h5>
    Way 1</h5>



    We just add new values to the list for CSIP4, which gives a high-level description of the CITS used. (Values need already; eHealth1, eHealth2, GeoVector, GeoRaster, CITS_SIARD [or should it be just SIARD]).


    Form: “Value”


    “Value” is to be decided by the DILCIS Board. The update is made in the vocabulary and in the extension schema. The value is given to the CITS creator for reference in the creation of the CITS. The list will grow with one value per new CITS.

<h5>
    Way 2</h5>



    We add a new value and includes the version of the CITS in CSIP4, meaning the update of CITS yields a new value.


    Form “Value_v?_?” (Where “v” is for “version” and “?_?” represents the version number)


    “Value” is to be decided by the DILCIS Board. The update is made in the vocabulary and in the extension schema. The value is given to the CITS creator for reference in the creation of the CITS. For each update of a CITS, a new value is added with the correct version to the vocabulary and given to the creator.


    The list will grow with one value per new CITS and then one per update. 

<h5>
    Way 3</h5>



    We have a list in CSIP4 where a high level is given following the proposal in #1. A suggestion of the list: ERMS, SIARD1, SIARD2, SIARDDK, GeoData, _SIARD, RecordsManagement, Archival, eHealth_, MIXED and OTHER. (In italic new values) We add a requirement and attribute where the exact name of the used CITS and its version is given.

The list will grow with one value per new high-level CITS or family of CITS’s (Example Economics as a family of CITS, Research as one where there is a need to be able to state which specification that have been used besides it being present in the submission agreement.). This high-level value is added to the vocabulary and the extension schema. It will be possible to give more than one CITS in this declaration. 


<table>
  <tr>
   <td><strong>CSIP118</strong>
   </td>
   <td><strong>Content Information Type Specification Used</strong>
<p>
<code>mets/@csip:USEDSPECIFICATION</code>
<p>
Used to declare the Content Information Type Specification that has been used for describing the content. The declaration gives the name and version of the used specification.
   </td>
   <td><strong>1..1</strong>
<p>
MUST
   </td>
  </tr>
</table>


<h4>Discussion</h4>


There is a preference in the board for using “Way 3” with the ability of giving a full name and its version number but since the suggestion is to not have a fixed value list instead allowing more flexibility in the use, “Way 2” has been decided to be the one to use. 

During the discussion there were also raised the challenge with how validatable a CITS is. The discussion ended with a decision that a three level validation possibility structure needs to be added. This will yield a new change request.

<h5>The three levels as a first draft description:</h5>




*   A specification is used by many and a request for endorsement is made. The CITS describing the use of the endorsed specification is focused on just how to place the content into a package following CSIP with no additions. Validation is focused upon the package itself.
*   The CITS is describing how to place the content into a package following CSIP with no additions in combination with a description of the format to use for the content. Validation is consisting of two parts, validation of the package itself and validation of the content following the content description.
*   The CITS thoroughly describes both the package with description of all content to be found in the package as well as giving the contents all parts. The validation will validate both the content, the presence of all expected content and the content itself. 

<h4>Result</h4>


The following Action points were agreed:



1. KB will inform about the set up from now on being used regarding the value list for CITS following “Way 2” to E-ARK A2 and A3.
2. KB will implement the description of the change management regarding the values in the value list into the relevant procedures.
3. KB will give the current CITS’s available a value and inform the responsible CITS lead.
4. KB will implement the change in the value list. Observe that it will not be fully implemented until release of the next version of the CSIP.
5. KB will take the description of the validation level structure into a change request for the DILCIS Board to agree upon.

 **Decision of Workplan:**


    KB will implement the action points.

<h2>Notes by:</h2>


Karin Bredenberg, 2021-04-28
