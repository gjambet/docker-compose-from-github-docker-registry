I solved this problem by logging into docker using GitHub username and personal access token as a password with read:packages scope.

Usage:

> docker login -u $GITHUB_USERNAME -p $GITHUB_TOKEN docker.pkg.github.com
> # then docker pull...
