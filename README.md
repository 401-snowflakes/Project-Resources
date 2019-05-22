***
<br>
<header>
<img src="./assets/CURVE-jasonb315.png" style="width:100px;"/>
<span style="font-size:40px;;">Curve: </span><span style="font-size:40px;;">subtitle</span>
</header>

***

This is a joint final project between the 401 Javascript and 401 ASP.Net classes at Code Fellows in Seattle, WA. The project will be completed in only 4 days between May 20 - May 24 2019.

#### Goal
Recreate the Medium **_Snowflake_** app for Code Fellows employee and student core competancy evaluations. Adapt the core competancies used in the careers curriculum as metrics. The front end should use React, and Gatsby JS while the backend should serve the required data to the front end using GraphQL while providing for a variety of different roles and permissions.
The application will heavily reference the Medium's Snowflake [Original Source Code](https://github.com/CodeFellows-Curve/snowflake).

<!-- --- -->

<!-- #### Table of Contents
* [Project Board]()
* [Roles and Responsibilities]()
* [GitHub Workflow]()
* [Daily Schedule]()
* [Team Heirarchy]()
  * [Integrations Team Resources]()
  * [UI/UX Team Resources]()
  * [Backend Integration]()
  * [Data]()
  * [Auth]()
* [Meetings]()
  * [Meeting Notes]()
  * [Meeting Agendas]()
* [Project References]() -->

---

#### Notes from Client (Brooke)
_Conversation 5/16/19_: All of the sub competancies and main competancies will have a maximum score of 4. The snowflake should graphically show ALL of the main competancies and subcompetancies. Each primary compentancy will have a different color (or shade). Use the [Engineering Competancy Matrix Scoring Guide](https://docs.google.com/spreadsheets/d/131XZCEb8LoXqy79WWrhCX4sBnGhCM1nAIz4feFZJsEo/edit#gid=0) as a guide for the requirements to move to the next level in score.

---

<!-- #### Project Description
_Pending_ -->

#### Jira Project Board
[Project Sprint Board](https://401curve.atlassian.net/secure/RapidBoard.jspa?rapidView=1&projectKey=CUR)

#### Roles and Responsibiities
<details>
  <summary><b>Senior Project Managers</b></summary>
  <p><b>Responsibilities</b></p>
    <ul>
      <li>Assist with problem solving as requested</li>
      <li>Participate in scrum meetings</li>
      <li>Review pull requests from deployment to master branches in GitHub</li>
      <li>Merge pull requests from deployment to master branches in GitHub</li>
    </ul>
</details>
<details>
  <summary><b>Project Manager</b></summary>
  <p><b>Responsibilities</b></p>
    <ul>
      <li>Coordinate daily project timelines</li>
      <li>Participate in all scrum meetings</li>
      <li>Lead team meetings</li>
      <li>Manage Jira project board</li>
      <li>Prepare meeting agendas from integration team feedback</li>
      <li>Assist with other tasks as requested</li>
    </ul>
</details>
<details>
  <summary><b>Integrations Team Members</b></summary>
  <p><b>Responsibilities</b></p>
    <ul>
      <li>Facilitate communications between teams</li>
      <li>Participate in scrum of scrum meeting, team specific meetings and end of day planning meeting</li>
      <li>Assist with planning sprints and management of Jira board</li>
      <li>Review and merge pull requests from designated project team from staging branch to deployment</li>
      <li>Ensure that all documentation and testing for assigned team is complete and high quality</li>
      <li>Assist with other tasks as requested</li>
    </ul>
</details>
<details>
  <summary><b>Team Leaders</b></summary>
  <p><b>Responsibilities</b></p>
    <ul>
      <li>Facilitate communications between designated team and integrations team point of contact</li>
      <li>Participate in scrum of scrum meeting and team specific meetings</li>
      <li>Create and delegate tasks from Jira board to team members</li>
    </ul>
</details>
<details>
  <summary><b>Team Member</b></summary>
  <p><b>Responsibilities</b></p>
    <ul>
      <li>Complete delegated tasks as assigned</li>
      <li>Participate in team specific meetings</li>
      <li>Add comments to completed tasks before the end of the day</li>
      <li>Communicate where additional features/tasks may be needed</li>
    </ul>
</details>

#### GitHub Flow
**All work will be done on feature specific branches that are branched off of the staging branch**
* **Team leaders (unless they designate another team member) will be responsible for:** 
  * Reviewing pull requests from the feature branch to staging branch
  * Merging pull requests from the feature branch to staging branch
* **Integration team members will be responsible for:** 
  * Reviewing pull requests from staging to depoloyment
  * Merging pull requests from staging to deployment
* **Senior project managers will be responsible for:**
  * Reviewing pull requests from development to master
  * Merging pull requests from development to master

 ---

<h2><b>Daily Meeting Schedule</b></h2>

<details>
  <summary><b>9:00 - 10:00 - Team Scrum Meetings (15 minutes per team)</b></summary>
  <p><b>Attendees</b></p>
  <ul>
    <li>PM</li>
    <li>Lead TAs</li>
    <li>Integrations Team Representative</li>
    <li>Team Members</li>
  </ul>
  <p><b>Agenda</b></p>
  <ul>
    <li>Present any work since last meeting</li>
    <li>Tasks for the day</li>
    <li>Any known or anticipated problems?</li>
    <li>Communicate any needed coordination with other teams</li>
  </ul>
</details>
<details>
  <summary><b>10:00 - 10:30 - Check in meeting</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>PM</li>
      <li>Integrations Team</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>Plan for the day</li>
      <li>Big picture tasks for each group</li>
      <li>Any additional coordination times between smaller groups?</li>
      <li>Review planned agenda for the Big Scrum Meeting</li>
    </ul>
</details>
<details>
  <summary><b>11:00 - Big Scrum Meeting - Approximately 30 min</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>Clients</li>
      <li>Lead TAs</li>
      <li>PM</li>
      <li>Integrations Team</li>
      <li>Team Leaders</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>What each group will be working on</li>
      <li>Planned inter-team coordination meetings (if any)</li>
      <li>Clarification questions asked of the clients</li>
      <li>Identify any problems where TA help needed</li>
    </ul>
</details>

<details>
  <summary><b>11:30 - Team Discussion (5-10 minutes)</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>Integrations Team Representative</li>
      <li>Team Members</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>Team leader and Integrations team representative communicates team specific information from Big Scrum meeting to team.</li>
    </ul>
</details>
<details>
  <summary><b>16:00-17:00 - Team Scrum Meetings (15 minutes per team)</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>Clients</li>
      <li>All TAs</li>
      <li>PM</li>
      <li>Integrations Team Representative</li>
      <li>Team Members</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>How did the day go</li>
      <li>What was accomplished</li>
      <li>Plan for the next day</li>
    </ul>
</details>
<details>
  <summary><b>17:00 - Demo Meeting (15-20 min)</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>Clients</li>
      <li>Lead TAs</li>
      <li>PM</li>
      <li>Integrations Team</li>
      <li>Team Leaders</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>What was accomplished today</li>
      <li>Demo</li>
      <li>Client Feedback</li>
    </ul>
</details>
<details>
  <summary><b>17:30 - Integrations Team Daily Retrospective Meeting</b></summary>
  <p><b>Attendees</b></p>
    <ul>
      <li>PM</li>
      <li>Integrations Team</li>
    </ul>
  <p><b>Agenda</b></p>
    <ul>
      <li>What was accomplished today</li>
      <li>New tasks for the following day</li>
      <li>Things to discuss/ask at next day big scrum meeting</li>
      <li>Problems were additional resources are needed.</li>
      <li>Update Jira Board</li>
    </ul>
</details>

***

<h2 align="center">Team Hierarchy</h2>
<p align="center">
<img src="./assets/teams-01.jpg" />
</p>

#### 

<details>
  <summary><b>Integrations Team</b></summary><br>
  <span><b>&nbsp; &nbsp; Team Leader: </b></span><span>Erin Trainor</span><br><br>
  <span>&nbsp; &nbsp; &#5852; Team Biographies  - Link Pending</span></br><br>
  <a href="https://docs.google.com/document/d/1RY_Ob5EYsAonB_acwMkEw99AdHmZTKBx20fd3x4WGxQ/edit?usp=sharing">&nbsp; &nbsp; &#5852; Group Agreement</a></br>
  <a href="https://docs.google.com/document/d/104WMsb7SM3s68rgwwktQSdUjv_HaSqFyRajnlSDvFqo/edit?usp=sharing">&nbsp; &nbsp; &#5852; User Stories</a><br><br>
</details>

<details>
  <summary><b>UI/UX - Javascript</b></summary><br>
  <span><b>&nbsp; &nbsp; Integrations Team Point of Contact: </b></span><span>Chris Merritt</span><br>
  <span><b>&nbsp; &nbsp; Team Leader: </b></span><span>Vanessa Wei</span><br><br>
  <span>&nbsp; &nbsp; &#5852; Team Biographies  - Link Pending</span></br><br>
  <a href="https://docs.google.com/document/d/1OPUpRXWkk1Dx0BmRjouBDBCOGXqrlE3Eh6Lt7vcCqz8/edit">&nbsp; &nbsp; &#5852; Group Agreement</a></br>
  <a href="https://docs.google.com/document/d/1-sHkbBGCe7hSizhoMnbMEGOERKmqodXlm7vNn_8pXeo/edit?usp=sharing">&nbsp; &nbsp; &#5852; User Stories</a><br><br>
</details>

<details>
  <summary><b>Backend Interface - Javascript</b></summary><br>
  <span><b>&nbsp; &nbsp; Integrations Team Point of Contact: </b></span><span>Greg Dukes</span><br>
  <span><b>&nbsp; &nbsp; Team Leader: </b></span><span>Spencer Hirata</span><br><br>
  <span>&nbsp; &nbsp; &#5852; Team Biographies  - Link Pending</span></br><br>
  <a href="https://docs.google.com/document/d/1zHWas520gGabNYsYsWhnB7dGbvR6hwNa1sw3Oxc140w/edit?usp=sharing">&nbsp; &nbsp; &#5852; Group Agreement</a></br>
  <a href="https://docs.google.com/document/d/1JnWA1EmyUWowkoHwlc4e0SlBN4xHoipjro0CWolIrOg/edit">&nbsp; &nbsp; &#5852; User Stories</a></br><br>
</details>

<details>
  <summary><b>Data - C#</b></summary><br>
  <span><b>&nbsp; &nbsp; Integrations Team Point of Contact: </b></span><span>Andrew Curtis</span><br>
  <span><b>&nbsp; &nbsp; Team Leader: </b></span><span>Dan Logerstedt</span><br><br>
  <span>&nbsp; &nbsp; &#5852; Team Biographies  - Link Pending</span></br><br>
  <a href="https://docs.google.com/document/d/14jUwk_TpGIYohoteQID2KzxtCYH_F5fuV8_K4IrYTjw/edit?usp=sharing">&nbsp; &nbsp; &#5852; Group Agreement</a></br>
  <a href="https://docs.google.com/document/d/1AEAnTw2npca0iKJMauaP610BuPSltbU-WWCmumHbyzI/edit?usp=sharing">&nbsp; &nbsp; &#5852; User Stories</a></br>
  <a href="https://docs.google.com/document/d/1ALGz_n_w2ro7ABXJRM1wrGTiiZpAuS7h_CFbI77kDxw/edit?usp=sharing">&nbsp; &nbsp; &#5852; Database Schemas</a></br><br>
</details>


<details>
  <summary><b>Auth - C#</b></summary><br>
  <span><b>&nbsp; &nbsp; Integrations Team Point of Contact: </b></span><span>Jason Burns</span><br>
  <span><b>&nbsp; &nbsp; Team Leader: </b></span><span>Tanner Percival</span><br>
  <p>&nbsp; &nbsp; &#5852; Team Biographies - Link Pending</p></br>
  <a href="https://docs.google.com/document/d/1Fg3xK7r6AbVOKgL1zoLrj0qWStzJTY22sHFbpZYmt40/edit?usp=sharing">&nbsp; &nbsp; &#5852; Group Agreement</a></br>
  <a href="https://docs.google.com/document/d/16IYEQbwUyXER-93ScNRK_hSLknBF_-xpLE8MxxJ7HzU/edit">&nbsp; &nbsp; &#5852; User Stories</a></br><br>
</details>

<details>
  <summary><b>Languages Used</b></summary>
  <p>&nbsp; &nbsp; JavaScript</p>
  <p>&nbsp; &nbsp; C#</p>
</details>

<details>
  <summary><b>Tools Used</b></summary>
  <p>&nbsp; &nbsp; GraphQL</p>
  <p>&nbsp; &nbsp; Gatsby JS</p>
  <p>&nbsp; &nbsp; D3</p>
  <p>&nbsp; &nbsp; OAuth or Auth0</p>
</details>

---

### Meeting Agendas
[Monday - May 20, 2019 - Scrum of Scrums](https://docs.google.com/document/d/1j5msQK3yvMYcWajPy490xPcdjOC0vuRDdcfY5PRCoec/edit?usp=sharing)
<!-- [Tuesday - May 21, 2019 - Scrum of Scrums]() - Link Pending
[Wednesday - May 22, 2019 - Scrum of Scrums]() - Link Pending
[Thursday - May 23, 2019 - Scrum of Scrums]() - Link Pending
[Friday - May 24, 2019 - Presentation Prep]() - Link Pending -->

### Meeting Notes
[Pre-Project Team Meeting](./meeting-notes/pre-project-team-meeting-051619.pdf)
<!-- [Monday - May 20, 2019 - Scrum of Scrums]() - Link Pending -->
<!-- [Tuesday - May 21, 2019 - Scrum of Scrums]() - Link Pending
[Wednesday - May 22, 2019 - Scrum of Scrums]() - Link Pending
[Thursday - May 23, 2019 - Scrum of Scrums]() - Link Pending -->

---
### Resources
<details>
  <summary><b>General Project References</b></summary>
  
  <a href="https://snowflake.medium.com/#1,2,3,2,4,1,1,4,3,2,0,4,2,2,3,0,Cersei%20Lannister,Staff%20Engineer">&#5852; Deployed Site To Be Emulated</a></br>
  <a href="https://github.com/Medium/snowflake">&#5852; Source Code of Deployed Site</a></br>
  <a href="https://codefellows.github.io/common_curriculum/career_coaching/Professional_Competencies">&#5852; Code Fellows Core Competancies to Be Included in Modified Application</a></br>
  <a href="https://docs.google.com/spreadsheets/d/131XZCEb8LoXqy79WWrhCX4sBnGhCM1nAIz4feFZJsEo/edit#gid=0">&#5852; Engineering Competancy Matrix Scoring Guide</a></br>
  <a href="https://docs.google.com/spreadsheets/d/1CzgWm-3V0Jk-84M-uYPgu6QCUdVDnjP8DKf4bb2aTeM/edit?usp=sharing">&#5852; Project Team Google Doc</a></br>

</details>

<details>
  <summary><b>GraphQL Resources (.NET)</b></summary>
  <a href="https://graphql-dotnet.github.io/docs/getting-started/introduction/">&#5852; GraphQL .NET</a></br>
  <a href="https://medium.com/volosoft/building-graphql-apis-with-asp-net-core-419b32a5305b">&#5852; Building GraphQL APIs with ASP.NET Core</a></br>
</details>

<details>
  <summary><b>GraphQL Resources (JavaScript)</b></summary>
  <a href="https://graphql.org/code/#javascript">&#5852; GraphQL Docs for JavaScript</a></br>
  <a href="https://www.howtographql.com/">&#5852; Full Stack Tutorial</a></br>
  <a href="https://dev.to/robmatyszewski/best-resources-to-learn-react-graphql-5dkk">&#5852; Best resources to learn React & GraphQL</a></br>
</details>

<details>
  <summary><b>D3 Resources (Javascript)</b></summary>
  <a href="https://d3js.org/">&#5852; D3 Main Site</a></br>
  <a href="https://medium.freecodecamp.org/learn-d3-js-in-5-minutes-c5ec29fb0725">&#5852; Learn D3 in 5 Minutes</a></br>
  <a href="https://scrimba.com/g/gd3js">&#5852; Free D3 Tutorials by Scrimba</a></br>
</details>

<details>
  <summary><b>Gatsby JS Resources (JavaScript)</b></summary>
  <a href="https://www.gatsbyjs.org/">&#5852; Gatsby JS Website</a></br>
  <a href="https://www.gatsbyjs.org/tutorial/">&#5852; Official Gatsby JS Tutorial</a></br>
  <a href="https://www.gatsbyjs.org/docs/querying-with-graphql/">&#5852; Querying Data in Gatsby JS with GraphQL</a></br>
  <a href="https://www.youtube.com/watch?v=6YhqQ2ZW1sc">&#5852; Gatsby Video Tutorial - 1 Hour</a></br>
  <a href="https://www.youtube.com/watch?v=8t0vNu2fCCM">&#5852; Gatsby Video Bootcamp Tutorial - 4 Hours</a></br>
</details>

<details>
  <summary><b>Auth0 Resources</b></summary>
  <a href="https://developer.github.com/v3/#authentication">&#5852; GitHub REST API v3 Auth</a></br>
  <a href="https://auth0.com/blog/securing-gatsby-with-auth0/">&#5852; Securing Gatsby with Auth0 (needs review)</a></br>
</details>

<details>
  <summary><b>Design Resources</b></summary>
  <p>&#5852; Code Fellows Style Guide - Link Pending</p></br>
</details>
