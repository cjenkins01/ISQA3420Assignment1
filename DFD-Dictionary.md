#Data Flow Diagram Dictionary

Developer - User responsible for submitting the software packages to be searched for OSS components that are updated to the database.

Software Package - Software submitted by the Developer to be scanned for OSS licenses and vulnerabilities.

Sofware Package License and Vulnerability Results - The results returned with License and Vulnerability information to the Developer and Manager.

Software Package License Results - The scanned licenses returned from the Scan for Licenses process.

Manager - External user that will query the database to request OSS information.

Package License and Vulnerability Request - Query submitted for information on an OSS packages License and Vulnerability information.

Manage Software Package for License and Vulnerability Scanning - Process that handles the software package sending it to the Scan License process and sends the package's license results to the database and the developer.

Scan for Licenses - Process that actually scans the software for Open Source Software (OSS) licenses and returns any results to the Manage Software Package for License Scanning.

Search Datastore for OSS Package Licenses and Vulnerabilities - Processes that allow the Manager or Developer to search the Datastore for OSS packages' licenses and vulnerabilities.

OSS Component Datastore - Database that stores the software package license information.

NIST Vulnerability Datastore - Database to be searched that contains the known vulnerabilities of OSS packages.

Search Datastore for Policy Documents - Processes that allow the Manager or Developer to search the OSS Policy Datastore for the company policies pertaining to OSS package licenses and vulnerabilies.

OSS Policy Datastore - Database that stores the company's OSS policy documents.

Create or Edit OSS Policy Documents - Process by which the Manager can create a policy document from scratch or edit existing policy documents.
