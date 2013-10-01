#####Use Case ID: UC-PAS17
#####Use Case Name: Nullify Location

**Level:**                     User Level Goal

**Primary Actors:**            Medical Record Clerk(MRC)

**Stakeholders:**              Medical Record Clerk(MRC), Patient , Healthcare Providers

**Purpose:**                   The main intent of this use case is to nullify service delivery locations.

**Pre Condition:**             MRC must be identified and authenticated.

**Post Condition:**            Service Delivery locations will be nullified successfully.

**Frequency of Occurrence:**   Low(Occasionally)
__________________________________________________________
**Main Success Scenario: (Add Person to Person Registry)**

1. MRC requests system to nullify a service delivery location record.
2. System displays a list of service delivery location records.
3. MRC specifies the service delivery location record “entered in error”.
4. System nullifies the service delivery location record.

_______________________________________________________________________________
**Alternate Flows** 

**Alt-1:**

1. Invalid information cannot be added.
2. Specified parent does not exist.
3. Invalid relationship.

________________________________________________________________________
**Reference Hl7 V3 Interaction Identifiers (Domain: Patient Administration):**

PRPA_ST202303UV02
_______________________________________________________________
**Reference CCHIT Criteria:**

N/A



