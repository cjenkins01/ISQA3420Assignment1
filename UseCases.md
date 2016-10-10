#Use Case 1

Title:
Add software packages to the OSS Component Datastore

Primary Actor:
Developer

Goal in Context:
Developers can scan software packages for licenses and vulnerabilities. Then they will add the software package to the OSS Component Datastore.

Preconditions:
Vulnerabilities must be in the NIST Vulnerability Datastore, and the Developer must have a Software Package to scan and add.

Main Success Scenario:
The software package is scanned and added to the datastore by the Developer.

Failed End Conditions:
The software package already exists in the datastore. The software does not have any licenses. The software package is not found in the NIST Vulnerability Datastore.

Trigger:
The software package is submitted by the Developer to be scanned for vulnerabilities and licenses.

#Use Case 2
Title:
Add Policy Documents to the OSS Policy Document Datastore

Primary Actor:
Manager

Goal in Context:
Managers can create or edit OSS policy documuments adding them to the OSS Policy Document Datastore.

Preconditions:
Must be an OSS Policy Document.

Main Success Scenario:
The Manager creates or edits a document and submits it to the OSS Policy Document Datastore for later retrieval.

Failed End Conditions:
The Manager tries to create a document that already exists.

Trigger:
The Manager sees a need to create a new policy document or edit an existing one.


#Use Case 3

Title:
Search Datastore for OSS Policy Documents

Primary Actor(s):
Developer and/or Manager

Goal in Context:
Find Policy Documents in the OSS Policy Document Datastore.

Preconditions:
The Manager and/or Developer must have a software package in qhich they are looking for a policy document.

Main Success Scenario:
The Manager and/or Developer submit the request and are returned the policy documentation pertaining to the OSS Package from the OSS Policy Document Datastore.

Failed End Conditions:
The policy document does not exist in the datastore for the package.

Trigger:
The Manager and/or Developer submit a request for a policy document.
