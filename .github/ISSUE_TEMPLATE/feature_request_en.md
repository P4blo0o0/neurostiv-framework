name: 💡 Feature Request
description: Suggest a template improvement
title: "[FEATURE] "
labels: ["enhancement"]
body:
  - type: dropdown
    attributes:
      label: For which template?
      options:
        - RAG Assessment Card
        - NTSR Innovation Tracker
        - Role Responsibility Matrix
        - Team Readiness Assessment
        - Weekly Retrospective Guide
        - Emergence Mapping
        - Decision Latency Tracker
        - All templates
        - New functionality
  - type: textarea
    attributes:
      label: Feature description
      placeholder: What improvement are you suggesting?
  - type: textarea
    attributes:
      label: Expected benefit
      placeholder: How will this improve work with templates?
