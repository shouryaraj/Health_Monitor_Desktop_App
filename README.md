<h1 align="center"> HealthMonitor project</h1>

<a name="desc"></a>
## 1. Description

An application that helps health practitioners monitor the vitalsof
their patients. The application need to connect to a FHIR server that stores electronic medical records
(EMRs).

***Features in the App ***
1. Options to select multiple vitals
2. Graph visualisation to monitor vitals
3. Multiple patient monitoring system
4. Dynamice selection of the frequency of refreshing the data
5. Summarised view of the patient details with the vitals
6. Different view if the vital reading is not in normal range.
7. Selection of the normal range for the vital

***UML for the App***
<img src="./DesignDocuments/Second iteration/Design Documents\uml.svg" width="100%">



<a name="usage"></a>
## 2 Instruction to Open the Project:

1) Open the Project using the pom.xml file from top level of the project file.


2) Make sure Java SDK has been added to the file, otherwise check it from the
    project structure, the file option top left hand side. In the Project 
    structure choose project.
    
3) If Driver class dosen't show the running option then choose Module from the
    project structure and select the 'src' as sources.

Setup of the Machine Learning program:

1) Installation of the of required modules.
   * pip install -r requirements.txt  for the python2
   * pip3 install -r requirements.txt for the python3
   or
   * python -m pip install -r requirements.txt

2) Two data set are available that are fetched from the server, both of the files don't have NULL position.

3) Running the MLDrive from the java project(src/MachineLearning) generate the data sets that are fetched from the server.

4) Result of the accuracy would show at the console.

