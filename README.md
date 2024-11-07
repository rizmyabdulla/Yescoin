
**Obtaining API Keys**
1. Go to [my.telegram.org](https://my.telegram.org) and log in with your phone number.
2. Select "API development tools" and register a new application.
3. Copy the **API_ID** and **API_HASH** to the `.env` file.

---

**Installation**

**Windows**

1. Download the script zip file and unzip it.

**Quick Start**
To install libraries and run the bot, open `run.bat` on Windows.

2. Open the folder in the terminal:
   ```shell
   cd Yescoin
   ```
3. To install automatically, run:
   ```shell
   run.bat
   ```

**Manual Installation on Windows**

```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
# Add your API_ID and API_HASH in the .env file
python main.py
```

---

**Termux**

1. Download the script zip file and unzip it.
2. Open the folder in Termux:
   ```shell
   cd $HOME
   ```

**Manual Installation on Termux**

```shell
pkg update && pkg upgrade -y
pkg install python git -y
cd Yescoin
pip install -r requirements.txt
nano .env
# Add your API_ID and API_HASH in the .env file
python main.py
```