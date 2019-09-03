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


### Promotion Process

The following are the steps that are followed 

#### Application Progression:

1. Employee fills out an **[Application for Promotion](#application-for-promotion)**.
1. Employee gets their mentor to sign the **[Application for Promotion](#application-for-promotion)**.
    * The employee hands in the application to their manager.
1. Manager fills out a **[Promotion Readiness](#promotion-readiness)** form.
1. Manager adds the **[Promotion Readiness](#promotion-readiness)** form along with the **[Application for Promotion](#application-for-promotion)** for to the same file and places the name of the applicant on the outside of the folder.
1. Manager hands in the Promotion folder to Human Resources.
    * Place **[Promotion Readiness](#promotion-readiness)** form in a folder with the **[Application for Promotion](#application-for-promotion)** placing the applicant's name on the outside of the folder.
1. **Special Considerations** - Check for any special considerations the employee might have. This could potentially alter other steps.
1. Human Resources validates the readiness of the applicant by checking their application.
    * Check applicant's seniority and a a point modifier to their overall application score.
    * Check applicant's annual rating against the rating rules and add modifier to overall application score. If applicant does not meet minimal requirements **[Reject Application](#reject-application)**.


#### Application for Promotion:

1. Personal Information
    * First Name
    * Last Name
    * Suffix
1. Date filled out


#### Promotion Readiness:

1. Manager fills out employee information.
    * First Name
    * Last Name
    * Suffix
    * Employee ID Number
    * Application for Promotion ID Number
1. Manager fills out section marked, "For Manager Only".
    * Manager First Name
    * Manager Last Name
    * Initial Rating 1 - 3 where:
        - 1 = Applicant would underperform in position
        - 2 = Applicant would meet the expectations of the position
        - 3 = Applicant would excel in the position
    * Comments on why the employee was rated how they were.
    * Yes or No, have you discussed the promotion with the employee prior to application.
    * A short description of what the discussion between the manager and employee was. 
    * Manager Signature
    * Date filled out
1. Human Resources fills out section marked, "For Human Resources Only".
    * HR Rep. First Name
    * HR Rep. Last Name
    * Yes or No, applicant meets...
    * HR Rep. Signature
    * Date filled out


#### Reject Application:

1. Mark application as rejected.
1. Note reason for rejection on the application.
1. Application goes to the employee's manager to discuss with the employee.
    * The **Promotion Readiness** form does not get shared directly with the employee but the application itself gets shared.
    * If the employee requests a copy of the application the manager will provide them with a photocopy of the application.
    * Specifically the manager will discuss ways that the employee can work towards getting meeting their goal of getting promoted. 
1. Manager makes an action plan and makes a copy that gets added to the application folder.
1. Application folder is handed back to Human Resources.
1. Human Resources files the application folder with the rest of the employee's information.


#### Validated Application:

1. Mark application as validated.
1. Fill in name of Primary Manager
1. Fill in name of interviewing Manager
1. Fill in name of interviewing HR. Rep
1. Fill in name of interviewing Department Technical Representative.
1. Fill in name of mentor


### Salary by Department and Position


#### Sales

| Position | Commission Pct. | Min. Compensation | Max. Compensation |
| ----------- | ----------- | ----------- | ----------- |
| Associate Sales Engineer | 3% | $00,000 | $00,000 |
| Sales Engineer | 3% | $00,000 | $00,000 |
| Sales Engineer Level 1 | 3% | $00,000 | $00,000 |
| Sales Engineer Level 2 | 3% | $00,000 | $00,000 |
| Senior Sales Engineer | 3% | $00,000 | $00,000 |
| Regional Director of Sales | 3% | $00,000 | $00,000 |
| National Director of Sales | 3% | $00,000 | $00,000 |


#### Engineering

| Position | Min. Compensation | Max. Compensation |
| ----------- | ----------- | ----------- |
| Associate Software Engineer | $00,000 | $00,000 |
| Software Engineer Level 1 | $00,000 | $00,000 |
| Software Engineer Level 2 | $00,000 | $00,000 |
| Senior Software Engineer | $00,000 | $00,000 |
| Principal Software Engineer | $00,000 | $00,000 |
| Architectural Software Engineer | $00,000 | $00,000 |
| Senior Architectural Software Engineer | $00,000 | $00,000 |


#### Project Management

| Position | Min. Compensation | Max. Compensation |
| ----------- | ----------- | ----------- |
| Associate Project Manager | $00,000 | $00,000 |
| Project Manager | $00,000 | $00,000 |
| Senior Project Manager | $00,000 | $00,000 |
| Principal Project Manager | $00,000 | $00,000 |
| Product Owner | $00,000 | $00,000 |


#### Analyst

| Position | Min. Compensation | Max. Compensation |
| ----------- | ----------- | ----------- |
| Associate Business Analyst | $00,000 | $00,000 |
| Business Analyst Level 1 | $00,000 | $00,000 |
| Business Analyst Level 2 | $00,000 | $00,000 |
| Senior Business Analyst | $00,000 | $00,000 |
| Product Owner | $00,000 | $00,000 |


#### Design

| Position | Min. Compensation | Max. Compensation |
| ----------- | ----------- | ----------- |
| Associate Designer | $00,000 | $00,000 |
| Graphic Designer | $00,000 | $00,000 |
| UI Designer | $00,000 | $00,000 |
| Senior UI Designer | $00,000 | $00,000 |
| Principal UI Designer | $00,000 | $00,000 |
| UX Designer | $00,000 | $00,000 |
| Senior UX Designer | $00,000 | $00,000 |
| Principal UX Designer | $00,000 | $00,000 |
| Designer Director | $00,000 | $00,000 |
