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
	- [ ] Hit `ctrl + p`  or `command + p` and type "Application"
	- [ ] In the command pallete list you should have an option for "Template - Add Application"
	- [ ] The new Application should be generated in your Application folder
- [ ] Review [[Application Overview]] again, the new application should already be in the list

> [!question] Lots of Applications?
> If you work with or need to track state across a lot of applications, you may want to set up subfolders within the Applications folder. You can modify the `Template - Add Application` quick add setting to prompt you for the folder to save the application in. By default, the action will drop a note into the root of the Applications Directory.

> [!important] 
> Weave uses the concept of Applications heavily in a lot of it's templates. If Applications are not relevant to what your doing, consider changing it to a high level organizable unit like "Projects" or "Initiaves". Make sure you update all relevant templates and community plugin settings with whatever you decide to use.

## 3 - Contacts

A contact is someone you interact with in your work environment. If you have meetings with this person, or have tasks with this person, they should be created in the Contacts directory. Spending the small amount of initial time to create the contact, allows you to better track what you are doing with that person, and when you are interacting with them. 

- [ ] Review the metadata for the [[John Smith]] demo contact.
- [ ] If you feel you need further metadata for your contacts, be sure to update the [[Templates/contact]] note to reflect your changes.
- [ ] Pay special attention to the `task_tag` metadata element in the contact. This is how you'll find associated tasks with your contact. When you create a task, be sure to tag the task with the associated person's task_tag.
- [ ]  Try the Quick Add command to create a new Contact
	- [ ] Hit `ctrl + p`  or `command + p` and type "Contact"
	- [ ] In the command pallete list you should have an option for "Template - Add Contact"
	- [ ] The new Contact should be generated in your Contact folder
- [ ] Review [[Contact Overview]] again, the new application should already be in the list

> [!question] Lots of Contacts?
> If you work with a lot of people, or work with people across many different companies, you may want to set up subfolders within the Contacts folder. You can modify the `Template - Add Contact` quick add setting to prompt you for the folder to save the Contact in. By default, the action will drop a note into the root of the Contact Directory.


