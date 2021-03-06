# Github-Automated-Build-Versioning-Actions

- This is a sample repository to demonstrate a basic example of automating the process
of build versioning and release creation.

- On each push to the master/main branch, a Github Action is triggered to derive the next
semantic version based on the conventional commits' history.

- This version is then applied to the docker image as a tag, which is pushed to the repo
described in the Action.

<br>

## Observations:

- The video that explains this repository is here: [Automated Build Versioning With GitHub Actions and Conventional Commits by Roman Ivaniuk](https://youtu.be/jq3ruE-Coes)

- Original repository: [RollerKnobster/SS-Actions-Auto-Version](https://github.com/RollerKnobster/SS-Actions-Auto-Version)
