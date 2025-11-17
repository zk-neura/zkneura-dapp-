name: Feature request
description: Suggest a new feature or improvement
title: "[Feature] "
labels: ["enhancement"]
body:
  - type: textarea
    id: summary
    attributes:
      label: Summary
      description: Briefly describe the feature you would like to see.
    validations:
      required: true
  - type: textarea
    id: motivation
    attributes:
      label: Motivation
      description: Why is this feature useful? What problem does it solve?
  - type: textarea
    id: proposal
    attributes:
      label: Proposal
      description: How do you imagine this feature working in the dApp?
  - type: textarea
    id: notes
    attributes:
      label: Additional context
      description: Any extra details, references, or mockups.
