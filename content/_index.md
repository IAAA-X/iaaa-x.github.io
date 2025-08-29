---
title: 'IAAA Workshop'
date: 2025-08-28
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Information Access in the Era of AI Agents"
      text: Workshop @ ACL 2026
      primary_action:
        text: Call for Papers
        url: /#call-for-papers
      secondary_action:
        text: Schedule
        url: /#schedule
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: workshop-description
    content:
      title: "Information Access in the Era of AI Agents"
      text: "[TODO] Add workshop description here."
  - block: custom-page-section
    id: call-for-papers
    filename: "calls/call_for_papers.md"  
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"  
  - block: people
    id: speakers
    file: speakers
    content:
      title: "Speakers"
  - block: custom-page-section
    id: schedule
    filename: "schedule.md"
    design:
      css_class: "max-w-full bg-gray-100 dark:bg-gray-900"
  - block: custom-page-section
    id: call-for-reviewers
    filename: "calls/call_for_reviewers.md"  
  - block: people
    file: organizers
    content:
      title: "Organizers"
      user_groups:
        - Founding Organizer
        - Members
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    file: advisors
    content:
      title: "Advising Committee"
      user_groups:
        - Frontier Board
        - Main Board
  - block: markdown
    id: contact
    content:
      title: "Contact"
      text: "[TODO] Add contact information here."
---
