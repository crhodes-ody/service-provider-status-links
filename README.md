# True up repository

This PR trues up the repository by adding proper version control hygiene and cleaning up formatting issues. Changes include:

1) Added .gitignore file to prevent IDE and OS-specific files from being committed,
2) Cleaned up README.md formatting by removing empty table rows and excessive blank lines.

Note: The existing .idea/ directory should be manually removed after merging this PR using: `git rm -r .idea/ && git commit -m 'Remove IDE configuration files' && git push`