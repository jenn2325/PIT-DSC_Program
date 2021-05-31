# Project "Interactive Tool Understanding Science Policy Issues"

Last edited: May 11th, 2021

#### Opportunity

[Motivation for the project, potential value and problem statement]

Sci4NY wants to visualize the top science-related policy issues by each NYC community district in order to create dialogue that science knowledge can help create better policy about important community/borough issues. One of their biggest bottlenecks is extracting data from pdf reports/websites. Having to enter data manually would be very time-consuming.

Is it possible to generate an systematic method of parsing NYC community district reoports pdf documents or district profile websites so that it could ease the data collection process?

#### Current State

[Why is **now** a good time to start this project with some background research]

New York City Department of Health have published NYC Community Health Profiles pdf documents for 59 community district(https://www1.nyc.gov/site/doh/data/data-publications/profiles.page), each captures the health of 59 community districts across the city. They contain over 50 measures of neighborhood health. These reports highlight the disparities among neighborhoods and can be used by policymakers, community groups, health professionals, researchers and residents to encourage community engagement and action.

New York City Department of City Planning published Community District Profiles for each of 59 community districts(https://communityprofiles.planning.nyc.gov). The profiles addresses the most pressing concerns, i.e. the top three pressing issues perceived and identified by that community district. 

#### People, roles, and contacts

[The people that will approve, execute, and sustain the project]

- Project Owner: Nancy Holt
- Data Scientist(s)
- Stakeholders: New York City Governments

#### Requirements and metrics

[Short & long term metrics that aligns the project efforts with the project's intent.]

[Metrics include guardrail metrics vs success metrics, i.e. when do you know something is wrong vs going well?]

[Metrics should be easily calculated]

- Deliverable
  - A documented library that ingests any video of people moving that can then
    correct identifying all the individuals then predict their emotional state.
  - A systematic algorithm that automatically extract the relevent data we need from Community Health Profiles pdf documents & Community District Profiles, and merge 59 community districts data. 
- Metrics
  - Coverage for test video files - 95% minimum
  - Precision controlling for recall being at least 50%
  - ...

#### Timeline and milestones

[Setting expectations for commitments across the group, definition of "project is kick-off ready"]

|--|--|--|
|Date|Description|People|
|6/14/2020|Kick-off & Data Delivery|John Doe, Jane Doe, and Josh Deere|
|4/7/2020|SME check-in with initial progress|John Doe, Jane Doe|
|4/15/2020|First round of results sharing|John Doe, Jane Doe, Josh Deere, Jac Deere|
|...|...|...|


#### Data Specification

[Setting expectations for commitments across the group]

|--|--|--|--|--|
|Description|Specification and attributes|Purpose|Source|Contact|
|USC Motion Tracking data|- motion data<br>- Emotional Prompt<br>- Id for individual actors<br>- ...|Required for linking motion to emotion|USC website, **approval necessary**|Expert: John Doe<br>Permissions: John Do|
|...|...|...|...|...|


#### Hand-off and maintenance

[Define project completion and potential hand-offs]

The project is complete when
  - The following R code is documented into private GitHub repository
    - Emotion prediction algorithm
    - Data ingestion, cleaning, processing
      - Automation is only required after ingestion
  - Data for the report is stored in Google Drive maintained by XYW 
  - Report for the project is reviewed and approved by ZZZ
    - If certain requirements are not satisfied by the project deadline, ...


- How will code and data be delivered?
- Who will take-over the project afterwards?
- When should hand-off begin?
- Technology requirements from the new team
- ...
