# OpenGeoDB-for-SAP-HANA

SAP HANA tables and models for the Open Source project OpenGeoDB (http://opengeodb.giswiki.org/wiki/OpenGeoDB). <br>

You can download the repository and import the content of the zip file as package to SAP HANA. Please assign the provided role to your user to select/insert from the schema. <br>

The data (SQL) can be found at http://opengeodb.giswiki.org/wiki/OpenGeoDB_Downloads <br>

After importing and assigning the role you can modify (e.g. by Notepad++) the downloaded SQL statements as with <br>

At the beginning of the SQL <br>
SET SCHEMA OPENGEODB <br>

Replace the SQLfiles by the prefix 'OpenGeoDB.catalog::' <br>
Search for:   INTO geodb <br>
Replace with: INTO "OpenGeoDB.catalog::geodb <br>

Search for:    VALUES
Replace with: " VALUES
