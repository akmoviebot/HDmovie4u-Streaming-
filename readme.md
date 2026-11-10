# HDmovie4u Streaming

A Telegram bot to turn media and document files into instant direct download and stream links.

## About This Bot

This bot provides stream links for Telegram files without waiting for the download to complete.

## Deploy To Render

https://render.com/deploy

## Deploy To Koyeb

https://app.koyeb.com/

## Deploy To Railway

https://railway.app/

## Features

- Superfast download and stream links.
- No ads in generated links.
- Fast interface.
- File information such as name and size.
- Updates channel support.
- MongoDB database support for broadcasting.
- Password protection.
- User-friendly interface.
- Ping check.
- User DC check.
- Real-time CPU, RAM and internet usage.
- Custom domain support.

## Host It on VPS Locally

```bash
git clone https://github.com/TECHNICAL-RB/HDmovie4u-Streaming
cd HDmovie4u-Streaming
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python3 -m Dxbots
