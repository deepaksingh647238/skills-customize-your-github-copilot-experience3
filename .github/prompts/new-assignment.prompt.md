# New Assignment Prompt

## Purpose
This prompt is used to guide the creation of new assignments for the educational portal. It ensures all assignments are consistent, student-friendly, and aligned with learning objectives.

## Instructions
- Clearly state the assignment title and objective.
- Break down the assignment into actionable tasks.
- Use encouraging, clear language suitable for students.
- List requirements as checklists for each task.
- Ensure alignment with project standards and template structure.

## Example Structure

# 📘 Assignment: [Assignment Title]

## 🎯 Objective
[Brief description of what the student will build or accomplish in this assignment]

## 📝 Tasks

### 🛠️ [Task 1 Title]
#### Description
[Description of what needs to be done by the student for this task]
#### Requirements
Completed program should:
- [Requirement 1]
- [Requirement 2]

### 🛠️ [Task 2 Title]
#### Description
[Description of what needs to be done by the student for this task]
#### Requirements
Completed program should:
- [Requirement 1]
- [Requirement 2]

---
agent: agent
description: Create a new programming homework assignment
argument-hint: Provide assignment details
---

# Create New Programming Assignment

Your goal is to generate a new homework assignment for the Mergington High School students.

## Step 1: Gather Assignment Information

If not already provided by the user, ask what the assignment will be about.

## Step 2: Create Assignment Structure

1. Create a new directory in the `assignments` folder with a unique name based on the assignment topic
1. Create a new file in the directory named `README.md` with the structure from the [assignment-template.md](../../templates/assignment-template.md) file
1. Fill out the assignment details in the README file
1. (Optional) Add starter code or attachments if the assignment needs them - add these files to the same assignment folder

## Step 3: Update Website Configuration

Update the assignments list in [config.json](../../config.json) website configuration file to include the new assignment. For the dueDate field, use the current date plus 7 days unless specified otherwise.