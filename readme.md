# Icalia Labs UX Toolkit

This repo contains some Sketch files that we use as a team to collect UI elements and UX flows generated across our projects.

Below you can read basic collaboration rules:

## Editing the master Sketch files

**Make sure your workspace is clean**

In your local repo, in master go to the Terminal and run:

- Git status
- If there are modified changes, evaluate if you need them
- If you need them, move them to a branch with: git checkout -b <new-branch>
- If you don’t need the changes, make sure the Sketch files are in the same state as the most recent commit, with git checkout HEAD -- <complete file path and name>
- Finally, make sure your local repository is currently on the master branch

**Set up your workspace**

- Determine which pull request(s) you are going to manually merge
- Open the pull request single view at Github.com
- Manually download the Sketch binary file (you’ll use the local file on your drive to avoid confusions in your local working repository)
- Preferably, rename the PR Sketch file on your Downloads folder to something like ‘PR SKETCH FILE.sketch’, to avoid confusions
- Open the PR Sketch file
- Go to your local repo, and open the master Sketch file you need to edit

**Sticth everything manually**

- Just common sense here; be extremely careful when editing the master file
- Additions are pretty straightforward, but things get tricky with deletions and substitutions
- If you are not sure you want to edit master files, seek for help from other senior designer in the team

**Keep track of changes**

Since Github can’t see inside our Sketch file, let’s help it a bit:

- Keep track of the artboards you are modifying
- Make sure to export every added / modified artboard as a JPG file for visual reference
- If any artboard gets deleted, delete the JPG file in the repo as well

**Ready to commit to master**

- Once ready, create a detailed commit that explains what PR or issue you are closing
- Start your commit with ‘Closes PR #1 –’, including the proper PR number before the hyphen, and followed by a short description of what the PR did… this will automatically generate a link between the commit and the PR, even if the PR is not merged via GitHub
- After commiting, go to the corresponding PR in the repo, and make sure to add a closing commentm, referencing the specific commit that closes the PR (e.g.: “This PR was succesfully merged with this commit: 27a1373”)


## Contributing with a Pull Request

**Planning your PR**

- It is best if you make a compact PR, focusing on a single flow or element, so the process of review and stitching is more manageable
- Your PR might be about:
	- Introducing a completely new flow to the library
	- Improving an existing flow with new screens or states
	- Editing or improving an existing UI element (or a concise group of elements)
	- Adding a completely new UI element (or a concise group of elements)

**Make sure your PR is about something new**

- Check open PRs, make sure that someone else is not editing the same flow or element that you want to edit
- NEVER edit directly master branch, always branch for new PRs
- When branching, name your branch ‘flow-name-of-the-flow’, or ‘element-name-of-the-element’ so we can easily identify the type of change

**Preparing your PR**

- In your local repository, in the newly created branch, open the master Sketch file you intend to edit
- Proceed with your edits

Since Github can’t see inside our Sketch file, let’s help it a bit:

- Keep track of the artboards you are modifying
- Make sure to export every added / modified artboard as a JPG file for visual reference
- If any artboard gets deleted, delete the JPG file in the repo as well

**Publishing your PR**

- Open the Github repository for the project, and visit the Pull Requests tab; once there, select New Pull Request
- Clarify a general idea of the Pull Request (What does this PR do?)
- List major changes to the Sketch file (specify as well non-visual changes (artboard names, symbols, etc.))
- List the specific master Sketch files you edited, follow this template:
	- Flows/UI-Toolkit-Flows-V_0.1.sketch
	- Artboards added: 11
	- Artboards edited: 0
	- Artboards deleted: 0
	- Edited in Sketch v 50.2
	- Plugin dependency: none
- Include a snapshot of your latest edit (a PNG or JPG will do) 
- Make sure to export the edited artboards as PNG files
- Assign a reviewer for your PR, and
- Publish your PR