# Hi! I'm cvrsxdrm 👋

I'm a beginner Python developer.

## 🚀 My Projects
* [Task Master](https://github.com/cvrsxdrm/task-master-bot) — A simple Telegram bot for recording tasks.
* [FinTrack Bot (WIP)](https://github.com/cvrsxdrm/fintrack-bot) — FinTrack Bot is your personal assistant for managing personal finances and monitoring cryptocurrency assets directly within Telegram.

## 🛠 Technologies
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) 
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
