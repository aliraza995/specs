#####Use Case ID: UC-PAS19
#####Use Case Name: Find Locations

**Level:**                     User Level Goal

**Primary Actors:**            Clerk

**Stakeholders:**              Clerk, Patient , Healthcare Providers

**Purpose:**                   The main intent of this use case is to find locations.

**Pre Condition:**             MRC must be identified and authenticated.

**Post Condition:**            Locations found successfully.

**Frequency of Occurrence:**   Low(Occasionally)
__________________________________________________________
**Main Success Scenario: (Find Locations)**

1. Clerk selects find service delivery location option.
2. System asks user to enter filtering criteria such as location metadata (name, zip code, type, status code).
3. Clerk specifies the filtering criteria.
4. System displays the list of service delivery location records.

________________________________________________________________________
**Reference Hl7 V3 Interaction Identifiers (Domain: Patient Administration):**

PRPA_ST202305UV02
_______________________________________________________________
**Reference CCHIT Criteria:**

IP 01.02
________________________________________________________________________
**Reference Hl7 V3 Interaction Identifiers (Domain: Patient Administration):**

PRPA_ST201301UV02
_______________________________________________________________
**Reference CCHIT Criteria:**

AM 01.01, AM 01.02, AM 01.03, AM 01.04, AM 01.05

_______________________________________________________________
**Reference Hl7 RMIM (Domain: Patient Administration):**
[More Details](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=306)

![prpa_rm202306uv query by details](https://f.cloud.github.com/assets/5391320/1295200/0ddde126-30a7-11e3-9856-bb39c787d057.png)
_______________________________________________________________
**Reference FHIR Resource:**
[More Details](http://www.hl7.org/implement/standards/fhir/resourcelist.html)

![location fhir resource](https://f.cloud.github.com/assets/5391320/1295189/b51b8674-30a6-11e3-8883-30c0c9cb1534.png)
_______________________________________________________________
**Reference CDA Template:**
[More Details](http://www.hl7.org/Special/committees/structure/index.cfm)

N/A
_______________________________________________________________
**Reference OpenEHR Archetypes (Version 1.4):**
[More Details](http://www.openehr.org/ckm/)

N/A




