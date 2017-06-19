# Descriptive Metadata Application Profile

| XPath      | `titleInfo/title` |
|------------|:------------------|
| Form label | Title            |
| Field type | Text field       |
| Help text  | <p>If you are a Bib Services student enter: [to be supplied] unless otherwise directed.</p> <p>If you are an Archives/Bib Services staff member, transcribe the title proper if available. Otherwise, create a supplied title based on the content of the object being described, and make note of this below.</p> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_title_s` |
| Display label | Title         |
| Note          |               |

| XPath      | `titleInfo/subTitle` |
|------------|:----------------------|
| Form label | Sub-Title |
| Field type | Text area       |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_subTitle_s` |
| Display label | |
| Note | |

| XPath      | `titleInfo/note`  |
|------------|:-|
| Form label | Title Note |
| Field type | Text field       | 
| Help text  | If this title is a supplied title, enter "Title based on content of [image, file, assignment]." If this title is a direct transcription of the original title, i.e. it is a title proper, leave this field blank. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_note_s` |
| Display label | |
| Note | |

| XPath      | `name` |
|------------|:-|
| Form label | Name |
| Field type | Tabs       |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@type]` |
|------------|:-|
| Form label | Type |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Personal, Corporate |

| XPath      | `name[@authority]`   |
|------------|:-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Source of authorized version of name, for example: <strong>viaf</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@authorityURI]` |
|------------|:-|
| Form label | Authority URI |
| Field type | Text field |
| Help text  | <p>URI of authority listing, for example: <strong>http://viaf.org</strong></p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@valueURI]` |
|------------|:-|
| Form label | Value URI |
| Field type | Text field |
| Help text  | <p>Unique URI for authority record, for example: <strong>http://viaf.org/viaf/29543057</strong></p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart` |
|------------|:-|
| Form label | Name |
| Field type | Text field |
| Help text  | <p>If known, list name of creator/contributor here using last name, first name format, drawing on standard or authorized versions where available. For more information, see FAQ.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart[@type="termsOfAddress"]` |
|------------|:-|
| Form label | Terms of Address |
| Field type | Text field |
| Help text  | Title and/or enumeration associated with a name, such as Jr., II, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart[@type="date"]` |
|------------|:-|
| Form label | Role |
| Field type | Text field |
| Help text  | <p>Date(s) associated with a name. This could be a person's birth and death dates, or the years of existence of an organization or administrative department. For more info, see FAQ.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/affiliation` |
|------------|:-|
| Form label | Affiliation |
| Field type | Text field |
| Help text  | An organization associated this person at the time that the resource was created. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/role/roleTerm[@authority="marcrelator" and type="text"]` |
|------------|:-|
| Form label | Role |
| Field type | Text field |
| Help text  | Select a role from <a  href="http://id.loc.gov/vocabulary/relators.html"  target="_blank">the MARC Code List for Relators</a>. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `typeOfResource` |
|------------|:-|
| Form label | Type of Resource |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre` |
|------------|:-|
| Form label | Genre |
| Field type | Field set, text field |
| Help text  | Chose the most appropriate genre heading for the item being described. Example: <strong>Personal correspondence</strong> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@authority]` |
|------------|:-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Select the genre source code from which you derived your term from this <a href="https://www.loc.gov/standards/sourcelist/genre-form.html" target="_blank">this</a>. Example: <strong>lcgft</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@authorityURI]` |
|------------|:-|
| Form label | Authority URI |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/authorities/genreForms |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@valueURI]` |
|------------|:-|
| Form label | Value URI |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/authorities/genreForms/gf2014026141 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo` |
|------------|:-|
| Form label | Origin Information |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/dateOther` |
|------------|:-|
| Form label | Date Issued (free text) |
| Field type | Text field |
| Help text  | Write out the date associated with this object without punctuation in the following format (including full month): <strong>22 October 1939</strong>. Sometimes the information is incomplete or estimated, in which case, use what information you have, using the conventions outlined in RAD Rule 1.4.B5. For examples, see the FAQ. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/dateIssued` |
|------------|:-|
| Form label | Date Issued (iso) |
| Field type | Text field |
| Help text  | Enter the date in the format YYYY-MM-DD if known. For incomplete or estimated dates, see the FAQ for direction. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/publisher` |
|------------|:-|
| Form label | Publisher |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/place/placeTerm[@authority="marccountry"]` |
|------------|:-|
| Form label | Country |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/place/placeTerm[@type="text"]` |
|------------|:-|
| Form label | Place |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `language` |
|------------|:-|
| Form label | Language |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `language/languageTerm[@authority="iso639-2b" @type="code"]` |
|------------|:-|
| Form label | Language |
| Field type | Tags |
| Help text  | Select a three letter iso639-2b language code from <a href="http://www.loc.gov/standards/iso639-2/php/code_list.php" target=_blank>this</a> list. Use <strong>zxx</strong> if there is no linguistic content. |
| Obligation | Required (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `abstract` |
|------------|:-|
| Form label | Description |
| Field type | Text area |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_abstract_s` |
| Display label | Description |
| Note | |

| XPath      | `identifier[@type="hdl"]` |
|------------|:-|
| Form label | Identifier (hdl) |
| Field type | Text field |
| Help text  | If handle exists, add it. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | mods_identifier_hdl_s |
| Display label | Identifier (hdl): |
| Note | |

| XPath      | `identifier[@type="local"]` |
|------------|:-|
| Form label | Identifier (local) |
| Field type | Text field |
| Help text  | ASC Number, call number, or other local YUL identifier |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | mods_identifier_local_s |
| Display label | Identifier (local): |
| Note | |

| XPath      | `identifier[@type="other"]` |
|------------|:-|
| Form label | Identifier (other) |
| Field type | Text field |
| Help text  | Any creator's descriptive system - example for negative assignments from the Computing and Network Services, Instructional Technology Centre they used assignments like: ITC assignment 85-946 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | mods_identifier_other_s |
| Display label | Identifier (other): |
| Note | |

| XPath      | `location` |
|------------|:-|
| Form label | Location |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `location/physicalLocation` |
|------------|:-|
| Form label | Box number |
| Field type | Text field |
| Help text  | The number of the box and file that contains the object. Note that there is a space before and after the "/". Example: 2007-054 / 025 (17) |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `location/note[@displayLabel="Location Note"]` |
|------------|:-|
| Form label | Location Note |
| Field type | Text field |
| Help text  | Any additional information relevant for the purposes of location, for example: </strong>Envelope 1 of 3</strong>. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription` |
|------------|:-|
| Form label | Physical Description |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/extent` |
|------------|:-|
| Form label | Extent |
| Field type | Text field |
| Help text  | Provide a descriptive statement regarding the physical extent of the object being described, following the conventions established in RAD 1.5B. See FAQ for examples based on format. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form` |
|------------|:-|
| Form label | Form |
| Field type | Field set, Text field |
| Help text  | Provide a designation of the particular physical presentation of the resource being described, focused on physical form or medium of material used to create a resource. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@authority]` |
|------------|:-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Select the form source code from which you derived your term from this <a href="https://www.loc.gov/standards/sourcelist/genre-form.html" target="_blank">this</a>. Example: <strong>gmgpc</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@authorityURI]` |
|------------|:-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/vocabulary/graphicMaterials |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@valueURI]` |
|------------|:-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Example:http://id.loc.gov/vocabulary/graphicMaterials/tgm004700 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |



| XPath      | `note[not(@*)]` |
|------------|:-|
| Form label | Note |
| Field type | Text area |
| Help text  | Include any general notes that do not fit into any other field. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `note[@type="publications"]` |
|------------|:-|
| Form label | Publication |
| Field type | Tag |
| Help text  | If known, enter the full citation for the date(s) the object was originally published, following the Chicago Manual of Style. If the object has been published in subsequent years, in other publications, films, articles or monographs, enter additional citations. |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `note[@type="funding"]` |
|------------|:-|
| Form label | Funding |
| Field type | Text area |
| Help text  | Make note of any funding or sponsorship involved in the digitization, migration or preservation of this object. For stock phrases, see FAQ. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]`|
|------------|:-|
| Form label | Relation |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/titleInfo/title` |
|------------|:-|
| Form label | Title |
| Field type | Text field |
| Help text  | If this object is part of a larger body of records that has been digitized, i.e. there is a contact sheet of images related to a specific file, note the Proper Title of that object here. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/identifier[@type='local']` |
|------------|:-|
| Form label | ASC Number |
| Field type | Text field |
| Help text  | If this object is part of a larger body of records that has been digitized, i.e. there is a contact sheet of images related to a specific file, note the ASC number of that object here. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/identifier[@type='uri']` |
|------------|:-|
| Form label | URI |
| Field type | Text field |
| Help text  | Enter URI for contact sheet, i.e. https://digital.library.yorku.ca/islandora/object/yul:372340</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]` |
|------------|:-|
| Form label | Relation |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]/titleInfo/title` |
|------------|:-|
| Form label | Title |
| Field type | Text field |
| Help text  | Collection/fonds title |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]/location/url[@note="Finding Aid"]` |
|------------|:-|
| Form label | uri |
| Field type | Select |
| Help text  | Select the Collection/fonds number. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject` |
|------------|:-|
| Form label | Subject |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/topic` |
|------------|:-|
| Form label | Topic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/geographic` |
|------------|:-|
| Form label | Geographic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/temporal` |
|------------|:-|
| Form label | Temporal |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/continent` |
|------------|:-|
| Form label | Continent |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/country` |
|------------|:-|
| Form label | Country |
| Field type | Text field |
| Help text  | Name of a country, i.e. a political entity considered a country. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/province` |
|------------|:-|
| Form label | Province |
| Field type | Text field |
| Help text  | Includes first order political divisions called provinces within a country, e.g. in Canada. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/region` |
|------------|:-|
| Form label | Region |
| Field type | Text field |
| Help text  | Includes regions that have status as a jurisdiction, usually incorporating more than one first level jurisdiction. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/county` |
|------------|:-|
| Form label | County |
| Field type | Text field |
| Help text  | Name of the largest local administrative unit in various countries, e.g. England. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/city` |
|------------|:-|
| Form label | City |
| Field type | Text field |
| Help text  | Name of an inhabited place incorporated as a city, town, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/citySection` |
|------------|:-|
| Form label | City Section |
| Field type | Text field |
| Help text  | Name of a smaller unit within a populated place, e.g., neighborhoods, parks, or streets. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/cartographics/coordinates` |
|------------|:-|
| Form label | Coordinates |
| Field type | Text field |
| Help text  | Please put coordinates in decimal format: 43.653333, -79.383889<br/><br/><strong>DO NOT</strong> use degree format 43°39′12″N 079°23′02″W |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="http://rightsstatements.org/vocab/InC/1.0/"]` |
|------------|:-|
| Form label | In copyright |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="https://creativecommons.org/publicdomain/mark/1.0/"]` |
|------------|:-|
| Form label | Public Domain |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction"]` |
|------------|:-|
| Form label | Rights statement |
| Field type | Text area |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

## Toronto Telegram Negatives Descriptive Metadata Application Profile

| XPath      | `identifier[@type='local']` |
|------------|:------------------|
| Form label | ASC Number        |
| Field type | Text field      |
| Help text  | Example: ASC29001 |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | mods_identifier_local_s |
| Display label | Identifier (local):  |
| Note          |               |

| XPath      | `location` |
|------------|:------------------|
| Form label | Location          |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `location/physicalLocation` |
|------------|:------------------|
| Form label | Box number        |
| Field type | Text field      |
| Help text  | <p>The number of the box that contains your negative envelope. Note that there is a space before and after the "/".</p><p><strong>Example:</strong> 1974-002 / 095</p> |
| Obligation | Required (Minimal: 0, Maximum: 1)  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `location/note[@displayLabel="Location Note"]` |
|------------|:------------------|
| Form label | Identifier Other  |
| Field type | Text field        |
| Help text  | <p>Occasionally with significant events, the Telegram will have multiple envelopes. In this case, note which envelope this is.</p> <strong>Example:</strong> Envelope 1 of 3.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]` |
|------------|:------------------|
| Form label |             |
| Field type | Field set   |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]/title` |
|------------|:------------------|
| Form label | Title            |
| Field type | Text area   |
| Help text  | For PDF, always use the title written on the envelope that contains the negative. Use a space colon space to separate information as it appears on the envelope. If there is a NOT USED or COPY stamped on your envelope, enter [not used] or [copy] in square brackets one space after your title. i.e. Colonial Tavern : Renovation : Waitress Contest [copy] <br/><br /> For TIF, if you are a Bib Services student enter: [to be supplied] <br /><br /> For TIF, if you are an Archives/Bib Services staff member create a title based on the content of the TIF image file. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]/note` |
|------------|:------------------|
| Form label | Title note            |
| Field type | Text field      |
| Help text  | If this title is a supplied title, enter "Title based on content of [image, file, assignment]." If this title is a direct transcription of the original title, i.e. it is a title proper, leave this field blank. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `abstract` |
|------------|:------------------|
| Form label | Description       |
| Field type | Text area      |
| Help text  | <p>For PDF, describe the contents of the assignment envelope, including any loose sheets of photographer instructions, the number of contact sheets and the assignment envelope's title, i.e. "File consists of front and back of negative envelope, front and back of loose sheet, and five contact sheets. Assignment: Dirty Shames : Singing Group."</p> <p>For TIF, if you are a Bib Services student do not enter any information.</p> <p>For TIF, if you are an Archives/Bib Services staff member, and have additional details to add in terms of the quality of the image (under exposed/over exposed), the state of the image (suffering from severe vinegar syndrome, smudged by finger print) or additional contextual information, please note it here.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | mods_abstract_s |
| Display label | Description  |
| Note          |              |

| XPath      | `name` |
|------------|:------------------|
| Form label | Name            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]` |
|------------|:------------------|
| Form label |             |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]/namePart` |
|------------|:------------------|
| Form label | Name            |
| Field type | Text field      |
| Help text  | Enter the name of the photographer on the assignment envelope, referring to the Toronto Telegram photographers listing. If there is no name on the assignment envelope, enter: <strong>[Telegram staff]</strong> using the square brackets. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]/roleTerm[@authority="marcrelator"]` |
|------------|:------------------|
| Form label |             |
| Field type | Text field      |
| Help text  | |
| Obligation | "Photographer" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `name[@type="corporate"]` |
|------------|:------------------|
| Form label |             |
| Field type |       |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden               |

| XPath      | `name[@type="corporate"]/namePart` |
|------------|:------------------|
| Form label | Name            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `name[@type="corporate"]/roleTerm[@authority="marcrelator"]` |
|------------|:------------------|
| Form label | Role            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Publisher" |
| Solr field |  |
| Display label |          |
| Note          | Hidden   |

| XPath      | `originInfo` |
|------------|:------------------|
| Form label | Origin Information |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateOther` |
|------------|:------------------|
| Form label | Date taken (free text)            |
| Field type | Text field      |
| Help text  | <p>Date the photographer wrote on the assignment envelope, likely on the back. Write this date without punctuation in the following format (including full month): 18 January 1967.</p> <p>Sometimes the information is incomplete, in which case, use the date information on the front of the envelope, to supplement the information you have, using square brackets. For more examples, see the <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>.</p> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateCreated` |
|------------|:------------------|
| Form label | Date taken (iso)            |
| Field type | Text field       |
| Help text  | This is the date the negative was used. This is stamped on the front of the envelope, near the title. Use the format YYYY-MM-DD (i.e. 1967-01-18). If the envelope is stamped "NOT USED" this field should not be entered. For more examples, see the <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateIssued` |
|------------|:------------------|
| Form label | Date published (iso) |
| Field type | Text field      |
| Help text  | This is the date the negative was used. This is stamped on the front of the envelope, near the title. Use the format YYYY-MM-DD (i.e. 1967-01-18). If there is a "NOT USED" or "COPY" stamp on the fron of the envelope, enter only the year and month that was handwritten on the back of the enveloped, i.e. 1967-01. For more examples, see the <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>. |
| Obligation | Required (Minimal: 0, Maximum: 1)  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/publisher` |
|------------|:------------------|
| Form label | Publisher            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `originInfo/place[1]/placeTerm` |
|------------|:------------------|
| Form label | Country            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Canada" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `originInfo/place[2]/placeTerm` |
|------------|:------------------|
| Form label | Place            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto" |
| Solr field |  |
| Display label |          |
| Note          | Hidden               |

| XPath      | `typeOfResource` |
|------------|:------------------|
| Form label | Type of Resource            |
| Field type | Text field      |
| Help text  | |
| Obligation | "still image" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `genre[@authority="bgtchm"]` |
|------------|:------------------|
| Form label | Genre            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Photographs" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `language/languageTerm` |
|------------|:------------------|
| Form label | Language            |
| Field type | Text field      |
| Help text  | |
| Obligation | "eng" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `note[not(@*)]` |
|------------|:------------------|
| Form label | Note            |
| Field type | Text field      |
| Help text  | This is a generic note field where you can add additional information pertinent to the item being described that does not logically fit into the existing schema. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription` |
|------------|:------------------|
| Form label | Physical Description            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription/form[@authority="marcsmd"]` |
|------------|:------------------|
| Form label | Form            |
| Field type | Text field       |
| Help text  | |
| Obligation | "photonegative" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `physicalDescription/extent` |
|------------|:------------------|
| Form label | Format            |
| Field type | Text field      |
| Help text  | <p><strong>For PDF</strong>- describe the assignment envelope using the following format: ## photographs : b&w negative ; #.# x #.# cm + 1 envelope : 14.2 x 11 cm</p> <p><strong>For TIF</strong>- describe the item using the following format: 1 photograph: b&w negative ; ##.# x ##.# cm. The one exception is when you're scanning 35 mm film, describe as 1 photograph : b&w negative ; 35 mm.</p> <p>For more examples, see <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription/note[@type="organization"]` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Text field |
| Help text  | <p><strong>If PDF</strong>, leave blank.</p> <p><strong>If TIF</strong>, enter the number (if visible) on the film strip negative. Count the total number of negatives in the assignment (do not rely on what is written on the envelope) and write in the following format One neg (#) scanned out of ## in assignment. (i.e. One neg (5-5A) scanned out of 30 in assignment. For more examples, see <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `note[@type="publications"]` |
|------------|:-|
| Form label | Publication |
| Field type | Tag |
| Help text  | If known, enter the full citation for the date(s) the image was published in the Telegram, following the Chicago Manual of Style. i.e. First Name Last Name (of reporter), "Article Title," The Toronto Telegram, Month dd, yyyy, edition, Section page number. If image has been published in subsequent years, in other publications, films, exhibits, articles or monographs, enter additional citations. |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/titleInfo` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/titleInfo/title` |
|------------|:------------------|
| Form label | Title            |
| Field type | Text field      |
| Help text  | <p>Title proper of the assignment envelope.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/identifier[@type='local']` |
|------------|:------------------|
| Form label | ASC Number            |
| Field type | Text field      |
| Help text  | <p>ASC number of assignment envelope.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/identifier[@type='uri']` |
|------------|:------------------|
| Form label | Parent URI            |
| Field type | Text field      |
| Help text  | <p><strong>If TIF</strong>, enter URI for PDF assignment envelope, i.e. https://digital.library.yorku.ca/islandora/object/yul:372340</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/titleInfo` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/titleInfo/title` |
|------------|:------------------|
| Form label | Title (Finding aid) |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram fonds, F0433" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/location` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden |

| XPath      | `relatedItem/location/url[@note="Finding Aid"]` |
|------------|:------------------|
| Form label | url (Finding aid) |
| Field type | Text field       |
| Help text  | |
| Obligation | "http://archivesfa.library.yorku.ca/fonds/ON00370-f0000433.htm" |
| Solr field |  |
| Display label |          |
| Note          | Hidden |

| XPath      | `subject` |
|------------|:-|
| Form label | Subject |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/topic` |
|------------|:-|
| Form label | Topic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/continent` |
|------------|:-|
| Form label | Continent |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/country` |
|------------|:-|
| Form label | Country |
| Field type | Text field |
| Help text  | Name of a country, i.e. a political entity considered a country. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/province` |
|------------|:-|
| Form label | Province |
| Field type | Text field |
| Help text  | Includes first order political divisions within a country, i.e. provinces in Canada, states in USA. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/region` |
|------------|:-|
| Form label | Region |
| Field type | Text field |
| Help text  | Includes regions that have status as a jurisdiction, usually incorporating more than one first level jurisdiction. i.e. York Region includes both the city of Markham and the city of Vaughan. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/county` |
|------------|:-|
| Form label | County |
| Field type | Text field |
| Help text  | Name of the largest local administrative unit, i.e. Dufferin County. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/city` |
|------------|:-|
| Form label | City |
| Field type | Text field |
| Help text  | Name of an inhabited place incorporated as a city, town, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/citySection` |
|------------|:-|
| Form label | City Section |
| Field type | Text field |
| Help text  | Name of a smaller unit within a populated place, e.g., neighbourhoods, parks, or streets. See <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a> for more details. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/cartographics/coordinates` |
|------------|:-|
| Form label | Coordinates |
| Field type | Text field |
| Help text  | <p>Please put coordinates in decimal format: 43.653333, -79.383889<strong>DO NOT</strong>use degree format 43°39′12″N 079°23′02″W</p> <p>See <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a> for more details.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction"]` |
|------------|:-|
| Form label | Useage rights |
| Field type | Select |
| Help text  | Select from the drop down list. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="http://rightsstatements.org/vocab/InC/1.0/"]` |
|------------|:-|
| Form label | In copyright? |
| Field type | Select |
| Help text  | Select from the drop down list. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="https://creativecommons.org/publicdomain/mark/1.0/"]` |
|------------|:-|
| Form label | Public Domain |
| Field type | Select |
| Help text  | Select from the drop down list.|
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

## Toronto Telegram Prints Descriptive Metadata Application Profile

| XPath      | `identifier[@type='local']` |
|------------|:------------------|
| Form label | ASC Number        |
| Field type | Text field      |
| Help text  | Example: ASC29001 |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | mods_identifier_local_s |
| Display label | Identifier (local):  |
| Note          |               |

| XPath      | `location` |
|------------|:------------------|
| Form label | Location          |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `location/physicalLocation` |
|------------|:------------------|
| Form label | Box number        |
| Field type | Text field      |
| Help text  | <p>The number of the box and file that contains the print. Note that there is a space before and after the "/".</p> <p><strong>Example:</strong> 1974-002 / 590</p> |
| Obligation | Required (Minimal: 0, Maximum: 1)  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `location/note[@displayLabel="Location Note"]` |
|------------|:------------------|
| Form label | Identifier Other  |
| Field type | Text field        |
| Help text  | <p>Occasionally there will be multiple folders of the same topic. In this case, note which folder this is.</p> <p><strong>Example:</strong> Folder 2 of 2.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]` |
|------------|:------------------|
| Form label |             |
| Field type | Field set   |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]/title` |
|------------|:------------------|
| Form label | Title            |
| Field type | Text area   |
| Help text  | <p>If you are a Bib Services student enter: [to be supplied]</p> <p>If you are an Archives/Bib Services staff member create a title based on the content of the photograph, incorporating any annotations on the reverse of the print, prioritizing captions or clippings pasted in from the printed issue of the Telegram.</p> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `titleInfo[not(@*)]/note` |
|------------|:------------------|
| Form label | Title note            |
| Field type | Text field      |
| Help text  | If this title is a supplied title, enter "Title based on content of [image, file, assignment]." If this title is a direct transcription of the original title, i.e. it is a title proper, leave this field blank. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `abstract` |
|------------|:------------------|
| Form label | Description       |
| Field type | Text area      |
| Help text  | <p>If you are an Archives/Bib Services staff member, and have additional details to add in terms of the quality of the image, manipulation techniques or additional contextual information, please note it here.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | mods_abstract_s |
| Display label | Description  |
| Note          |              |

| XPath      | `name` |
|------------|:------------------|
| Form label | Name            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]` |
|------------|:------------------|
| Form label |             |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]/namePart` |
|------------|:------------------|
| Form label | Name            |
| Field type | Text field      |
| Help text  | Enter the name of the photographer if their name is stamped or written on the verso of the print, referring to the Toronto Telegram photographers listing. If there is no name visible, enter <strong>[Telegram staff]</strong> using square brackets. If this is a reproduction print from a wire service, enter the full authority name, referring to the Wire Service Companies listing. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `name[@type="personal"]/roleTerm[@authority="marcrelator"]` |
|------------|:------------------|
| Form label |             |
| Field type | Text field      |
| Help text  | |
| Obligation | "Photographer" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `name[@type="corporate"]` |
|------------|:------------------|
| Form label |             |
| Field type |       |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden               |

| XPath      | `name[@type="corporate"]/namePart` |
|------------|:------------------|
| Form label | Name            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `name[@type="corporate"]/roleTerm[@authority="marcrelator"]` |
|------------|:------------------|
| Form label | Role            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Publisher" |
| Solr field |  |
| Display label |          |
| Note          | Hidden   |

| XPath      | `originInfo` |
|------------|:------------------|
| Form label | Origin Information |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateOther` |
|------------|:------------------|
| Form label | Date taken (free text)            |
| Field type | Text field      |
| Help text  | <p>Date the photographer wrote on the assignment envelope, likely on the back. Write this date without punctuation in the following format (including full month): 18 January 1967.</p> <p>Sometimes the information is incomplete, in which case, use the date information on the front of the envelope, to supplement the information you have, using square brackets. For more examples, see the <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>.</p> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateCreated` |
|------------|:------------------|
| Form label | Date taken (iso)            |
| Field type | Text field       |
| Help text  | This is the date the photograph was taken. Potentially stamped on the verso of the print, or noted in the caption information. Write this date in the following format YYYY-MM-DD (i.e. 1945-01-18). For more examples see the <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a>. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/dateIssued` |
|------------|:------------------|
| Form label | Date published (iso) |
| Field type | Text field      |
| Help text  | This is the date the print was first published in the Telegram. Likely stamped on the verso of the print. |
| Obligation | Required (Minimal: 0, Maximum: 1)  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `originInfo/publisher` |
|------------|:------------------|
| Form label | Publisher            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `originInfo/place[1]/placeTerm` |
|------------|:------------------|
| Form label | Country            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Canada" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `originInfo/place[2]/placeTerm` |
|------------|:------------------|
| Form label | Place            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto" |
| Solr field |  |
| Display label |          |
| Note          | Hidden               |

| XPath      | `typeOfResource` |
|------------|:------------------|
| Form label | Type of Resource            |
| Field type | Text field      |
| Help text  | |
| Obligation | "still image" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `genre[@authority="bgtchm"]` |
|------------|:------------------|
| Form label | Genre            |
| Field type | Text field      |
| Help text  | |
| Obligation | "Photographs" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `language/languageTerm` |
|------------|:------------------|
| Form label | Language            |
| Field type | Text field      |
| Help text  | |
| Obligation | "eng" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `note[not(@*)]` |
|------------|:------------------|
| Form label | Note            |
| Field type | Text field      |
| Help text  | This is a generic note field where you can add additional information pertinent to the item being described that does not logically fit into the existing schema. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription` |
|------------|:------------------|
| Form label | Physical Description            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription/form[@authority="marcsmd"]` |
|------------|:------------------|
| Form label | Form            |
| Field type | Text field       |
| Help text  | |
| Obligation | "photoprint" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `physicalDescription/extent` |
|------------|:------------------|
| Form label | Format            |
| Field type | Text field      |
| Help text  | Describe the item using the following format: 1 photograph : b&w print ; ##.# x ##.# cm |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `physicalDescription/note[@type="organization"]` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Text field |
| Help text  | 1 print scanned out of folder. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `note[@type="publications"]` |
|------------|:-|
| Form label | Publication |
| Field type | Tag |
| Help text  | If known, enter the full citation for the date(s) the image was published in the Telegram, following the Chicago Manual of Style. i.e. First Name Last Name (of reporter), "Article Title," The Toronto Telegram, Month dd, yyyy, edition, Section page number. If image has been published in subsequent years, in other publications, films, exhibits, articles or monographs, enter additional citations. |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="otherVersion"]` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="otherVersion"]/identifier[@type='uri']` |
|------------|:------------------|
| Form label | Negative URI            |
| Field type | Text field      |
| Help text  | If this print has a corresponding negative that has been digitized, please enter the full uri here. For example, for <a href="https://digital.library.yorku.ca/yul-100417/hurricanes-hazel-1954-no-3-folder">ASC05571</a>, <strong>https://digital.library.yorku.ca/yul-100404/hurricane-hazel-flame-thrower-humber</strong> would be entered. |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/titleInfo` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem[@type="host"]/titleInfo/title` |
|------------|:------------------|
| Form label | Title            |
| Field type | Text field      |
| Help text  | <p>Title proper of the file folder, as listed in the Telegram finding aid.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |


| XPath      | `relatedItem[@type="host"]/identifier[@type='uri']` |
|------------|:------------------|
| Form label | Parent URI            |
| Field type | Text field      |
| Help text  | <p>Enter URI for Toronto Telegram file level uri in finding aid, if it exists (rarely used).</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field |  |
| Display label |          |
| Note          |               |

| XPath      | `relatedItem` |
|------------|:------------------|
| Form label | Relation            |
| Field type | Field set      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/titleInfo` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/titleInfo/title` |
|------------|:------------------|
| Form label | Title (Finding aid) |
| Field type | Text field      |
| Help text  | |
| Obligation | "Toronto Telegram fonds, F0433" |
| Solr field |  |
| Display label |          |
| Note          | Hidden              |

| XPath      | `relatedItem/location` |
|------------|:------------------|
| Form label |             |
| Field type | markup      |
| Help text  | |
| Obligation |  |
| Solr field |  |
| Display label |          |
| Note          | Hidden |

| XPath      | `relatedItem/location/url[@note="Finding Aid"]` |
|------------|:------------------|
| Form label | url (Finding aid) |
| Field type | Text field       |
| Help text  | |
| Obligation | "http://archivesfa.library.yorku.ca/fonds/ON00370-f0000433.htm" |
| Solr field |  |
| Display label |          |
| Note          | Hidden |

| XPath      | `subject` |
|------------|:-|
| Form label | Subject |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/topic` |
|------------|:-|
| Form label | Topic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/continent` |
|------------|:-|
| Form label | Continent |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/country` |
|------------|:-|
| Form label | Country |
| Field type | Text field |
| Help text  | Name of a country, i.e. a political entity considered a country. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/province` |
|------------|:-|
| Form label | Province |
| Field type | Text field |
| Help text  | Includes first order political divisions within a country, i.e. provinces in Canada, states in USA. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/region` |
|------------|:-|
| Form label | Region |
| Field type | Text field |
| Help text  | Includes regions that have status as a jurisdiction, usually incorporating more than one first level jurisdiction. i.e. York Region includes both the city of Markham and the city of Vaughan. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/county` |
|------------|:-|
| Form label | County |
| Field type | Text field |
| Help text  | Name of the largest local administrative unit, i.e. Dufferin County. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/city` |
|------------|:-|
| Form label | City |
| Field type | Text field |
| Help text  | Name of an inhabited place incorporated as a city, town, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/citySection` |
|------------|:-|
| Form label | City Section |
| Field type | Text field |
| Help text  | Name of a smaller unit within a populated place, e.g., neighbourhoods, parks, or streets. See <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a> for more details. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/cartographics/coordinates` |
|------------|:-|
| Form label | Coordinates |
| Field type | Text field |
| Help text  | <p>Please put coordinates in decimal format: 43.653333, -79.383889</p><p><strong>DO NOT</strong> use degree format 43°39′12″N 079°23′02″W</p> <p>See <a href="https://digital.library.yorku.ca/content/toronto-telegram-faq" target="_blank">Toronto Telegram FAQ</a> for more details.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction"]` |
|------------|:-|
| Form label | Useage rights |
| Field type | Select |
| Help text  | Select from the drop down list. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="http://rightsstatements.org/vocab/InC/1.0/"]` |
|------------|:-|
| Form label | In copyright? |
| Field type | Select |
| Help text  | Select from the drop down list. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="https://creativecommons.org/publicdomain/mark/1.0/"]` |
|------------|:-|
| Form label | Public Domain |
| Field type | Select |
| Help text  | Select from the drop down list.|
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |
