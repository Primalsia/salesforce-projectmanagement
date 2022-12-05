<p align="center">
<img src="https://i.imgur.com/lJJahXK.png" height="50%" width="50%" alt="Salesforce logo"/>
</p>

<h1>Salesforce - Project Management</h1>
Brief tutorial showcasing the steps I took to create a project management application in Salesforce. <br/>

<h2>Environments and Technologies Used</h2>

- Salesforce
- Lightning App

<h2>Project Management App Steps</h2>

- Schema Builder
- Project and Timesheet Object
- URL-Driven Report Configuration for Projects

<h2>Project Management</h2>

<p>
<img src="https://i.imgur.com/whiLiyM.png" height="80%" width="80%" alt="Schema Creation"/>
</p>
<p>
First and foremost, to lay the foundation of my application, I created an ERD, or an Entity Relationship Diagram to show links between the entities or objects created and the relationship between them, then went on to create the schema. I created two main objects, the project object and timesheet object, and added their various fields or attributes within the Schema Builder within the Salesforce environment.
<br/>
-------------------------------------------------------------
<br/>
An ERD is a logical, visual diagram of entities, such as people, things or objects, and how they relate to each other within a database or system. A data schema is a relational model or diagram as well, however it is used as a blueprint to build a database and show how data will be stored in a database, whether that database is relational or non-relational. An entity relationship diagram is essential because they ultimately tell a story about an entity and can show the various effects on different structures within an entity, and data schemas are just as essential to group logical entities, protect objects, etc.
</p>
<br/>

<p>
<img src="https://i.imgur.com/5OfB25G.png" height="80%" width="80%" alt="Creating Report"/>
</p>
<p>
Using the Report Types in Setup, I created a new custom report type that uses the project and timesheet objects. The reports will basically summarize the time for projects. In the report builder, since it is url-driven, I followed the schema created with the projects selected by ID, or accounts, and with records from timesheets. After, I edited the sharing settings and created the custom tabs. 
</p>
<br/>

<p>
<img src="https://i.imgur.com/OlEWDL2.png" height="60%" width="60%" alt="Creating an App"/>
</p>
<p>
I used the App Manager in Setup, to create a new lightning app and followed through the prompts. I named this application, Projedex.
</p>
<br/>

<p>
Here is my completed project management application called Projedex:
</p>
<p>
<img src="https://i.imgur.com/6pWohub.png" height="50%" width="50%" alt="Showcasing App"/><img src="https://i.imgur.com/Un5iIlo.png" height="50%" width="50%" alt="Projects Tab"/>
<img src="https://i.imgur.com/nGHJczi.png" height="50%" width="50%" alt="Timesheets Tab"/><img src="https://i.imgur.com/xw7H0Rg.png" height="50%" width="50%" alt="Showing Specific Timesheet"/>
<img src="https://i.imgur.com/WeI6ji6.png" height="50%" width="50%" alt="Reports Tab Focusing on Report"/>
</p>
<br/>

<a href = https://trailblazer.me/id/ablanding>Check me out on trailblazer!</a>
