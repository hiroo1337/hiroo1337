```py

from abc import ABC, abstractmethod


class Hiro(ABC):

    @abstractmethod
    def get_contact():
        pass

    @abstractmethod
    def get_languages():
        pass

    @abstractmethod
    def get_coding_skills():
        pass


class Profile(Hiro):

    @staticmethod
    def get_contact():
        return "https://discord.gg/boosts-universes"

    @staticmethod
    def get_languages() -> tuple:
        supported_languages = ("English",)
        return supported_languages

    @staticmethod
    def get_coding_skills() -> tuple:
        preferred_editor = "vscode"
        expertise_areas = ["automation", "learning"]
        programming_languages = {"expert": "python"}
        return programming_languages, expertise_areas, preferred_editor

```

<h1 align="center">Hi 👋, I'm hiro</h1>
<h3 align="center">A passionate developer</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=hiroo1337&label=Profile%20views&color=0e75b6&style=flat" alt="hiroo1337" /> </p>

- Currently learning **Python and Java**

- How to reach me?: discord: **hirosimha**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://discord.gg/boosts-universes" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="boosts-universes" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=hiroo1337&show_icons=true&locale=en&layout=compact" alt="hiroo1337" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=hiroo1337&show_icons=true&locale=en" alt="hiroo1337" /></p>
