# Getting Started

Thank you for downloading Weave! Hopefully this vault template provides inspiration to better your tracking processes for work. This vault is **highly** oppiniated and some of the decisions within may not match your work style. Feel free to adopt the portions that work and discard the rest, everyone's perfect system will look different.

This note aims to provide you with a guided onboarding process to the layout of the vault and how each peice interconnects. A Task list is provided below for you to work through to better understand the design of the system.

Weave uses a large amount of community plugins to streamline repetitive tasks, and provide data views into the notes you generate. Further information and credit to those authors is provided in the github repo for this project.

If Weave helped you, consider giving it a star on github.

## 1 - Overview Files

At the top level of the vault we have the folders that organize our notes, and (excluding this getting started note) 3 Overview Notes to help you gain insight into the current state of your vault.

- [ ] Review [[Application Overview]]
- [ ] Review [[Contact Overview]]
- [ ] Review [[Task Overview]]

> [!tip]
> Consider "starring" the overviews that provide value to you. These overviews look at the entire vault, more targetted data views and lists are generated within notes.


## 2 - Applications

I designed Weave to help me keep track of my software development work, as well as the developers I manage. Within my team, we have several applications that we work against.
Weave uses these "Applications" to help sort your daily log, as well as track tasks and meetings pertinent to the application your supporting. 

- [ ] Change the [[Demo]] Application to something relevant to you.
- [ ] Try the Quick Add command to create a new application
	- [ ] Hit `ctrl + p`  or `cmd + p` and type "Application"
	- [ ] In the command pallete list you should have an option for "Template - Add Application"
	- [ ] The new Application should be generated in your Application folder, with it's own folder matching the application name you provided.
	- [ ] Try adding an application specific note:
		- [ ] This command **MUST** be run from within the application note you want the note added to (example, be inside the [[Demo]] note before running the command)
		- [ ] Hit `Ctrl/Cmd + p` and type 'Application Note'
		- [ ] In the command pallete list you should have an option for "Template - Add Application Note"
		- [ ] Fill out a name and begin adding notes to the application
- [ ] Review [[Application Overview]] again, the new application should already be in the list

> [!important] 
> Weave uses the concept of Applications heavily in a lot of it's templates. If Applications are not relevant to what your doing, consider changing it to a high level organizable unit like "Projects" or "Initiaves". Make sure you update all relevant templates and community plugin settings with whatever you decide to use.

## 3 - Contacts

A contact is someone you interact with in your work environment. If you have meetings with this person, or have tasks with this person, they should be created in the Contacts directory. Spending the small amount of initial time to create the contact, allows you to better track what you are doing with that person, and when you are interacting with them. 

I use the Contacts section to help me remember who and what I did with a person, as well as drive conversation with them. I have all my tasks for each person tagged with that persons `task_tag`. If I'm in a follow up meeting or want to check what I have pending for someone, I can find them and view all tasks related to them.

- [ ] Review the metadata for the [[John Smith]] demo contact.
- [ ] If you feel you need further metadata for your contacts, be sure to update the [[Templates/contact]] note to reflect your changes.
- [ ] Pay special attention to the `task_tag` metadata element in the contact. This is how you'll find associated tasks with your contact. When you create a task, be sure to tag the task with the associated person's task_tag.
- [ ]  Try the Quick Add command to create a new Contact
	- [ ] Hit `ctrl + p`  or `cmd + p` and type "Contact"
	- [ ] In the command pallete list you should have an option for "Template - Add Contact"
	- [ ] The new Contact should be generated in your Contact folder
- [ ] Review [[Contact Overview]] again, the new application should already be in the list

> [!question] Lots of Contacts?
> If you work with a lot of people, or work with people across many different companies, you may want to set up subfolders within the Contacts folder. You can modify the `Template - Add Contact` quick add setting to prompt you for the folder to save the Contact in. By default, the action will drop a note into the root of the Contact Directory.


## 4 - Daily

Daily is where I spend the bulk of my time using this system.  At the top of the daily file is a list of all `Over Due` tasks, something you may want to address today, and if not will be shown again tomorrow. Any tasks due 'today' will be marked in the `Due Today` section, and finally and new tasks you generate should be added to the `New Today` section. There is a hotkey combination that will automatically generate a new task in the `New Today` 

As I do things during the day, I add a note in the Daily Log with a time stamp to help me remember when and why something occured. Meetings you attend are automatically displayed on the day via the Data View plugin. The Daily log and the Applications mentioned above come together in the daily file as I log my actions against specific applications that I am responsible for.

Finally a daily checklist of tasks to complete to stay on top of your system is displayed every day.

>[!tip]
>Everytime you open this vault, you should be directed to your current daily file.
>
>The included community addon `Calendar` is available on the right fly out menu. If you click on a day, it will generate a Daily file specific to that day.

- [ ] Take a look at the [[daily]] template file 
	- [ ] Change some of the demo application names to reflect applications you've added above.
	- [ ] Modify any tasks in the Daily Checklist to better reflect your workflow
- [ ] Pick a consistent numbering strategy for your time stamps if you are going to use them.
	- [ ] I use Military time (i.e. 13:00, 07:00 etc.)
	- [ ] `cntrl + shift + t` or `cmd + shift + t` will insert the current time to help speed up your logging.
	- [ ] You can change this hotkey in Settings -> Hotkeys -> `Natural Language Dates: Insert the current time`
- [ ] Use the hotkey `Ctrl + Alt + Shift + T` or `Cmd + Alt + Shift + T` to bring up an input box to add a task to the current day. You can do this from anywhere in Obsidian, helping to capture tasks quickly.
	- [ ] You can change this keybinding in the Settings -> Hotkeys -> `QuickAdd: Capture - Add to daily task` entry.
	- [ ] Make sure you tag either yourself (using #me) or someone else (using their relvant `task_tag` as your filling out the note so you don't forget who this is for!)


## 5 - Meetings

Any meeting you want to take notes on, or draw reference to in the future should be saved into the `Meetings` folder. A few example templates have been provided in the `System/Templates`  directory. If you consistently attend / host a meeting (like a standup, or a developer meeting) you should template it and add a quick action to create it.

Most of the time, for ad hoc meetings you want to document / remember, the `General` meeting type is appropriate. Don't over automate things, but if you are consistantly creating the same text over and over, it's a good candidate for templating.

- [ ] Take a look at the `meeting` templates in `System/Templates`.
	- [ ] You may want to add your company name into the standup / team meeting.
		- [ ] Or maybe remove it entirely if you only ever work inside your own company.
- [ ] [[meeting_team]] shows an example of a reoccuring meeting every 7 days with the ability to navigate between meetings (assuming they are always x number of days apart).
- [ ] Quick Add is used heavily here to generate a meeting by type
	- [ ] Look at Settings -> QuickAdd and review the templates for each meeting type.
- [ ] Create a team meeting by:
	- [ ] Hit `Cntrl + P` or `Cmd + P` and type out Team
	- [ ] Your top option should be: `QuckAdd: Template - Team Meeting`
	- [ ] Click Enter and begin filling in meeting details
- [ ]  Create a Standup meeting by:
	- [ ] Hit `Cntrl + P` or `Cmd + P` and type out Standup
	- [ ] Your top option should be: `QuckAdd: Template - Standup Meeting`
	- [ ] Click Enter and begin filling in meeting details
- [ ]  Create a General meeting by:
	- [ ] Hit `Cntrl + P` or `Cmd + P` and type out General
	- [ ] Your top option should be: `QuckAdd: Template - Team Meeting`
	- [ ] Click Enter and provide a name to help you remember this meeting (I often just use the title of the meeting from my email)
	- [ ] Begin filling in meeting details
- [ ] Take a look at some of the demo meetings provided to see the interlinking between the application, contact, tasks, and meetings

> [!tip] Lots of Meetings?
> If you (unfortunately) spend most of your time in meetings like me, you might want to subfolder your meeting types. You can modify the `Template - Add <Meeting Name>` quick add setting to save the meeting into a folder specific to it's type, or have the quick add prompt you.