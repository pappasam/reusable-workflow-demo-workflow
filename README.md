# Reusable workflow demo

This proof of concept demonstrates the usage of GitHub reusable workflows as documented here: <https://docs.github.com/en/actions/sharing-automations/reusing-workflows>

| Role       | Job                  | Repo Link                                                      |
| ---------- | -------------------- | -------------------------------------------------------------- |
| Workflow   | Be used by consumers | <https://github.com/pappasam/reusable-workflow-demo-workflow>  |
| Consumer 1 | Check for hello.txt  | <https://github.com/pappasam/reusable-workflow-demo-consumer1> |
| Consumer 2 | Check for world.txt  | <https://github.com/pappasam/reusable-workflow-demo-consumer2> |

This successfully demonstrates one parameterized workflow file that is re-used across multiple repositories in a GitHub organization (in this case, my default personal organization).
