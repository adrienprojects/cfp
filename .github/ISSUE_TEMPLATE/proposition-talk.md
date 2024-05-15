name: Proposition talk
about: NantesJUG CFP
title: Soumission au CFP NantesJUG
labels: new
assignees: adrienpessu


- type: checkboxes
  id: customer-criteria-1
  attributes:
    label: Type de session
    options:
      - label: 'Quickie 20/30 minutes'
      - label: 'Conférence 45/60 minutes'
  validations:
    required: true

- type: input
  id: customer-criteria-2
  attributes:
    label: Titre de la session
  validations:
    required: true

- type: textarea
  id: customer-criteria-3
  attributes:
    label: Abstract
  validations:
    required: true
