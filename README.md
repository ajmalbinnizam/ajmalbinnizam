<h2> I'm Ajmal Bin Nizam! <img src="https://media.giphy.com/media/12oufCB0MyZ1Go/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">
<p><em>Associate Analyst at <a href="https://www.ey.com">EY GDS</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Instagram ](<i class="ri-instagram-line"></i>)](https://instagram.com/ajmalbinnizam)
[![Linkedin](https://img.shields.io/badge/-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ajmalbinnizam/)](https://www.linkedin.com/in/ajmalbinnizam/)
![GitHub followers](https://img.shields.io/github/followers/ajmalbinnizam?label=Follow&style=social)
[![website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Google-Chrome&logoColor=white&link=https://ajmalbinnizam.github.io/)](https://ajmalbinnizam.github.io/)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class DataAnalyst
    def __init__(self):
        self.name = "ajmal bin nizam"
        self.role = "Associate analyst in EY GDS"
        self.location = "8.8932\xc2\xb0 N, 76.6141\xc2\xb0 E"
        self.blog = "https://ajmalbinnizam.medium.com/"
        self.knowledge_base = ["Data science", "Machine Learning","web development", "music production"]
        self.knowledge_base.insert(0, "data and analytics")
    def say_hi(self):
        print(
            """Hello my friend, thanks for dropping by!
This is {name}, I live in {location}. I work as an {role} and recently I am focusing on {focus}.
I have wide interests, but most of them are {knowledge_base}.
I write down tips and lecture notes on my personal tech blog, which can be found here: {blog}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,))
                
me = DataAnalyst()
me.say_hi()

```

