<h2> I'm Ajmal Bin Nizam! <img src="https://media.giphy.com/media/xTiTnnnWvRXTeXx3wc/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">
<p>Associate Analyst at <a href="https://www.ey.com">EY GDS</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</p>

<a href="https://instagram.com/ajmalbinnizam"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Instagram_colored_svg_1-512.png" width="22"> </a>
<a href="https://www.linkedin.com/in/ajmalbinnizam/"><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" width="30"> </a>
[![website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Google-Chrome&logoColor=white&link=https://ajmalbinnizam.github.io/)](https://ajmalbinnizam.github.io/)


```python

class DataAnalyst:
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

