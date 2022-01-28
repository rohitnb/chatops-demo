# Chatops Demo

## How does this demo work?

Modify `.github/pr-cmd-approved.txt` with GitHub Handles of approved users to run the relevant commands as a space separated list

Example:

```
hello=user1 user2 user3
bye=user4 user5
```

You can add more commands but remember to add & modify the relevant Actions workflow YAML files. For example, if you have N Pull Request ChatOps commands to run, you should plan for N actions workflows.
