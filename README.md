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
⬆️ Pushed 10 commits to zryyyy/github-readme-stats
⬆️ Pushed 0 commit to zryyyy/hexo-theme-volantis
```

```
<p align="center">
  Last refresh: 
  <b>2024-09-29T00:56:37Z</b>
</p>
```

```
⭐️ 35 📦 zryyyy/Cisco-Packet-Tracer-Chinese
⭐️ 1  📦 zryyyy/AutoApiSecret
⭐️ 1  📦 zryyyy/AutoApiSR
⭐️ 1  📦 zryyyy/Nerd-Font-Patcher
```

**Last Activity:** `Sunday, September 29th 2024, 8:56:37 am`



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
1. 🗣 Commented on [#4](https://github.com/lxgw/LxgwWenkaiGB/issues/4#issuecomment-2376328313) in [lxgw/LxgwWenkaiGB](https://github.com/lxgw/LxgwWenkaiGB)
2. 🗣 Commented on [#4](https://github.com/lxgw/LxgwWenkaiGB/issues/4#issuecomment-2376265251) in [lxgw/LxgwWenkaiGB](https://github.com/lxgw/LxgwWenkaiGB)
3. 🗣 Commented on [#148](https://github.com/lxgw/LxgwWenKai/issues/148#issuecomment-2376177117) in [lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai)
4. 🗣 Commented on [#148](https://github.com/lxgw/LxgwWenKai/issues/148#issuecomment-2375892925) in [lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai)
5. ❗ Opened issue [#148](https://github.com/lxgw/LxgwWenKai/issues/148) in [lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai)
6. 💪 Opened PR [#926](https://github.com/volantis-x/hexo-theme-volantis/pull/926) in [volantis-x/hexo-theme-volantis](https://github.com/volantis-x/hexo-theme-volantis)
7. 🗣 Commented on [#1](https://github.com/DiamondHunters/NodeInject_Hook_example/issues/1#issuecomment-2365177890) in [DiamondHunters/NodeInject_Hook_example](https://github.com/DiamondHunters/NodeInject_Hook_example)
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
Last Updated: `Sunday, September 29th, 2024, 8:57:05 AM`
<!--RECENT_ACTIVITY:last_update_end-->

<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
2. ⭐ Starred [`bensadeh/tailspin`](https://github.com/bensadeh/tailspin)<br>
3. ⭐ Starred [`Dhghomon/easy_rust`](https://github.com/Dhghomon/easy_rust)<br>
4. ⭐ Starred [`xyflow/xyflow`](https://github.com/xyflow/xyflow)<br>
5. ⭐ Starred [`leaningtech/webvm`](https://github.com/leaningtech/webvm)<br>
6. ⭐ Starred [`AppHouseKitchen/AlDente-Charge-Limiter`](https://github.com/AppHouseKitchen/AlDente-Charge-Limiter)<br>
7. ⭐ Starred [`tisfeng/Easydict`](https://github.com/tisfeng/Easydict)<br>
8. ⭐ Starred [`Z4nzu/hackingtool`](https://github.com/Z4nzu/hackingtool)<br>
9. ⭐ Starred [`Atlas-OS/Atlas`](https://github.com/Atlas-OS/Atlas)<br>
10. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
<!--RECENT_ACTIVITY:end-->



### [Profile Readme Development Stats(WakaTime)](https://github.com/marketplace/actions/profile-readme-development-stats)

**Demo:**  [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)

```
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```
