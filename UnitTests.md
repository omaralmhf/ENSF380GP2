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

## Supply
**testSupplyType**
- Description: setType() updates value; getType() retrieves it.
- Test Value(s): "Water"

**testSupplySetQuantity**
- Description: setQuantity() updates value; getQuantity() retrieves it.
- Test Value(s): 100

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