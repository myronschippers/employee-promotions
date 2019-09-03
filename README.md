# Employee Promotions (exercise)

This is an exercise meant to be completed using a front-end framework of your choosing and state management of some kind. THe sample solution will be built out with React and Redux but there are a few other options listed below. 

## The Scenario

A company wants to streamline their promotions process to make it a little easier to determine if an employee meets all of the prerequisites for a promotion and calculate all pay increases that would be needed for the employee's promotion. They want this to be a tool that an employee can use as well in order to track their progress and motivate them to achieve more within the company. There will be 3 different users in this application; the employee, the manager, and operations. Each user is going to have a different role in the application and different tasks for them to complete. A promotion is primarily a vertical movement to the next position in the companies specific Career Track but occasionally an employee will move laterally into a new Career Track all together.


## General Information

**Career Tracks/Departments:**

* Sales
* Engineering
* Project Manager
* Analyst
* Design


## Requirements


### Company Promotion Rules

- [ ] **Application for Promotion** - Every employee must fill out an Application for Promotion in order to be considered for promotion to a new position. The application has certain required information while other information is voluntary for the purpose of producing analytics for the company.
    * First Name
    * Last Name
    * Current Position
    * Position Applying For
- [ ] Employee must have been in their current position for a minimum of 1 full year.
    * The only way an employee can be promoted with less than a year in a position is if they were highered into the position with **Special Consideration**.
- [ ] Promotions can only be made in the fourth quarter of the business year.
- [ ] An employee may apply for a promotion at any time if the promotion is to a position level lower than that of a Senior but for any position level of Senior or higher there must be a posting for that position.
- [ ] **Seniority Consideration** - If an employee has been in a position for 3 or more years they will be given special consideration over other candidates.
- [ ] **Annual Rating Consideration** - The employee must meet one of the following conditions in order to be eligible for a promotion.
    * If the employee has been in their current position for only one year they must have an annual rating of at least 5.
    * If the employee has been in their current position for 2 to 3 years they must have an average annual rating of at least 4 or greater. 
    * If the employee has been in their current position for 3 or more years they must have an average annual rating of at least 3 or greater.
- [ ] **Special Consideration** - If an employee has certain Special Considerations this may mean that are exempt from having to meet other conditions for promotion. An employee is only allowed a total of 3 Special Considerations and in order to get a Special Consideration they have to meet particular conditions. This part of the process is still very subjective and manual.
    * Higher Contract
    * 


### Promotion Checkpoints/Steps

1. **Special Considerations** - Check for any special considerations the employee might have. This could potentially allter other steps.
1. Human Resources Validation for Readiness of Applicant.
    * Check for 

### Promotion Logic

#### Sales

1. Sales Associate
    * Pay Range: $30,000 - $45,000
    * Sales Commission: 3%
1. Sales Engineer
    * Pay Range: $00,000 - $00,000
    * Sales Commission: 3%
1. Sales Regional Director
    * Pay Range: $00,000 - $00,000
    * Sales Commission: 0%
1. Sales National Director
    * Pay Range: $30,000 - $45,000
    * Sales Commission: 3%


#### Engineering

1. Software Engineer Apprentice
1. Software Engineer Level 1
1. Software Engineer Level 2
1. Senior Software Engineer
1. Principal Software Engineer
1. Architectural Software Engineer
1. Senior Architectural Software Engineer


#### Project Manager

1. Project Management Associate
1. Project Manager
1. Senior Project Manager
1. Principal Project Manager
1. Product Owner

#### Analyst

1. Associate Business Analyst
1. Business Analyst Level 1
1. Business Analyst Level 2
1. Senior Business Analyst
1. Product Owner

#### Design

1. Associate Designer
1. Graphic Designer
1. UI Designer
1. Senior UI Designer
1. Principal UI Designer
1. UX Designer
1. Senior UX Designer
1. Principal UX Designer

### Data Structure



### Server and Database