# Task Description
## API-Based Task Management System
-   In this task, you will be working on developing an API-based task management system using Laravel.
# Features
## User Authentication:
-   Users can sign up with email verification.
-	Users can log in with bearer tokens.
-	Users can log out.
-	Users can edit their information.

## Password Management:
-   Implement a reset-password functionality with email.

## Notification System:
-   Users can receive notifications when tasks or sub-tasks are assigned to them.

## Project Management:
-   Users can create projects (becomes the project owner).
-   Users can access and see their projects.
-   Users cannot search or see other projects.
-   Owner Users have all permissions of the project.
-   Users with permission can edit or delete the project.
-   Project permissions are role-based (e.g., Owner - Member - Viewer).
-   Each project can have many users.
-   Each project can have many tasks.
-   Owner User can request other users to join a project via email.
-   Users must accept to join a project.

## Task Management:
-   Users can see their tasks and other tasks within their projects (implement filter).
-   Users can see their sub-tasks and other sub-tasks within their projects (implement filter).
-   Users with permission can create, edit, and delete tasks and sub-tasks.
-   Each task is related to a single project assigned by the project owner.
-   Each task is related to many users.
-   Each sub-task is related to a single user.
-   Users with permission can assign tasks and sub-tasks to other users.
-   Each task ends only when all of its sub-tasks are completed.
-   Each task and sub-task can have labels.
-   Each task can have many sub-tasks.
-   Each sub-task must have a deadline date.
-   Users with permissions can set status for tasks (e.g., Todo, Doing, Done).

## File Management:
-   Each project and task can have files.
-   Files can only be uploaded or deleted.
-   Users in a project have access to see all project and its tasks’ files.

# Tools and Packages
-   Use the Spatie Laravel-permission package for handling permissions.

# Attention!
-   Firstly fork project from github and develop your project, finally be ready to make a pull request to return back your changes into main project. Don't forget, this step is crucial for you and your project won't be accepted unless you do details of this section!
