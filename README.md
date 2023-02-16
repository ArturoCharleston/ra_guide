# *Guidelines for Research Assistants*

Contents:
1. [Administrative tasks](#1-administrative-tasks)
    1. [Managing project tasks with Asana](#i-managing-project-tasks-with-asana). Setting up Asana, keeping track of work, defining meeting agendas.
        1. [Setting up new projects](#setting-up-new-projects)
        2. [Using sections, columns, tasks and subtasks to keep track of work](#using-sections-columns-tasks-and-subtasks-to-keep-track-of-work)
        3. [Tracking priorities in the admin section](#tracking-priorities-in-the-admin-section)
        4. [Following up on presentation comments](#following-up-on-presentation-comments)
    2. [Managing meetings](#ii-managing-meetings). Preparing agendas before meetings, sending meeting recaps and keeping a record of previous meetings.
    3. [Weekly timesheets and recaps](#iii-weekly-timesheets-and-recaps). Preparing weekly timesheets and recaps.
    	1. [Weekly timesheets](#timesheets)
    	2. [Weekly recaps](#weekly-recaps)
    4. [Professional development meetings](#iv-professional-development-meetings). Regular calls to provide feedback, discuss areas to improve and review graduate school applications.
    5. [Tracking conference and presentation deadlines](#v-keeping-track-of-conference-and-presentation-deadlines). Using [remindR](https://github.com/clandinq/remindr) to keep track of deadlines, mantaining a conference calendar.
    	1. [remindR system](#reminder-system)
        2. [Conference calendar](#calendar-with-conference-dates)
    6. [Partner data requests](#vi-partner-data-requests). Following up with partners on meetings and data requests.
    8. [Holidays & time off](#vii-holidays-and-time-off). Official university holidays, paid time off, and process for scheduling days off.

2. [Keeping files organized](#2-keeping-files-organized)
    1. [General project organization](#i-general-project-organization). Overview of how you should use Dropbox, Github and Overleaf for academic projects.
    2. [Working with GitHub](#ii-working-with-github). Setting up and using GitHub locally and in the server.
        1. [Setting up a new repo on GitHub and cloning locally](#setting-up-a-new-repo-on-github-and-cloning-locally)
        2. [Setting up an existing repo on the server or a new computer](#setting-up-an-existing-repo-on-the-server-or-a-new-computer)
        3. [Updating the GitHub repo](#updating-the-github-repo)
    3. [Working with Dropbox](#iii-working-with-dropbox). Keep a backup of project files and data on Dropbox.
    4. [Working with KLC](#iv-working-with-the-kellogg-linux-cluster-klc-server). Setting up the server and keeping project updated with GitHub.
        1. [Transferring files with FileZilla](#transferring-files-via-filezilla)
        2. [Accessing KLC](#accessing-klc)
        3. [Running scripts](#running-scripts)
    5. [Keeping Github and Dropbox updated](#v-keeping-github-and-dropbox-updated). Update Github and Dropbox with one simple terminal command.

3. [Coding best practices](#3-coding-best-practices)
    1. [Working with EPS figures](#i-working-with-eps-figures)
    2. [Generating different presentation versions](#ii-generating-different-presentation-versions). Simplify generation of multiple presentation versions and presentation updating.

4. [Conducting Surveys](#4-conducting-surveys)
	1. [Pre-fieldwork](#i-pre-fieldwork)
	2. [During fieldwork](#ii-during-fieldwork)
	3. [Post-fieldwork](#iii-post-fieldwork)

# 1. Administrative tasks
## i. Managing project tasks with Asana
We use [Asana](https://asana.com/) to keep track of project tasks, provide updates and follow up on meetings. Before setting up Asana, read the [product guide](https://asana.com/guide/help) and [common questions](https://asana.com/guide/help/faq/common-questions) to understand how Asana works. As a very brief introduction, Asana has five levels of organization:
1. **Organizations**. Your user will be part of the Northwestern Kellogg organization. This is defined by the email address you use, so it is important that you register with your @kellog.northwestern.edu email address.
2. **Teams**. Teams are comprised of groups/sections of tasks (what asana calls "projects") and team members. We will have one team per academic project.
3. **Projects**. Projects are groupings of tasks in similar categories.  For example, we will always have an Admin and Analysis section in our Projects, and these sections are what Asana defines as projects. In the rest of this guide, I will refer to academic projects as *Projects*, and the subcomponents/sections of Asana teams and workspaces as *projects*.
4. **Tasks**. Tasks are individual components of projects that contain deadlines, descriptions and opportunities to comment and upload content. Tasks can be assigned to multiple projects.
5. **Subtasks**. Tasks are subdivisions of tasks that function in the same way, allowing you to set deadlines and update content.

### Setting up new Projects
1. First, download and install [Asana](https://asana.com/). For Asana to function correctly, you must register with your Kellogg email, which will grant you access to the Kellogg organization on Asana. 
2. Create a new team by clicking on **Add Team** in the left panel. We will have one team per Project, and if you're working on more than one Project, you will be able to see all the teams in the same window.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_1.png" align="center" height="30%" width="30%">

2. Write down the name of the Project (preferrably one or two words) and a short description. You can start inviting members at this point, but you will have to add them to each Asana project once they are created.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_2.png" align="center" height="35%" width="35%">
    
3. The next step is to create Asana projects, which will be sections of our Project.
    1. Click on **Create a Project** below the selected team.

        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_3.png" align="center" height="30%" width="30%">
        
    2. Select **Blank project** for project setup.
    
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_4.png" align="center" height="40%" width="40%">
    
    3. Define the section's name (e.g. "Admin"), choose **Board** as the default view, and leave privacy settings as **Public to team**. Click **Continue** to finalize creating this project. If you forget to set this up when creating the project, you can configure Board as the default view in the project settings.
        
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_6.png" align="center" height="30%" width="30%">
        
    4. Click on **Start adding tasks** and **Go to project**.
        
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_7.png" align="center" height="30%" width="30%">
        
    5. By default, the project will have three columns: To do, In progress, and Complete. Add a fourth column called "Archive".
        
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_8.png" align="center" height="50%" width="50%">
        
    6. Once you have set up an initial project, click on the three dots next to the project name and select **Duplicate Project**. Duplicate the project to generate a section called Admin, a second one called Agenda, and a third one called Analysis. These three sections will be the base of the Project, since most tasks will fall into the Analysis category, Agenda is used for meetings, and Admin will contain administrative tasks. More details are explained in the [following part of the guide](https://github.com/skhiggins/ra_guide/#using-sections-to-keep-track-of-different-types-of-tasks).

        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_9.png" align="center" height="40%" width="40%">
        
    7. For each duplicated project, click on the down arrow next to the project name, and change the project's color so that it is easily identifiable.
    
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_11.png" align="center" height="40%" width="40%">
        
    8. Here is an example of how the sections of a Project looks like:
        
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/asana_setup_12.png" align="center" height="25%" width="25%">        
        
    9. Once all projects have been set up, invite all researchers and RAs as collaborators to the team. Once they have accepted your invitation, you can (and should) invite them to join the rest of the projects.  Ask collaborators (by assigning them a first task) to input their full name and a picture so that it's easy to identify task ownership. You can invite new members to a maximum of three projects. You can see who is a member of each project on the left of the search bar: 
    
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/colab_1.png" align="center" height="40%" width="40%">        
        
### Using sections, columns, tasks and subtasks to keep track of work
#### Sections
Keep different types of tasks in separate sections. Most projects will have the following sections:
- **Admin**: This section should contain administrative tasks. For example, writing up presentation comments and organizing tasks in Asana.
- **Agenda**: Keep items to be discussed in meetings in this section. Also, there should be a category (column) titled "Priorities" with the priorities of all the team members. This is explained more in detail in the [next part of the guide](https://github.com/skhiggins/ra_guide/#keeping-track-of-agenda-contents).
- **Analysis**: All analysis-related tasks will be in this section. This should be the center of any project.
- **Presentations**: Tasks for presentations and conferences.
- **References**: Relevant references to keep in mind when writing the paper.
- **Comments**: Presentation comments. More details in the following sections.

Other sections projects can have include:
- Budget
- Grant deliverables
- Surveys

Feel free to set up new sections if necessary.

#### Columns
Most sections should have the following columns:
- **To do**: Tasks that have not been started yet.
- **In progress**: Tasks you are currently working on.
- **Complete**: Recently completed tasks.
- **Archive**: Completed tasks that have been discussed with researchers and whose output has been acknowledged. 

When completing a task, move it to the **Complete** column and add the task to the **Agenda** section to ensure it gets discussed in the next meeting with PIs. If it's a minor task that does not to be discussed in a meeting, you can assign a subtask to a PI so that they review what you've done, or alternatively, tag them in a comment. Once the task has been acknowledged, and if there are no more follow-up tasks that will be assigned to the same item, you can mark it as complete by clicking the check mark button and moving it to **Archive**.

#### Tasks and subtasks
All the work you do can be added as tasks and subtasks. The following is an example of a couple of tasks in Asana:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/task.png" align="center" height="25%" width="25%">

Lengthier tasks should be broken down into subtasks:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/subtask.png" align="center" height="40%" width="40%">

General guidelines for working with tasks and subtasks:
- **Naming**: Tasks and subtasks should have clear, short names that makes it easy to identify them. You can write down a full breakdown of the required task in the description section of the task or subtask. 
- **Deadlines**: When creating tasks, assign them to the main person responsible for completing the task, and assign a deadline. They are generally not hard deadlines, but can help to prioritize and identify tasks that have dragged on for longer than necessary. For tasks assigned to you, if the person creating the task did not put a deadline, set your own deadline to give the researchers a sense of when you think the task will be completed by. Subtasks can also have deadlines assigned to them. 
- **Adding results**: When adding results (graphs or tables), attach them as screenshots or JPG / PNG files, since PDF and EPS files will not show previews. If necessary, you can also attach Excel documents. If the description does not include it, add the reason why the analysis is being conducted, what the hypothesis was being tested, whether the results confirm or reject the hypothesis, and what can be concluded from the results.
- **Likes**: Use the like button to indicate that you've seen a task that has been assigned to you. **Don't forget to like comments to let PIs and other RAs know that you have seen their comments**.

### Tracking priorities in the admin section
The first column in the **Admin** section should be called "Priorities", and will include a task for each team member with their priorities:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/priorities_1.png" align="center" height="25%" width="25%">     

Include as subtasks current tasks by order of priority, with the most important tasks first. Delete subtasks when completed. This is so that it's easier to keep track of current tasks (since most of the time there will be several tasks assigned to you), and that PIs can know what your curent priorities are. **Always keep this section up to date**. Here is an example of a priorities task:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/priorities_2.png" align="center" height="40%" width="40%">     

### Keeping track of agenda contents
The agenda section is used to keep track of current priorities and items to be discussed in each meeting. Start by creating a column for each regular meeting:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_0.png" align="center" height="50%" width="50%">     

Follow these steps to add tasks to the agenda:
1. Click on a task that you want to add to a meeting agenda.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_1.png" align="center" height="25%" width="25%"> 
    
2. Click on **Add to projects** and select **Agenda**.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_2.png" align="center" height="30%" width="30%"> 
  
3. Select the meeting to add the task to.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_3.png" align="center" height="30%" width="30%"> 

4. The other section's color will display in the selected task. For example, this task is in the section **Analysis** and the Admin's section pink color is drawn over the task.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_4.png" align="center" height="25%" width="25%"> 

5. Once you have added all relevant tasks to the agenda, it will be easier to write the agenda email and add the detailed agenda to the Google Docs with detailed agendas and meeting recaps.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/agenda_5.png" align="center" height="25%" width="25%"> 

### Following up on presentation comments
PIs receive valuable comments from conferences where they present their academic projects. Asana can help convert these comments to actionable tasks, and by grouping comments by topic, prioritize which should be worked on first.

1. After each paper presentation, add a task in **Admin** asking the presenter to share the comments from the presentation. If you have the opportunity of being at the presentation, write down _every_ question asked, and who asked the question.
2. Create a document in the Project's Dropbox where you keep all presentation comments (example [here](https://github.com/skhiggins/ra_guide/blob/main/docs/Presentation%20comments.docx)). Color-code comments from PIs and RAs and highlight comments that should become tasks:

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/comments_1.png" align="center" height="40%" width="40%"> 

3. Add comments to the **Comments** section on Asana. Group comments by topic, and make sure to assign actionable comments to the **Analysis** section.

    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/comments_2.png" align="center" height="50%" width="45%"> 
    <br/><br/>
    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/asana/comments_3.png" align="center" height="40%" width="40%"> 
    
4. Once a comment has been dealt with (either task has been done, or PI has responded the comment), move the comment to the **Complete** column in the **Comments** section. Assign the task to PIs so they can review, and once processed, ensure they are marked as complete and moved to the **Archive** column.

## ii. Managing meetings
1.	Send a meeting agenda **at least an hour before each meeting** with detailed items to discuss in the meeting and attaching all content relevant to the meeting. A useful way to remember is to set a calendar event with an email reminder for the agenda an hour or more before the meeting. Keep track of content for each meeting in Asana:
    1. Keep track of agenda items by adding them as tasks in an Asana project titled “Agenda”. 
    2. Make a different section for each recurring meeting, and update tasks with what was discussed in the presentation. 
    3. When tasks are complete, mark as complete and move to a section titled “Complete”.
2.	Send a meeting recap after each meeting with detailed notes about what was discussed in each meeting.
    1. Each item should have a discussion and tasks section.
        1. In the discussion section, write comments when possible as problem + potential solution.
        2. Immediately add items from tasks section to Asana.
    2. Upload summaries to a Google Docs document, and include this link in all recap emails.

## iii. Weekly timesheets and recaps

## Timesheets
All research assistants fill out a weekly timesheet. This is helpful for planning, making sure PIs are optimizing your time and setting realistic expectations about how long different tasks will take. You can start by using the [timesheet template](https://github.com/skhiggins/ra_guide/blob/main/docs/Timesheet_template_individual.xlsx).

### Filling out timesheets
There are two options for filling out timesheets: filling out the timesheet directly or using [Clockify](https://clockify.me/).

#### 1. Filling out Excel timesheet directly
One option is to keep the Excel open and fill it in when you start and stop working on a task. You can use a couple of shortcuts to make filling out the timesheet easier: `Ctrl+;` to enter the current date in a cell and `Ctrl+Shift+;` to enter the current time. 

#### 2. Using Clockify 
[Clockify](https://clockify.me/) is a time tracking app for Mac OS X, Windows, and web browsers. With Clockify, you can register individual entries as parts of tasks and projects, which makes this app easily compatible with the format of timesheets: 
- **Projects**: This field is useful when you want to track your time beyond RA work (for example, to keep yourself accountable when studying for the GRE or working on graduate school applications). You can make a project titled *RA work* and then only keep these entries for the timesheet.
- **Tasks**: This field can be used for project names if you're working on multiple projects (or for multiple PIs), or for individual tasks that group several subtasks if you only work for one PI.
- **Description**: Here, you should provide a short but useful description of the current task you're working on.

	<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/clockify/clock_1.png" align="center" height="40%" width="40%">
	<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/clockify/clock_2.png" align="center" height="25%" width="25%"> 

To download your Clockify entries for last week:
1. First, open https://app.clockify.me/reports/detailed. 
2. Then, select the entries for last week and filter by project or client.
 
	<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/clockify/clock_3.png" align="center" height="35%" width="35%">

3. Afterward, click on **Export** and **Save as CSV**. 

	<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/clockify/clock_4.png" align="center" height="30%" width="30%">

4. Download the [Clockify processing script](https://github.com/skhiggins/ra_guide/blob/main/scripts/prepare_timesheet.R) and update the location of the Downloads folder. 
5. Once you run the script, you can copy and paste the output directly into the timesheet. 

By default, Clockify keeps the filters you used in your last session, so it is easier to download data after doing the initial set-up.

The benefit of using Clockify is that you can easily track time for your other personal projects, whether taking a class or preparing applications. Additionally, you can analyze how you're spending your time, which can help you make necessary changes to your workday.

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/clockify/clock_5.png" align="center" height="60%" width="60%">

## Weekly recaps
You should include timesheets in a weekly email sent every Monday morning recapping what the main things you accomplished during the last week were and your main priorities for the upcoming week in bullet points. Include as the subject of the email: [Name] Weekly email (X hours). Below are a few example emails from other RAs:
### RA working for 1 professor on 1 project
Last week:
1. Worked on grant deliverable: updated prize analyses scripts and wrote the section in Overleaf.
2. Reviewed survey incentives documentation.
3. Updated the tool data.
4. Implemented, tested, and published the set of new questions in Qualtrics. I also updated the English and Spanish versions of the questionnaires.
5. Minor tasks: Assigned tasks to Vicente, asked Nico about Google Ads consultation and posted his answer in Asana, emails with J-PAL, reviewed old budget documentation to switch to the research account after depleting TFI funds, and updated our master budget.

This week:
1. Work on NBER IRB submission.
2. Review the last version of the follow-up survey.
3. Pilot the follow-up survey.
4. Finish all the pending tasks for the prize analysis (review my writing and update scripts).

### RA working for 1 professor on multiple projects
Last week:
1. Project A:
	1. Worked on updating non-adoption calculations (top priority for tomorrow’s meeting)
	2. Worked on updating survey weights
	3. Generated output directories, updated previous tables and scripts
2. Project B:
	1. Set up new git locally in server,
	2. Started replication (currently about 50% through).

This week:
1. Project A:
	1. Update survey weights
	2. Finish updating non-adoption calculations
	3. Finish updating above-below median number of workers heterogeneity
	4. Finish updating Asana with all previous comments
2. Project B:
	1. Finish replication

### RA working separately for multiple professors
Last week:
1. Sean:
	1. Updated survey with profits note and num of employees questions
	2. Tested new way to ask for banks/firms of POS in survey
	3. Updated manual of surveyor
	4. Summarized EMEC scripts
2. Jacopo:
	1. Analyzed the case of dscrgrp variable from ESS
	2. Produced correlation tables (ESS, Gallup)
	3. Produced new graphs about dscr variables

This week:
1. Sean:
	1. Figure out what is going on with the NAs
	2. Add pre-survey questions about finding the owner of the retail
2. Jacopo:
	1. Figure out what is going on with some countries and number of respondents in ESS

## iv. Professional development meetings
We will have regularly scheduled (monthly or quarterly) professional development meetings to provide feedback to each other, help pinpoint strengths I can highlight in a letter of recommendation, discuss areas to improve (which will be a mandatory point in each meeting, so don’t interpret feedback on areas to improve as a bad sign), and check in on the status of your preparation for grad school applications.
 
In general, we can discuss the following things in the meeting:

1. **Graduate school preparation**
    - What classes are you taking/how are they going?
    - Status of GRE/TOEFL/anything else you need to do for grad school applications
    - Give me feedback: how can I do a better job mentoring/supporting you?
2. **RA work**
    - What were you most proud of this month/quarter?
    - What do you think you could improve on?
    - What areas would you like to grow?

By 5pm the night before the meeting, please e-mail me with:

1. Graduate school preparation:
    - An outline of how your graduate school preparation is going (if applicable)
2. RA work:
    1. A brief summary of what you've accomplished in the last month.
    2. Describe areas you can improve.
    3. Discuss things you'd like to grow into.
3. An outline of other issues you'd like to discuss

At the end each meeting, remember to schedule next month's/quarter's meeting. You can set up a repeating Google Calendar event with an email reminder a few weeks before to confirm the date and time.

## v. Keeping track of conference and presentation deadlines
### Reminder system
One important aspect of RA work is keeping track of deadlines related to presentations and grants. Professors must keep track of several deadlines: 
- Applications to dozens of conferences over the course of a single year to present their current work
- Sending paper drafts to discussants on time
- Preparing slides for presentations
- Submitting grand deliverables

Managing this manually is both time consuming and often leads to unwanted errors. I wrote a series of scripts ([remindR](https://github.com/clandinq/remindr)) to help project managers, researchers, research assistants and students keep track of deadlines related to academic projects. This system can send out four types of reminders:
1.	Future conference reminders. These are reminders to check if future conferences have announced details that would allow to track them (deadlines, submission links, and descriptions).
2.	Conference deadlines. Reminders to submit papers or abstracts to conferences.
3.	Upcoming presentations. Reminders for upcoming presentations, including slide submission deadlines.
4.	Grant deadlines. This can be useful both when applying for grants and when submitting grant deliverables.

Follow the instructions on the repo to set up remindR in your computer. The system is easy to set up, works with Mac OS X and Windows, and can be constantly modified when we’re notified of new deadlines. Please confirm with Sean / other PIs whenever you add a deadline to one of the lists. Also, it is important to keep track of the log to see that the system is working smoothly, and raise an issue on GitHub whenever there is a coding issue.

### Calendar with conference dates
Along with this reminder system, you should create a new calendar where you make all-day events for conferences we have applied, are applying to, and are presenting in. This way, we can determine whether there are any overlapping conferences and choose which one to apply to. 

Event titles should begin with **APP:** if applied or are applying to the conference, and **PRES:** if we are presenting at a conference. Include more details in the event description, including the conference website. Below is an example of a situation where having calendar events proved helpful: we found a conflict between two conferences and decided PIs could present in both.

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/calendar.png" align="center" height="60%" width="60%">        

## vi. Partner data requests
Many of our projects will have partners who help us implement the project. It is important to confirm meetings with partners, which might not happen in regular intervals and could be forgotten, and follow up on data requests to keep track of their progress. 

1. **Meetings**. On days with a meeting programmed, send the partner an email in the morning confirming the call. 
2. **Data requests**. 
	1. When a meeting is programmed, include a summary of what was requested in the email confirming the call. When there are pending data requests but no meetings programmed, send weekly emails asking for the status of the data requests. 
	2. Add a task in the "Agenda" section in Asana titled "Current data requests," where you update the status of current data requests each week. You can create a new subtask for every piece of data requested.

## vii. Holidays and time off

### University policies on holidays and time off

- **Paid university holidays**. You can view the university holiday calendar [here](https://www.northwestern.edu/hr/benefits/leaves-holidays/university-scheduled-holidays.html). In cases when you have to work on an official holiday, you can make up by taking an alternate workday off. For example, in your timesheet, you would register the working hours during that day and add a note in the “Time off” sheet that says you have an extra vacation day.
- **Vacation time**. During your first year, you will have 2 weeks of vacation time. After you have completed one year, you will have 3 weeks of vacation time per year. Any week where you want to take a vacation day would have 8 fewer hours of expected work. You can view more details [here](https://www.northwestern.edu/hr/benefits/leaves-holidays/vacation-time.html).
- **Personal floating holidays**. [Personal floating holidays](https://www.northwestern.edu/hr/benefits/leaves-holidays/personal-floating-holidays.html) are available for personal use and may be used as an extension of vacation time. The number of personal floating days available depend on the hire date. Hires from September 1 to November 30 (as it is the case with most RAs) will have 3 personal floating holidays available during the fiscal year (September 1 to August 31). Personal floating holidays unused at the end of the fiscal year are forfeited.
- **Vacation payouts**. Staff members will be paid out their accrued and unused vacation time and personal floating holidays at the termination of their contract. You can find more information about the process [here](https://www.northwestern.edu/hr/benefits/leaves-holidays/vacation-time.html).
- **Sick days**. 15 [sick days](https://www.northwestern.edu/hr/benefits/leaves-holidays/sick-time/incidental-sick-time.html) available per year.

### Process for taking time off
1. Ask for permission to supervisors.
2. Add days off to [WFS](https://www.northwestern.edu/hr/essentials/hr-systems/timekeeping/instructions.html).
3. Forward approval to department manager.
4. Send supervisors a calendar invite for an all-day event titled “RA *name* day off” for the days you will be out.

The process for days off if you are going to make up the hours and not take a vacation day are steps 1 and 3 above.

# 2. Keeping files organized
## i. General project organization
In academic projects, it's essential to keep files synchronized between multiple computers and backed-up over time. This allows to easily share scripts and results with PIs, keep raw and processed data backed up, maintain a record of changes in different files, and permit other RAs and PIs to work on the same papers, presentations and scripts. We accomplish all of these tasks with the help of Dropbox, Github and Overleaf: Dropbox mainly for backing-up data, GitHub to track the history of file changes and update files, and Overleaf to allow PIs to easily modify papers without having to use a Latex processor. This system also integrates with the KLC server for processing large datasets.

Our system works the following way:
1. **Local folder set-up and structure**. For existing projects, you should [clone the repo in your computer](#setting-up-an-existing-repo-on-the-server-or-a-new-computer). If this is a new project, start by setting up a local project folder with the following structure:
    - **admin**: This folder should contain administrative files, for example agreements, contracts, and grant proposals.
    - **data**: Only raw data go in this folder.
    - **documentation**: Documentation about the data goes in this folder.
    - **logs**: Only create this folder when generating logs from running scripts on the server.
    - **paper**: Paper tex and pdf documents.
    - **pictures**: Any pictures to be included in the paper or presentation.
    - **presentations**: Presentation tex and pdf documents.
    - **proc**: Processed data sets go in this folder.
    - **results**: Results go in this folder.
        - **figures**: Subfolder for figures.
	- **tables**: Subfolder for tables.
    - **scripts**: Code goes in this folder
        - **programs**: A subfolder containing functions called by the analysis scripts (if applicable).
    - An .Rproj file for the project. (This can be created in RStudio, with File > New Project.).
    You will normally work in your local folder unless working with large datasets or complex scripts (when you will have to use the server).

2. **Keep files backed-up and updated with GitHub**
    - Git is an open-source version control system that helps track file changes across time. GitHub is a company that hosts Git repositories (project folders), including the full history of each file. For example, for any given script that is constantly synchronized with GitHub, you can access the different versions of the script you had backed up over time. You can learn more about Git and GitHub [here](https://docs.github.com/en/get-started/using-git/about-git). 
    - If you set up a new project folder from scratch, follow the [instructions](#setting-up-a-new-repo-on-github-and-cloning-locally) to set up a new GitHub repo.
    - Every time you are done making important changes to a file, want to back-up your work or share it with another project member, you should [push your changes to GitHub](#updating-the-github-repo). At the same time, during this process you will import the changes made (pushed) by other users to the repository (repo).
    
3. **Back up data with Dropbox**
    - Dropbox is mainly used for backing-up raw datasets. This can help reduce disk usage when working with large datasets, as you can delete the raw dataset from your local `data` folder and still be able to access it on Dropbox. We also use Dropbox for keeping constant backups of results and scripts that can easily be shared with PIs.

4. **Working on papers using Overleaf**
    - Some PIs prefer to work on papers using Overleaf, and it can also be useful to access and edit papers and presentations from any computer. To sync with GitHub, the users who want to make changes on Overleaf must have a Premium Overleaf subscription, either the Standard or Professional plan. Project members that don't need to make changes on Overleaf do not need to have a Premium subscription.
  
5. **Working on the server**
    - When working from the server, you will [set up the GitHub repo on the server](#setting-up-an-existing-repo-on-the-server-or-a-new-computer) and keep scripts and results backed-up with GitHub.
    - Files can be sent (raw data) and retrieved (processed data) using [FileZilla](#transferring-files-via-filezilla)

The system is summarized in the following chart:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/org_map.png" align="center" height="30%" width="30%">        

## ii. Working with GitHub
GitHub is used to help facilitate sharing results and scripts with PIs and other research assistants, ensuring reproducibility of code, and having an up-to-date backup of current work, along with version control.
### Setting up a new repo on GitHub and cloning locally
1. Create new repo on GitHub, including a template .gitignore file. Modify .gitignore file on GitHub to include additional folders and files to exclude from updates: documents, data and certain file types.
2. Type the following commands in terminal:
    1. Change to directory where repo will be cloned 
        ```sh
        cd work
        ``` 
    2. Clone repo
        ```sh
        git clone https://github.com/user123/myproject
        ```

### Setting up an existing repo on the server or a new computer
KLC folders should be set up using Github (as if they were additional computers), so it’s easy to keep track of changes and sync files between the server and your local computer.

#### If there is already a folder set up on the server or computer and that be linked to the GitHub project repo
Type the following commands in the terminal:
1. Change directory to the existing folder
    ```sh
    cd existing_folder
    ``` 
2. Initialize repo
    ```sh
    git init
    ``` 
3. Link to existing repo
    ```sh
    git remote add origin https://github.com/user123/myproject
    ``` 
4. Git fetch using personal access token instead of password (https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
    ```sh
    git fetch
    ``` 
5. Checkout (here substitute main for master if master is name of branch generated on Github).
    ```sh
    git checkout origin/main -ft
    ``` 

#### If there is no folder set up on the server/computer:
Type the following commands in the terminal:
1. Change to directory where repo will be cloned 
    ```sh
    cd work
    ``` 
2. Clone repo
    ```sh
    git clone https://github.com/user123/myproject
    ```

### Updating the GitHub repo
First, modify files locally. Then, type the following commands in the terminal:
1. Change directory to project folder
    ```sh
    cd work/myrepo
    ``` 
2. Add new and modified files
    ```sh
    git add .
    ``` 
3. Review added files
    ```sh
    git status
    ``` 
4. Commit files and add a message
    ```sh
    git commit -m “This message describes what was changed in the current commit"
    ``` 
5. Get most up to date code from remote repo.
    ```sh
    git pull
    ```
6. Push changes to remote repo
    ```sh
    git push
    ```

### Creating a fork of a repo and making a pull request    
To make changes in repos where you are not the collaborator, you need to fork (create your own version of) the repo, make changes, and make a *pull request* to merge these changes back into the original repo. Follow these steps to fork a repo and create a pull request:

1. Install the [GitHub Command Line Interface (CLI)](https://cli.github.com/). If you have [Homebrew](https://brew.sh/) installed (on Mac OS X), you can install by typing on the command line `brew install gh`.
2. [Fork the repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
    ```sh
    gh repo fork https://github.com/otheruser/repo_a
    ``` 
3. Clone forked repo
    ```sh
    git clone https://github.com/myuser/repo_a
    ``` 
4. Change directory to local folder
    ```sh
    cd repo_a
    ``` 
5. Make changes to files locally 
6. Add, commit and push changes. This updates files on your own fork of the repo.
7. Change directory to local folder
    ```sh
    git add .
    git commit -m “Add a message here”
    git push
    ```   
8. Create [pull request](https://cli.github.com/manual/gh_pr_create). Add title, insert details in body (if necessary) and submit pull request. Select other user’s repo as base repo.
    ```sh
    gh pr create
    ```   

## iii. Working with Dropbox
- Keep all raw data backed up in the Dropbox. You should **never** save scripts directly or reference raw data that in the Dropbox project folder.
- The Dropbox folder can also contain administrative files and presentations that are not required in the GitHub.
- All files from the local project folder (the one synced with GitHub) except `data` should be routinely copied from the local folder over to Dropbox to keep a back-up of all files. We accomplish this using a [shortcut](#v-keeping-github-and-dropbox-updated) that substitutes multiple git commands and copies the data to Dropbox.
- For large project folders you will need a Dropbox Plus account. The easiest way to get it is to buy it (choose the “billed yearly” option for the price discount – it costs about $100) and then send the receipt to [Adam Troutman](adam.troutman@kellogg.northwestern.edu) and you will receive reimbursement into the bank account where you are paid by Northwestern. 

## iv. Working with the Kellogg Linux Cluster (KLC) server
Processing of large datasets (dataset size approximating RAM size) should be done on KLC. The workflow is the following:
1. Write scripts locally and push to GitHub.
2. Upload raw files with FileZilla to KLC, update server with scripts using GitHub.
3. Update results produced in server with GitHub.

### Transferring files via FileZilla
You should only upload and download data (both raw and proceessed) via [FileZilla](https://filezilla-project.org/), and keep updated results and scripts using GitHub. To upload new files, you can input the following on FileZilla:
- **Host**: klc.ci.northwestern.edu
- **Username**: Your NetID
- **Password**: Password for your NetID
- **Port**: 22
To upload files, drag to the selected folder on the right pane. To download files, right click download.

### Accessing KLC
1.	If you’re not connected to a network at Northwestern, use [GlobalProtect](https://kb.northwestern.edu/page.php?id=94726) to connect via VPN.
2.	If you have a Mac, open the terminal. If you have Windows, first install Cygwin so that you can use Linux commands from the command line, then you can open the command line with Windows+R, type cmd, Enter.
3.	In the terminal or command line, type:
    ```sh
    ssh <netID>@klc.ci.northwestern.edu
    ```
4.	Enter the password you created for your netID.
5.	Now you should be connected to KLC. 

### Running scripts
Once you have (1) set up GitHub to work with the KLC folder, (2) uploaded necessary data files, and (3) updated scripts using GitHub, there are two ways to run scripts on the server:
#### Running files with a 00_run script and no visible output
This first version will generate logs and return the command line for other work.
```sh
cd path_of_project_folder
module load stata/17 # or module load R/4.0.3 [or latest; check what’s available with module avail R]
nohup R CMD BATCH --vanilla -q scripts/00_run.do logs/00_run.log & # Nohup is so that if you get logged out the script keeps running.
```
#### Running do files (Stata) with visible output
The second option will display the output on the terminal.
```sh
cd path_of_project_folder
module load stata/17
stata-mp
# Set base directory and relative file paths
do scripts/myscript.do
```
## v. Keeping Github and Dropbox updated 
- We use Dropbox as a backup folder and to easily share files with PIs. Since copying files manually to update the Dropbox is a tedious task, and we are interested in mantaining the folder up to date, we developed a shortcut that substitutes multiple git commands and copies the data to Dropbox. This reduces the time necessary to update the git (making it easier to make multiple commits and keep the git up to date), and makes it much easier to keep Dropbox in sync with the git (instead of having to manually copy files every time you make a commit).
- Files we only want in Dropbox and not in the git (for example, admin files) will not be modified by this system, as they are never involved in a commit.
- Processed data will also not be linked to Dropbox. Anyone who needs to have the processed data will need to run the scripts to obtain the data in proc/ on their local git folder. 
 
### Setting up and running dual Github-Dropbox updates
1. Download and edit Github to Dropbox backup script.
    1. Download the file [github_to_dropbox.R](/scripts/github_to_dropbox.R) and put it in your local project folder inside /scripts/programs/.
    2. Update the path of the Dropbox folder where files should be routinely backed up to.
            
	    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/gh_db_1.png" align="center" height="60%" width="60%">

2. Add shortcuts to bash profile.
    1. Open a new terminal window and edit the bash profile:
        ```sh
        vi ~/.zprofile
        ``` 
    2. Insert at the bottom of the bash profile the following lines:
		```sh
		function logupdate () {
		    echo "********Pull from repo********"
		    git pull
		    echo "********Push recent changes to repo********"
		    git push
		    echo "********Export commit to log********"
		    echo "Generating log..."
		    git log --name-status HEAD^..HEAD > "$(pwd)/git_log.txt"
		    echo "********Update Dropbox********"
		    echo "Updating files on Dropbox..."
		    Rscript $(pwd)/scripts/programs/github_to_dropbox.R
		}
		
		function gitcommit () {
		    echo "********Adding all files to commit********"
		    git add .
		    git commit -m $@
		    logupdate
		}
		``` 
		The first function pulls and pushes a recent commit, generates a log of this commit, and mirrors the same changes on Dropbox. The second function adds all files to the commit and runs the first function. To add only certain files to the commit, do the commit manually  (`git add file_special; git commit -m "Upload only one file"`) and the run `logupdate`.

    3. Save the bash profile (press Escape, type :wq, and hit Enter)

3. Make changes and run Github - Dropbox dual backup shortcut. Remember to change directory to the desired project folder.
    ```sh
    cd project_folder
    gitcommit "My first commit with the shortcut"
    ``` 
    
    <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/gh_db_2.png" align="center" height="80%" width="80%">
	    
# 3. Coding best practices
## i. Working with eps figures
Working with .eps files is useful because of their high resolution and ability to modify them. However, Latex can only compile PDF files, so we must use the package `epstopdf` to convert files automatically to .eps when compiling. Sometimes, the `epstopdf` package will not generate a PDF file. The following steps have been useful to solve this issue:
1.  Use script [gen_figures.R](https://github.com/skhiggins/ra_guide/blob/main/scripts/gen_figures.R) to make a list with all .eps files included in the folder /results/figures, and generate a .tex document with all of them.
2.  Force full typeset this document to convert all eps figures to PDF.

## ii. Generating different presentation versions
When presenting papers at academic conferences, we will have to generate multiple versions of presentations with different lengths, changing which slides we include in the main presentation and which we send to the appendix. The following system generates multiple versions of presentations while keeping them all up to date with the latest content and reducing the need for making manual changes:

1. **Update master presentation**. 
    - Generate a "master presentation" with all of the slides that can be included in the different presentation versions.
    - To modify a slide for all presentations, make changes in the master presentation. 
	- Keep all slides clearly labeled, with labels defined as *group*_*slidename*. For example, a slide in the model section could be labeled *model_introduction*, and a slide in the results section discussing takeup *takeup_overall*. Labels have to be included in the line immediately following `\begin{frame}`:
		```latex
		\begin{frame}{Effect of Reminder by Offer Value}
			\label{s:takeup_beta_rem_short_byfee}
		```
    - Insert all buttons to slides that could or will be in the appendix in the master presentation. Buttons reference slide labels.
    	- To insert a button, define the following button functions in the preamble of the document:
    		```latex
			\newcommand{\inlinebuttonto}[2]{%
				\hyperlink{#1}{\beamergotobutton{#2}}
			}
			\newcommand{\buttonto}[2]{%
				\centering
				\hyperlink{#1}{\beamergotobutton{#2}}
			}
			```
		- The first type of button can be used to insert a buton right after a sentence:
			
			```latex
			\item<+-> Anticipated reminders do not reduce initial take-up
				\begin{itemize}
					\item Evidence of overconfidence about memory \inlinebuttonto{s:model_predictions}{Model predictions}
				\end{itemize}	
			```
			
			<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/pres_tex_4.png" align="center" height="70%" width="70%">

		- The second type is for creating links in the bottom of a slide:

			```latex
				% Buttons
				\vspace{.5\baselineskip}
				\buttonto{s:takeup_beta_dl_short}{Pooled across value of the offer}
				\buttonto{s:takeup_beta_dl_short_openemail_byfee}{Opened first email}
				\buttonto{s:takeup_dl_long_byfee}{Longer-term take-up}
			\end{frame}
			```
			
			<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/pres_tex_5.png" align="center" height="70%" width="70%">
			
        - If a slide is included in the main part of the presentation, any buttons from other slides in the main presentation to that slide will be removed. For example, if slides A and B are included in the main presentation, they will not have any buttons referencing each other. If slide A is in the main presentation and slide B is in the appendix, buttons from slide A to B and slide B to A will not be removed.
	    

2. **Define which slides to include in main presentation and in presentation appendix**. 
	- If this is the first time using this system, run script [presentation_versions.R](https://github.com/skhiggins/ra_guide/blob/main/scripts/presentation_versions.R) to generate /presentations/slide_dataset.xlsx. Remember to first update the name of the master presentation (line 25).
	- To define what content will be in a presentation, modify the relevant presentation colum in presentations/slide_dataset.xlsx. For example, the content for the 15-minute version of the presentation is defined in the column titled “15”.  Each slide can be included in the main part of the presentation, in the appendix, or not included at all. To include a slide in the main part of the presentation, mark the slide as 1. To include the slide in the appendix, mark the slide with a 2. To omit the slide, mark the slide with a 0.
	- Both slides included in the main part and in the appendix have the same order as in the master presentation. To update the order, the master presentation must be updated. 
    	    
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/pres_tex_3.png" align="center" height="60%" width="60%">
3. **Update and run the presentation versions script**.
	1. Update the presentation or presentations to modify (line 95) in script [presentation_versions.R](https://github.com/skhiggins/ra_guide/blob/main/scripts/presentation_versions.R).
	2. Run the full script to generate the desired .tex document.
	3. Compile the master presentation and verify that there are no bugs or errors. **Remember to always pull the latest presentation content from Github before compiling the presentation**.
	
4. **Compile the presentation and push changes to GitHub**.

**Note**: The person updating the master presentation should also run the presentation versions script and push to GitHub, to ensure all presentations are kept up to date.

5. **Extra: generating and compiling all presentation versions with a shell shotcut**. 
    1. Open a new terminal window and edit the bash profile:
        ```sh
        vi ~/.zprofile
        ``` 
    2. Insert at the bottom of the bash profile the following lines:
		```sh
		compile_pres () {
		    echo "********Update presentations with latest content********"
		    Rscript $(pwd)/presentations/presentation_versions.R
		    echo "********Compile presentations********"
		    # Change directory to presentations folder
		    cd presentations

		    # Define extensions to delete
		    extensions=(aux bak bbl bcf blg brf dvi fls log nav out snm thm toc xml)

		    # Loop over .tex files in current directory
		    for file in *.tex; do
			# First run
			pdflatex "$file"

			# Run biber
			biber "${file%.*}"

			# Second run
			pdflatex "$file"

			# Delete additional files in current directory
			for ext in "${extensions[@]}"; do
			    find . -maxdepth 1 -name "*.$ext" -delete
			done
		    done

		    # Go back to main directory
		    cd ../
		}
		``` 
		The first part of the function runs the presentation versions script and updates all presentation .tex files. The second part compiles all the presentations and deletes redundant files that were required for compilation. 

    3. Save the bash profile (press Escape, type :wq, and hit Enter)

    4. You can use the shorcut simply by opening a new terminal, switching to the project directory and typing the following commmand: `compile_pres`.

# 4. Conducting Surveys

Some of the projects involve conducting surveys. This section aims to outline the general process of conducting surveys. The most important thing to keep in mind is that **each survey is unique**. This means that while there is a general process, each step should be analyzed and evaluated within the context of each survey. To make it easier to identify parts of the process, you can divide it into three main parts: pre-fieldwork, during fieldwork and post-fieldwork.

## i. Pre-fieldwork

**Project organization**

- Folder structure
  - It is important to have a defined folder structure for the project, saved in either Dropbox or Box (for easy encryption using Boxcryptor). This is to ensure easy collaboration with team members that may not be in close proximity, and to ensure that project files are organized in an easily understandable structure
  - A sample project structure folder from IPA looks like this:

	<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/conducting_surveys/folder_structure.png" align="center" height="70%" width="70%">

- 01\_Project development is for storing proposals, contracts, and concept notes for the project prior to its start.
- 02\_Project and Survey Management is for storing timesheets, deliverables.
- 03\_Project Finance is to store files pertaining to budgets, expenses and financial reports.
- 04\_Research Design is to store articles, pre-analysis plan materials, and anything pertaining to the design of the project.
- 05\_Intervention is for files regarding the intervention. If the intervention requires a data workflow (such as with SMS/encouragement design projects), It could be put in here, encrypting the folders with any PII so only team members with PII access can use these files. Other files that can be stored here are Meeting minutes with partners, design files for the intervention (presentations, images, etc).
- 06\_Human Subjects is for files regarding IRB. The original application, and any subsequent amendments, should be stored in separate folders for ease of navigation.
- 07\_Questionnaires & Data is to store all the items pertaining data collection. This is arguably the most important folder in your project structure, as it will contain the survey materials (training materials, questionnaire, survey programming), the survey data, and the survey data workflow files (cleaning, quality checks, anonymization). At least three subfolders should be had within this folder, for the questionnaire, the logistics/training files, and data and analysis. Within data and analysis, an organized folder structure for each round of data collection (baseline, midline, endline, etc.) will be key in ensuring data security and easy collaboration with the rest of the team. A proposed structure from IPA is as follows: Note the Rproj file in this folder, for usage of the here package in R. For python users using Spyder, the project .spyproject folder should also be set at this level. Most likely, folders rawdata, dtafiles, and proc will be encrypted. It is recommended that data with identifiable information is not stored anywhere outside these folders, to minimize the copies of identifiable data in the project folders and the chances of a data security breach.

- 08\_Analysis & Results is a folder where de-identified (clean) data should be stored, to conduct analyses for the final deliverable of the project (working paper). Data would come from the final cleaning file (do file, python or R script) to a similar folder structured as seen above, but simplified to data (no rawdata), analysis files (dofiles, scripts) and outputs(tables, graphs, proc). That way, a shareable, replicable analysis package can be prepared to accompany the project's working paper while ensuring data security. A proposed data flow would be as follows:
    - Survey raw data is downloaded into the rawdata folder is 07\_Questionnaires & Data
    - Survey data is processed (through do files or scripts) and de anonymized
    - From the processing files, the de-anonimized data is exported to 08\_Analysis & Results\data
    - Analysis scripts can be prepared starting from 08\_Analysis & Results\data to produce the results of the project
- 09\_Outreach, is to store files pertaining to dissemination of results. Thai folder serves primarily to store pictures of the project for use in dissemination materials.
- 10\_Field manager is for survey productivity projections and other smaller documents pertaining to data collection. This folder can be ignored and its contents be included in 07\_Questionnaires & Data, in the subfolder for logistics and training.

**Tasks organization**

- The project needs to have a tool for delegating and tracking the completion of project tasks.
- For Sean's projects this should be using Asana, but a simple todo list, deadlines, and gantt chart, which can be prepared through excel, should be the minimum.
- Minimum tasks for a survey project, roughly in chronological order (many of these can be done simultaneously):
  - Finalize questionnaire.
  - Translate survey in local language.
  - Program survey.
  - Encrypt SurveyCTO forms.
  - Submit IRB protocol.
  - Bench test survey.
  - Hire supervisors.
  - Pilot survey.
  - Hire enumerators.
  - Set up field manager budget, payroll system, per diem, and incentives.
  - Create field protocols and survey manual.
  - Create safety and security plan for field staff.
  - Program backcheck survey.
  - Set up backcheck randomization.
  - Set up high frequency checks.
  - Create action plan for HFCs and BCs.
  - Create training materials.
  - Train survey team.
  - Setup devices with programmed survey.
  - Establish reporting system for PIs.
  - Implement false launch and implement changes to team and/or survey.
  - Implement soft launch and implement changes to team and/or survey.
  - Accompany enumerators in first week.
  - Spot check enumerators.
  - Run HFCs.
  - Conduct backchecks.
  - Provide field team feedback based on data.
  - Download and clean survey data.
  - Close SurveyCTO server.
  - De-identify data.
  - Backup project folders and data.
  - Close IRB.

### I. Designing the survey 

- Before starting to write a draft, keep in mind the following:
  - Purpose of the survey: you only want to pose questions that are actually aligned with the purpose of the survey. No more, no less.
  - Characteristics of the sample: Since you are asking people, you should know their characteristics and their context. You cannot ask people their experience with snowy weather if they live in the desert.
- Prepare a draft of the survey:
  - Create the draft in a word document that includes the _track changes_ option. This is helpful because the draft will have a lot of changes that can be approved or discarded.
  - Structure the draft as follows:
    + Introductory speech: It should include the purpose of the survey and why we are interested in surveying that person.
    + Informed consent: It should include the information that IRB boards ask every study to tell to their participants. It also includes their authorization or agreement to participate in the study. Also, it may include their authorization to record them for quality check purposes.
    + Questions: There are several types of questions, the best way to ask a question depends on the answer you want to get.
    + Concluding comments: After all the questions have been asked, there should be a concluding section acknowledging the person's participation in the study and, if applicable, about delivering the compensation for having participated.
  - All sections and questions should be numbered, this makes referencing questions easier, e.g., A.1., B.2., C.3.
  - Note that the wording of questions may change and new questions may be added even when data is already being collected.
- Conduct bench tests: One common practice is to conduct bench tests, which consist of surveying other RAs or people you know to check if the proposed questions in the draft 1) make sense, 2) are efficiently worded, 3) actually ask what you want to ask and 4) are sorted correctly. At this point of the process, a bench test will serve as a preliminary test.

### II. Programming the survey in SurveyCTO 

Once the draft has been tested enough times, it is time to program it using SurveyCTO. SurveyCTO is a platform that allows people to collect high-quality data using mobile phones, tablets, or computers—even offline. For more information, visit [https://www.surveycto.com/](https://www.surveycto.com/). Usually, programming the survey is a cyclical stage.

- Open a server in SurveyCTO: note that there are free and premium servers in the platform. For the purpose of draft and piloting, you can use a free server.
- It is highly recommended to program it using the excel template, it makes editing easier.
- Name variables as question numbers. Ensure that the paper questionnaire is numbered _section.question number_. Using question numbers allows to more easily sync changes between paper and programmed survey versions, also Stata has a 32 character limit, ensures we do not go over and have truncated variables.
- SurveyCTO works closely with Stata, so for R users, do not divide section and numbers with periods (.). If imported into Stata periods are ignored as separators, always use underscore(\_).

Once you have completed the survey programming, you should perform bench tests with the fieldwork team (field coordinator, supervisors, and surveyors) as well. It is important that all the team practice as they are going to conduct the survey. At the end of them, you should have a well-tested instrument. You may have found some typos, sentences that could be better explained, and perhaps questions that need more context. It is way preferable to find these opportunity areas before starting fieldwork.

### III. IRB

An Institutional Review Board (IRB) is an administrative committee that provides ethical and regulatory oversight of research that involves human subjects. For the case of surveys, it is always necessary to have an IRB involved. Note that for internationally conducted surveys, some local regulations may apply. Most commonly IRB will be approved by the university (in Sean's case, Northwestern - [https://irb.northwestern.edu/submitting-to-the-irb/eirb/](https://irb.northwestern.edu/submitting-to-the-irb/eirb/)). If the project is managed by IPA, IPA has its own IRB that can provide this service.

Each project must have an IRB approval, whether it is just one or many surveys. In order to have an approval, you must submit a series of documents that show the purpose of the study, and the study itself. The main documents that should be submitted to IRB are:

1. Study protocol: This document is addressed to the IRB. It describes the study, its purpose, targeted sample, and procedures.
2. Consent form: A document that explains the participants all the details of the study and asks them to authorize their own participation.
3. Survey: a final draft of the survey in a Microsoft Word format. It is important to do it in this format because it allows the IRB to track changes if necessary.
4. Other documents may be added to the submission if necessary.

The IRB will review the application and send comments if necessary before the approval. It is important to note that all documents must be consistent. Also note that the actual survey cannot be implemented until the IRB approves it. After the approval, you can request an amendment if necessary. This process takes some time and changes cannot be implemented until the amendment is approved. In some institutions, amendments have a cost.

### IV. Piloting the survey 

Piloting the survey is an essential step in the process. Its purpose is to test the survey out of the sample, so that when the actual sample is surveyed, the survey is ready. Make sure that the survey is already programmed in SurveyCTO. There can be many series of piloting, in line with its purpose.

One thing to measure during pilots is the success rate. Through this analysis, you can be able to identify the reasons why the rate can be low and reinforce strategies to increase it. Also, piloting can define

It is recommended that a final piloting is held right before the actual fieldwork. It is a simulation of what the actual fieldwork would look like. This is the part of the survey where a lot of improvements can be done. Most of the steps that will be described in the fieldwork section should be implemented during the pilot. During this step of the process, dynamics will be designed.

### V. Hiring of field team 

**Hiring supervisors:** Supervisors must have proven data supervisor experience, or extensive survey experience and show aptitude to lead data collection teams and be organized. In particular, supervisors need to be:

- Communicative, able to relay information efficiently to the research team
- Organized, able to assign and follow up on work to their assigned survey team
- Leaders, able to provide advice and resolve any conflicts in the field according to the established survey protocols

Supervisor should be hired ideally before the enumerators, and should be employed during the piloting phase of the questionnaire, to intimately familiarize them with the questionnaire, which will allow them to provide further feedback to the surveyors in the field and grant them more independence when making decisions.

**Hiring enumerators:** Hiring of the field team should be done such that the field team is assembled at most a week before launching field work. This is to ensure that there is sufficient training and filtering processes conducted on the team before field work. If the survey is short (15 min or less), this timeline can be condensed as training time should be shorter. Further, this timeline can be reduced if it is not possible to hire all the enumerators on time. It is important to start training with at least the expected amount of surveyors.

**Surveyor profile:** Work in progress.

## ii. During fieldwork

### VI. Data collection team composition

Having a good task distribution by usage of the team is recommended to avoid burnout, and ensure that protocol is followed for all the activities that happen simultaneously during fieldwork. As a result, solo RA work should be discouraged unless no other alternative is possible.

1. Field work coordinator: this person is in charge of supervising the field team and procures all the material, such as telephones, tablets or uniforms.
2. Human Resources manager: this person is in charge of hiring the field team and deals with the issues that can emerge during the field work and programs payments.
3. RA - data cleaner: this person is in charge of cleaning data from the survey, so that it can be analyzed without issues like typos or coding mistakes.
4. RA - survey programmer: this person is in charge of maintaining the SurveyCTO updated with the last version of the survey.
5. RA - quality controller: this person is in charge of running quality checks and documents mistakes in the field so that the data cleaner can implement those changes.
6. General coordinator: this person manages the budget, coordinates the whole team and serves as a liaison between the team and the PI.

### VII. Quality checks

To ensure that high-quality data is being produced, we must monitor data collection to detect programming errors, surveyor errors, data fabrication, poorly understood questions, and other issues. The two useful tools you must work with to monitor are the **survey tracker** and **back checks**.

a. **Survey Tracker**: It is highly recommended to create a survey tracker on Google Sheets. [SurveyCTO has a functionality](https://docs.surveycto.com/05-exporting-and-publishing-data/03-publishing-data-to-the-cloud/02.forms-to-google-sheets.html#:~:text=To%20configure%20any%20one%20of,Sheets%20and%20Google%20Drive%20accounts.) where you can connect your selected data to a spreadsheet in real time. You can find a template [here](https://docs.google.com/spreadsheets/d/1_9gNi29DZlGjvSPkMg1I5NqQzB8P2BagJ9EB5SXAJpA/edit?usp=sharing).
With it, you will keep track of:
(i) how many responses you obtain daily and the last seven days, (ii) what is the status of each survey, (iii) the distance to the goal at the target level, (iv) the average duration of the survey and its main sections, (iv) the productivity of each surveyor.

Examples where the tracker is useful:
- You observe that you're not reaching the goal in a geographic area or group and time is running out.
  - With survey statuses, you could plan revisiting eligible respondents, for example those who didn't fully reject to participate.
- You observe that a certain surveyor has a survey duration time above the mean or a low response rate.
  - Above all, creating the tracker would help to identify this situation promptly. Once you have identified it, you could do back checks (audits) to identify challenges that the surveyor is facing, plan a strategy to improve, and give useful feedback to do it better.

b. **Back checks**: [Data quality checks](https://www.povertyactionlab.org/resource/data-quality-checks) are important to identify the reliability of the data collected, specifically back checks. We will choose the way in which we want to corroborate that collected responses are reliable depending on survey logistics, budget, respondent availability, respondent fatigue, among others. We could re-interview respondents with a shorter form based on the original, but with fewer questions, or audit the audios of the interviews generated by surveyCTO.

Option 1: Re-interviewing. The questions to be included in this survey must be selected strategically. You should ask the most important questions you want to confirm. We don't want to fatigue respondents. The team that would perform back check interviews should not be the same team conducting the original survey; you may have to hire and train additional staff. As such, back-checking surveys can carry a high cost. One money-saving alternative can be to record telephone numbers of respondents so that surveyors can call respondents instead of traveling to their locations. Visit [J-Pal's research resources](https://www.povertyactionlab.org/resource/data-quality-checks)for more information on this.

Option 2: Audits. The questions to be included in an audit survey could be all in the original survey. The team that would perform audits will listen to the audios and fill out a survey specifically for audits. Remember that people without Human Subjects certification can access a maximum of 20% of all data with PII.

We recommend adding time stamps for the most important questions, or those you want to observe closely, for any reason. Once you collect responses, you could:
- Compare the original data to the audit data and observe if there are any differences.
- Monitor surveyors performance.
- Identify issues during data collection that can't be identified through the survey tracker, such as a poor introductory speech, questions that were not properly asked, or surveyors not making sure they are surveying the right person.

### VIII. Documenting mistakes

Errors in the survey, or data entry errors by the enumerators, should be documented in a google sheet shared with the research team.

The person documenting errors is a team member that is in constant communication with the enumerators, such as a supervisor, or the field coordinator. This allows these mistakes to be documented in a timely fashion. The reporter must have easy access to the internet and a computer to do this. As such, in the case of in person surveys, the reporter will likely be the field coordinator, who should be looped into all communication channels used by the survey team. An Example of the reporting format for survey errors is as follows:
	
<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/conducting_surveys/example_survey_errors.png" align="center" height="70%" width="70%">

Key here is to have the question number, such that the question with issues can be quickly found and dealt with by any member of the team.

For data entry errors, the format for reporting issues is similar:

<img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/conducting_surveys/example_data_errors.png" align="center" height="70%" width="70%">

An example flow for how these formats can be employed is as follows:

- A surveyor finds a mistake in the programming, or makes a mistake in the form.
- The surveyor writes or calls their field supervisor to report the problem.
- The field supervisor confirms the mistake with the surveyor.
- The field supervisor passes on the report to the field coordinator.
- The field coordinator documents the instance in the report on google docs.
- An RA will check the errors, and attempt to fix them.
  - Programming errors will be corrected and a new survey version with the correction will be shared with the team.
  - Data entry errors will be added to a replacements file to make the corrections manually with the raw data.
- If the error cannot be fixed, the RA will discuss with the field supervisor to gather more information and solve the problem reported, or clarify if the issue was due to user error.
- The RA marks the error corrected or not, and provides comments based on this assessment.

This format allows having issues with the survey programming organized in a collaborative environment, where any member of the team can document issues with the survey, and can be particularly helpful with larger survey teams where the amount of feedback from enumerators can be overwhelming.

### IX. High Frequency Checks (HFC)

HFCs are to be run daily (or, with projects of low intensity, every other day), should be reviewed by the RA team daily, and feedback on them (if any) should be prepared for the day after. As a result, it is important to have a dedicated person to run the page and revise the output of these quality checks so that prompt feedback can be given to the enumerators when quality issues arise.

For IPA staff, HFCs are set up using a IPA's internal ipacheck package, which can be used by anyone outside of IPA. This can be set up using Stata (Stata 17 or higher needed at the time of writing), using:
```stata
net install ipacheck, all replace from([https://raw.githubusercontent.com/PovertyAction/high-frequency-checks/master](https://raw.githubusercontent.com/PovertyAction/high-frequency-checks/master))

ipacheck update
```

Using the command ipacheck new, files will create all the files needed to run the HFCs and the necessary instructions on how to feed the inputs. More information can be found in IPA's [Github page](https://github.com/PovertyAction/high-frequency-checks).

J-Pal has worked on a template for using [R](https://drive.google.com/file/d/1f-5SPiGKZqWg70BL9ov9aBKNBJuRPm1d/view) in HFCs.

SurveyCTO also has a version of HFCs that should fulfill the most basic needs of data collection, and are easy to set up. More information on this through this [link](https://support.surveycto.com/hc/en-us/articles/4468397058963-Guide-to-automated-quality-checks).

Broadly, HFCs should check your data for:

- Flag forms with variable outliers that may indicate falsification or quality issues with the surveyors
- Duplicated surveys (if no controls to constrain surveyors from filling forms for already-surveyed IDs are in place)
- Flag incomplete surveys
- Flag surveys that are missing certain key variables that may suggest issues with the survey or the data collection devices themselves
- Flag variables that have all missing values and may be because of a faulty skip pattern in the survey
- Flag "other" answers for multiple-choice questions to assess surveyor quality, or possibly add more answer choices to the questions.
- Flag percentage of non-response answers by enumerator, to assess quality
- Conduct backchecks/audio audits

It is strongly encouraged that RAs use the IPA package as it is complete and provides outputs to easily check responses and/or entire surveys, connecting directly to the SurveyCTO server. If no Stata license is available for RAs, other options for R and Python users should be scoped out. HFCs should **always** be conducted for any data collection effort.

#### **Open-ended and multiple-choice with** **_other_** **option questions**

HFCs produce an output file that gathers open-ended and _other_ responses but you are encouraged to create your own versions. The objective of these files are to make easier to review all responses aiming to categorize them facilitating data analysis. Note that you must review ***all*** the responses.

**(1) Multiple-choice with _other_ option:**


We have identified two reasons why surveyors do not identify respondents' responses in existing choices or categorizations:
- There is no category to which the response belongs 
- The category exists but it is difficult to determine whether the answer given corresponds to one of them at the time of the survey


It is important to supervise periodically, ***at least weekly***, these responses to:
1. Identify if responses belong to any existing category. If so, you have to categorize these responses in the correspondending choice.
2. Identify who are the surveyors that are incurring in the error mentioned before (1.) to give promptly feedback and reduce cleaning efforts.
3. Count how many times responses that don't belong to any existent category are repeating a simmilar topic. If you observe that are repeated at least five times, you have to propose a new category to include it in the survey. 
Each categorization and new category has to be approved by the Principal Investigator.   

Here is an example of a [script that gathers other option responses](https://github.com/skhiggins/ra_guide/blob/main/scripts/survey_other_gathering.R), it is recommended to create your own version as you can customize the output according to your needs. The output of this script is an [excel file](https://github.com/skhiggins/ra_guide/blob/main/docs/other_responses_file.xlsx) in which you should (1) add columns indicating the number and label to which each response belongs, and (2) indicate the responses that repeat topics five times or more. You will share a similar file with the PI for approval. To replace the above categorizations in the data, you can either use the replacements file produced by the HFC or replace it directly creating a script.  

**(2) Open-ended:**


When starting data collection this type of questions have no prior categorization. Sometimes, it is common for participants to give similar answers to a certain question. To see if this happens, you must identify recurring topics mentioned along data collection and propose categories at least ***on a weekly basis***. To do that, you must:
1. Write a script that produces a list of all these questions and their answers. Here is an example of two scripts that produce a list of those questions. The [first one](https://github.com/skhiggins/ra_guide/blob/main/scripts/01a_open_responses.R) produces periodical lists and the [second](https://github.com/skhiggins/ra_guide/blob/main/scripts/01b_open_responses_historical.R) appends those lists.
2. Identify the topics that are being repeated within each question.
3. Count how many times topics are being repeated.
4. Propose categorizations for those who are repeated at least five times. Each category must be approved by the Principal Investigator. [Here](https://github.com/skhiggins/ra_guide/blob/main/docs/open_responses_categorized_for_Sean.xlsx) is an example of a categorized list. Note that the file has two sheets, one for the answers and one for the proposed categories.


They can be addressed in two different ways:
1. If it is still early in the fieldwork, this question can turn into a multiple-choice with other option question. 
2. If you are in the late stage of the fieldwork, the responses will be categorized post-fieldwork. In this case, answers will be recoded using non-PII data.
In either case, you must merge these new categories with the original data collection, so that you have the original question and the new version of the question in the same dataset. Here is an example of a [script that recodes open-ended responses](https://github.com/skhiggins/ra_guide/blob/main/scripts/survey_openended_recoding.R).

### X. Survey Report

Another important tool to ensure that high-quality data is being produced is the survey report. The survey report also helps to visualize how data is behaving, have an idea of responses, have evidence of the functionality of a question and double check the surveyor's productivity. For example, if many people answer "Don't know" to question A.3, it means that question A.3 is probably a bad question.

**Survey report protocol**

In order for the survey report to be helpful, this protocol should be followed:

1. A preliminary version of the scripts should be written before the field-work starts. 
2. Once the field-work starts, the survey report should be updated every certain time. It is reccomended to update the report before every periodic meeting. For example, in the Financial Technology Adoption survey, the report was updated every week.
3. After updating the survey report, share it with Sean and other team members, so that they can take a look at it before a meeting.
4. Read the report and identify strange patterns or answers to the questions and discuss them.
5. Apply the agreed changes to the report.
6. When the field-work ends, produce a final version of the report. This will be useful for further data analysis.


**How to produce the survey report**

Data cleaning is essential to produce the report. This step implies manipulating data to facilitate the production of tables and figures. Usually, data cleaning is done in one script and includes the following three sections: 

1. Basic cleaning of the responses dataset: This section cleans and formats the dataset to have uniform responses. For example, in this section, one can make sure that all columns with dates have the same format.
2. Text Audit data cleaning: Text Audit data is a group of .csv files created by SurveyCTO that include a list of the questions of the survey and a timestamp that indicates the second that have passed since the beginning of the survey until the question's first appereance. This data is helpful to measure duration and if there are any questions that people are slow to answer. In the second case, it could be a red flag.
3. Reshaping data: To make easier the production of tables and figures, it is often helpful to reshape data.

Here is an example of the [script that cleans data from a survey](https://github.com/skhiggins/ra_guide/blob/main/scripts/survey_cleaning.R).

Once the cleaning step is complete, the survey report can be produced. It can be produced in R using markdown or producing the figures and tables, and then building a TeX file. To produce figures and tables, you should first clean data, so that you ensure that you do not have potential errors. Here is an example of a [script that produces a survey report using markdown](https://github.com/skhiggins/ra_guide/blob/main/scripts/survey_report_markdown.Rmd) and a [script that produces figures and tables for a survey report](https://github.com/skhiggins/ra_guide/blob/main/scripts/survey_report.R).
The survey report must include the following:

1. Text Audit Data: This section includes a table for average time in successful surveys, to measure duration of successful surveys and a table for average time in successful surveys per enumerator. Other tables of duration per section can be added.
2. Response Rate Statistics: This section includes tables of response rate in general and per enumerator. Other tables of response rates can be added according to the necessity of each survey.
3. Unsuccessful surveys: Includes a table of reasons for unsuccessful surveys.
4. Surveyor Productivity: This section includes tables per enumerator to visualize their productivity.
5. Results: This section includes three figures per question of the survey. First, a figure showing the results or answers of the question. Second, a histogram of the duration of the question. And third, a figure comparing actual answers with "Don't know" and "Refused to answer".

Here is an example of the [survey report](https://github.com/skhiggins/ra_guide/blob/main/docs/survey_report_anonymized.pdf).

## iii. Post-fieldwork

Work in progress.
