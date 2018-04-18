# Planner tasks and plans API overview
Planner provides a simple and visual way for teams to organize their work.  Customers can use Planner to create plans, organize and assign tasks, share progress, and collaborate on content.  Planner provides several interactive experiences including a task board, a charts page, and a schedule view, as well as integrations throughout Office 365.

![alt text](https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-docs/2742019740c2e0bb851dcac3aa643bdc799f0baa/concepts/images/plannerboard.png "Image of Planner board")


## Why integrate with Planner tasks?
Planner provides task tracking capabilities for collaboration experiences in Office 365.  If your scenarios require tracking tasks and organizing work for a team or group of end users, Planner is the right service for you.  Planner integration can help you reach the millions of users collaborating on Office 365. 

### Organize your team’s work
Planner provides a shared space where you can build a team, create tasks, and assign them to others on the team.  Planner makes it easy for everyone to know who’s doing what and if things are on track.  You can update tasks with additional information like due dates, progress, and descriptions, and then further organize tasks with customizable buckets and category labels.   

### Collaborate across Office 365
Planner integrates into collaboration experiences across Office 365.  In addition to Planner web and mobile clients, users can view and update Planner plans and tasks from within SharePoint and Microsoft Teams.  

Planner itself is also powered by the Microsoft Graph and the Office 365 group service.  Files that you upload and attach to Planner tasks are stored in SharePoint.  Planner comments leverage Outlook group conversations under the covers.

Note: Put an image here showing the relationship between Planner and other things

### Automate the creation of plans and tasks
Are you working on repeated process or project type? You can use the Planner API to automate the creation of a plan and a list of tasks.  
 
## Top capabilities

|Operation|URL|
|:--------|:--|
|See all the plans for a group|[https://graph.microsoft.com/v1.0/groups/{id}/planner/plans](https://developer.microsoft.com/en-us/graph/graph-explorer?request=groups/{id}/planner/plans&version=v1.0)|
|See tasks in a plan|[https://graph.microsoft.com/v1.0/planner/plans/{id}/tasks](https://developer.microsoft.com/en-us/graph/graph-explorer?request=planner/plans/{id}/tasks&version=v1.0)|
|See all my tasks assigned to me across plans|[https://graph.microsoft.com/v1.0/me/planner/tasks/](https://developer.microsoft.com/en-us/graph/graph-explorer?request=me/planner/tasks/&version=v1.0)|


## Next steps
{Include a link to the root node of your API set in the v1.0 reference section.}
https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/planner_overview