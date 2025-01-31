## Shell Script Automation

This Bash script retrieves and lists users who have read (pull) access to a specific GitHub repository. It uses the GitHub API and requires authentication via a username and personal access token (PAT).

## How It Works:

Takes repository owner and name as command-line arguments.

Sends a request to the GitHub API to fetch the list of collaborators.

Filters users with read access using jq, a JSON processing tool.

Displays the list of users who have read permissions.

## Usage:

Run the script with the repository owner and name as parameters:

    ./script.sh <repo-owner> <repo-name>

For example:

    ./script.sh SathwikaKarre shell-script-projects
    
It will output the list of users with read access to the specified repository.








