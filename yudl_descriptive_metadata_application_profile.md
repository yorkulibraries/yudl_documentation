# Descriptive Metadata Application Profile
## York University Digital Library

| MODS                                                                                                               | Example/Notes      |
|--------------------------------------------------------------------------------------------------------------------|--------------------|
| `titleInfo/title`                                                                                                  | Required           |
| `titleInfo/subTitle`                                                                                               |                    |
| `titleInfo/note`                                                                                                   |                    |
| `name[@type]`                                                                                                      | Personal/Corporate |
| `name[@authority]`                                                                                                 |                    |
| `name[@authorityURI]`                                                                                              |                    |
| `name[@valueURI]`                                                                                                   |                    |
| `name/namePart`                                                                                                    |                    |
| `name/namePart[@type="termsOfAddress"]`                                                                            |                    |
| `name/namePart[@type="date"]`                                                                                      |                    |
| `name/affiliation`                                                                                                 |                    |
| `name/role/roleTerm[@authority="marcrelator" and type="text"]`                                                     |                    |
| `typeOfResource`                                                                                                   | Required           |
| `genre`                                                                                                            | Required           |
| `genre[@authority]`                                                                                                |                    |
| `genre[@authorityURI]`                                                                                             |                    |
| `genre[@valueURI]`                                                                                                 |                    |
| `originInfo/dateOther`                                                                                             | Required           |
| `originInfo/dateIssued`                                                                                            |                    |
| `originInfo/publisher`                                                                                             |                    |
| `originInfo/place/placeTerm[@authority="marccountry"]`                                                             |                    |
| `originInfo/place/placeTerm[@type="text"]`                                                                         |                    |
| `language`                                                                                                         | Unbounded          |
| `abstract`                                                                                                         |                    |
| `identifier[@type="hdl"]`                                                                                          |                    |
| `identifier[@type="local"]`                                                                                        | Required           |
| `identifier[@type="other"]`                                                                                        |                    |
| `location/physicalLocation`                                                                                        |                    |
| `location/note[@displayLabel="Location Note"]`                                                                     |                    |
| `physicalDescription/extent`                                                                                       | Required           |
| `physicalDescription/form`                                                                                         | Required           |
| `physicalDescription/form[@authority]`                                                                             |                    |
| `physicalDescription/form[@authorityURI]`                                                                          |                    |
| `physicalDescription/form[@valueURI]`                                                                              |                    |
| `note[not(@*)]`                                                                                                    |                    |
| `note[@type="publications"]`                                                                                       | Unbounded          |
| `note[@type="funding"]`                                                                                            |                    |
| `relatedItem[@type="host"]/titleInfo/title`                                                                        |                    |
| `relatedItem[@type="host"]/identifier[@type='local']`                                                              |                    |
| `relatedItem[@type="host"]/identifier[@type='uri']`                                                                |                    |
| `relatedItem[not(@*)]/titleInfo/title`                                                                             |                    |
| `relatedItem[not(@*)]/location/url[@note="Finding Aid"]`                                                           |                    |
| `subject/topic`                                                                                                    | Unbounded          |
| `subject/geographic`                                                                                               | Unbounded          |
| `subject/temporal`                                                                                                 | Unbounded          |
| `subject/hierarchicalGeographic/continent`                                                                         |                    |
| `subject/hierarchicalGeographic/country`                                                                           |                    |
| `subject/hierarchicalGeographic/province`                                                                          |                    |
| `subject/hierarchicalGeographic/region`                                                                            |                    |
| `subject/hierarchicalGeographic/county`                                                                            |                    |
| `subject/hierarchicalGeographic/city`                                                                              |                    |
| `subject/hierarchicalGeographic/citySection`                                                                       |                    |
| `subject/cartographics/coordinates`                                                                                | Decimal format     |
| `accessCondition[@type="useAndReproduction" and @xlink:href="http://rightsstatements.org/vocab/InC/1.0/"]`         | Select             |
| `accessCondition[@type="useAndReproduction" and @xlink:href="https://creativecommons.org/publicdomain/mark/1.0/"]` | Select             |
| `accessCondition[@type="useAndReproduction"]`                                                                      | Text area          |              

