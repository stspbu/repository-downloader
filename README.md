**RepositoryDownloader** is a customizable tool for downloading repositories from github by search query.

<hr>

#### Requirements
Python 3.4+

#### Settings
You have to create file "conf/settings.json" with tool settings, see "conf/settings.json.example"

##### Required settings
* repo_query_string — your search query

##### Optional settings
* repo_count — max count of repositories — 10 by default
* repo_dir — output dir for downloaded repositories — working dir by default
* github_token — github API token for more API calls — unset by default
