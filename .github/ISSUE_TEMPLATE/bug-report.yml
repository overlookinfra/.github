name: Bug Report
about: Create a report to help us improve.
title: ''
labels: Bug, bug
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: checkboxes
    id: security
    attributes:
      label: Is this a critical security issue?
      description: If this is a security issue, then please report via email to
security@overlookinfratech.com rather than filing an issue!
      options:
        - label: This is not a security issue.
          required: true
  - type: textarea
    id: description
    attributes:
      label: Describe the Bug
      description: A clear and concise description of what the bug is.
      placeholder: Tell us what you see!
    validations:
      required: true
  - type: textarea
    id: expected-behaviour
    attributes:
      label: Expected Behavior
      description: A clear and concise description of what you expected to happen.
      placeholder: Tell us what should have happened.
    validations:
      required: true
  - type: textarea
    id: reproduce
    attributes:
      label: Steps to Reproduce
      description: Step by step operations to reproduce the behavior:
      placeholder: |
        1. Go to '...'
        2. Click on '....'
    validations:
      required: true
  - type: textarea
    id: environment
    attributes:
      label: Environment
      description: Describe any relevant environment
      value: |
        Version [e.g. 1.27.0]
        Platform [e.g. Ubuntu 18.04]
    validations:
      required: true
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Add any other context about the problem here.
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
