name: Bug report
description: Report a bug in the ZK-Neura dApp
title: "[Bug] "
labels: ["bug"]
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: What happened? What did you expect to happen?
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: List the steps to reproduce the issue.
      placeholder: |
        1.
        2.
        3.
    validations:
      required: true
  - type: input
    id: browser
    attributes:
      label: Browser
      placeholder: "Chrome 120, Firefox 122, etc."
  - type: input
    id: os
    attributes:
      label: Operating System
      placeholder: "Windows 11, macOS Sonoma, etc."
  - type: input
    id: wallet
    attributes:
      label: Wallet
      placeholder: "Phantom, Solflare, Backpack, etc."
