# ADX Mirror Workflow
Owner [@ADX](https://t.me/adx69)

## Dont use this in Your main account, risk of account suspension

## Prerequisite
Fork this Repo,
Setup secrets in settings --> Secrets


`GH_TOKEN` :- Your github personal access token of the account in which main mirror repo is there <br> Example KenHV or Weeb, from https://github.com/settings/tokens

`MIRROR_REPOSLUG` :- Your Secret Repository of the mirror bot repo, as in `<username>/<reponame>` for eg `adx/KnHV-Mirror-bot`







Then edit .github/workflows/mirror-bot.yml


Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

And Then Deploy from actions.
