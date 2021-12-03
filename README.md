```zsh
# Install Homebrew
% /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Build system and JDK

```zsh
% brew install gradle@6 # This will install openjdk@11 as a dependency

# For the system Java wrappers to find this JDK, symlink it with
% sudo ln -sfn $(brew --prefix)/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk

# Add the following to your .zshrc
export JAVA_HOME=$(/usr/libexec/java_home -v11)
```

## Browsers

Choose your favourite(s) unless you are happy with Safari

```zsh
% brew install --cask google-chrome
% brew install --cask firefox
% brew install --cask brave-browser
% brew install --cask microsoft-edge
```

## REST client

Choose your favourite(s) or something else

```zsh
% brew install --cask postman
% brew install --cask insomnia
```

## Other required casks

```zsh
% brew install --cask intellij-idea # Not required if you don't use IntelliJ IDEA
% brew install --cask slack
% brew install --cask zoom
% brew install --cask wkhtmltopdf   # Required for fax
% brew install --cask aws-vault
% brew install --cask docker        # Will install kubectl as well
% brew install --cask tunnelblick   # VPN

% brew install gpg
# Add the following to your .zshrc
export GPG_TTY=$(tty)
```

## Other required formulae

```zsh
% brew install git
% brew install vault
% brew install jq
% brew install aws-iam-authenticator
% brew install pre-commit
% brew install awscli
```

## Optional formulae

```zsh
% brew install tree
% brew install z
```

## Command completion

```zsh
# Add the following to .zsh to enable command completion 
autoload bashcompinit && bashcompinit
autoload -Uz compinit && compinit
```

## Requests

Request the following items through FreshService

- [GitHub Access](https://wolt.freshservice.com/support/catalog/items/51)
- [OpsTools](https://wolt.freshservice.com/support/catalog/items/47)
- [Jira](https://wolt.freshservice.com/support/catalog/items/52)
- [IntelliJ IDEA Ultimate](https://wolt.freshservice.com/support/tickets/23839)


Follow the instructions in [Checklist of Accounts and Permissions](https://woltwide.atlassian.net/wiki/spaces/ENG/pages/1057129928) page

Follow [Dev env access](https://kube-login.development-internal.dev.woltapi.com) to setup AWS / Kubernetes config

## Useful links

- [Slack](https://wolt.slack.com)
- [Mail](https://accounts.google.com/signin/v2/identifier?continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&hl=en-GB)
- [Calendar](https://calendar.google.com)
- [FreshService](https://wolt.freshservice.com)
- [Wolt at Work](https://corporate.wolt.com)
- [AWS Console](https://wolt.signin.aws.amazon.com/console)
- [Jira](https://woltwide.atlassian.net/jira)

## Confluence pages

- [Wolt Finland](https://woltwide.atlassian.net/wiki/spaces/PEOP/pages/179437569)
- [Wifi](https://woltwide.atlassian.net/wiki/spaces/PEOP/pages/227737638)
