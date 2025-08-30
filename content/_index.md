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
      text: "[Workshop Venue TBD]"
      primary_action:
        text: Call for Papers
        url: /#workshop-description
      secondary_action:
        text: Schedule
        url: /#schedule
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark min-h-screen"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-building.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: custom-page-section
    id: workshop-description
    filename: "workshop_description.md"
    design:
      css_class: "bg-white dark:bg-gray-800"
  - block: custom-page-section
    id: call-for-papers
    filename: "calls/call_for_papers.md"  
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"  
     # - block: people
   #   id: speakers
   #   file: speakers
   #   content:
   #     title: "Speakers"
  - block: custom-page-section
    id: schedule
    filename: "schedule.md"
    design:
      css_class: "bg-white dark:bg-gray-800"
     # - block: custom-page-section
   #   id: call-for-reviewers
   #   filename: "calls/call_for_reviewers.md"  
  - block: people
    id: organizers
    file: organizers
    content:
      title: "Organizer Committee"
      user_groups:
        - Organizers
        - Senior Organizers
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    id: advisors
    file: advisors
    content:
      title: "Advisory Board"
    design:
      css_class: "bg-white dark:bg-gray-800"
  - block: markdown
    id: contact
    content:
      title: "Contact"
      text: "We will upload our email soon."
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
---

<style>
/* Make navbar logo larger */
.navbar-brand img,
.navbar .navbar-brand img,
.navbar-brand svg,
header img,
[data-bs-target*="navbar"] img {
  width: 108px !important;
  height: auto !important;
  max-height: 72px !important;
}

/* Hide Privacy and Terms of Service links */
footer a[href*="privacy"],
footer a[href*="terms"],
footer a[href="/privacy/"],
footer a[href="/terms/"] {
  display: none !important;
}
</style>
