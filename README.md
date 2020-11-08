# Project_Akarata Userbot
<p align="center">
<a href="https://github.com/Akarata/Project_Akarata/actions?query=workflow%3AFailedChecker" > <img src="https://img.shields.io/github/workflow/status/Akarata/Project_Akarata/AkaChecker/master?label=Build&style=flat-square&logo=github-actions&logoColor=white&color=98CE00" alt="FailedChecker" /></a>
    <a href="https://www.codacy.com/manual/MoveAngel/One4uBot?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=MoveAngel/One4uBot&amp;utm_campaign=Badge_Grade"><img src="https://img.shields.io/codacy/grade/e758192aef1c4178be8777694409b248?style=flat-square&logo=codacy&color=17BEBB" alt="codacy badge"/></a>
    <a href="https://github.com/Akarata/Project_Akarata/actions?query=workflow%3APyLint"> <img src="https://img.shields.io/github/workflow/status/Akarata/Project_Akarata/PyLint/master?label=PyLint&style=flat-square&logo=github-actions&logoColor=white&color=98CE00" alt="Pylint" /></a><br>
    <a href="https://github.com/Akarata/Project_Akarata/commits/master"><img src="https://img.shields.io/github/last-commit/Akarata/Project_Akarata/master?label=Last%20Commit&style=flat-square&logo=github&color=8C86AA" alt="Commit" /></a>
    <a href="https://github.com/Akarata/Project_Akarata/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/Akarata/Project_Akarata?label=Contributors&style=flat-square&logo=github&color=FF4D80" alt="Contributors" /></a>
    <a href="https://github.com/Akarata/Project_Akarata/watchers"><img src="https://img.shields.io/github/watchers/Akarata/Project_Akarata?label=Watch&style=flat-square&logo=github&color=FF70A6" alt="Watch" /></a>
    <a href="https://github.com/Akarata/Project_Akarata/stargazers"><img src="https://img.shields.io/github/stars/Akarata/Project_Akarata?label=Stars&style=flat-square&logo=github&color=F87575" alt="Stars" /></a>
    <a href="https://github.com/Akarata/Project_Akarata/network/members"><img src="https://img.shields.io/github/forks/Akarata/Project_Akarata?label=Fork&style=flat-square&logo=github&color=E0777D" alt="Fork" /></a>
    <a href="https://hub.docker.com/repository/docker/akarata/project"> <img src="https://img.shields.io/docker/image-size/akarata/project/latest?label=Docker%20Size&style=flat-square&logo=docker&logoColor=white&color=1B98E0" alt="Docker Image" /></a><br>
    <a href="https://hub.docker.com/repository/docker/akarata/project/tags"> <img src="https://img.shields.io/docker/v/akarata/project/latest?label=Docker%20Version&style=flat-square&logo=docker&logoColor=white&color=1B98E0" alt="Docker Version" /></a><br>
</p>


[![ logo](https://telegra.ph/file/3e712650d6b40736f6a71.jpg)](https://heroku.com/deploy)

### The Easy Way to deploy the bot
Get APP ID and API HASH from [HERE](https://my.telegram.org) and BOT TOKEN from [Bot Father](https://t.me/botfather) and then Generate stringsession by clicking on run.on.repl.it button below and then click on deploy to heroku . Before clicking on deploy to heroku just click on fork and star just below

[![Get string session](https://repl.it/badge/github/sandy1709/sandeep1709)](https://generatestringsession.sandeep1709.repl.run/)

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Akarata/Project_Akarata)
<p align="center">
  
### The Normal Way

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Configuration



**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**

Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`

    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

## Credits
Thanks to :
*   [RaphielGang](https://github.com/RaphielGang) - Telegram-Paperplane
*   [sandeep.n](https://github.com/sandy1709) - Catuserbot
*   [Md Jisan](https://github.com/Jisan09) - Catuserbot
*   [Alfiananda](https://github.com/alfianandaa) - ProjectAlf
*   [Mr.Miss](https://github.com/keselekpermen69) - UserButt
*   [AdekMaulana](https://github.com/adekmaulana) - ProjectBish
*   [MoveAngel](https://github.com/MoveAngel) - One4uBot
*   [AidilAryanto](https://github.com/aidilaryanto) - ProjectDils 
*   [AnggaR69s](https://github.com/GengKapak/DCLXVI) - DCLXVI

