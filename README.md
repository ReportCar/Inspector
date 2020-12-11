# Inspector

This was previously a private GitHub for a collaborative potential project that has since been scrapped. The project includes some preliminary code, as well as the ticketing system in place to write the code for the project. It may be picked back up in the future.

### Lifecycle of a ticket

KEY

Steps : Any associated git commands (terminal in this case) | Alternative commands

- Make sure master branch is up to date : git status / git pull (if branch is out of date)
- Create a new branch based on current ticket : (from master branch) git checkout -b NameTicketHere
- You should now be in a new working branch, make your changes!
- Stage files / Commit your changes : git add . | git commit -m "My commit message to describe my work."
- Push those changes to github for a peer review : git push origin NameTicketHere (pushing to the origin of this branch i.e. master)

Should now be done with any git related commands

- Go to https://github.com/ReportCar/Inspector and navigate to the Pull Requests Tab
- There should be a popup, highlighted in a manilla color, with a request to create a new pull request - select this button
- In the PR, best practice is to write a summary of your ticket and the work you had to do.
- Once complete click "Create New Pull Request"
- Assign a peer on this project to review and partake in Quality Assurance checks as outlined by the ticket
- Peer may request changes and inquire about process taken to complete ticket
- Once PR has been approved by peer, merge ticket with main branch (master in this case)
- Ticket is complete
