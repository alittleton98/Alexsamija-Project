# Alexsimija Project

### Machine learning model to test interactions between devices learning separately then teaching each other to understand effectiveness of community based learning. 

_**Etymology: Alexsimija is a portmanteua of "Alexandrian Academy" in Macedonian \(Aleksandriska akademija\). This name was chosen to represent the Library of Alexandria's wealth of information and the cultural accumulation of knowledge within various subjects of the "academy".**_

### Original Developer: Andrew Littleton \(2021\)

DWRL Collaborative 

### Most Recent Documentation Update: 06/15/2021

## Development Specifications:

* [Python 3.9.5](https://www.python.org/downloads/release/python-395/) For ML, and general programming for the experiment
  * SciPy Libraries
* [R](https://www.r-project.org/) For the statistical analysis
  * dplyr
* If desired, the branches can be kept and the experiment can be performed

## Deployment Instructions 

_Applies to DWRL Collaborative Learning Experiment, but can be modified for other projects_

\[Development\]

## Branch Descriptions

My own experiment is included in the repository but will be packaged within its own folders. The Alexsimija Project branches are the ones that will matter when forking. 

### Alexsimija Project

* main: Branch to be forked from or to clone for most stable build
* master: Documentation update. Routinely merged into main
* teacher-dev: Non project specific development branch that the modifiable teaching model will be built in. This is the CONTROL and is meant to be replicated before being experimented on
* student-dev: Non project specific development branch that the modifiable Learnning model will be built in. This is the CONTROL and is meant to be replicated before being experimented on
* database-management: Handles database CRUD and local data files.

### DWRL Collaborative Learning Experiment 

* robert-dev: Development branch Robert. Updates to his learning model for experimentation will be developed here
* rosalind-dev: Development branch Rosalind. Updates to her learning model for experimentation will be developed here
* glados-dev: Development branch GLaDOS. Updates to her teaching practice for experimentation will be developed here
* glados-actual: Experiment branch GLaDOS. Deployed to GLaDOS device and runs experiment from there. Reports to external device.
* robert-actual: Experiment branch Robert. Deployed to Robert device and runs experiment from there. Reports to GLaDOS
* rosalind-actual: Experiment branch Rosalind. Deployed to Rosalind device and runs experiment from there. Reports to GLaDOS



