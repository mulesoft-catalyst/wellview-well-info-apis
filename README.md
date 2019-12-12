# wellview-well-info-apis
Peloton's Wellview is a system used in most major Oil & Gas companies for well planning, drilling, completion, testing and workovers. This system is a single comprehensive drilling and well information datastore that reduces duplicate data entry, improves data quality, and creates a collaborative information environment.

O&G executives need the cost information associated with each well operation to determine the profit (or loss) of each project. The cost is often referred to as AFE (Authorization for Expenditure). These AFE information is available in Wellview, but executives needed a mobile application to view these information in near real-time.

Hence a project was commenced to create API-led connectivity into Wellview (which is SQL Server based). A Process and a System APIs were created, and used extensively by the Mobile Application. The same set of APIs can be readily re-used by any other consumers that require the same holistic information on wells.

The APIs are developed in Mule 3. Please feel free to update them to run in Mule 4.
