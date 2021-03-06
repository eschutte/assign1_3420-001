# Use Case 1
## Title: Licence and Vulnerability Information
### Primary Actor:
Manager

### Goal in Context:  
The manager is able to see the licence and vulnerability information provided by the project.

### Stakeholders:  
- Manager: Receives information on the project

- Developer: Reveices information on the project and all policies to be met

- Owner: Understands decisions made by manager and developer based on the software

### Preconditions:
- Package information is stored into the database  

- Proper information plrovided

### Main Succes Scenario:  
Manager receives license and vulnerability
information for the project packages that are requested.

### Failed End Conditions:  
Manager recives inacurate or invalid licence and/or vulnerability information. 

### Trigger:
Manager identifies or uploads project information to which license and
vulnerability information is provided.

# Use Case 2
## Title: Submit Software Package
### Primary Actor:
Developer

### Goal in Context:  
The developer will create a software package that will be sent through License Vulnerability checks and also policy checks, then be sent back to be added to the open sourche software database.

### Stakeholders:  
- Manager: Can overveiw the software package and see information on it.

- Developer: Creates software to add to the OSS Database

### Preconditions:
- It must have software licensing
- Software Package can't have already been created
- Software Package can be fount in the NIST Database for licensing scan

### Main Succes Scenario:  
Developer creates a OSS Package that passes through the NIST vulnerability database and is added to the OSS database

### Failed End Conditions:  
 The software package has no license or isn't found on the NIST database

### Trigger:
Developer submits the software package and it is submitted to the OSS database.

# Use Case 3
## Title: Manager changes policy documents for the OSS policy database
### Primary Actor:
Manager

### Goal in Context:  
The manager wants to change the policy of the document license and vulnerabilities

### Stakeholders:  
- Manager: Reveiws policies set in place and makes changes

### Preconditions:
- Policy is set in place
- Manager dissagrees with the policy and sees need for change

### Main Succes Scenario:  
The Manager changes the policy he thinks needed to be altered and the software package will have less license and vulnerability errors.

### Failed End Conditions:  
- Manager sees nothing wrong with the policies set in place
- There is no policies for the manager to modify

### Trigger:
Manager making changes where they are needed.

