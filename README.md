github-permanently-delete-git-file-action
=========================================
[![Actions Status](https://github.com/dirkarnez/github-docker-compose-action/workflows/docker-compose-actions-workflow/badge.svg)](https://github.com/dirkarnez/github-docker-compose-action/actions)

### SERIOUS WARNING
USE AT OWN RISK. THE CODE IN THIS REPOSITORY IS FOR **PERMANENTLY** DELETING FILE(S) IN YOUR OWN REPOSITORY OF CHOICE. DO NOT USE TO DAMAGE OTHER'S REPOSITORIES. MYSELF AND ANY CODE IN THIS REPOSITORY (INCLUDING YOUR OWN FORK OF THIS REPOSITORY, WITH OR WITHOUT ANY KIND OF MODIFICATION MADE) DO NOT HAVE ANY RESPONSIBILITY FOR ANY KIND OF DAMAGE / MODIFICATION / ANY OTHER RESULT. I AM IN NO WAY GUARANTEE ANY CODE IN THIS REPOSITORY WILL PRODUCE ANY KIND OF INTENDED / ASSUMED RESULT.

### How to use
1. Fork this
2. Set your own secret `GH_PAT`
3. Edit [.github/workflows/push.yml](.github/workflows/push.yml), replacing environment variables `target_repo`, `target_repo_branch`, `target_file_remove`
4. Commit and github will do the rest!
