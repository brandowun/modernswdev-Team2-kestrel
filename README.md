# Team 2 Project - "PawLink"

## Team Members
- Daniel Trimble (dstrimble)
- Billy Spann (billyspann)
- Brandon Wilson (brandowun)
- Elizabeth Lee (elizlee1)
- Mia Diaz Cruz (miadc0117)
- Daniel Cronin (dcronin05)
- Stefany Roman (stefanyromann)

## Tech Stack
- Python
- Flask
- SQLite
- HTML/JS/CSS

## Project Idea
Pet matching app where pet owners build profiles to coordinate park meetups.

## Mission Statement
Our mission is to link pups and people in the real world by simplifying socialization. Matching dogs based on location, size, energy, and temperament, we make community park meetups safer, more predictable, and way more fun. Better matches, better playdates, more tail wags. Welcome to Pawlink.

## Defined roles
PawLink has 2 user roles
Unregistered Users
Registered Users

### Unregistered User
A visitor who has yet to create an account or logged in. They can learn what PawLink is, but unable to create matches or meetups until they sign up

What they can do:
They can view the front pages to see what Pawlink is about and the idea behind it. 
Create accounts which would be sigining up for Pawlink
Log in, if they have an account.

What they can't do:
They can't create or edit a profile
They can't browse or  match with other pet owners
They can't create, join, or view park metups

### Registered User
A pet owner who has created an account and is logged in. They have full access to PawLinks core features.

What they can do:
They can log in and out
Create and edit their profile and dog's profile (location, size, energy, temperament).
Browse and match with other pet owners based on compatibility 
Coordinate park meetups with their matches.
Rate dogs and comment on your rating (possibly???)

What they can't do:
Remove uerses
Edit code via frontend nore backend

## Team Workflow

### Definition of Done

Every pull request is reviewed and approved by a team member who did not write the changes. Each pull request describes what changed and why. A pull request that implements a backlog item links to that Issue, and all acceptance criteria on the Issue are met.

This Definition of Done grows as the pipeline develops: automated tests in Module 6, CI enforcement in Module 7, and static analysis later in the course.

### Communication

Slack (class workspace, Team 2 channel) for async updates and blockers. Google Meet for team meetings. GitHub is the source of truth for work state. Work is tracked through Issue and pull request interaction in comments, reviews and commits.

### Branching Strategy

All work happens on a `feature/`, `bug/` or `docs/` branch. `main` is protected
and accepts changes only through a pull request approved by another teammate.
Branch names start with the prefix and a short description, e.g.
`bug/fix-login-logic-typo`.

| Prefix | Use | Example |
| :--- | :--- | :--- |
| `feature/` | New capability | `feature/user-login` |
| `bug/` | Defect fix | `bug/remove-extra-description` |
| `docs/` | Documentation only | `docs/add-roles-file` |
