# Package Reality Check: privacy policy

Last updated: 3 November 2026. Contact: emilhuseynov1233@gmail.com

Package Reality Check is a Forge app for Jira. It checks whether npm and PyPI packages named in a work item, or sent by an AI
coding agent through its MCP endpoint, exist and look normal.

## What the app reads
- When you open the app's panel on a work item, or ask the Dependency Doctor agent to scan one, the app reads that work item's
  summary, description and comments through the Jira API, using your own permissions.
- When a coding agent calls the MCP endpoint, the app reads the package names or text the agent sends.

## What leaves Atlassian
Only package names. The app asks the public registries registry.npmjs.org, api.npmjs.org and pypi.org about each name it found.
No work item text, user names, account IDs or other personal data are sent anywhere.

## What the app stores
Nothing. The app has no database and keeps no copy of work items, results or requests. Atlassian keeps standard Forge
platform logs for the app, under Atlassian's own privacy policy.

## Your choices
Uninstalling the app from your site stops all of the above. Questions go to the contact address at the top.
