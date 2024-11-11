# JMP Test Data

The files found under this directory are taken from the data files included in this project.  The 
following process is used for testing.

***Note:*** The JMP addon script (JSL) was modified to output the visual elements data to CSV files. 
These files are the output files included with this test data. 

1. Build a JMP test environment that includes the files found in this GitHub repo. 
2. Run each one of the selected input CSV files through a test process as follows. 
   3. BASE - Default JMP addin settings. 
   4. DIFF - Add the differential/slope calculations. 
   5. SHAP - Select the SHAP output option (which runs the included python notebook)
6.  Capture the CSV output data for each of the tests.

