# Woordly  
**About the project:** The port of the Wordle game in Telegram

<a href="https://t.me/woordly_bot">
<img alt="Static Badge" src="https://img.shields.io/badge/Demo_Bot-Woordly-blue?style=for-the-badge&logo=telegram">
</a>

**Technology stack**
* *API*: Aiogram
* *Container*: Docker

# Installation:
1) Clone this repo: `git clone https://github.com/ornarasus/Woordly.git`
2) Change directory: `cd Woordly`
3) Install package: `pip install aiogram`
4) Setup token of telegram bot in `settings.py`
5) Build image: `docker build --tag woordly .`
6) Run container: `docker run woordly`