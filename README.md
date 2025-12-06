Task Manager / Kanban Board — README

A simple, clean, browser-based Task Management & Kanban Board built using HTML, CSS, and JavaScript.
All data is saved locally in the browser using localStorage, so your tasks and columns stay exactly the way you left them — even after refresh.

🚀 Key Features
🎨 Color-Coded Tasks (Priority Highlighting)

Each task can be assigned a color label, chosen from a set of quick-select color buttons.
This allows you to:

Highlight task priority levels

Distinguish different task types

Categorize tasks visually

Improve clarity for fast scanning

Every task visibly shows the color on its left border.

📁 Columns for Organizing Categories & Attributes

Tasks can be arranged into different columns, each representing a category, workflow stage, or attribute.

Examples:

To-Do

In Progress

Done

Backlog

Design

Review
…and more.

✔ Add New Columns

You can manually create unlimited new columns to represent new categories or workflows.

✔ Delete Columns

Columns can be removed when no longer needed.

✔ Evenly Spaced Columns

Columns automatically adjust and spread evenly across the screen, even as more are added.

🔀 Drag & Drop Task Movement

Tasks can be easily moved between columns using drag and drop, enabling:

Workflow progression

Categorization changes

Reassigning responsibility

Reorganization

Simply drag the task and drop it onto another column.

📝 Basic Description for Every Task

Each task includes a permanent, always-visible basic description area where users can write:

Summary

Core instructions

Notes

Quick references

This is always displayed and editable.

💬 Expandable Extra Details Section

A major highlight feature:

Each task includes an ℹ️ info icon, which toggles a hidden text box.

This area is perfect for:

Additional context

Technical details

Background information

Feedback

Sub-notes

Comments

Requirements

Multi-line details

This section remains hidden by default, keeping the interface clean, and appears only when needed.

📅 Automatic Start Date (Permanent)

When a task is created:

The system automatically captures the real-time date and time.

This value is permanent, uneditable, and saved forever.

It marks the exact moment the task was created.

This helps teams understand:

How long a task has existed

Historical timelines

When work began

📅 Editable End Date

Each task has a user-editable End Date, allowing:

Setting deadlines

Planning schedules

Tracking expected completion time

The user can adjust this date anytime.

📊 Progress Bar Indicator

Every task has a progress slider (0–100%).

This helps team members:

Signal work progress

Communicate status

Estimate workload

Give a rough visual summary of how far a task has gone

The slider instantly updates and is saved automatically.

🗑️ Delete Mode (Task Deletion System)

To prevent accidental deletion:

✔ A Delete Button activates Delete Mode

When delete mode is ON:

Clicking any task deletes it immediately

Multiple tasks can be deleted at once

Delete mode prevents accidental removal

✔ Delete Columns

Columns can also be deleted manually using the delete-column button.

💾 Automatic Local Storage Saving

All data saves instantly and automatically:

Columns

Tasks

Colors

Titles

Descriptions

Extra details

Progress

Dates

Layout

No database needed — your browser keeps everything safe.

🧱 Technologies Used

HTML — structure

CSS — simple, clean styling

JavaScript — interactivity and dynamic updates

localStorage — save all data locally

No frameworks required.

📌 Summary

This Task Manager app is a simple yet powerful system designed for clean workflow visualization and easy categorization.

With features like:

Color-coded priorities

Multiple customizable columns

Drag & drop movement

Auto-generated creation timestamps

Editable deadlines

Progress indicators

Extra detail sections

Safe deletion mode

…it becomes a lightweight but highly functional productivity tool for individuals or teams.
