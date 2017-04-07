This is an unofficial wrapper for cleverbot.io API, an alternative free Cleverbot client.

First, install the package:
```
pip install cleverbot_io
```

Set your settings:
```py
import cleverbot_io
bot = cleverbot_io.set(user='APIUSER', key='APIKEY', nick='SESSIONNICK(optional)')
```

Then make your program talk:
```py
print(bot.ask("Just a small town girl")) # Or another text
```
