# Descriptive Metadata Application Profile

| XPath      |`titleInfo/title` |
|------------|------------------|
| Form label | Title            |
| Field type | Text field       |
| Help text  | <p>If you are a Bib Services student enter: [to be supplied] unless otherwise directed.</p> <p>If you are an Archives/Bib Services staff member, transcribe the title proper if available. Otherwise, create a supplied title based on the content of the object being described, and make note of this below.</p> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_title_s` |
| Display label | Title         |
| Note          |               |

| XPath      | `titleInfo/subTitle` |
|------------|----------------------|
| Form label | Sub-Title |
| Field type | Text area       |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_subTitle_s` |
| Display label | |
| Note | |

| XPath      | `titleInfo/note`  |
|------------|-|
| Form label | Title Note |
| Field type | Text field       | 
| Help text  | If this title is a supplied title, enter "Title based on content of [image, file, assignment]." If this title is a direct transcription of the original title, i.e. it is a title proper, leave this field blank. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_titleInfo_note_s` |
| Display label | |
| Note | |

| XPath      | `name` |
|------------|-|
| Form label | Name |
| Field type | Tabs       |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@type]` |
|------------|-|
| Form label | Type |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Personal, Corporate |

| XPath      | `name[@authority]`   |
|------------|-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Source of authorized version of name, for example: <strong>viaf</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@authorityURI]` |
|------------|-|
| Form label | Authority URI |
| Field type | Text field |
| Help text  | <p>URI of authority listing, for example: <strong>http://viaf.org</strong></p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name[@valueURI]` |
|------------|-|
| Form label | Value URI |
| Field type | Text field |
| Help text  | <p>Unique URI for authority record, for example: <strong>http://viaf.org/viaf/29543057</strong></p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart` |
|------------|-|
| Form label | Name |
| Field type | Text field |
| Help text  | <p>If known, list name of creator/contributor here using last name, first name format, drawing on standard or authorized versions where available. For more information, see FAQ.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart[@type="termsOfAddress"]` |
|------------|-|
| Form label | Terms of Address |
| Field type | Text field |
| Help text  | Title and/or enumeration associated with a name, such as Jr., II, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/namePart[@type="date"]` |
|------------|-|
| Form label | Role |
| Field type | Text field |
| Help text  | <p>Date(s) associated with a name. This could be a person's birth and death dates, or the years of existence of an organization or administrative department. For more info, see FAQ.</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | ``name/affiliation` |
|------------|-|
| Form label | Affiliation |
| Field type | Text field |
| Help text  | An organization associated this person at the time that the resource was created. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `name/role/roleTerm[@authority="marcrelator" and type="text"]` |
|------------|-|
| Form label | Role |
| Field type | Text field |
| Help text  | Select a role from <a  href="http://id.loc.gov/vocabulary/relators.html"  target="_blank">the MARC Code List for Relators</a>. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `typeOfResource` |
|------------|-|
| Form label | Type of Resource |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre` |
|------------|-|
| Form label | Genre |
| Field type | Field set, text field |
| Help text  | Chose the most appropriate genre heading for the item being described. Example: <strong>Personal correspondence</strong> |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@authority]` |
|------------|-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Select the genre source code from which you derived your term from this <a href="https://www.loc.gov/standards/sourcelist/genre-form.html" target="_blank">this</a>. Example: <strong>lcgft</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@authorityURI]` |
|------------|-|
| Form label | Authority URI |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/authorities/genreForms |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `genre[@valueURI]` |
|------------|-|
| Form label | Value URI |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/authorities/genreForms/gf2014026141 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo` |
|------------|-|
| Form label | Origin Information |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/dateOther` |
|------------|-|
| Form label | Date Issued (free text) |
| Field type | Text field |
| Help text  | Write out the date associated with this object without punctuation in the following format (including full month): <strong>22 October 1939</strong>. Sometimes the information is incomplete or estimated, in which case, use what information you have, using the conventions outlined in RAD Rule 1.4.B5. For examples, see the FAQ. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/dateIssued` |
|------------|-|
| Form label | Date Issued (iso) |
| Field type | Text field |
| Help text  | Enter the date in the format YYYY-MM-DD if known. For incomplete or estimated dates, see the FAQ for direction. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/publisher` |
|------------|-|
| Form label | Publisher |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/place/placeTerm[@authority="marccountry"]` |
|------------|-|
| Form label | Country |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `originInfo/place/placeTerm[@type="text"]` |
|------------|-|
| Form label | Place |
| Field type | Text field |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `language` |
|------------|-|
| Form label | Language |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `language/languageTerm[@authority="iso639-2b" @type="code"]` |
|------------|-|
| Form label | Language |
| Field type | Tags |
| Help text  | Select a three letter iso639-2b language code from <a href="http://www.loc.gov/standards/iso639-2/php/code_list.php" target=_blank>this</a> list. Use <strong>zxx</strong> if there is no linguistic content. |
| Obligation | Required (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `abstract` |
|------------|-|
| Form label | Description |
| Field type | Text area |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | `mods_abstract_s` |
| Display label | |
| Note | |

| XPath      | `identifier[@type="hdl"]` |
|------------|-|
| Form label | Identifier (hdl) |
| Field type | Text field |
| Help text  | If handle exists, add it. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `identifier[@type="local"]` |
|------------|-|
| Form label | Identifier (local) |
| Field type | Text field |
| Help text  | ASC Number, call number, or other local YUL identifier |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `identifier[@type="other"]` |
|------------|-|
| Form label | Identifier (other) |
| Field type | Text field |
| Help text  | Any creator's descriptive system - example for negative assignments from the Computing and Network Services, Instructional Technology Centre they used assignments like: ITC assignment 85-946 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `location` |
|------------|-|
| Form label | Location |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `location/physicalLocation` |
|------------|-|
| Form label | Box number |
| Field type | Text field |
| Help text  | The number of the box and file that contains the object. Note that there is a space before and after the "/".
Example: 2007-054 / 025 (17) |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `location/note[@displayLabel="Location Note"]` |
|------------|-|
| Form label | Location Note |
| Field type | Text field |
| Help text  | Any additional information relevant for the purposes of location, for example: </strong>Envelope 1 of 3</strong>. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription` |
|------------|-|
| Form label | Physical Description |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/extent` |
|------------|-|
| Form label | Extent |
| Field type | Text field |
| Help text  | Provide a descriptive statement regarding the physical extent of the object being described, following the conventions established in RAD 1.5B. See FAQ for examples based on format. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form` |
|------------|-|
| Form label | Form |
| Field type | Field set, Text field |
| Help text  | Provide a designation of the particular physical presentation of the resource being described, focused on physical form or medium of material used to create a resource. |
| Obligation | Required (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@authority]` |
|------------|-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Select the form source code from which you derived your term from this <a href="https://www.loc.gov/standards/sourcelist/genre-form.html" target="_blank">this</a>. Example: <strong>gmgpc</strong> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@authorityURI]` |
|------------|-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Example: http://id.loc.gov/vocabulary/graphicMaterials |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `physicalDescription/form[@valueURI]` |
|------------|-|
| Form label | Authority |
| Field type | Text field |
| Help text  | Example:http://id.loc.gov/vocabulary/graphicMaterials/tgm004700 |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |



| XPath      | `note[not(@*)]` |
|------------|-|
| Form label | Note |
| Field type | Text area |
| Help text  | Include any general notes that do not fit into any other field. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `note[@type="publications"]` |
|------------|-|
| Form label | Publication |
| Field type | Tag |
| Help text  | If known, enter the full citation for the date(s) the object was originally published, following the Chicago Manual of Style. If the object has been published in subsequent years, in other publications, films, articles or monographs, enter additional citations. |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `note[@type="funding"]` |
|------------|-|
| Form label | Funding |
| Field type | Text area |
| Help text  | Make note of any funding or sponsorship involved in the digitization, migration or preservation of this object. For stock phrases, see FAQ. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]`|
|------------|-|
| Form label | Relation |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/titleInfo/title` |
|------------|-|
| Form label | Title |
| Field type | Text field |
| Help text  | If this object is part of a larger body of records that has been digitized, i.e. there is a contact sheet of images related to a specific file, note the Proper Title of that object here. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/identifier[@type='local']` |
|------------|-|
| Form label | ASC Number |
| Field type | Text field |
| Help text  | If this object is part of a larger body of records that has been digitized, i.e. there is a contact sheet of images related to a specific file, note the ASC number of that object here. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[@type="host"]/identifier[@type='uri']` |
|------------|-|
| Form label | URI |
| Field type | Text field |
| Help text  | Enter URI for contact sheet, i.e. https://digital.library.yorku.ca/islandora/object/yul:372340</p> |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]` |
|------------|-|
| Form label | Relation |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]/titleInfo/title` |
|------------|-|
| Form label | Title |
| Field type | Text field |
| Help text  | Collection/fonds title |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `relatedItem[not(@*)]/location/url[@note="Finding Aid"]` |
|------------|-|
| Form label | uri |
| Field type | Select |
| Help text  | Select the Collection/fonds number. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject` |
|------------|-|
| Form label | Subject |
| Field type | Field set |
| Help text  | |
| Obligation | |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/topic` |
|------------|-|
| Form label | Topic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/geographic` |
|------------|-|
| Form label | Geographic |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/temporal` |
|------------|-|
| Form label | Temporal |
| Field type | Tag |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: n) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/continent` |
|------------|-|
| Form label | Continent |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/country` |
|------------|-|
| Form label | Country |
| Field type | Text field |
| Help text  | Name of a country, i.e. a political entity considered a country. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/province` |
|------------|-|
| Form label | Province |
| Field type | Text field |
| Help text  | Includes first order political divisions called provinces within a country, e.g. in Canada. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/region` |
|------------|-|
| Form label | Region |
| Field type | Text field |
| Help text  | Includes regions that have status as a jurisdiction, usually incorporating more than one first level jurisdiction. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/county` |
|------------|-|
| Form label | County |
| Field type | Text field |
| Help text  | Name of the largest local administrative unit in various countries, e.g. England. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/city` |
|------------|-|
| Form label | City |
| Field type | Text field |
| Help text  | Name of an inhabited place incorporated as a city, town, etc. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/hierarchicalGeographic/citySection` |
|------------|-|
| Form label | City Section |
| Field type | Text field |
| Help text  | Name of a smaller unit within a populated place, e.g., neighborhoods, parks, or streets. |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `subject/cartographics/coordinates` |
|------------|-|
| Form label | Coordinates |
| Field type | Text field |
| Help text  | Please put coordinates in decimal format: 43.653333, -79.383889
<br/><br/><strong>DO NOT</strong> use degree format 43°39′12″N 079°23′02″W |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="http://rightsstatements.org/vocab/InC/1.0/"]` |
|------------|-|
| Form label | In copyright |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction" and @xlink:href="https://creativecommons.org/publicdomain/mark/1.0/"]` |
|------------|-|
| Form label | Public Domain |
| Field type | Select |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | Yes/No |

| XPath      | `accessCondition[@type="useAndReproduction"]` |
|------------|-|
| Form label | Rights statement |
| Field type | Text area |
| Help text  | |
| Obligation | Optional (Minimal: 0, Maximum: 1) |
| Solr field | |
| Display label | |
| Note | |
