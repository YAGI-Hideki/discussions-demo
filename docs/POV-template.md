NOTE: Replace the following tokens with appropriate values:
|||
|--|--|
|{CUSTOMER_NAME} - | The customer |
|{GITHUB_EXEC_SPONSOR}| Sr. Exec for the account, e.g., Merrit Traughber or Lamar Caldwell for Amer Central |
| {GITHUB_ACCT_EXEC} | Responsible EAM |
| {GITHUB_TECH_MGR}|Technical PRP for POV, generally the Account SE|
----------------

# GitHub Enterprise Proof of Value

<p align="center">
  <img src="../images/customer-icon.png" height=200  >
</p>

## Executive Summary
GitHub and {CUSTOMER-NAME} will partner to conduct a trial implementation and Proof of Value (PoV) of GitHub Enterprise Server (GHES).  The goal of this PoV will be to validate that GitHub meets {CUSTOMER-NAME}’ requirements as stated in this document.  


This document covers a Proof of Value for the following GitHub platform(s):
 - GitHub Enterprise Cloud

Greetings!
We are delighted to work with {CUSTOMER-NAME} to pilot GitHub Enterprise and demonstrate the value of our software collaboration platform. Working towards success, we will need:


 - {CUSTOMER-NAME}’s objectives and requirements, 
 - a plan with target dates for key events, 
 - roles of the people who will pilot GitHub Enterprise, the workflows they will pilot, the criteria they will use to determine success, and
 - roles and responsibilities of key people involved in the POV.

After the completion of the POV, should you choose to move GitHub Enterprise into production, we will continue to work with you to plan and execute a successful implementation.

We look forward to working with you!
	________________
## {CUSTOMER-NAME} Business Objectives & Requirements

{CUSTOMER-NAME} will evaluate GitHub Enterprise (GHEC) against the list of requirements in this document.  This evaluation will conclude with a decision whether or not to purchase GHEC.

### Roles, Objectives, and Success Criteria  
{CUSTOMER-NAME} and GitHub identified three high-level roles that will evaluate GitHub Enterprise’s ability to meet the above objectives:


 - Implementation & Administration
 - Migration

We identified several objectives for each high-level role, each with its own set of success criteria. These are detailed in full in the Appendix. 

The goal of this POV effort is to confirm GitHub Enterprise’s ability to address and solve {CUSTOMER-NAME}’s defined business requirements. As such, both GitHub and {CUSTOMER-NAME} understand the scope of this Proof of Value will evaluate a subset of GitHub Enterprise's full capabilities.

### Expectations
#### Human Resources
GitHub will:
 - Provide {CUSTOMER-NAME} access to the account management team, including a Solutions Engineer and a Sales Representative
 - Provide {CUSTOMER-NAME} full access to Enterprise Support for the duration of the POV

{CUSTOMER-NAME} will:
 - Provide access to staff conducting the evaluation
 - Carry out the tasks necessary to evaluate the requirements articulated in the appendix below.

### Technical Expectations

GitHub will:
 - Provide {CUSTOMER-NAME} with a trial license of GitHub Enterprise for the duration of the POV (30 days).

{CUSTOMER-NAME} will:
 - Identify and make accessible the Enterprise systems to be integrated with GitHub Enterprise, such as CI/CD tooling, SAML IdP, etc.
 - Share any testing plans with GitHub; and
 - Share their testing results with GitHub.

### Key Roles
|Role|Responsibilities|Person(s)
|--|--|--|
|Executive Sponsor(s)|Manage overall process, final approvals {GITHUB_EXEC_SPONSOR}|
|Project Manager (customer)|Provide customer physical and technical resources to complete objectives of POV. Facilitate scheduling of resources, timeframes, technical goals, and objection handling.|{CUSTOMER-NAME} TBD|
|Project Coordinator (GitHub)|Identify customer business requirements, primary GitHub business contact.|{GITHUB_ACCT_EXEC}|
|Technical Project Manager (GitHub)|Provide GitHub technical resources to complete objectives of POV. Facilitate scheduling of technical resources and timeframes. <br> Primary GitHub technical contact. Provide onsite, offsite, and remote technical support for POV. Verify evaluation plans, test plans provide technical knowledge transfer.|{GITHUB_TECH_MGR}|

	

### Pre-POV Checklist

|Platform | Event | By | Date | Notes |
|--|--|--|--|--|
|GHEC | Trial org created | {CUSTOMER_NAME} | | [Org Name](https://github.com) |
|GHES | Hardware provisioned | {CUSTOMER_NAME} | | | 
|GHEC/S | Enterprise Provisioned | {GITHUB_ACCT_EXEC} | | [Enterprise](https://github.com) |
|GHEC/S | GitHub Orientation Mtg | {GITHUB_TECH_MGR} ||  | 

### Milestones   
|Event|Date|
|--|--|
|POV Preparatory Meeting (Define users, responsibilities, timelines, use cases, success criteria, etc)|TBD|
|POV Plan Review | TBD |
|Provision GitHub Trial (See Pre-POV Checklist) | TBD |
|POV Execution (Start of pilot)|TBD|
|Initial Training/Enablement|TBD|
|Use Case Validation Against Success Criteria|TBD|
|Compile POV Results|TBD|
|Present POV Results to Pilot Team & {CUSTOMER-NAME} Management|TBD|
|Weekly Cadence Checkpoints|TBD|

If {CUSTOMER-NAME} determines GitHub Enterprise provides real value to their software development process we will work with you to procure the solution according to the following schedule:


|Event|Date|
|--|--|
|Finalize Proposal|TBD|
|Sign Contracts and Process Purchase Order|TBD|
|Implementation Coordination Meeting|TBD|
|Implementation Kickoff|TBD|
|Migrate Data|TBD|
	
## Approval


### {CUSTOMER-NAME} Approval Process


Please provide details about your software acquisition process.  This will help us to prepare and speed the process.


|Person|Responsibility|
|--|--|
|*{CUSTOMER-NAME} TBD*|Technical Approval|
|*{CUSTOMER-NAME} TBD*|Infrastructure Approval|
|*{CUSTOMER-NAME} TBD*|Security Approval|
|*{CUSTOMER-NAME} TBD*|Legal/Contract Approval|


# Appendix: Success Criteria

This appendix is a list of success criteria that we’ve gathered from other Proof of Value activities. Some items on this list might not be relevant, some items that should be on this list might be missing, in which case please feel free to add as many as you like. Customize for use and to achieve the business objectives detailed above.

### Administration and Deployment

|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|A1|Empower project owners to maintain access controls for their repositories||
|A2|Empower project owners to manage integrations between their repositories and other tooling||
|A3|Scalability||
|A4|Dashboards, alerting and reporting||
|A5|Performance (Number of clones)||
	

### Migration
|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|M1|Upload code from user computers||
|M2|Perform `point-forward` migration of repo into Git from legacy system(s).||
|M3|Perform migration of repo into Git with history preserved from legacy system(s)||
|M4|Support for GIT LFS||

### Developer Experience
|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|D1|Content (code, context) is easily searchable<br>Advance search to find source and files||
|D2|Content is browsable by authenticated users||
|D3|Provide workflow(s) for proposing changes to codebase||
|D4|Open source software development||
|D5|Easily create issues for discussion about the code||
|D6|Assign labels to issues and filter||
|D7|Assign issues to multiple people||
|D8|Easily invite individuals and teams to contribute to the discussion||
|D9|Assign issues to milestones||
|D10|Pull requests||
|D11|Versioning/Tagging||
|D12|Nested groups and projects||
|D13|Built-in to-do list||
|D14|Capture discussion about code development decisions||
|D15|Facilitate creation of teams focused on expertise and/or areas of interest||
|D16|Invite non-core teams (expertise, interest, discipline) to review process||
|D17|Ability to conduct code reviews with a flexible workflow||
|D18|Require proposed changes to code to pass build tests before merging||
|D19|Allow a limited group of approved persons to merge code into master/production branch||
|D20|Limit the ability to commit to certain branches to specific users.||
|D21|Require code review prior to merging into production branch||
|D22|Allows to revert changes back to previous state||
|D23|Allows to see history of code changes||
|D24|List of approvers/code owners for pull requests||
|D25|Render documentation maintained as part of the codebase within the application||
|D26|Allow repository owners to create wikis for their repositories||
|D27|Enable the creation and publication of static websites to promote repositories, teams, and/or share information with a wider audience. ||

### Enterprise and Development System Integration

|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|I1|GitHub Enterprise configured to use enterprise authentication provider, e.g., LDAP and/or SAML LDAP or AD integration||
|I2|Work with other IDEs and text editors through use of companion app||
|I3|Integrate with ??||
|I4|Usage with multiple build systems (multiple versions of Teamcity)||
|I5|Provide ready-to-use integrations with common development tools||
|I6|Provide webhooks and API for building integrations with other tooling||
|I7|Support of server side hooks||
	

|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|S1|Security by a specialized group or team member||
|S2|Enhanced security - Enforce merge checks, support hooks and IP whitelisting that can block a user internally.||
|S3|Allow for enabling of restrictions at the branch level||
|S4|SOC II compliance||
|S5|ISO 27001||
|S6|Completion of {CUSTOMER-NAME} security vetting process||
	

## Continuous Integration
|ID|Description|Priority (critical, important, nice to have)|Successfully Piloted (yes / no)|
|--|--|--|--|
|C1|Built-in robust CI||
|C2|Tight integration of CI with pull requests and issues||
	

# Appendix: Technical Landscape
### Platform(s) Being evaluated
GitHub Enterprise Cloud
### Integrations (Authentication/Authorization):
Azure AD

### Integrations (CI/CD):
Jira
<<{CUSTOMER-NAME}, additional integrations here>>

### Integration (IDE)
Visual Studio
<<{CUSTOMER-NAME}, additional integrations here>>

### Integration (Other)
