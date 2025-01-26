# Team Documentation

## Our Team
[Will be added in team-members.md]

## Team Rules
[Will be added in team-rules.md]

## Important Links
- [Team Rules](team/team-rules.md)
- [Team Members](team/team-members.md)
- [Git Commands](tutorials/git-commands.md)
- [Workflow](tutorials/workflow.md)
- [Standup Template](meetings/standup-template.md)

## Hjälp kommandon att använda
# Hämta senaste versionen från main
git pull origin main

# Skapa och byt till ny branch
git checkout -b feature/add-word-xyz

# Lägg till ändrade filer
git add .

# Commit med beskrivande meddelande
git commit -m "Add definition for XYZ"

# Pusha branch till remote
git push origin feature/add-word-xyz

# Om det behövs - uppdatera branch med main
git checkout main
git pull origin main
git checkout feature/add-word-xyz
git merge main
