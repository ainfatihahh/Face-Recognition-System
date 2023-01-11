# Project Overview

# A.PLANNING THE PROJECT


### **Project Management Life Cycle**
In project management, Work Breakdown Structure (WBS) is a very important tool 
because it provides the basis for deciding how to do the work. The WBS also provides a basis 
for creating the project schedule and performing earned value management for measuring and 
forecasting project performance.


The project management life cycle is represented and documented in the form of Gantt Chart which
allows staff to follow the guidelines and achieved the milestone from time to time. The project
life cycle WBS breakdown the task and work of every members such as project manager into several modules. Every member have their own roles and part in every stage of the lifecyle based on the constructed WBS.
.In the Gantt chart, the processes included are initiating 
process, planning process, executing process, monitoring and controlling process, and lastly 
closing process.

Project Management WBS's is shown in the table below:
![wbs](https://user-images.githubusercontent.com/121369021/211588932-dfd26309-8883-4d53-a8a6-9cf32ce1a6f7.png)

As for the Face Recognition Project, the system WBS are represented as follow. This WBS is constructured to breakdown the technical part of the project into several modules such as Face Detection, Face Recognition, interface design and API management:

![GAMBAR](https://user-images.githubusercontent.com/121369021/211601484-75baf904-121c-4246-bd56-0af0f6d7d5cd.png)

### **Project Scope Statement**

The scope involved in Face Recognition System is divided into two 
parts namely module specification and user specification as follows:

a) Detection and Recognition
<br><br>
This module is built to detect and track people from cameras. User may see 
people who are left behind in a vehicle. The system will use is OpenCV 
and Haarcascade algorithm.

b) People Information
<br><br>
This system will detect people and offer information such as attendance about 
their name, face, time, and date.


### **Risk Identification Chart (Quality,Cost,Time)**
| CONTROL ELEMENT | ISSUE | SITUATION | DISCLOSURE |
| ---         |     ---      |          --- |          --- | 
|  *QUALITY* <br> ((Poor attitude toward quality; substandard design, materials, and workmanship; inadequate quality assurance program))   | 1.	Inadequate Quality Assurance Program: Facial Recognition systems can be impacted by poor lighting or low image quality. The data may not match up with the person’s nodal points because of camera angles being obscured; this creates an error when matching faceprints cannot be verified in the database. <br> <br> 2.	 Inadequate Quality Assurance Program: The relative angle of the target's face has a significant impact on the recognition score. Usually, several angles are employed when enrolling a face in the facial recognition software (profile, frontal and 45-degree are common). Anything less than a frontal view affects the algorithm’s capability to generate a template for the face. The more direct the image and the higher its resolution, the higher the score of any resulting matches.| How: The output result tends to unrecognize or wrongly recognized people faces. <br> <br> When: The quality problem of will be determined during the unit testing phase | Assign one member to purchase a good quality camera and get a good lighting tools so that the outcome will be satisfied. |
| *COST* <br>  (Estimating errors; inadequate productivity, cost, change, or contingency) |<br> 1. Contigency: If one of the team members damages the camera or lighting equipment, the cost of the items will go up. <br> <br>2. Inadequate productivity: Team members who were impacted by COVID-19 and were unable to deliver what they were expected to deliver, which resulted in additional costs, need to be budgeted for the same equipment.      | How: The monthly bills shows unexpected extra charged to the bills. <br> <br> When: The problem most probably will be encountered during the project execution and project implementation. | Notify the owner through email or discord whenever budget exceed threshold in the AWS cloud computing service.  |
| *TIME* <br> (Errors in estimating time or resource availability; errors in determining the critical path; poor allocation and management of float; early release of competitive products)     |  1. Project not able to reach the milestone set as described in the Gantt Chart.<br> <br> 2. Erros in estimating resource availability: There are not enough server to be used to run the face recognition model training | How: The members are stuck with a certain problem and drag all the other team members <br> <br> When: The problem will be encountered during the project excution and monitoring phase.  |  Ask support from the other team member and switch their task or job to other job to avoid him/her to stuck in the problem loop.   |

### **Roles and Responsibility**

This section defines the various roles and responsibilities of the project team members.
This project has 15 titlesincluding Project Manager. The summary of the title, roles and
responsibilities are given in the table below

| ROLES | PERSON IN CHARGE | RESPONSIBILITY |
| ---  |     ---      |    --- | 
|  **Project Manager**  |AIN FATIHAH AIMAN BINTI MOHD YUSSUF| The Project Manager is accountable to the Project Director for all the project office management related activities. In addition to assisting in the creation of the master project schedule and all other project work plans, the project manager prepares, directs, and monitors the daily internal activities that support the project office. Face Recognition Project's project manager will need to determine who we can approach with our idea and who is most likely to accept it. The project manager must also verify that all initiation and planning documentation, including the Gantt chart and Work Breakdown Structure (WBS), are created in a complete and understandable manner. <br><br> The development, upkeep, and adherence to the Project Office infrastructure and supporting methodology (such as processes, procedures, standards, and templates) that are in accordance with OSI Best Practices and policies are the responsibility of the Project Manager. The Face Recognition Project must continue to be watched after to ensure that its progress complies with its requirements and scope. If a problem arises, the project manager must work on a solution.|
|  **Procurement Manager** | NOR AILY BINTI ROZALI  | The RFP or RFO and other solicitation documents are created under the direction and management of the procurement manager. The procurement manager is in charge of integrating all the parts, guaranteeing consistency and continuity throughout the whole procurement process, and adhering to procurement standards, rules, and regulations. Other departments of the project office may be given responsibility for particular sections. This involves coordinating contract negotiations, planning and monitoring the procurement calendar, supervising the production of the RFP or RFO, and managing the review of proposals and offers as well as vendor selection. <br> <br>  The project's contract, rules, and timelines must be discussed with each member by the procurement manager. Additionally, the procurement manager must make sure that no employee uses corporate funds to purchase any linked items. The procurement manager must approve all expenses.|
|  **Risk Manager**   | NURUL HANIM BINTI ABDUL HALIM@HALIM | The project's risk management and tracking responsibilities fall under the purview of the risk manager. In order to ensure that prime contractor risk management initiatives do not negatively affect the project, the risk manager also keeps an eye on them. The project's risk manager oversees risk identification sessions, monitors prime contractor risk management efforts, and takes part in division-level risk management activities for risks that cross project boundaries or are outside the scope of the project. The risk manager also manages and tracks potential and active risks, maintains the risk management tool and documentation information. <br> <br> Every risk associated with this project must be listed. For instance, the team must do the collection of multiple input images for feature extraction from an image for the face recognition project. If the team is obliged to shoot images on a street where cars are driving very quickly, this session could be deadly. As a result, the team will discuss potential solutions to this challenge. <br> <br>  Unexpected issues could arise at any stage of this project. Therefore, the risk management must record every danger so that they can avoid it and take precautions to ensure that specific issue won't arise.|
|  **Administrative Manager**   | NURUL HANIM BINTI ABDUL HALIM@HALIM |  |
|  **Financial Analyst** | NOR AILY BINTI ROZALI  | |
|  **Project Scheduler**  |AIN FATIHAH AIMAN BINTI MOHD YUSSUF| |
|  **Quality Manager**  |AIN FATIHAH AIMAN BINTI MOHD YUSSUF| |
|  **Stakeholder Coordinator** | NOR AILY BINTI ROZALI  | |
|  **Technical Manager**   | NURUL HANIM BINTI ABDUL HALIM@HALIM |  |
|  **Implemetation Manager** | NOR AILY BINTI ROZALI  | |
|  **Test Manager** | NOR AILY BINTI ROZALI  | |
|  **Operations Manager**  |AIN FATIHAH AIMAN BINTI MOHD YUSSUF| |
|  **Customer Support Manager**   | NURUL HANIM BINTI ABDUL HALIM@HALIM |  |
|  **Executive Steering Committee** | NOR AILY BINTI ROZALI  | |
|  **Office of Technology Services (OTech) Representative**  |AIN FATIHAH AIMAN BINTI MOHD YUSSUF| |






