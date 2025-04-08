<h2 align="left">Hi 👋! My name is Hram and I'm a beginner developer , from Russia.</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hramchik&hide_title=true&hide_rank=true&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=true" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Hramchik&locale=en&hide_title=true&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=true" height="150" alt="languages graph"  />
</div>

###

<br clear="both">

<img align="left" height="150" src="https://i.imgflip.com/65efzo.gif"  />

###

<div align="right">
  <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=cpp" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=java" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=cmake" height="40" alt="cmake logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=kotlin" height="40" alt="kotlin logo"  />
</div>

###

<div align="right">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitch/default.svg" width="52" height="40" alt="twitch logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gitlab/default.svg" width="52" height="40" alt="gitlab logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/telegram/default.svg" width="52" height="40" alt="telegram logo"  />
</div>

###

<br clear="both">

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

###
