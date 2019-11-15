# Use Ansible to mirror Git repos in multiple locations

Ever have a need to maintain code in multiple Git repositories?<br>
This simple Ansible Playbook can accomplish the task.<p>

To mirror a repo, perform the following:

    1. Add a new "include_task" section in mirror_repos.yml. (Add repo_name and source/dest url's)
    2. Create an empty repo at the destination location.
    3. Run the mirror_repos.yml playbook.

