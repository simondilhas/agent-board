# agent-board

Keeps the [Roadmap board](https://github.com/users/simondilhas/projects/7) and the agent labels in sync, every 5 minutes.

| Board column | Label |
|---|---|
| Backlog | no agent label |
| Ready | `agent_ready` (drag here to start the agent) |
| In progress | `agent_working` |
| Review | `agent_finished` |
| Done | issue closed |

Setup: repo secret `PROJECT_TOKEN`, a classic personal access token with scopes `repo` and `project`.
Run it by hand under Actions → "Agent board sync" → Run workflow.
