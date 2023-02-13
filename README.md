# CSC4710-Project-4

### Project 4: ToDo List version 4

A web application to store a to-do list.

### Basic characteristics

1. No user identification needed.
2. The current user can see all the tasks.

---

### Tasks

Each task consists of

1. Task description (required)
2. Due date (required)
3. Task category (optional)
4. Priority level (optional) (Values: 1-4, where 1 is the highest priority)
5. Status (active or completed)

(Optional) means is optional to the user. So, the user does not have to provided that information.
However, the database must store that information, if provided.

---

### Categories

Each task category consists of

1. Name
2. Parent category
   a. Another existing category which does not have a parent category.
   b. If the current category is already a parent category of another one, this attribute cannot
   be modified.

---

### Functionalities

1. Current user can create tasks.
2. Current user can mark a task as completed.
3. Current user can create categories.
4. Current user can edit categories (and subcategories).
5. A category may have a parent category. A category with a parent category is called a
   subcategory.

---

### Views or reports

1. The default list view of the application will show overdue tasks and due-today tasks. Tasks will
   be sorted by priority.
2. The user can select a view for only completed tasks on a specific day. Tasks will be sorted by due
   date.
3. The user can select a report for a specific week. This report will show the day and the number of
   the tasks completed per each day and in total.
