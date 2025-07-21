name: User Story
description: Create a user story with acceptance criteria
title: "[USER STORY] <Title>"
labels: user story
body:
  - type: markdown
    attributes:
      value: |
        ## User Story
        As a [role], I need [feature] so that [benefit].

  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria (Gherkin format)
      description: |
        Given [some context]
        When [an action is carried out]
        Then [a consequence or outcome should happen]
      placeholder: |
        Given the user is on the login page
        When they enter valid credentials
        Then they should be redirected to the dashboard
    validations:
      required: true
