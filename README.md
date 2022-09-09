# Base-Operations
Technical Assessment

The project assignment contains 8 files. 
* File name ‘BaseOperations.ipynb’ contains the python code for the assignment.  
* The file name ‘BaseOperationsAWS.ipynb’ suggests how the code would run in the AWS cloud. Here it is assumed that the AWS cloud would be used for data engineering and ETL purposes.
* The file ‘Data Warehouse Architecture.png’ contains a data warehouse structure. A similar architecture can be used by BaseOperations. This is just a potential architecture design where assumptions have been made wrt data sources, data crawling to the staging area, and parsing data into different layers. It is assumed that AWS Glue would be used for ETL purposes.
* ‘Sample Unit Test.ipynb’ contains a sample code that can be used for unit testing. The target and source locations have been assumed as Target Folder and Source/Raw Folder. The file ‘Sample Unit Test Report.docx’ contains the report and documentation of the performed unit test. This is just an overview of how the documentation can be done for unit testing.
* ‘test_database’ is the file created when connecting it with SQLite.
* ‘Assessment Presentation.pptx’ is the PowerPoint presentation that talks about the data architecture, a similar ERD, and considerations which need to be taken while solving a real-life problem
* ‘SampleCloudFormationTemplate.yaml’ is a sample script for doing cloud formation on AWS Cloud. Cloud formation can also be done with the help of Troposphere (a python package used for generating the template).
