# ProjectGitGud.Malden
A project to help learn git basics and encourage collaborative mission development

First we'll go through the process of getting a shared projects, making some changes and submitting the changes.
You don't need to understand what is going on doing this; we're doing the 'mechanical' stuff for now and will come back and explain it all later.

# Install Git

# (Recommended) Install GitHub Desktop

# Clone this Repo

# Fetch, and pull

# Make the Assigned Changes

# Commit the Assigned Changes

# Push the assigned changes

# Ok, so what was all that about
Firstly we should look at what git is. It's basically software to track and share changes to projects.
GitHub is one site that hosts projects for you, and also gives you a lot of helpful features to help you manage a project.

We cloned the repo, which makes a copy on your computer. We then fetched, which checks for changes. Of course, we only just made the copy so no changes had been made. We then pulled, which adds the changes to your copy. Again, no changes were made. Fetching and pulling before you work is a good habit to have when you are just beginning.

Since we put the mission in the arma missions folder, we just launched arma and edited the mission.

After this, we commit the changes. This tracks a set of changes in git. If we go through and change the spelling on a word in multiple files in a project, we might track those changes in a single commit.
We also used a commit message. *Get in the habit of using short, but descriptive commit messages*. It will help you go back and locate changes later on.

Finally, we push the changes. This updates the remote git repository (GitHub, in this case) with the changes.

At this point other people can clone or pull our changes. It's important to remember committing commits it to your local copy of the project: its not on the internet until you push.

# General Workflow
- if you don't have a copy of a project, clone it
- before starting work, fetch and pull changes. While still learning git, do both even if not necessary.
- make your changes
- every time you've made a group of changes that belong together, do a commit
- once you are done making changes, and after committing the final bit of work, push

If no one works on things simultaneously, things go smoothly as described above.
Git is far more powerful than what we are doing with it here (and we can work simultaneously), but we'll get into that once you are comfortable with this simple workflow.