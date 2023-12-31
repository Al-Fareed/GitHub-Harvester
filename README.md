# Repo Fetcher
The Repo Fetcher is a versatile tool designed to extract and showcase the essential contents of a GitHub repository. It seamlessly retrieves and organizes files, excluding specified patterns, to offer a concise overview of the repository's key components. This tool proves invaluable for developers, project managers, and contributors seeking a quick glance at the project structure without the noise of unnecessary files
## Example
from FetchRepo.RepoFetcher import harvest_github_repo

repo_link = "https://your/github-repo/link"
access_token = "your access token" #(if the repository is private)
code = harvest_github_repo(repo_link,branch="main",access_token=access_token)
print(code)