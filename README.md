# gha-files-changed
* This repository provides functionality to get a boolean response on whether files in a specified `folder_path`
were changed compared to:
  * previous commit on same branch when using PUSH as a trigger
  * target branch when using PULL_REQUEST as a trigger


### How to use it
* [.github/workflows/files_changed.yaml](https://github.com/aseem-hegshetye/gha-files-changed/blob/main/.github/workflows/files_changed.yaml) 
  * This file has the actual code that checks for file changes in `folder_path`
* [.github/workflows/on_push.yaml](https://github.com/aseem-hegshetye/gha-files-changed/blob/main/.github/workflows/on_push.yaml)
  * This file shows how to use file_changed in your gha file for PUSH trigger
* [.github/workflows/on_pr.yaml](https://github.com/aseem-hegshetye/gha-files-changed/blob/main/.github/workflows/on_pr.yaml)
  * This file shows how to use file_changed in your gha file for PULL_REQUEST trigger