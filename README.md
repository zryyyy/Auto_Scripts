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
⬆️ Pushed 1 commit to zryyyy/zryyyy
⬆️ Pushed 1 commit to zryyyy/zryyyy
⬆️ Pushed 1 commit to zryyyy/zryyyy
⬆️ Pushed 1 commit to zryyyy/zryyyy
⬆️ Pushed 1 commit to zryyyy/zryyyy
```

```
<p align="center">
  Last refresh: 
  <b>2025-03-22T00:54:50Z</b>
</p>
```

```
⭐️ 54 📦 zryyyy/Cisco-Packet-Tracer-Chinese
⭐️ 1  📦 zryyyy/Nerd-Font-Patcher
⭐️ 0  📦 DennyNo1/KnowledgeBase-Vue3
⭐️ 0  📦 DennyNo1/KnowledgeBase-Vue3-Mobile
```

**Last Activity:** `Saturday, March 22nd 2025, 8:54:50 am`



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
1. 💪 Opened PR [#31](https://github.com/Codennnn/Green-Wall/pull/31) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
2. 🗣 Commented on [#24](https://github.com/Codennnn/Green-Wall/issues/24#issuecomment-2702968131) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
3. 🗣 Commented on [#24](https://github.com/Codennnn/Green-Wall/issues/24#issuecomment-2702960250) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
4. 🗣 Commented on [#30](https://github.com/Codennnn/Green-Wall/pull/30#issuecomment-2693575634) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
5. 💪 Opened PR [#30](https://github.com/Codennnn/Green-Wall/pull/30) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
6. 🗣 Commented on [#29](https://github.com/Codennnn/Green-Wall/pull/29#issuecomment-2683797913) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
7. 🗣 Commented on [#29](https://github.com/Codennnn/Green-Wall/pull/29#issuecomment-2683785595) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
8. 🗣 Commented on [#29](https://github.com/Codennnn/Green-Wall/pull/29#issuecomment-2681362009) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
9. 🗣 Commented on [#29](https://github.com/Codennnn/Green-Wall/pull/29#issuecomment-2680926963) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
10. 💪 Opened PR [#29](https://github.com/Codennnn/Green-Wall/pull/29) in [Codennnn/Green-Wall](https://github.com/Codennnn/Green-Wall)
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
Last Updated: `Saturday, March 22nd, 2025, 8:55:07 AM`
<!--RECENT_ACTIVITY:last_update_end-->

<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
2. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
3. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
4. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
5. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
6. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
7. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
8. ⭐ Starred [`wxt-dev/wxt`](https://github.com/wxt-dev/wxt)<br>
9. ⭐ Starred [`lin-stephanie/astro-antfustyle-theme`](https://github.com/lin-stephanie/astro-antfustyle-theme)<br>
10. ⭐ Starred [`muxinc/player.style`](https://github.com/muxinc/player.style)<br>
<!--RECENT_ACTIVITY:end-->



### [Profile Readme Development Stats(WakaTime)](https://github.com/marketplace/actions/profile-readme-development-stats)

**Demo:**  [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)

```
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```
