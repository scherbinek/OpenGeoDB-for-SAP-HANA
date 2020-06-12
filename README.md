# OpenGeoDB-for-SAP-HANA

SAP HANA tables and models for the Open Source project OpenGeoDB (http://opengeodb.giswiki.org/wiki/OpenGeoDB).

You can download the repository and import the content of the zip file as package to SAP HANA. Please assign the provided role to your user to select/insert from the schema.

The data (SQL) can be found at http://opengeodb.giswiki.org/wiki/OpenGeoDB_Downloads 

After importing and assigning the role you can modify (e.g. by Notepad++) the downloaded SQL statements as with

At the beginning of the SQL
SET SCHEMA OPENGEODB

Replace the SQLfiles by the prefix 'OpenGeoDB.catalog::'
Search for:   INTO geodb
Replace with: INTO OpenGeoDB.catalog::geodb
