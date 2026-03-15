## Test Auto Deploy

Automated script testing project based on Github Actions

### [Profile Readme](https://github.com/marketplace/actions/profile-readme)

#### Docs

```yaml
jobs:
  publish:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@master
        with:
          persist-credentials: false
          fetch-depth: 0
      - name: Create README.md
        uses: actions-js/profile-readme@master
        with:
          username: <your username>
          github_token: ${{ secrets.GITHUB_TOKEN }}
      - name: Commit & Push changes
        uses: actions-js/push@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```

#### Example

```
⬆️ Pushed undefined commit to zryyyy/zryyyy
⬆️ Pushed undefined commit to zryyyy/zryyyy
⬆️ Pushed undefined commit to zryyyy/zryyyy
⬆️ Pushed undefined commit to zryyyy/bing-wallpaper
⬆️ Pushed undefined commit to zryyyy/zryyyy
```

```
<p align="center">
  Last refresh: 
  <b>2026-03-15T01:43:04Z</b>
</p>
```

```
⭐️ 68 📦 zryyyy/Cisco-Packet-Tracer-Chinese
⭐️ 1  📦 zryyyy/Nerd-Font-Patcher
⭐️ 0  📦 DennyNo1/KnowledgeBase-Vue3-Mobile
⭐️ 0  📦 morefree0203/vue
```

**Last Activity:** `Sunday, March 15th 2026, 9:43:04 am`



### [GitHub Activity in Readme](https://github.com/marketplace/actions/github-activity-readme)

#### Docs

```yaml
name: Update README
on:
  schedule:
    - cron: "*/30 * * * *"
  workflow_dispatch:
jobs:
  build:
    name: Update this repo's README with recent activity
    runs-on: ubuntu-latest
    permissions:
      contents: write

    steps:
      - uses: actions/checkout@v3
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

#### Example

<!--START_SECTION:activity-->
1. 🚀 Published release [Archive](https://github.com/zryyyy/bing-wallpaper/releases/tag/archive) in [zryyyy/bing-wallpaper](https://github.com/zryyyy/bing-wallpaper)
<!--END_SECTION:activity-->



### [Recent GitHub Activity - Profile Readme](https://github.com/marketplace/actions/recent-github-activity-profile-readme)

#### Docs

```yaml
# This is a basic workflow to help you get started with Actions

name: CI

# Controls when the workflow will run
on:
  # Triggers the workflow on push or pull request events but only for the master branch
  push:
    branches: [ master ]
  pull_request:
    branches: [ master ]

  # Allows you to run this workflow manually from the Actions tab
  workflow_dispatch:

# A workflow run is made up of one or more jobs that can run sequentially or in parallel
jobs:
  # This workflow contains a single job called "build"
  build:
    # The type of runner that the job will run on
    runs-on: ubuntu-latest

    # Steps represent a sequence of tasks that will be executed as part of the job
    steps:
      # Checks-out your repository under $GITHUB_WORKSPACE, so your job can access it
      - uses: actions/checkout@v3

      # Runs a single command using the runners shell
      - name: Run a one-line script
        run: echo Hello, world!

      # Runs a set of commands using the runners shell
      - name: Run a multi-line script
        run: |
          echo Add other actions to build,
          echo test, and deploy your project.

```

#### Example

<!--RECENT_ACTIVITY:last_update-->
Last Updated: `Sunday, March 15th, 2026, 9:43:21 AM`
<!--RECENT_ACTIVITY:last_update_end-->

<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
2. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
3. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
4. ⬆️ Pushed undefined commit(s) to [zryyyy/bing-wallpaper](https://github.com/zryyyy/bing-wallpaper)<br>
5. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
6. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
7. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
8. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
9. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
10. ⬆️ Pushed undefined commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
<!--RECENT_ACTIVITY:end-->



### [Profile Readme Development Stats(WakaTime)](https://github.com/marketplace/actions/profile-readme-development-stats)

**Demo:**  [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)

```
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```
