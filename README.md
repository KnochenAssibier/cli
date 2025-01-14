Dr66DrDrhuiigit --version

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

bundle config https://rubygems.pkg.github.com/NAMESPACE USERNAME:TOKEN

$ gem push --key github \
--host https://rubygems.pkg.github.com/NAMESPACE \
GEM_NAME-0.0.1.gem

gem.metadata = { "github_repo" => "ssh://github.com/OWNER/REPOSITORY" }

source "https://rubygems.org"

gem "rails"

source "https://rubygems.pkg.github.com/NAMESPACE" do
  gem "GEM_NAME"
end


$ rubin -topic public.hello -record "Dragonfly out in the sun you know what I mean"

9:49PM	INFO	rubin/main.go:60	Welcome to rubin  {"version": "v0.0.5", "built": "now", "commit": "7759eb6"}
9:49PM	INFO	rubin/client.go:27	Kafka REST Proxy Client configured  {"endpoint": "https://localhost:443", "useSecret": true}
9:49PM	INFO	rubin/client.go:53	Push record  {"url": "https://localhost.cloud:443/kafka/v3/clusters/abc-r2d2/topics/public.hello/records"}
9:49PM	INFO	rubin/client.go:84	Record committed  {"status": "topic", "public.hello": 200, "offset": 43, "partition": 0}

$ rubin -help

Welcome to rubin v0.1.5 built now by go (b368bf8)

This application is configured via the environment. The following environment
variables can be used:

KEY                          TYPE             DEFAULT    REQUIRED    DESCRIPTION
KAFKA_REST_ENDPOINT          String                      false       Kafka REST Proxy Endpoint
KAFKA_CLUSTER_ID             String                      false       Kafka Cluster ID
KAFKA_PRODUCER_API_KEY       String                      false       Kafka API Key with Producer Privileges
KAFKA_PRODUCER_API_SECRET    String                      false       Kafka API Secret with Producer Privileges
KAFKA_HTTP_TIMEOUT           Duration         10s        false       Timeout for HTTP Client
KAFKA_DUMP_MESSAGES          True or False    false      false       Print http request/response to stdout
KAFKA_LOG_LEVEL              String           info       false       Min LogLevel debug,info,warn,error


$ rubin -help

Welcome to rubin v0.1.5 built now by go (b368bf8)

This application is configured via the environment. The following environment
variables can be used:

docker run --rm ghcr.io/tillkuhn/rubin:v0.1.2 -help

client := rubin.New(&rubin.Options{
	RestEndpoint:      "https://localhost:443",
	ClusterID:         "abc-r2d2",
	ProducerAPIKey:    "1234567890",
	ProducerAPISecret: "**********",
})
resp, err := client.Produce(context.Background(), Request{
	Topic:   "public.hello",
	Data:    "Dragonfly out in the sun you know what I mean",
	Key:     "134-5678",
	Headers: map[string]string{"heading": "for tomorrow"},
})
fmt.Printf("Record successfully commited, offset=%d partition=%d\n", resp.Offset, resp.PartitionId)

$ rubin -topic public.hello -record '{"msg":"hello"}' -key "123" -header "source=ci" -header "mood=good"

$ rubin -help

Welcome to rubin v0.1.5 built now by go (b368bf8)

This application is configured via the environment. The following environment
variables can be used:

KEY                          TYPE             DEFAULT    REQUIRED    DESCRIPTION
KAFKA_REST_ENDPOINT          String                      false       Kafka REST Proxy Endpoint
KAFKA_CLUSTER_ID             String                      false       Kafka Cluster ID
KAFKA_PRODUCER_API_KEY       String                      false       Kafka API Key with Producer Privileges
KAFKA_PRODUCER_API_SECRET    String                      false       Kafka API Secret with Producer Privileges
KAFKA_HTTP_TIMEOUT           Duration         10s        false       Timeout for HTTP Client
KAFKA_DUMP_MESSAGES          True or False    false      false       Print http request/response to stdout
KAFKA_LOG_LEVEL              String           info       false       Min LogLevel debug,info,warn,error

docker run --rm ghcr.io/tillkuhn/rubin:v0.1.2 -help

payload := map[string]string{"user": "james.bond", "id": "007"}
event, err = rubin.NewCloudEvent("//hr/manager", "user.created", payload)
resp, err := client.Produce(ctx, Request{ "app.user",  event})

In addition, the following CLI arguments are supported
  -ce
    	CloudEvents format for event payload (default: STRING or JSON)
  -header value
    	Header formatted as key=value, can be used multiple times
  -help
    	Display this help
  -key string
    	Kafka Message Key (optional, default is generated uuid)
  -record string
    	Request payload to send into the Kafka Topic
  -source string
    	CloudEventy: The context in which an event happened (default "rubin/cli")
  -subject string
    	CloudEventy: The subject of the event in the context of the event producer
  -topic string
    	Name of target Kafka Topic
  -type string
    	CloudEvents: Type of event related to the originating occurrence (default "event.Event")
  -v string
    	Verbosity, one of 'debug', 'info', 'warn', 'error' (default "info")

go get github.com/tillkuhn/rubin

client := rubin.New(&rubin.Options{
	RestEndpoint:      "https://localhost:443",
	ClusterID:         "abc-r2d2",
	ProducerAPIKey:    "1234567890",
	ProducerAPISecret: "**********",
})
resp, err := client.Produce(context.Background(), Request{
	Topic:   "public.hello",
	Data:    "Dragonfly out in the sun you know what I mean",
	Key:     "134-5678",
	Headers: map[string]string{"heading": "for tomorrow"},
})
fmt.Printf("Record successfully commited, offset=%d partition=%d\n", resp.Offset, resp.PartitionId)

docker run --rm ghcr.io/tillkuhn/rubin:v0.1.2 -help

payload := map[string]string{"user": "james.bond", "id": "007"}
event, err = rubin.NewCloudEvent("//hr/manager", "user.created", payload)
resp, err := client.Produce(ctx, Request{ "app.user",  event})

$ make help

Usage: make <OPTIONS> ... <TARGETS>

Available targets are:

all                  Initializes all tools
build                Builds all binaries
ci                   Executes lint and test and generates reports
clean                Cleans up everything
coverage             Displays coverage per func on cli
docker               Builds docker image
download             Downloads the dependencies
fmt                  Formats all code with go fmt
help                 Shows the help
html-coverage        Displays the coverage results in the browser
lint                 Lints all code with golangci-lint
run                  Run the app
run-help             Run the app and display app helm
test                 Runs all tests  (with colorized output support if gotest is installed)
test-build           Tests whether the code compiles
test-int             Run integration test with tag //go:build integration
tidy                 Cleans up go.mod and go.sum

# Gemfile
gem 'devise'

