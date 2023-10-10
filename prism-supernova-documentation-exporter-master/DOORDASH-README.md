##Setup your local repo
1. Clone this repository
1. Add the Supernova Exporter Documentation repo as an upstream: `git remote add upstream git@github.com:Supernova-Studio/exporter-documentation.git  git remote set-url --push upstream DISABLE`

##Updating the fork:
1. `git fetch upstream`
1. `git rebase upstream/master`
1. Deal with any conflicts
1. If CSS or DOM structure changed, give a quick look over the changed areas. Fixed and patch as needed.


##Running Export Code Locally:
1. Download the SuperNova VS Code extension https://developers.supernova.io/latest/obtaining-production-code/using-the-vs-code-extension.html
1. Grab an API Key from your Supernova Profile Settings
1. 