```py
import finesse
import reader

class Rusty:
    def __init__(self):
        self.variables = {
            'name': 'redacted',
            'age': 'redacted',
            'profession': 'Versatile Integrative Development / Online Freelancing.',
            'languages': ('English', 'French', 'Spanish', 'Russian')
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
                print(f'Languages: {value}')

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
    me = Rusty()
    me.description()
    me.links()
    reader.Mother().finesse()
```

<!--
**RHQ-Rusty/RHQ-Rusty** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
