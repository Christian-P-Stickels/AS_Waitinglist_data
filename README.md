# AS_Waitinglist_data

AS_Waiting_list_clearance_and_mortality_app Executable

1. Prerequisites for Deployment 

Verify that version 9.10 (R2021a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2021a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-AS_Waiting_list_clearance_and_mortality_app.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

4. USER INFOMATION

This app is to provide an estimation at smaller scales only and relies on
the assumptions of the model it was built upon. Please read the paper that 
this app was distributed with before running it so that you understand these 
assumptions and limitations. 

The results produced are always an estimate based on assumptions and we do not 
claim that these are the results that you will see in different situations. 
Instead, app results should be used for the basis of a discussion on how to 
improve the clinical situation by giuving estimates for scenarios that may happen. 
We do not allow the adjustment of mortality estimates in-app, if you believe that 
mortality estimates are wrong, we invite you to write your own code or email the 
author to ask for the code that we used.
