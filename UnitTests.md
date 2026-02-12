## Inquirer
**testInquirerFirstName**
- Description: getFirstName() returns the firstName from constructor.
- Test Value(s): "John"

**testInquirerLastName**
- Description: getLastName() returns the lastName from constructor.
- Test Value(s): "Smith"

**testInquirerPhone**
- Description: getServicesPhoneNum() returns the phone from constructor.
- Test Value(s): "403-555-0123"

**testInquirerInfo**
- Description: getInfo() returns the info from constructor.
- Test Value(s): "Searching for family"

**testInquirerInvalidFirstName**
- Description: Constructor rejects null firstName
- Test Value(s): null

**testInquirerInvalidLastName**
- Description: Constructor rejects null lastName
- Test Value(s): null

**testInquirerInvalidInfo**
- Description: Constructor rejects null info
- Test Value(s): null

**testInquirerInvalidNumber**
- Description: Constructor rejects null servicesPhone
- Test Value(s): null


## Supply
**testSupplyType**
- Description: setType() updates value; getType() retrieves it.
- Test Value(s): "Water"

**testSupplySetQuantity**
- Description: setQuantity() updates value; getQuantity() retrieves it.
- Test Value(s): 100

**testSupplyInvalidQuantity**
- Description: Constructor and setQuantity() reject null or negative quantity
- Test Value(s): -1, null

**testSupplyInvalidType**
- Description: Constructor setType() reject null type
- Test Value(s): null


## DisasterVictim
**testVictimSetFirstName**
- Description: setFirstName() updates value; getFirstName() retrieves it.
- Test Value(s): "Jane"

**testVictimSetLastName**
- Description: setLastName() updates value; getLastName() retrieves it.
- Test Value(s): "Doe"

**testVictimDateOfBirth**
- Description: setDateOfBirth() updates value; getDateOfBirth() retrieves it.
- Test Value(s): 1990-01-01

**testVictimSetFamilyConnections**
- Description: setFamilyConnections() updates value; getFamilyConnections() retrieves it.
- Test Value(s): Array of FamilyRelation objects

**testVictimSetMedicalRecords**
- Description: setMedicalRecords() updates value; getMedicalRecords() retrieves it.
- Test Value(s): Array of MedicalRecord objects

**testVictimSetPersonalBelongings**
- Description: setPersonalBelongings() updates value; getPersonalBelongings() retrieves it.
- Test Value(s): Array of Supply objects

**testVictimGender**
- Description: setGender() updates value; getGender() retrieves it.
- Test Value(s): "female"

**testVictimComments**
- Description: setComments() updates value; getComments() retrieves it.
- Test Value(s): "Allergic to nuts"

**testVictimEntryDate**
- Description: getEntryDate() returns the date from constructor.
- Test Value(s): 2024-02-11

**testVictimInvalidFirstName**
- Description: setFirstName() rejects invalid first names.
- Test Value(s): null

**testVictimInvalidLastName**
- Description: setLastName() rejects invalid last names.
- Test Value(s): null

**testVictimInvalidGender**
- Description: setGender() rejects invalid gender values.
- Test Value(s): null, 3

**testVictimInvalidComments**
- Description: setComments() rejects invalid comments input.
- Test Value(s): null

**testVictimInvalidDateOfBirth**
- Description: setDateOfBirth() rejects invalid DOB values.
- Test Value(s): 2100-01-01

**testVictimInvalidFamilyConnections**
- Description: setFamilyConnections() rejects invalid inputs.
- Test Value(s): null, contains null element(s)

**testVictimInvalidMedicalRecords**
- Description: setMedicalRecords() rejects invalid inputs.
- Test Value(s): null, contains null element(s)

**testVictimInvalidPersonalBelongings**
- Description: setPersonalBelongings() rejects invalid inputs.
- Test Value(s): null, contains null element(s)

**testVictimPersonalBelongingAddRemoveInvalidInputs**
- Description: addPersonalBelonging()/removePersonalBelonging() reject invalid inputs.
- Test Value(s): null

**testVictimAddPersonalBelonging**
- Description: addPersonalBelonging() adds item to list.
- Test Value(s): Supply("Water", 1)

**testVictimRemovePersonalBelonging**
- Description: removePersonalBelonging() removes item from list and does nothing if belonging is not in list.
- Test Value(s): Supply("Water", 1)

**testVictimFamilyConnectionAddRemoveInvalidInputs**
- Description: addFamilyConnection()/removeFamilyConnection() reject invalid inputs.
- Test Value(s): null

**testVictimAddFamilyConnection**
- Description: addFamilyConnection() adds relation to list.
- Test Value(s): FamilyRelation(victimA, "Sibling", victimB)

**testVictimRemoveFamilyConnection**
- Description: removeFamilyConnection() removes relation from list and does nothing if relation is not in list.
- Test Value(s): FamilyRelation(victimA, "Sibling", victimB)

**testVictimMedicalRecordAddRemoveInvalidInputs**
- Description: addMedicalRecord()/removeMedicalRecord() reject invalid inputs.
- Test Value(s): null

**testVictimAddMedicalRecord**
- Description: addMedicalRecord() adds record to list.
- Test Value(s): MedicalRecord(location, "Checkup", 2024-02-10)

**testVictimRemoveMedicalRecord**
- Description: removeMedicalRecord() removes record from list and does nothing if record is not in list.
- Test Value(s): MedicalRecord(location, "Checkup", 2024-02-10)


## Location
**testLocationName**
- Description: setName() updates value; getName() retrieves it.
- Test Value(s): "Shelter 1"

**testLocationAddress**
- Description: setAddress() updates value; getAddress() retrieves it.
- Test Value(s): "123 Main St"

**testLocationSetOccupants**
- Description: setOccupants() updates value; getOccupants() retrieves it.
- Test Value(s): Array of DisasterVictim objects

**testLocationSetSupplies**
- Description: setSupplies() updates value; getSupplies() retrieves it.
- Test Value(s): Array of Supply objects

**testLocationInvalidName**
- Description: setName() rejects invalid names.
- Test Value(s): null

**testLocationInvalidAddress**
- Description: setAddress() rejects invalid addresses.
- Test Value(s): null

**testLocationInvalidOccupants**
- Description: setOccupants() rejects invalid inputs.
- Test Value(s): null, contains null element(s)

**testLocationInvalidSupplies**
- Description: setSupplies() rejects invalid inputs.
- Test Value(s): null, contains null element(s)

**testLocationOccupantAddRemoveInvalidInputs**
- Description: addOccupant()/removeOccupant() reject invalid inputs.
- Test Value(s): null

**testLocationAddOccupant**
- Description: addOccupant() adds victim to occupants list.
- Test Value(s): DisasterVictim("John", 2024-02-10)

**testLocationRemoveOccupant**
- Description: removeOccupant() removes victim from occupants list and does nothing if victim is not in list.
- Test Value(s): DisasterVictim("John", 2024-02-10)

**testLocationSupplyAddRemoveInvalidInputs**
- Description: addSupply()/removeSupply() reject invalid inputs.
- Test Value(s): null

**testLocationAddSupply**
- Description: addSupply() adds supply to inventory list.
- Test Value(s): Supply("Water", 10)

**testLocationRemoveSupply**
- Description: removeSupply() removes supply from inventory list and does nothing if supply is not in list.
- Test Value(s): Supply("Water", 10)


## MedicalRecord
**testMedicalTreatmentDetails**
- Description: setTreatmentDetails() updates value; getTreatmentDetails() retrieves it.
- Test Value(s): "Standard checkup"

**testMedicalDateOfTreatment**
- Description: setDateOfTreatment() updates value; getDateOfTreatment() retrieves it.
- Test Value(s): 2024-02-10

**testMedicalRecordSetLocation**
- Description: setLocation() updates value; getLocation() retrieves it.
- Test Value(s): Location("Shelter A", "123 Main St")

**testMedicalRecordInvalidTreatmentDetails**
- Description: setTreatmentDetails() rejects invalid treatment details.
- Test Value(s): null

**testMedicalRecordInvalidDateOfTreatment**
- Description: setDateOfTreatment() rejects invalid treatment dates.
- Test Value(s): 2100-01-01

**testMedicalRecordInvalidLocation**
- Description: setLocation() rejects invalid location.
- Test Value(s): null


## FamilyRelation
**testRelationRelationshipTo**
- Description: setRelationshipTo() updates value; getRelationshipTo() retrieves it.
- Test Value(s): "Sibling"

**testFamilyRelationSetPersonOne**
- Description: setPersonOne() updates value; getPersonOne() retrieves it.
- Test Value(s): DisasterVictim("John", 2024-02-10)

**testFamilyRelationSetPersonTwo**
- Description: setPersonTwo() updates value; getPersonTwo() retrieves it.
- Test Value(s): DisasterVictim("Jane", 2024-02-10)

**testFamilyRelationInvalidRelationshipTo**
- Description: setRelationshipTo() rejects invalid relationship values.
- Test Value(s): null

**testFamilyRelationInvalidPeople**
- Description: setPersonOne()/setPersonTwo() reject invalid people.
- Test Value(s): null, same victim for both sides


## ReliefService
**testReliefInfoProvided**
- Description: setInfoProvided() updates value; getInfoProvided() retrieves it.
- Test Value(s): "Provided shelter"

**testReliefDateOfInquiry**
- Description: setDateOfInquiry() updates value; getDateOfInquiry() retrieves it.
- Test Value(s): 2024-02-11

**testReliefServiceSetInquirer**
- Description: setInquirer() updates value; getInquirer() retrieves it.
- Test Value(s): Inquirer("John", "Doe", "403-555-0100", "Looking for family")

**testReliefServiceSetMissingPerson**
- Description: setMissingPerson() updates value; getMissingPerson() retrieves it.
- Test Value(s): DisasterVictim("Jane", 2024-02-10)

**testReliefServiceSetLastKnownLocation**
- Description: setLastKnownLocation() updates value; getLastKnownLocation() retrieves it.
- Test Value(s): Location("Shelter B", "456 Oak St")

**testReliefServiceInvalidInfoProvided**
- Description: setInfoProvided() rejects invalid info values.
- Test Value(s): null

**testReliefServiceInvalidDateOfInquiry**
- Description: setDateOfInquiry() rejects invalid inquiry dates.
- Test Value(s): 2100-01-01

**testReliefServiceInvalidInquirer**
- Description: setInquirer() rejects invalid inquirer references.
- Test Value(s): null

**testReliefServiceInvalidMissingPerson**
- Description: setMissingPerson() rejects invalid missing person references.
- Test Value(s): null

**testReliefServiceInvalidLastKnownLocation**
- Description: setLastKnownLocation() rejects invalid location references.
- Test Value(s): null

**testReliefServiceGetLogDetails**
- Description: getLogDetails() returns a meaningful summary containing inquirer and missing person information.
- Test Value(s): Valid ReliefService instance
