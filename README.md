<kbd><img src="https://c.tenor.com/76XxFDBUu48AAAAC/frustrated-mad.gif" width="352" height="224" /></kbd>




# 👋 Hi,
-  I’m interested in coding, reading, music, apes
-  currently working as a React Native developer
-  looking to collaborate on React/JS/Electron/React Native project
-  Also I'm big fan of Neovim, Tmux
-  Running Arch Linux with KDE on my mobile workstation
- 📫 You can reach me edmondavetisyanw@gmail.com
<!---
edavetisyan/edavetisyan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
