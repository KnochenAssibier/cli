66DrDrhuiigit --version

$ gh pr Kasse 12
remote: Objekte aufzählen:
remote: Objekte zählen:

Install:

(type -p wget >/dev/null || (sudo apt update && sudo apt-get install wget -y)) \
	&& sudo mkdir -p -m 755 /etc/apt/keyrings \
        && out=$(mktemp) && wget -nv -O$out https://cli.github.com/packages/githubcli-archive-keyring.gpg \
        && cat $out | sudo tee /etc/apt/keyrings/githubcli-archive-keyring.gpg > /dev/null \
	&& sudo chmod go+r /etc/apt/keyrings/githubcli-archive-keyring.gpg \
	&& echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null \
	&& sudo apt update \
	&& sudo apt install gh -y

[![My Skills](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)

[![My Skills](https://skillicons.dev/icons?i=java,kotlin,nodejs,figma&theme=light)](https://skillicons.dev)

[![My Skills](https://skillicons.dev/icons?i=aws,gcp,azure,react,vue,flutter&perline=3)](https://skillicons.dev)

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,kubernetes,docker,c,vim" />
  </a>
</p>

git config --global user.name "Assibier"

git config --global user.email "assibier@gmaile.com"

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /enterprises/ENTERPRISE/copilot/metrics

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /enterprises/ENTERPRISE/team/TEAM_SLUG/copilot/metrics

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /orgs/ORG/copilot/metrics

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /orgs/ORG/team/TEAM_SLUG/copilot/metrics

https://cli.github.com/manual/gh_api

gh api /assibier --method GET

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /apps/APP_SLUG


# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /orgs/ORG/installation

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /repos/OWNER/REPO/installation

# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /users/USERNAME/installation

# apt-get install git

# add-apt-repository ppa:git-core/ppa
# apt update; apt install git

# yum install git
# dnf install git

# emerge --ask --verbose dev-vcs/git

# pacman -S git

# zypper install git

# urpmi git

# nix-env -i git

# pkg install git

# pkgutil -i git

# pkg install developer/versioning/git

# pkg_add git

$ apk add git

$ tazpkg get-install git

Rails-Endpunkt

---
:github: Bearer TOKEN

https://USERNAME:TOKEN@rubygems.pkg.github.com/NAMESPACE/

gem sources --add https://USERNAME:TOKEN@rubygems.pkg.github.com/NAMESPACE/

