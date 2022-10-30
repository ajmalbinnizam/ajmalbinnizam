<h2>Hi👋, I'm Ajmal Bin Nizam! <img src="https://media.giphy.com/media/xTiTnnnWvRXTeXx3wc/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">
<p>Working as a Full stack Data engineer in <a href="https://www.ey.com">EY GDS</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</p>

## Connect me on:

<a href="https://instagram.com/ajmalbinnizam"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Instagram_colored_svg_1-512.png" width="26"> </a>
<a href="https://www.linkedin.com/in/ajmalbinnizam/"><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" width="30"> </a>
<a href="https://ajmalbinnizam.github.io"><img src="https://img.icons8.com/fluent/96/000000/domain.png" width="30" alt="ajmal bin nizam"/></a>


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
<a href="https://pythontutor.com/render.html#code=class%20DataAnalyst%3A%0A%20%20%20%20def%20__init__%28self%29%3A%0A%20%20%20%20%20%20%20%20self.name%20%3D%20%22ajmal%20bin%20nizam%22%0A%20%20%20%20%20%20%20%20self.role%20%3D%20%22Associate%20analyst%20in%20EY%20GDS%22%0A%20%20%20%20%20%20%20%20self.location%20%3D%20%228.8932%5Cxc2%5Cxb0%20N,%2076.6141%5Cxc2%5Cxb0%20E%22%0A%20%20%20%20%20%20%20%20self.blog%20%3D%20%22https%3A//ajmalbinnizam.medium.com/%22%0A%20%20%20%20%20%20%20%20self.knowledge_base%20%3D%20%5B%22Data%20science%22,%20%22Machine%20Learning%22,%22web%20development%22,%20%22music%20production%22%5D%0A%20%20%20%20%20%20%20%20self.knowledge_base.insert%280,%20%22data%20and%20analytics%22%29%0A%20%20%20%20def%20say_hi%28self%29%3A%0A%20%20%20%20%20%20%20%20print%28%0A%20%20%20%20%20%20%20%20%20%20%20%20%22%22%22Hello%20my%20friend,%20thanks%20for%20dropping%20by!%0AThis%20is%20%7Bname%7D,%20I%20live%20in%20%7Blocation%7D.%20I%20work%20as%20an%20%7Brole%7D%20and%20recently%20I%20am%20focusing%20on%20%7Bfocus%7D.%0AI%20have%20wide%20interests,%20but%20most%20of%20them%20are%20%7Bknowledge_base%7D.%0AI%20write%20down%20tips%20and%20lecture%20notes%20on%20my%20personal%20tech%20blog,%20which%20can%20be%20found%20here%3A%20%7Bblog%7D%22%22%22.format%28%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20name%3Dself.name,%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20location%3Dself.location,%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20role%3Dself.role,%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20focus%3Dself.knowledge_base%5B0%5D,%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20knowledge_base%3D%22,%20%22.join%28self.knowledge_base%5B1%3A%5D%29,%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20blog%3Dself.blog,%29%29%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0Ame%20%3D%20DataAnalyst%28%29%0Ame.say_hi%28%29&cumulative=false&curInstr=21&heapPrimitives=nevernest&mode=display&origin=opt-frontend.js&py=3&rawInputLstJSON=%5B%5D&textReferences=false">Click here, to run the code</a>
