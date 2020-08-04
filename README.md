```py
## Native Modules
from os import system
import sys

## Local Imports
import finesse
import reader

## A Graceful Dumbass
class Rusty:
    def __init__(self):
        self.variables = {
            'name': 'redacted',
            'age': 'redacted',
            'profession': 'Versatile Integrative Development / Online Freelancing.',
            'spokenLanguages': ['English', 'French', 'Spanish', 'Russian'],
            'codeLanguages': ['HTML', 'PHP', 'JS', 'C/C++', '(some) C#', 'Python', 'Java', '(some) Delphi']
        }

    def description(self):
        print('------Rusty------')
        for index, value in enumerate(self.variables.values()):
            if index == 0:
                print(f'Name: {value}')
            elif index == 1:
                print(f'Age: {value}')
            elif index == 2:
                print(f'Profession: {value}')
            elif index == 3:
                print('Spoken Languages:')
                for language in spokenLanguages:
                    print(f'\t- {language}')
            elif index == 4:
                print('Code Languages:')
                for language in codeLanguages:
                    print(f'\t- {language}')
            else:
                print('Why is this happening?')

    def links(self):
        platforms = {
            'Website': 'https://rhq.pw/',
            'Landing Page': 'https://xelta.rhq.pw/',
            'Discord Username': 'Dumbledoofus#0420',
            'Discord Server': 'https://discord.gg/97VBSbA'
        }

        print('\n-----Contact-----')
        for key, value in platforms.items():
            print(f'{key}: {value}')


if __name__ == '__main__':
    try:
        me = Rusty()
        me.description()
        me.links()
        reader.Mother().finesse()
    except:
        print(f'This is me, but failing.')
        system("pause > NUL")
        sys.exit()
```

![My Stats](https://github-readme-stats.vercel.app/api?username=RHQ-Rusty&show_icons=true)

<!-- Credit for Base Theme to https://github.com/zoony1337 -->

<!--
DEFAULT // HERE FROM GITHUB

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
