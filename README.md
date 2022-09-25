# Twitch Viewbot [![Python 3.x](https://img.shields.io/badge/PYTHON-3.X-blueviolet?style=for-the-badge)](http://www.python.org/download/) [![MIT License](https://img.shields.io/badge/LICENSE-MIT-brightgreen?style=for-the-badge)](https://github.com/Memisz/Twitch-Viewbot/blob/main/LICENSE)
Simple twitch viewer bot witch requires a large amount of proxies (if you want to use public proxies, however works better with private proxies) to generate views for specific stream.

# Usage
- Press the `code` button and `download ZIP`, then extract the zip file from the file explorer
- Once you've done that you'll need to install python3, it can be found at https://www.python.org/downloads/ (keep in mind if you install it from there you'll need to tick the install to PATH button) or from windows store or your package manager of choice
- Open cmd and locate the path of the extracted repository, alternatively on windows 11 this can be done from file explorer by just right clicking and pressing open in terminal

- Then you would need to install requirements! You can do it by executing this command
```
python -m pip install -r requirements.txt
```
- Once you've done that you can do this command and you're good to go
```
python threads_viewer.py your_channel_name max_nb_of_threads
```
