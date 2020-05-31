# Information System Development Methodologies - Assessment 1

## Defining the Problem
### Objectives
* Calls can be specified to RMs and improve call routing and dynamic call flow control
* Aid RMs in serving their end-customers (or potential customers)
* Match RMs and end-customers according to RMs skills and customers profiles
* Direct in bound customers to an Interactive Voice Response unit prompting them for options, and reasons for calling in a few words
* Redirect the call to an Automatic Call Distributor routing the call to the first available appropriate RM
* Improve out-bound system processes

#### Problem Statement:
The travel company wants to improve the operation of their in-house Call Management Center (CMC) by implementing a system which will help adjust the call flow rate to suitable Relationship Managers(RM). During busy times, customers are directed towards a voice repsonse system where they are required to wait before being connected to Relationship Managers (RM). As a result, potential and valued customers are disconnected from the call and are required to wait. This leads to a negative outcome, with customers being dissatisfied with the service, by not receiving the relevant information about a suitable travel package. Ultimately, the needs of our users are not being met from this current system.  

#### Empathy Map

##### Commercial Customer 

![alt text](https://github.com/RhysandLy/ISDM---Group-4/blob/thivya-98-patch-1/Images/Empathy%20Map%20photo.PNG "Commercial Customer Empathy Map")

##### Business Customer

![alt text](https://github.com/RhysandLy/ISDM---Group-4/blob/Rhys/Images/Empathy%20Map%20Business%20Customers%20-%20rhys.PNG "Business Customer Empathy Map")

##### Relationship Managers
![alt text](https://github.com/RhysandLy/ISDM---Group-4/blob/Daisy/Images/Empathy%20Map%20(Relationship%20Managers).png "Relationship Manager Empathy Map")

##### Potential Customers
![alt text](https://github.com/Bilal13396989/ISDM---Group-4/blob/master/Empath%20Map%20Potential%20Customer%20ISDM.png "Potential Customer Empathy Map")

### Stakeholders
* Customers
    * Calling Business
    * Commercial (travelling for leisure)
    * Customers for recruitment (Potential Customers)
* Relationship Managers (RM)    

## Approach
### How Might We (HMW) Statements
#### Business Customers
* HMW filter through travel packages for business Customers?
* HMW give Business Customers the right packages for them?
* HMW match Business Customers to RMs?
#### Commercial Customers
* HMW give Commercial Customers the right packages for them?
* HMW match Commercial Customers to RMs?
#### Customers for recruitment
* HMW advertise to new customers to use our services?
#### Relationship Managers (RM)
* HMW match RMs to callers that support thier skills and knowledge of specific travel packages?
* HMW quantify RM's skills?
* HMW find the right travel package for the required needs?

### Design Thinking Approach and Ideation Reflection
The call management centre (CMC) needs a new and improved system to assist in routing calls in an automated way, and during times of high call traffic. Our team has brainstormed ideas for efficiently routing calls with the new system. Changing from a manual system to an automated one, the system can use intelligent call routing. The customer first uses the customer profiler tool to create an account before they can call the Travel company and be matched with a Relationship Manager, the customer will then be given a unique ID that they will use to be matched with a Relationship Manager. 

When a user calls the company they are prompted by an automated message that asks for a unique ID, which is then linked to their profile in the system database and matched with a Relationship Manager that will deal with their call. If a user does not have an ID, they will be directed to an Interactive Voice Response unit prompting them questions about their reason for calling (business or leisure) and very basic information, including name, age, preferred language. From their they will be put on hold and then matched to an available corresponding Relationship Manager.

For out-bound calls from Relationship Managers, employees are given set times to carry out these calls. When they need to do out-bound calls, the system displays a target list of users that have not called the company, and relevant information to help perform a sale. The system generates a generic script and guide to help the Relationship manager.

In times of high traffic calling, customers will still be met with automated message asking for customer ID however they are not instantly routed to a Relationship Managers, they will be put on hold until a Relationship manager is free.

Our team wanted to prioritise efficiency and speed with the new system. In consideration of the customers, we believe customers do not want to spend long amounts of time waiting on hold, to be met with a Relationship manager that is not suited to their needs. The use of the automated intelligent call routing system creates a much more efficient calling environment. When considering the Relationship Managers, the customer profiler tool allows the Relationship Managers skills to be used to their full potential, by being matched with customers that they can relate to, Relationship Managers want to make as many sales as they can utilizing their skills. Rather than being general, our team decided to go with a more specialized approach for call routing.


## Agile Methodology
### Scrum

Our team utilised the Agile methodology in developing this project. Weekly scrum meetings were held, where we reviewed the work that had been done and identified and assigned the work that had yet to be done. Aligning with the scrum team model, our team was self sufficient and all work processes were organised by us, instead of an external force. By using tools including Github, Draw.io, Google Docs and Google Slides, we were able to collaborate efficiently and track progress using version control. ‘Commits’ were made by each team member in constantly merging their current work with the ‘master’ version. This also enabled constant feedback from each team member that could be incorporated to improve each iteration, and ensured high productivity and strong cooperation. To overcome the challenge of a lack of face-to-face meetings, we used Facebook Messenger and Zoom as our main forms of communication, which met our needs adequately. We nominated a Scrum Master, Rhys, who facilitated Scrum and communication between the Product Owner and Development Team. We used Github Project Boards and Issues to list a Sprint Backlog we followed and used to prioritise activities in, as shown below:

![Project Board](https://github.com/RhysandLy/ISDM---Group-4/blob/Daisy/Images/Project%20Board.png)

![Issues](https://github.com/RhysandLy/ISDM---Group-4/blob/Daisy/Images/Issues.png)

Issues were opened and closed as progress was made. We also developed a Product Backlog of user stories as shown in Work Products and Models.

While we developed several iterations of work models, this project was relatively short in time and did not include any testing or coding, and so only one sprint was conducted. A sprint review was conducted on 29/05/2020, where a meeting with the Product Owner was held and feedback given after an examination of the completed work. A sprint retrospective was conducted on 31/05/2020, where we identified areas where we could improve, namely our work model iterations.  

During weekly scrum meetings, our team identified and analysed progress that had been made, discussed any issues in working processes, such as re-assigning tasks that better suited certain members, and any work that should be completed by the next meeting. Requirements did not change during the development process, meaning the development process was relatively smooth and high adaptability was not needed, although by aligning with the agile methodology, was still highly achievable. 

## Assumptions

* There are also travel packages to more than just holidays, customers can also purchase business packages to business trips. 
* Before customers call, they must have used the customer profile using the profiler tool.
* A target list is created with potential customers that have used the profiler tool, and have agreed to be call, sent messages etc.
* Outbound calls are performed in set times made by managers when times are quiet.
* The script and guidelines given to the relationship manager from the system to help in providing an improved service to the end-customer is only to advise, and does not have to be followed exactly
* Prior to starting the role, each RM is required to complete a questionnaire to align their knowledge with the company requirements. It is assumed that this is checked through interviews and skills testing
* Call matching is currently handled manually.
* A physical receptionist was hired to assort the inbound calls from the customers to the correct Relationship Manager through the private automatic branch exchange.
* Customer data is stored in a database with all relevant information about them that will be used to match them to a Relationship Manager.
* Managers can access the database with customer information.
* In busy times, inbound callers that stay on hold for long times if a matching relationship manager is busy, they currently redirected to the next available relationship manager.
* Our team is only dealing with the call routing system and out-bound calls, anything else is out of scope
* There are specific Relationship Managers for Outbound calling, but regular Relationship Managers can also perform Outbound calls.

## Work Products and Models
### User Stories

| As a/an   | I want to…                                                                    | so that                                                                                 |
|-----------|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Customer  | be able to communicate using my preferred language                            | I can explain my requirements better.                                                   |
| Customer  | be directed to the best suitable Relationship Manager                         | I can gather precise knowledge about my travel packages without any misunderstandings.  |
| Customer  | be assigned to the Relationship Manager who knows my detail and my interests. | they can provide me with information without any basic questions.                       |
| Customer  | be able to get the perfect and precise services                               | my time doesn’t waste.                                                                  |
| Customer  | be able to continue my call with the previous assigned Relationship Manager   | I can continue my conversation                                                          |
| Customer  | be able to know the estimated time it will take in queue                      | I can plan accordingly on to wait or call later.                                        |
| Customer  | be able to know the status of my travel packages and the procedure            | I know if any changes are supposed to be made or not.                                   |

| As a/an               | I want to..                                                                 | So that                                      |
|-----------------------|-----------------------------------------------------------------------------|----------------------------------------------|
| Relationship Manager  | be matched with the  customers I have information about                     | I can provide them with the best service.    |
| Relationship Manager  | be able to access the required information about the customer               | I know what exactly is required out of me.   |
| Relationship Manager  | receive customers details such as their past purchases                      | I can recommend them the perfect deal.       |
| Relationship Manager  | be evaluated and assigned to the parts where I have interest and knowledge  | I can be motivated and enjoy working.        |
| Company Manager       | I want to assign the Relationship Managers to the customers they know about | they can enjoy and provide better services.  |

| As a/an              | I want to…                                                  | So that                                                                  |
|----------------------|-------------------------------------------------------------|--------------------------------------------------------------------------|
| Business Customer    | Save money with business packages                           | I can invest them.                                                       |
| Business Customer    | I want to be given the best option for my travelling needs  | I don’t have to worry about anything related to it and focus on my work. |
| Commercial Customer  | Have a good relaxing and cost saving budget deals.          | me and my family can enjoy without going out of my budget.               |
| Commercial Customer  | I want my package to include places which I can see there.  | I don’t have to do any additional work towards it.                       |
| Potential Customer   | be offered a deal which is relevant and special             | my time doesn’t waste  in unnecessary conversation.                      |

### Use Case Diagram
![alt text](https://github.com/RhysandLy/ISDM---Group-4/blob/Rhys/Images/ISDM%20Diagrams-Use%20Case%20Diagram%20v2.png "Use Case Diagram")

### Activity Diagram For Inbound Customers
![alt text](https://github.com/Bilal13396989/ISDM---Group-4/blob/master/ISDM%20Diagrams-Activity%20Diagram%20(1).png"Activity Diagram For Inbound Customers")

### Activity Diagram For Outbound Customers
![alt text](https://github.com/Bilal13396989/ISDM---Group-4/blob/master/ISDM%20Diagrams-Activity%20Diagram-2%20(2).png "Activity Diagram For Outbound Customers")

## Advantages for developing a new Information System

Developing an information system for the in-house call management centre will provide a higher level of personalised service to customers. With being closer with the high-level support team the relationship managers can help resolve customer related issues quicker and more efficiently. Having a more personalised customer service, by routing calls from  customers to a matching relationship manager through the system, they can build strong relationships and customers are more likely to call again and/or purchase another package and in turn improving the business’ profits.

With the current system, callers and relationship managers are manually matched, which is an inefficient way for routing as it wastes time, potential sales and in turn costs more money. With a new call routing system,  the company is given another way to improve customer experience, relationships and fosters loyalty when paired with an appropriate relationship manager quickly, as callers are pleased that the business understands their needs, interests and values their time.

The new system will be extremely scalable, intelligent call routing can be implemented with many different deployment models. Depending on future and or changing business requirements the call routing system can be scaled up or down easily. This “future-proof” design of the system is important in this ever-changing technological society where businesses are always looking to upgrade and improve themselves.

Cost effectiveness is a massive advantage when implementing a new intelligent call routing system, it can optimize operational costs by ensuring that calls are always routed to a matching relationship manager and never lost or sent to voicemail, eliminating any revenue losses that may occur due to lost calls. The improvement in call routing caller to matching relationship managers will help capitalise on conversion rates by providing a better customer experience to inbound callers. The complexities that come with manual pre-routing and computer telephony integration are eliminated with the newly defined scalable, cost-effective, customer-based information system.

With outbound calls, relationship managers are also matched with customers that have shown interest in the company’s services. The information shown to the relationship managers in the database collected from the profiler tool, allows the relationship managers to make a more personal connection and target what the customer really wants. The script and guidelines given to the relationship manager from the system is a unique way to personalise the customer experience and improve relations. This will help the relationship managers make a sale or intrigue the customer enough to call and buy a travel package.

The new system eliminates cold calling and only relies on warm calling (The prospect has some level of interest.). This makes the companies services more personal, and more appealing to customers, that favour the respect of an individual's desires. Cold calling usually ends with the customer hanging up and no sale is made.  Unsolicited calls will not help the company improve sales and profits but will most likely waste the company’s time and money. Through the new system relationship manager will only deal with customers that have shown interest and used the profiler tool and will be more likely to sell a travel package.
The new system will favour more effective and personal inbound and outbound calling strategies, thus improving sales and customer relationships.


