# Lab 03 – Working with Git History, Stashing, and Reverting Commits

## Task 1: Handling Local and Remote Commit Conflicts
- Steps:
  1. Edit README.md remotely and commit.
  2. Edit README.md locally and commit.
  3. Pull, merge or rebase as required.
  4. Push changes.
- Screenshots required:
  - remote_edit.png
  - local_commit.png
  - push_error.png
  - merge_commit.png
  - push_after_merge.png
  - rebase_pull.png
  - push_after_rebase.png

## Task 2: Creating and Resolving Merge Conflicts Manually
- Steps:
  1. Edit README.md remotely and commit.
  2. Edit README.md locally and commit.
  3. Pull with rebase, resolve conflicts, and push.
- Screenshots required:
  - remote_conflict_edit.png
  - local_conflict_edit.png
  - local_conflict_commit.png
  - conflict_push_error.png
  - conflict_message.png
  - resolved_readme.png
  - rebase_continue.png
  - push_after_resolve.png

## Task 3: Managing Ignored Files with .gitignore
- Steps:
  1. Create `textfiles` folder with 3 files.
  2. Commit and push.
  3. Add `.gitignore` and push.
  4. Remove tracked files with `git rm --cached` and push.
- Screenshots required:
  - push_textfiles.png
  - gitignore_push.png
  - repo_still_has_textfiles.png
  - rm_cached_push.png
  - repo_textfiles_removed.png

## Task 4: Temporary Changes and git stash
- Steps:
  1. Create a feature branch, make changes.
  2. Stash, switch branches, return, and pop stash.
- Screenshots required:
  - modified_readme.png
  - checkout_error.png
  - stash_command.png
  - branch_switched.png
  - back_to_feature.png
  - status_clean.png
  - stash_pop.png

## Task 5: Checkout a Specific Commit
- Steps:
  1. View commit history with `git log`.
  2. Checkout specific commit and return.
- Screenshots required:
  - log_before_checkout.png
  - detached_head.png
  - back_to_main.png

## Task 6: Resetting Commits (Soft vs Hard)
- Steps:
  1. Add 2 commits.
  2. Soft reset, verify, commit again.
  3. Hard reset, verify.
- Screenshots required:
  - first_commit.png
  - second_commit.png
  - log_before_reset.png
  - file_before_reset.png
  - soft_reset.png
  - log_after_soft_reset.png
  - file_after_soft_reset.png
  - file_after_hard_reset.png
  - hard_reset.png
  - log_after_hard_reset.png

## Task 7: Amending the Last Commit
- Steps:
  1. Make a small change, commit.
  2. Amend last commit with new change.
- Screenshots required:
  - first_amend_commit.png
  - amend_commit.png

## Task 8: Reverting a Commit
- Steps:
  1. Commit temporary change.
  2. Revert commit safely and push.
- Screenshots required:
  - commit_temp_file.png
  - revert_commit.png
  - revert_push.png

## Task 9: Force Push
- Steps:
  1. Create test branch, commit, push.
  2. Hard reset, force push.
- Screenshots required:
  - new_branch.png
  - force_commit.png
  - push_force_branch.png
  - hard_reset_force.png
  - normal_push.png
  - force_push.png

## Task 10: Running Gitea in Codespaces
- Steps: Fork repo, create codespace, run Docker Compose, setup Gitea, create repo.
- Screenshots required:
  - forked_gitea.png
  - codespace_loading.png
  - docker_up.png
  - gitea_install_page.png
  - admin_setup.png
  - gitea_dashboard.png
  - gitea_new_repo.png

## Task 11: Creating GitHub Pages Portfolio Site
- Steps: Create GitHub Pages repo, push files, confirm live site.
- Screenshots required:
  - github_pages_repo.png
  - local_static_site.png
  - push_static_site.png
  - github_pages_settings.png
  - live_site.png
