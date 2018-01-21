---
layout: slide-deck
title: "Planning software"
desc: "An overview of the Agile development process, parts we’re going to use, and how we’ll use GitHub as project management software."

slides:
  - type: super-big-text
    content: |
      **Planning software**

  - content: |
      ## Agile practices

      - Focus on users & customers
      - Reorient when requirements & people’s minds change

      ### Methodologies

      - **Scrum**: Small features, completed in a set timeframe, assigned to a single person
      - **Kanban**: A visualization system for tracking task flow

  - content: |
      ## Sprints

      *Taken from Scrum*

      1. Start by meeting to define deliverables
      2. Determine the due date for all the deliverables
      3. Assign each deliverable to a single person

      *We’ll follow a 1-week schedule*

  - type: figure
    image: sprint-flow.svg
    caption: "*A simplified sprint flow*"

  - content: |
      ## Sprint visualization

      *Taken from Kanban*

      1. Create new board for the sprint
      2. Put all the tasks into the **“To do”** column
      3. When a task is underway, move to **“In progress”**
      4. When a task is complete, move to **“In review”**
      5. When approved, move to **“Done”**

  - type: figure
    image: task-board.svg
    caption: "*An example task board*"

  - content: |
      ## GitHub project management

      *We can do all this within GitHub’s tools!*

      - **Issues** — tasks: categorized, assigned to people
      - **Milestones** — sprints: group issues & assign a deadline
      - **Projects** — visualization: create & automate boards

      *And store our code in the same place!*

  - type: figure
    image: "labels.png"
    caption: "GitHub Issue labels"
    notes: |
      - **blocked** — (yellow) something held-up by another task, awaiting something else to be completed; technical debt: code that needs to be written better

      - **bug** — (red) critical, something broken, something needs fixing

      - **content** — (purple) creation, writing, acquiring, editing written text content

      - **design** — (blue) graphic design, UX, illustration, preparing assets

      - **dev** — (dark blue) writing code, debugging, maintaining code

      - **enhancement** — (green) something to be added, new, not fully specified yet

      - **product** — (dark green) overarching ideas, decisions & discussions

  - content: |
      ## Project boards

      - Create a new “Project” for each sprint (week)
      - Set up automation features so some cards can automatically move

  - content: |
      ## Milestones

      Every sprint (week) create a milestone with a deadline to group all the sprint’s tasks.

  - content: |
      ## Issues as todos

      *Each task is…*

      - Defined in a separate Issue
      - Further broken down within the Issue using lists
      - Assigned to a single individual
      - Assigned to the sprint’s milestone
      - Assigned to the sprint’s project board

  - content: |
      ## Issue or it doesn’t exist

      Slack is ephemeral—if there isn’t an Issue on GitHub, the task doesn’t exist.

      - Slack is for quick questions and starting points
      - Issues are for deep discussions & work definitions

---
