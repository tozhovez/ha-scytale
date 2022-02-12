# ha-scytale
# Scytale Home Assignment
Hi there!

In this home assignment you'll be developing a Spark ETL to list all pull requests of two users - one from GitHub and one from GitLab.

### Instructions
1. Fetch a list of all repositories of a user from GitHub and GitLab.
1. For each repository, list all PRs.
1. Store all of the **normalized** results in a JSON file.

#### Note
For normalization, we want a single schema for both GitHub and GitLab.
The following fields are mandatory:
- Owner: The owner of the repository.
- Source: GitHub/GitLab.
- External ID: The id of the repository in the service.
- Name: The repository name.
- Private: whether the repository is private or not.

### What we're looking for
- The code should work!
- Separation of concerns - good directory/file/logical structure.
- Readable code.


---
Please send us a zip file/github repo with your solution when you finish.
If you have any questions please don't hesitate to reach us through email or the phone!

Enjoy!

-- *Scytale R&D*
