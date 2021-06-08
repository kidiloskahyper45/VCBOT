# Calls Music 2 — The first open-source PyTgCalls based project

## Requirements

- FFmpeg
- Node.JS 15+
- Python 3.7+

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### The good way

1. Install Python requirements:
   ```bash
   pip install -U -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```
# How To Host

The easiest way to deploy this Bot

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Aparichithan/VCBOT"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

### Heroku

[Click here](https://heroku.com/deploy?template=https://github.com/callsmusic/callsmusic-2_heroku/)

## Commands

| Command | Description                                  |
| ------- | -------------------------------------------- |
| /play   | play the replied audio file or YouTube video |
| /pause  | pause the audio stream                       |
| /resume | resume the audio stream                      |
| /skip   | skip the current audio stream                |
| /stop   | clear the queue and stop the audio stream    |

## License

### GNU Affero General Public License v3.0

[Read more](http://www.gnu.org/licenses/#AGPL)

