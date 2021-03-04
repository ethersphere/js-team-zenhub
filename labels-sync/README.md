# GitHub Labels sync

This package allows to sync labels to GitHub repos.

### Usage

In order to run this tool, you have to have GitHub token available.
See [this tutorial](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) on how
to get it, you need to give it `repo` scope to write to the repositories
where you want to sync the labels.

```shell
$ npm install 
$ GITHUB_ACCESS_TOKEN="your GH token" npm start -- ethersphere/bee-js # Replace that with your repo! ;-)
```

*TIP! If you use `--dry-run` you can see what changes will be done prior real execution*

It below the hood uses [github-label-sync](https://github.com/Financial-Times/github-label-sync),
so check it out for other options.
