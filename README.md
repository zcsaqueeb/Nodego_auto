# NodeGo BOT
NodeGo BOT

- Register Here : [NodeGo](https://app.nodego.ai/r/NODE61F26B83356B)
- Use Code : NODE61F26B83356B

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Claim Daily Check-In
  - Auto Complete Available Tasks
  - Auto Added Node & Send Ping Every 10 Minutes
  - Multi Accounts With Threads
  - For Now, Only Support Run 1 Node ID

Note: 
1. Only running 1 node if run without proxy.
2. If there is an error. Please first find out the meaning of the error with the status code displayed. if the error is with status code 500 or higher. The problem is on the project server. Some of you opened an issue and complained that there was an error with status code 502 and told me to update the bot. Hey sir, are you kidding me?

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/vonssy/NodeGo-BOT.git
   ```
   ```bash
   cd NodeGo-BOT
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

- **tokens.txt:** You will find the file `tokens.txt` inside the project directory. Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    eyjxxxx1
    eyjxxxx2
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
