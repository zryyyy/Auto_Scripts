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
⬆️ Pushed 926 commits to zryyyy/waline
⬆️ Pushed 173 commits to zryyyy/OpenWrt-X86
⬆️ Pushed 12 commits to zryyyy/newifi3-d2-openwrt
```

```
<p align="center">
  Last refresh: 
  <b>2024-09-09T00:51:29Z</b>
</p>
```

```
⭐️ 27 📦 zryyyy/Cisco-Packet-Tracer-Chinese
⭐️ 1  📦 zryyyy/AutoApiSecret
⭐️ 1  📦 zryyyy/AutoApiSR
⭐️ 0  📦 DennyNo1/KnowledgeBase
```

**Last Activity:** `Monday, September 9th 2024, 8:51:29 am`



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
1. 🗣 Commented on [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6#issuecomment-2333069648) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
2. 🔒 Closed issue [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
3. 🗣 Commented on [#4](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/4#issuecomment-2323643229) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
4. 🗣 Commented on [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6#issuecomment-2323638117) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
5. 🗣 Commented on [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6#issuecomment-2323619125) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
6. 🔓 Reopened issue [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
7. 🗣 Commented on [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6#issuecomment-2323329707) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
8. 🔒 Closed issue [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
9. 🗣 Commented on [#6](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese/issues/6#issuecomment-2317299867) in [zryyyy/Cisco-Packet-Tracer-Chinese](https://github.com/zryyyy/Cisco-Packet-Tracer-Chinese)
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
Last Updated: `Monday, September 9th, 2024, 8:51:57 AM`
<!--RECENT_ACTIVITY:last_update_end-->

<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
2. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
3. ⬆️ Pushed 926 commit(s) to [zryyyy/waline](https://github.com/zryyyy/waline)<br>
4. ⬆️ Pushed 173 commit(s) to [zryyyy/OpenWrt-X86](https://github.com/zryyyy/OpenWrt-X86)<br>
5. ⬆️ Pushed 12 commit(s) to [zryyyy/newifi3-d2-openwrt](https://github.com/zryyyy/newifi3-d2-openwrt)<br>
6. ⭐ Starred [`oxc-project/oxc`](https://github.com/oxc-project/oxc)<br>
7. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
8. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
9. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
10. ⬆️ Pushed 1 commit(s) to [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)<br>
<!--RECENT_ACTIVITY:end-->



### [Profile Readme Development Stats(WakaTime)](https://github.com/marketplace/actions/profile-readme-development-stats)

**Demo:**  [zryyyy/zryyyy](https://github.com/zryyyy/zryyyy)

```
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```
