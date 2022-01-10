### Hi Folks, I'm Kenned Ferreira 👋

![visitor badge](https://visitor-badge.glitch.me/badge?page_id=kennedfer.visitor-badge&left_color=red&right_color=green&left_text=Hello%20Visitors)

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Gapur&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true&theme=dracula" />

name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}

![Alt text](https://spotify-recently-played-readme.vercel.app/api?user=31ba4zphpkwqykc7zl6t5ox6o5fy&unique={true|1|on|yes})

