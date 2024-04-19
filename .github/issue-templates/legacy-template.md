---
title: Issue created on {{ date | date ('MMM Do at HH:mm:ss') }}
assignees: KemingHe
labels: bug, enhancement
---

<!-- 
RELOCATED from top because bad parser.

./.github/issue-templates/legacy-template.md

Template markdown for creating issues,
for the legacy auto-issue actions.
-->

The full `tools.context.payload` content is listed below:

- Event: {{ event }}
- Sha: {{ sha }}
- Ref: {{ ref }}
- Workflow: {{ workflow }}
- Action: {{ action }}
- Actor: {{ actor }}


- Payload.action: {{ payload.action }}
- Payload.sender.login: {{ payload.sender.login }}
- Payload.pull_request.number: {{ payload.pull_request.number }}
- Payload.pull_request.html_url: {{ payload.pull_request.html_url }}
- Payload.pull_request.body: {{ payload.pull_request.body }}
- Payload.issue.number: {{ payload.pull_request.number }}
- Payload.issue.html_url: {{ payload.pull_request.html_url }}
- Payload.issue.body: {{ payload.pull_request.body }}

- Payload.repository.full_name: {{ payload.repository.full_name }}
- Payload.repository.name: {{ payload.repository.name }}
- Payload.repository.owner.login: {{ payload.repository.owner.login }}
- Payload.repository.owner.name: {{ payload.repository.owner.name }}
- Payload.repository.html_url: {{ payload.repository.html_url }}
