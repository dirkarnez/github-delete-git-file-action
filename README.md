github-permanently-delete-git-file-action
=========================================
[![Actions Status](https://github.com/dirkarnez/github-docker-compose-action/workflows/docker-compose-actions-workflow/badge.svg)](https://github.com/dirkarnez/github-docker-compose-action/actions)

### How to use
1. Fork this
2. Set your own secret `GH_PAT`
3. Edit [.github/workflows/push.yml](.github/workflows/push.yml), replacing environment variables `target_repo`, `target_repo_branch`, `target_file_remove`
4. Commit and github will do the rest!
