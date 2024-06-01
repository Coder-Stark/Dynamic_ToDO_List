# Dynamic To-Do List Application

## Overview

The Dynamic To-Do List application allows users to manage their tasks efficiently. The application is divided into three sections: Pending, In-Progress, and Completed. Users can add tasks, move tasks between sections, edit, and delete tasks.

## Getting Started

To get started with the application, follow these steps:

1. **Install dependencies:**
   ```bash
   npm install
2. **Run the application:**
   ```bash
    npm start
## Application Structure

## Sections

# Pending
1. Contains newly added tasks with a title and description.
2. Each task has buttons to edit, delete, move to In-Progress, or move to Completed.

# In-Progress
1. Contains tasks currently being worked on.
2. Each task has a button to move it to Completed.

# Completed
1. Contains tasks that have been completed, with a timestamp in the format "DD/MM/YYYY, HH:mm".

# Technologies Used
1. ReactJS for building the user interface.
2. LocalStorage for storing tasks data persistently.

## Features
1. Add Tasks: Quickly add new tasks with titles and descriptions.
2. Edit Tasks: Modify task details to keep your list up to date.
3. Delete Tasks: Remove tasks that are no longer needed from any list.
4. Move Tasks:
   1. From Pending to In-Progress or Completed.
   2. From In-Progress to Completed.
5. Completed Tasks: Completed tasks include a timestamp for reference.