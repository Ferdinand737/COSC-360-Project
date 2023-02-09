# COSC 360 Project Proposal

### Team Members

Ferdinand Haaben
Ansyn Neuhaus

### Project
Our project is a disscussion forum website similar to Reddit. Registered users will be able to participate in discussions, unregisterd users will be able to view discussions and admin accounts will be able to moderate user posts.
#### Requirement Lists

##### Front-end requirements

- Hand-styled layout with contextual menus (i.e. when user has logged on to site, menus reflect change).

- 2 or 3 column layout using appropriate design principles (i.e. highlighting nav links when hovered over, etc) responsive design

- Form validation with JavaScript

- Responsive design philosophy (minimum requirements for different non-mobile display sizes)

- Simple discussion (topics) grouping and display

- Navigation breadcrumb strategy (i.e. user can determine where they are in threads)

- AJAX (or similar) utilization for asynchronous updates (meaning that if a discussion thread is updated, another user who is viewing the same thread will not have to refresh the page to see the update)

- Visual display of updates, etc (site usage charts, etc)

- Activity by date

##### Data base requiremetns 

- Data storage in MySQL

- User images (thumbnail) and profile stored in database

##### Back-end requirements

- Server-side scripting with PHP

- Appropriate security for data

- Site must maintain state (user state being logged on, etc)

- Error handling (bad navigation)

- Hot threads/hot item tracking

- Tracking (including utilizing tracking API or your own with - - visualization tools)

- Alerts on page changes

| User features										| User          | Admin		| Non-Regisetered User |
| ------------------------------------------------- |:-------------:| ---------:|:---------------------|
| view reports on usage (with filtering)			|				| &#x2713;	|					   |
| Tracking comment history from a user’s perspective|			    | &#x2713;	|					   |
| Collapsible items/treads without page reloading	|		&#x2713;| &#x2713;	|			   &#x2713;|
| View activity by date								|		&#x2713;| &#x2713;	|			   &#x2713;|
| Search and analysis for topics/items				|		&#x2713;| &#x2713;	|			   &#x2713;|
| Profile images									|		&#x2713;| &#x2713;	|					   |
| Post Discussion Thread							|		&#x2713;| &#x2713;	|					   |
| Delete Discussion Threads							|				| &#x2713;	|					   |



