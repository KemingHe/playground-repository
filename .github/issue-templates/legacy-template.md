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

- Workflow: {{ context.workflow }}
- Author: {{ context.actor }}

The full `tools.context.payload` content is listed below:

- Context.workflow: {{ context.payload }}
- Workflow: {{ workflow }}
- Event: {{ event }}
- Sha: {{ sha }}
- Ref: {{ ref }}
- Payload: {{ payload }}
- Payload.sender: {{ payload.sender }}
- Payload.sender.login: {{ payload.sender.login }}
- Payload.repository.name: {{ payload.repository.name }}
